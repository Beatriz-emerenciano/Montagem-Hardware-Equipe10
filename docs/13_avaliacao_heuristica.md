# Entrega 13 — Avaliação de IHC por inspeção heurística

**Data:** {{dd/mm/aaaa}}  
**Status:** ⬜ não iniciada  
**Responsabilidade:** 1 avaliação completa por integrante, sobre todas as telas/estados relevantes do projeto.

## Objetivo da atividade

Encontrar problemas de usabilidade por inspeção sistemática da interface com as **10 heurísticas de Nielsen**. Cada avaliador trabalha individualmente primeiro; depois a equipe consolida problemas duplicados e prioridades.

> **Parte de violações:** registre somente problemas reais. Não invente uma violação para “preencher” cada heurística. Para provar que todas foram exercitadas, use a **matriz de cobertura H1–H10**. Para heurísticas sem violação, a disciplina solicita um exemplo didático de boa prática.

## 1. Heurísticas adotadas

1. Visibilidade do status do sistema
2. Compatibilidade entre o sistema e o mundo real
3. Controle e liberdade do usuário
4. Consistência e padrões
5. Prevenção de erros
6. Reconhecimento em vez de memorização
7. Flexibilidade e eficiência de uso
8. Estética e design minimalista
9. Ajudar usuários a reconhecer, diagnosticar e recuperar-se de erros
10. Ajuda e documentação

## Cobertura especial para interfaces administrativas e analíticas

Quando existirem, não limite a avaliação às “telas principais”. Inspecione também:

- dashboard em estados normal, vazio e erro;
- filtros sem resultado e filtros combinados;
- relatórios e exportação;
- histórico/listas longas;
- formulários CRUD (criação, edição, exclusão, validação);
- alteração de perfil/permissão;
- confirmações de ações destrutivas;
- processamento/loading/progresso;
- falha e recuperação;
- comparação de resultados;
- mensagens de termos técnicos, métricas e recomendações;
- ajuda/documentação contextual.

Em TCCs técnicos, observe especialmente se a interface comunica o estado do processamento e traduz informações técnicas para o vocabulário do usuário escolhido.

## 2. Escopo da inspeção

| Item | Definição |
|---|---|
| Versão avaliada | {{https://www.figma.com/design/GOwGWxzY02kVQPyRxh8Hvy/Untitled?node-id=8-11497&t=fK84Mhn0DBXdw7mc-1%7D%7D  e  https://www.figma.com/design/aBMOmlgOWEY6xu68Mx2nhb/Untitled?node-id=2-1195&t=W4srdMUEHGzcyYeH-1%7D%7D/commit/16/11}} |
| Telas/estados | {{tela de detapa de revisão e tela de montagem}} |
| Fluxos | {{M01/M02...}} |
| Dispositivo/viewport | {{Computador Desktop / Notebook — Aplicação Web Responsiva, viewport padrão 1440x900px (resolução mínima suportada 1366x768px), operando via mouse/trackpad e teclado físico.}} |
| Avaliadores | {{nomes}} |

## 3. Procedimento individual

Cada avaliador deve:

1. percorrer os fluxos/telas ao menos uma vez para familiarização;
2. inspecionar novamente aplicando sistematicamente H1–H10;
3. registrar cada problema com evidência e contexto;
4. atribuir severidade **depois de compreender bem o problema**, justificando a decisão;
5. não discutir achados com os demais antes de terminar a inspeção individual, quando o objetivo for preservar independência.

### Escala de severidade (0–4)

| Grau | Interpretação |
|---:|---|
| 0 | não é considerado problema de usabilidade |
| 1 | problema cosmético; corrigir se houver tempo |
| 2 | problema menor; baixa prioridade |
| 3 | problema maior; alta prioridade |
| 4 | catástrofe de usabilidade; correção imperativa antes de disponibilizar |

Ao justificar, considere **frequência, impacto e persistência** do problema no contexto real de uso.

---

## Avaliador A01 — {{Beatriz}}

### 4. Matriz de cobertura das 10 heurísticas

| Heurística | Telas/fluxos examinados | Houve violação? | IDs dos achados | Exemplo de boa prática se não violada |
|---|---|---|---|---|
| H1 (Visibilidade do status do sistema)| {{F01 → F02 → F03 (Revisão) e F04 → F05 → F06 (Montagem)}} | não | {{}} | {{Barra de progresso contínua (Progresso: Componente 1 de 3 até 3 de 3 concluídos), breadcrumb de localização (01 Revisão — 02 Montagem) e selo ✓ Encaixado no gabinete}} |
| HeurísticaTelas/fluxos examinadosHouve violação?IDs dos achadosExemplo de boa prática se não violadaH1 (Visibilidade do status do sistema)   F01 → F02 → F03 (Revisão) e F04 → F05 → F06 (Montagem)não—Barra de progresso contínua (Progresso: Componente 1 de 3 até 3 de 3 concluídos), breadcrumb de localização (01 Revisão — 02 Montagem) e selo ✓ Encaixado no gabinete.   H2 (Compatibilidade entre sistema e mundo real) | {{F02, F03, F04, F05}} | não |  |so de ilustrações técnicas fiéis aos componentes físicos (Placa-mãe, Memória RAM, CPU, etc.), vista interna do gabinete aberta ("Bancada de Montagem") e linguagem didática sem jargões de sistema.  |
| HeurísticaTelas/fluxos examinadosHouve violação?IDs dos achadosExemplo de boa prática se não violadaH1 (Visibilidade do status do sistema)   F01 → F02 → F03 (Revisão) e F04 → F05 → F06 (Montagem)não—Barra de progresso contínua (Progresso: Componente 1 de 3 até 3 de 3 concluídos), breadcrumb de localização (01 Revisão — 02 Montagem) e selo ✓ Encaixado no gabinete.   H2 (Compatibilidade entre sistema e mundo real)   F02, F03, F04, F05não—Uso de ilustrações técnicas fiéis aos componentes físicos (Placa-mãe, Memória RAM, CPU, etc.), vista interna do gabinete aberta ("Bancada de Montagem") e linguagem didática sem jargões de sistema.   H3 (Controle e liberdade do usuário) | {{F02, F03, F04, F05}} | não | |Botões persistentes ← Voltar ao Menu e ← Voltar para lista na revisão; botão Sair da Montagem, acesso rápido Consultar Componentes e atalho Esc: cancelar seleção antes do encaixe.  |
|H4 (Consistência e padrões) | {{Transição M01 (F01–F03) → M02 (F04–F06) e tela final F06}} | sim |V01, V02  | (Violada pela alternância abrupta de Dark Mode na Revisão para Light Mode na Montagem [V01] e pelo rótulo "Montar novamente" no lugar do fechamento u: concluir previsto no MoLIC [V02]). |


## Avaliador A01 — {{Larissa}}
| H5 (Prevenção de erros)| {{F03, F04, F05}} | não |  |Destaque visual da zona de encaixe com borda tracejada (Área de Encaixe: Placa-mãe), aviso preventivo "Antes de montar: Verifique a compatibilidade entre as peças" e indicador de peça em foco antes da confirmação.  |
|H6 (Reconhecimento em vez de memorização)| {{F02, F04, F05}} | não |  |Miniaturas e resumos funcionais visíveis em todos os cards da grade (F02); bandeja lateral mantém ícones, nomes e descrições das 3 peças visíveis simultaneamente ao gabinete durante toda a montagem (F04)).  |
| H7 (Flexibilidade e eficiência de uso) | {{F02, F03, F04, F05}} | não |  |Suporte híbrido para interação via mouse (clique / arrastar e soltar) e atalhos completos de teclado (1–6 para abrir peças na revisão; Espaço, Setas, Enter, Esc e M na montagem)  |
| H8 (Estética e design minimalista)| {{F02, F03, F04, F05, F06}} | sim|V03  | (Layout geral limpo, mas violada pela presença de microtextos com fonte excessivamente reduzida nas legendas inferiores da bancada de montagem e caixas ALT, prejudicando a legibilidade [V03]) |
|H9 (Reconhecer, diagnosticar e recuperar-se de erros)| {{F03R (Falha de imagem) e F04R (Ruptura [TA] no encaixe)}} | não |  | Banners de alerta em âmbar de alto contraste com linguagem clara ("Componente incorreto ou fora da área de encaixe" e "Não foi possível carregar a imagem"), acompanhados de botões diretos de recuperação (Tentar novamente) e manutenção do progresso. |
| H10 (Ajuda e documentação) | {{F02, F03, F04, F05}} | não | - | Instruções contextuais integradas no topo da bancada ("Encontre o ponto de conexão: Selecione a peça e confirme o encaixe..."), descrições ALT visíveis nas ilustrações e botão persistente Consultar Componentes durante a prática |

### 5. Declaração de violações

| ID | Heurística | Tela/estado | Problema observado | Evidência | Severidade | Justificativa da severidade | Recomendação |
|---|---|---|---|---|---:|---|---|
| V01 | H1 | {{F02}} | {{o que ocorre, em que ação e qual consequência}} | ![print](../assets/13_heuristica/v01.svg) | 3 | {{frequência/impacto/persistência}} | {{correção específica}} |

**Qualidade do relato:** o problema deve ser observável e localizado. Evite “interface confusa” sem dizer **o que**, **onde**, **quando** e **para quem**.

### 6. Boas práticas — heurísticas não violadas (atividade didática)

| Heurística sem violação | Exemplo no sistema | Evidência | Por que atende |
|---|---|---|---|
| {{H4}} | {{...}} | {{print}} | {{...}} |

> Repita a seção para A02, A03... um avaliador por integrante.

## 7. Consolidação da equipe

Problemas iguais ou muito semelhantes encontrados por avaliadores diferentes devem ser consolidados, preservando quem os encontrou.

| ID consolidado | Achados individuais | Heurística | Problema | Severidade final | Prioridade | Responsável pela correção |
|---|---|---|---|---:|---|---|
| HC01 | V01(A01), V04(A02) | H1 | {{...}} | {{...}} | alta | {{...}} |

## 8. Síntese e plano de melhoria

- Quantidade de problemas por heurística e severidade.
- Problemas críticos/graves que bloqueiam teste ou release.
- Padrões recorrentes entre telas.
- Correções que serão feitas antes/para a avaliação com usuários.

## Checklist

- [ ] Cada integrante fez uma inspeção completa e identificada.
- [ ] Todas as telas/estados relevantes foram examinados.
- [ ] Estados administrativos, filtros, relatórios, históricos, processamento e erros foram incluídos quando existentes.
- [ ] A inspeção avaliou a interface/protótipo, não o mérito técnico do algoritmo/modelo.
- [ ] H1–H10 aparecem na matriz de cobertura de cada avaliador.
- [ ] Parte de violações contém apenas violações, sem “forçar” exemplos.
- [ ] Todo problema tem print/localização e contexto.
- [ ] Severidade possui justificativa, não apenas número.
- [ ] Recomendação resolve a causa ou reduz o impacto.
- [ ] Achados duplicados foram consolidados ao final.
