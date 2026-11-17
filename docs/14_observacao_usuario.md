# Entrega 14 — Avaliação de usabilidade por observação de usuários

**Data:** {{dd/mm/aaaa}}  
**Status:** ⬜ não iniciada  
**Responsabilidade:** solução consolidada por equipe. O número de participantes finais observados deve ser igual ao número de integrantes, conforme o modelo da disciplina; recomenda-se que cada integrante seja responsável por conduzir/analisar ao menos um participante.

## Objetivo da atividade

Observar usuários representativos realizando tarefas reais ou realisticamente simuladas para identificar problemas de eficácia, eficiência, compreensão e satisfação que não podem ser inferidos apenas por inspeção.

> **Participantes finais não devem ser membros da equipe.** Um integrante pode participar do teste piloto apenas para validar roteiro/equipamentos, sem contar na amostra final.

### Quando o usuário é um perfil profissional especializado

Em TCCs técnicos, o público pode ser DBA, analista, pesquisador, administrador, técnico ou outro especialista. Priorize participantes que possuam relação real com as tarefas. Se não for possível recrutar o perfil ideal, qualquer participante aproximado/proxy deve ser **justificado previamente e tratado como limitação**; não apresente o resultado como equivalente ao de especialistas reais.

O teste avalia a **interação com o protótipo**. Não é necessário que o participante valide o desempenho científico do algoritmo. Resultados simulados podem ser usados quando declarados e coerentes com a tarefa.

Tarefas podem envolver, por exemplo, interpretar um dashboard, configurar uma análise, encontrar uma execução no histórico usando filtros, comparar resultados, gerar relatório, revisar alerta ou administrar permissões.

## A. Fluxograma do processo — equipe

![Fluxograma](../assets/14_testes/fluxograma_avaliacao.svg)

O fluxograma deve representar, no mínimo: planejamento → recrutamento → consentimento → preparação → execução das tarefas/observação → pós-teste → consolidação/análise → recomendações.

## B. Procedimento de preparação e execução — equipe

### Passo 1 — Objetivos e versão avaliada

**Versão/commit/Figma:** {{16/11/2026}}  
**Metas de usabilidade relacionadas:** {{MU01...}}

### Passo 2 — Participantes

| ID | Perfil | Critérios que justificam participação | Integrante responsável |
|---|---|---|---|
| U01 | {{Estudante de graduação em Ciência da Computação (1º semestre, 19 anos — nível iniciante em hardware, sem experiência prática prévia em montagem de computadores).}} | {{Representa fielmente o público-alvo primário do Hardware Quest (estudantes ingressantes que precisam compreender a função básica dos componentes na etapa de Revisão M01 e praticar o encaixe guiado na etapa de Montagem M02), possuindo familiaridade básica com navegação web em desktop/notebook.}} | {{Beatriz}} |
| | U02 | {{Estudante de curso técnico em Informática / Sistemas de Informação (2º período, 20 anos — conhecimento teórico introdutório sobre peças, com pouca prática em bancada).}} | {{Representa o perfil de estudante em fase de consolidação de conceitos de hardware, permitindo avaliar se os signos visuais, alertas de ruptura ([TA]) e atalhos de teclado suportam tanto a consulta rápida quanto a autonomia na montagem sem depender de instruções externas.}} | {{Larissa}} | 

### Passo 3 — Consentimento e privacidade

- Termo/registro de consentimento: {{Apresentação da pesquisa

Esta pesquisa faz parte do Trabalho de Conclusão de Curso (TCC) de graduação em Ciência da Computação do Centro Universitário FEI.

O objetivo é desenvolver e avaliar um jogo sério voltado à aprendizagem de identificação e montagem de componentes de hardware, analisando a usabilidade do jogo, o desempenho dos participantes e sua contribuição para a aprendizagem.Os dados serão utilizados exclusivamente para fins acadêmicos e científicos, no desenvolvimento do Trabalho de Conclusão de Curso.

As informações serão tratadas de forma confidencial e terão acesso restrito aos pesquisadores. Os resultados poderão ser apresentados no trabalho acadêmico, mas sem a divulgação individual dos nomes e endereços de e-mail dos participantes.

A participação nesta pesquisa é voluntária. O participante poderá optar por não participar, sem qualquer prejuízo.

Ao selecionar a opção de aceite, declara que leu e compreendeu as informações apresentadas e que concorda em participar da pesquisa, autorizando o tratamento dos dados informados para as finalidades descritas neste termo.

Identificação dos responsáveis

Pesquisadoras responsáveis: Beatriz Cristina Emerenciano e Larissa Santos Fiuza.

Professor orientador: Rafael Gomes Alves.

Instituição: Centro Universitário FEI.00}}

- Gravação de tela/áudio/vídeo: sim/não e finalidade.
- Forma de anonimização: IDs `U01`, `U02`...
- Local e período de armazenamento: {{...}}

### Passo 4 — Teste piloto

**Data:** {{16/11/2026}}  
**O que foi validado:** roteiro,entendimento das instruções  
**Mudanças após piloto:** {{ em desenvolvimento}}

### Passo 5 — Tarefas

| ID | Cenário/instrução apresentada | Critério de sucesso | Métricas | Ligação com modelo |
|---|---|---|---|---|
| UT01 | {{"Você acabou de entrar no jogo Hardware Quest e quer entender melhor o que cada peça faz antes de começar. Dê uma olhada nas opções disponíveis e descubra qual é a função principal da Placa-mãe.}} | {{resultado observável}} | sucesso, tempo, erros, ajudas, satisfação | {{T01/M01/F01}} |
| UT01 | {{“Você precisa...” sem dizer o controle}} | {{resultado observável}} | sucesso, tempo, erros, ajudas, satisfação | {{T01/M01/F01}} |
| UT01 | {{“Você precisa...” sem dizer o controle}} | {{resultado observável}} | sucesso, tempo, erros, ajudas, satisfação | {{T01/M01/F01}} |
v

### Passo 6 — Protocolo do moderador

1. Receber participante e explicar que **o produto está sendo avaliado, não a pessoa**.
2. Obter consentimento.
3. Aplicar perfil pré-teste mínimo necessário.
4. Ler instruções padronizadas.
5. Observar sem ensinar o caminho; registrar pedidos de ajuda separadamente.
6. Se usar *think aloud*, explicar e aplicar de forma consistente.
7. Após cada tarefa, registrar satisfação/SEQ ou escala definida.
8. Fazer pós-teste/entrevista breve.
9. Encerrar e explicar uso dos dados.

## C. Resultados — por participante

### U01 — {{perfil resumido}}

| Tarefa | Grau de sucesso | Erros | Tipos de erro/dificuldade | Ajudas | Tempo | Satisfação | Evidência/observação |
|---|---|---:|---|---:|---|---|---|
| UT01 | total/parcial/falha | {{n}} | {{...}} | {{n}} | {{mm:ss}} | {{escala}} | {{fala/comportamento}} |

**Link da gravação (se autorizado):** {{...}}  
**Resposta pós-teste:** {{...}}

> Repita para U02, U03...

## D. Consolidação por tarefa

| Tarefa | Taxa de sucesso | Tempo típico | Erros recorrentes | Satisfação | Meta atendida? | Problemas prioritários |
|---|---:|---|---|---|---|---|
| UT01 | {{...}} | {{...}} | {{...}} | {{...}} | sim/não | {{...}} |

## E. Achados e recomendações

| ID | Achado | Evidência (quant. + qual.) | Impacto | Recomendação | Artefatos a revisar |
|---|---|---|---|---|---|
| AU01 | {{...}} | {{2/4 falharam + fala U03...}} | {{...}} | {{...}} | {{MoLIC/Figma/signos...}} |

## F. Comparação com a avaliação heurística

| Problema | Detectado na heurística? | Detectado por usuários? | O que aprendemos |
|---|---|---|---|
| {{...}} | sim/não | sim/não | {{...}} |

## G. Conclusão

A conclusão deve responder:

1. Quais metas de usabilidade foram atingidas?
2. Quais problemas foram recorrentes e com quais perfis/tarefas?
3. O que surpreendeu a equipe?
4. Quais mudanças são prioritárias?
5. Que limitações do teste impedem generalizações amplas?

## Checklist

- [ ] Número de participantes finais atende ao enunciado.
- [ ] Participantes são representativos do público e não são membros da equipe.
- [ ] Se foram usados participantes proxy, a justificativa e a limitação estão explícitas.
- [ ] O teste avalia a interação; não confunde usabilidade do protótipo com desempenho técnico do TCC.
- [ ] Tarefas administrativas/analíticas usadas no teste são rastreáveis a objetivos e cenários.
- [ ] Há consentimento e anonimização.
- [ ] Foi realizado teste piloto.
- [ ] Tarefas têm critérios de sucesso definidos antes do teste.
- [ ] Moderadores não ensinaram o caminho durante a tarefa.
- [ ] Resultados estão separados por usuário e por tarefa.
- [ ] Foram registrados sucesso, erros, ajudas, tempo e satisfação quando aplicáveis.
- [ ] Conclusão combina evidência quantitativa e qualitativa.
- [ ] Achados geram recomendações e atualização da rastreabilidade.
