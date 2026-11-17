# Entrega 11 — Protótipo no Figma

**Data:** {{16/11/2026}}  
**Status:**🟩 concluída 
**Responsabilidade:** 1 protótipo integrado por equipe cobrindo os fluxos MoLIC. Se a turma exigir divisão individual, identifique o responsável por cada fluxo/tela.

## Objetivo da atividade

Materializar o modelo de interação em um protótipo navegável, preservando a lógica dos objetivos, tópicos, signos, feedbacks, alternativas e recuperações definidos anteriormente.

## Biblioteca de possibilidades para projetos técnicos

O protótipo deve materializar os fluxos definidos nas entregas anteriores. Dependendo do escopo, podem fazer sentido:

1. **Dashboard:** indicadores, alertas, estado, tendências e atalhos para tarefas frequentes.
2. **Configuração/parametrização:** escolhas, presets, validação e explicação de opções técnicas.
3. **Entrada de dados:** upload, conexão, seleção, pré-visualização e validação.
4. **Processamento:** fila, status, progresso, cancelamento, falha e reexecução.
5. **Relatório/resultados:** síntese, métricas, gráficos, explicação, exportação e compartilhamento.
6. **Histórico:** busca, filtros, ordenação, paginação, detalhes e repetição de execução.
7. **Comparação:** antes/depois, modelo A/B, execução A/B, baseline ou períodos.
8. **Explicabilidade:** confiança, fatores, evidências, limitações e correção/contestação.
9. **Administração:** usuários, grupos, perfis, permissões, integrações e políticas.
10. **CRUDs de domínio:** somente quando criar/consultar/editar/excluir representa tarefa real.
11. **Auditoria/logs:** histórico de alterações e eventos em linguagem adequada.
12. **Alertas/ocorrências:** severidade, impacto, ação, responsável e resolução.
13. **Ajuda/documentação:** apoio contextual a tarefas complexas.

### Estados que não podem ser esquecidos

Quando aplicável, considere: vazio/sem dados; carregamento/processamento; sucesso; erro de entrada; erro de processamento; filtro sem resultados; permissão insuficiente; confirmação de ação destrutiva; cancelamento/desfazer/recuperação; dados desatualizados/conflito.

> Esta lista é repertório de design, **não uma exigência de quantidade de telas**. A rastreabilidade deve explicar por que cada tela existe.

## Link do Figma

etapa de revisão
**Protótipo:** {{https://www.figma.com/design/GOwGWxzY02kVQPyRxh8Hvy/Untitled?node-id=8-11497&t=fK84Mhn0DBXdw7mc-1}}  
**Arquivo editável:** {{https://www.figma.com/design/GOwGWxzY02kVQPyRxh8Hvy/Untitled?node-id=8-11497&m=dev&t=fK84Mhn0DBXdw7mc-1}}  
**Última verificação de permissão:** {{16/11/2026}}

Etapa de montagem:
**Protótipo:**{{https://www.figma.com/design/aBMOmlgOWEY6xu68Mx2nhb/Untitled?node-id=2-1195&t=W4srdMUEHGzcyYeH-1}}
**Arquivo editável:**{{https://www.figma.com/design/aBMOmlgOWEY6xu68Mx2nhb/Untitled?node-id=2-1195&m=dev&t=W4srdMUEHGzcyYeH-1}}
**Última verificação de permissão:** {{16/11/2026}}


> Teste o link em janela anônima. O avaliador deve conseguir abrir o protótipo sem solicitar permissão.

## Cobertura MoLIC → Figma

| MoLIC | Objetivo | Fluxo/telas no Figma | Estados de erro/recuperação | Responsável |
|---|---|---|---|---|

|M01 (Etapa de Revisão) |O01 (Compreender componentes de hardware)|(Acesso Ubíquo / Menu) → F02 (Consultar lista de componentes) → F03 (Examinar componente)|F03R (Estado de ruptura [TA] na cena Examinar componente: alerta de erro ao carregar detalhes + botão de recuperação Tentar Novamente)| {{ Beatriz }} |
|M02 (Etapa de Montagem) |O02 (Montar computador na prática)|F04 (Montar computador — estado inicial) → F05 (Encaixe validado / próximo destaque em loop) → F06 (Visualizar resultado da montagem)(Inclui fechamento F06 → F01 via u: concluir / gcc: Montar computador)|F04R (Estado de ruptura [TA] após u: soltar componente: banner de alerta de componente incorreto ou fora da área de encaixe com retorno imediato à cena Montar computador)| {{Larissa}} |


## Catálogo de telas/estados

### F01 — {{nome da tela/estado}}

![F01](../assets/11_figma/f01.svg)

**Objetivo do usuário:** {{Iniciar a exploração livre dos componentes de hardware antes ou durante o jogo}}  
**Signos principais:** {{Botão/opção de navegação global Revisar Componentes (u: revisar componentes), título do jogo (Hardware Quest) e indicador de acesso rápido.}}  
**Origem no MoLIC:** {{M01 / Acesso ubíquo (retângulo cinza arredondado).}}

*Objetivo do usuário:** {{: Identificar o local correto de instalação no gabinete e encaixar as peças de hardware solicitadas}}  
**Signos principais:** {{Representação visual do gabinete (d: gabinete), zona de encaixe destacada (d: regiao_destacada), bandeja com as 3 peças da etapa (d: lista(3 componentes)), ação de seleção e posicionamento (u: selecionar componente X, arrastar e soltar / alternativa via teclado) e soltura (u: soltar componente).}}  
**Origem no MoLIC:** {{M02 / Cena "Montar computador".}}

> Documente também estados que muitas equipes esquecem: carregamento, vazio, confirmação, sucesso, erro, permissão negada, cancelamento, desfazer/voltar quando aplicável.

## Sistema visual e consistência

| Elemento | Regra adotada | Justificativa |
|---|---|---|
| Tipografia | {{Fonte sem serifa geométrica/técnica (ex.: Inter ou Roboto), com hierarquia clara entre títulos de cena (24px–28px, Bold), subtítulos/tópicos (18px, SemiBold) e textos de descrição/diálogos (16px, Regular, altura de linha 1.5).}} | {{arante alta legibilidade durante a leitura das descrições técnicas de hardware (F03) e instruções de montagem (F04), evitando fadiga visual e atendendo às boas práticas de leitura na Web}} |
| Cores | {{Fundo escuro neutro de baixo brilho (#0F172A) com superfícies de cards em cinza-ardósia (#1E293B), textos principais em branco-gelo (#F8FAFC), cor primária de ação em ciano/azul vibrante (#38BDF8), sucesso em verde (#22C55E), alerta/destaque em âmbar (#F59E0B) e erro/ruptura em vermelho (#EF4444).}} | {{Estabelece hierarquia visual alinhada à estética de jogos digitais sem comprometer a acessibilidade: todas as combinações mantêm razão de contraste mínima de 4.5:1 para textos e 3:1 para bordas, slots destacados (regiao_destacada) e ícones (WCAG 2.2 AA).}} |
| Componentes | {{Cards padronizados com bordas arredondadas (12px), divisória horizontal interna entre tópico e conteúdo (espelhando a estrutura visual das cenas do MoLIC), botões primários/secundários com área mínima clicável de 44x44px e variantes explícitas de estado (Default, Hover, Focus, Selected, Disabled).	Preserva a consistência estrutural entre a etapa de revisão (M01) e a etapa de montagem (M02), facilita o reconhecimento imediato de elementos interativos e assegura usabilidade tanto via mouse/toque quanto por navegação por teclado (Tab + Enter/Espaço).
Feedback	Sistema multimodal que nunca depende apenas da cor: banners/toasts em alto contraste acompanhados de ícones semânticos (check, triângulo de alerta, cadeado), rótulos textuais explícitos ([TA] para rupturas e confirmações de encaixe), barra de progresso contínua e regiões aria-live para leitores de tela.}} | {{Preserva a consistência estrutural entre a etapa de revisão (M01) e a etapa de montagem (M02), facilita o reconhecimento imediato de elementos interativos e assegura usabilidade tanto via mouse/toque quanto por navegação por teclado (Tab + Enter/Espaço).}} |
| Feedback | {{Sistema multimodal que nunca depende apenas da cor: banners/toasts em alto contraste acompanhados de ícones semânticos (check, triângulo de alerta, cadeado), rótulos textuais explícitos ([TA] para rupturas e confirmações de encaixe), barra de progresso contínua e regiões aria-live para leitores de tela.}} | {{Garante que o usuário perceba imediatamente o retorno do preposto (d:) em validações de encaixe (F05), falhas de carregamento (F03R) ou posicionamento incorreto (F04R), assegurando recuperação rápida de erros e acessibilidade para pessoas com daltonismo ou deficiência visual.}} |

## Verificação de acessibilidade básica

Para produto Web, considere critérios pertinentes da WCAG vigente (por exemplo, contraste, foco, tamanho de alvo, texto alternativo e navegação por teclado quando aplicáveis). Para outras plataformas, use as recomendações adequadas ao contexto.

## Checklist

- [ x Link do Figma está acessível.
- [] Há screenshots representativos no repositório.
- [x] Todos os MoLIC relevantes estão cobertos.
- [x] Estados de erro, feedback e recuperação foram prototipados.
- [x] Terminologia/signos são consistentes com Entrega 9.
- [x] Componentes equivalentes se comportam de forma consistente.
- [x] Fluxos críticos são clicáveis do início ao fim.
- [x] O protótipo está pronto para inspeção e testes, sem “links mortos” nas tarefas avaliadas.
- [ ] Dashboards, relatórios, históricos, filtros, administração e CRUDs presentes possuem justificativa rastreável.
- [x] Estados de vazio, processamento, erro e recuperação foram considerados quando pertinentes.
- [ ] Resultados técnicos são apresentados de forma interpretável para o perfil de usuário.
- [ ] A equipe distingue no protótipo o que é interação simulada e o que é funcionalidade técnica realmente integrada, quando necessário.
