# Entrega 12 — Planejamento da avaliação de usabilidade (DECIDE)

**Data:** {{16/11/2026}}  
**Status:** 🟩 concluída
**Responsabilidade:** 1 solução por equipe

## Objetivo da atividade

Planejar a avaliação antes de executá-la, ligando perguntas de avaliação a métodos, participantes, tarefas, métricas, aspectos práticos, ética e forma de análise.

## O que está sendo avaliado

Em projetos cuja interface foi criada ou ampliada para a disciplina, o plano deve declarar explicitamente que a avaliação investiga **a qualidade da interação/protótipo**, não a validade científica ou o desempenho técnico do algoritmo/modelo do TCC.

Exemplos de perguntas:

- o DBA consegue localizar e comparar duas execuções?
- o analista entende o significado de um indicador?
- o administrador consegue alterar uma permissão sem risco de erro não percebido?
- o usuário compreende que o processamento está em andamento e consegue recuperar-se de uma falha?
- os filtros ajudam a localizar o histórico relevante?
- um relatório permite identificar a informação necessária para a decisão?

Se o protótipo utiliza dados ou resultados simulados, documente isso no plano.

## A. Método DECIDE

| Etapa | Aplicação no projeto |
|---|---|
| **D — Determine the goals** | Quais objetivos da avaliação? Relacione às metas de usabilidade da Entrega 8. |
| **E — Explore the questions** | Quais perguntas específicas a avaliação deve responder? |
| **C — Choose the evaluation paradigm and techniques** | Quais métodos serão usados e por quê? Ex.: inspeção heurística + observação de usuários. |
| **I — Identify the practical issues** | Participantes, recrutamento, ambiente, equipamentos, piloto, cronograma, responsáveis, riscos técnicos. |
| **D — Decide how to deal with ethical issues** | Consentimento, privacidade, gravação, anonimização, interrupção, dados sensíveis. |
| **E — Evaluate, interpret and present the data** | Como dados quantitativos/qualitativos serão consolidados, comparados às metas e apresentados. |

## B. Perguntas de avaliação

| ID | Pergunta | Método | Métrica/evidência | Critério esperado |
|---|---|---|---|---|
| QA01 | {{Os usuários conseguem acessar a etapa de revisão, consultar um componente (F02 → F03) e iniciar a montagem sem solicitar ajuda?}} | Observação de usuários (Teste de usabilidade) |axa de sucesso na tarefa (T01), número de pedidos de ajuda e cliques fora de fluxo.| {{MU01: ≥ 90% de conclusão sem ajuda externa e média de ≤ 1 erro de navegação por participante.}} |
| QA02 | {{O sistema fornece feedbacks visíveis, claros e imediatos sobre o progresso e o resultado de cada encaixe (F04 → F05)?}} |Avaliação heurística + Observação | Número e severidade de violações na H1 (Visibilidade do status do sistema); tempo de reação do usuário após soltar a peça.| {{MU02: Zero violações críticas/graves na H1 e reconhecimento imediato do status (acerto ou erro) em ≤ 3 segundos.}} |
| QA03 | {{Ao ocorrer uma ruptura de encaixe ([TA] d: componente incorreto ou fora da area de encaixe em F04R), o usuário compreende o erro e se recupera com facilidade?}} | Observação de usuários (Teste com cenário de erro induzido)|Taxa de recuperação autônoma após o alerta [TA], número de tentativas repetidas no mesmo slot errado e relatos verbais (Think-Aloud). | {{MU03: ≥ 85% dos participantes corrigem o posicionamento na tentativa seguinte sem abandonar a tarefa.}} |
| QA04 | {{A linguagem técnica, os signos de hardware e os controles de retorno (Voltar para lista, Concluir) são intuitivos e consistentes entre revisão e montagem?}} |Avaliação heurística + Entrevista pós-teste |Violações na H2 (Correspondência entre o sistema e o mundo real) e H4 (Consistência e padrões); escala de facilidade percebida (1 a 5). | {{MU04: Nota média ≥ 4,0/5,0 na clareza das instruções e ausência de ambiguidade nos rótulos de ação.}} |
| QA05| {{Os elementos interativos, destaques de encaixe (regiao_destacada) e mensagens de erro são acessíveis via teclado e possuem contraste adequado?}} |Razão de contraste medida (texto ≥ 4.5:1; componentes ≥ 3:1), tamanho mínimo de alvo (≥ 44x44px) e navegação completa por Tab/Enter.  | {{MU05: 100% dos fluxos principais e alertas [TA] operáveis via teclado e em conformidade com WCAG 2.2 nível AA.}} |


## C. Escopo e participantes

| Item | Planejamento |
|---|---|
| Perfis | {{Estudantes de graduação em áreas de computação/tecnologia (calouros ou períodos iniciais) e estudantes do ensino médio/técnico com interesse em hardware, representando o público-alvo educacional do Hardware Quest (nível iniciante a intermediário em montagem de computadores).}} |
| Critérios de inclusão/exclusão | {{Inclusão: Ter idade ≥ 18 anos (ou consentimento formal), possuir familiaridade básica com navegação web (mouse/teclado) e aceitar o Termo de Consentimento Livre e Esclarecido (TCLE) Exclusão: Técnicos profissionais de manutenção de hardware com experiência avançada (evitando viés de conhecimento prévio na etapa de revisão) e integrantes da própria equipe de desenvolvimento do projeto..}} |
| Nº de participantes | {{30 participantes.}} |
| Ambiente | remoto |
| Dispositivo | {{omputador desktop ou notebook (resolução mínima 1366x768px ou 1440x900px) equipado com mouse/trackpad, teclado físico (para validar acessibilidade e navegação por Tab/Enter) e navegador web atualizado (Google Chrome, Edge ou Firefox).}} |
| Protótipo/versão | {{Protótipo navegável de média/alta fidelidade no Figma (v1.0), contemplando os fluxos completos dos diagramas MoLIC M01 (Etapa de Revisão: telas F01 → F02 → F03 e estado de ruptura F03R) e M02 (Etapa de Montagem: telas F04 → F05 → F06 e estado de ruptura F04R)}} |
| Teste piloto | {{• Quem: 1 colega estudante externo ao grupo de desenvolvimento, conduzido pelo moderador e acompanhado pelo observador.


• Quando: 2 dias antes do início oficial da coleta com os participantes.


• O que validar: Clareza do enunciado das tarefas e do roteiro Think-Aloud, funcionamento de todos os links/hotspots e estados de erro no protótipo do Figma, calibração do tempo total da sessão (meta de 15–20 min) e adequação da planilha de registro de métricas.}} |

## D. Lista de tarefas de avaliação

| ID | Cenário neutro entregue ao usuário | Objetivo oculto da avaliação | Critério de sucesso | Tempo-limite (se houver) |
|---|---|---|---|---|
| UT01 | {{"Você acabou de entrar no jogo Hardware  e quer entender melhor o que cada peça faz antes de começar. Dê uma olhada nas peças disponíveis e descubra qual é a função principal da Placa-mãe."}} | {{Validar o acionamento do acesso ubíquo (F01), a navegação na lista de componentes (F02) e a leitura dos signos detalhados na cena Examinar componente (F03).}} | {{T01 / O01 (M01): Validar o acionamento do acesso ubíquo (F01), a navegação na lista de componentes (F02) e a leitura dos signos detalhados na cena Examinar componente (F03).}} | {{O participante acessa a área de revisão, seleciona a Placa-mãe e identifica verbalmente sua função na tela de detalhes (F03) sem precisar de ajuda do moderador.}} |2 minutos|
| UT02 | {{"Agora que você já viu a Placa-mãe, verifique também para que serve a Memória RAM e, em seguida, vá para a parte prática de montagem do computador."}} | {{T02/O02}} | {{T02 / O01 → O02 (M01): Avaliar a percepção e o uso do fluxo alternativo de retorno (u: voltar para lista / pressup: usuario deseja consultar outro componente) e a transição de meta (u: iniciar montagem / gco: Montar computador).}} | {{O participante retorna à lista (F02), abre os detalhes da Memória RAM (F03) e aciona o botão para iniciar a montagem (F04) com sucesso.}} |2minutos|

> Uma boa instrução descreve o objetivo do participante sem dizer **onde clicar** ou usar o rótulo exato do controle que está sendo testado.

## E. Instrumentos

- [Modelo de termo de consentimento](../instrumentos/termo_consentimento_modelo.md)
- [Roteiro de teste](../instrumentos/roteiro_teste_usabilidade.md)
- [Planilha de observação](../instrumentos/planilha_observacao_modelo.md)
- [Formulário de avaliação heurística](../instrumentos/formulario_heuristica_modelo.md)
- {{questionário pré/pós-teste}}

## F. Plano de análise

Defina antes dos testes:

- sucesso total / parcial / falha;
- o que conta como erro, dúvida, ajuda e abandono;
- como tempo será medido;
- escala de satisfação pós-tarefa;
- como observações/falas serão codificadas;
- como problemas serão priorizados;
- como comparar resultados às metas de usabilidade.

## Checklist

- [ ] As seis etapas DECIDE foram contextualizadas, não apenas expandidas por sigla.
- [x] Perguntas de avaliação têm método e evidência correspondentes.
- [x] O plano distingue avaliação de IHC de avaliação técnica/científica do TCC.
- [x] Dados ou processamentos simulados no protótipo estão declarados.
- [x] Tarefas vêm de objetivos/cenários relevantes.
- [x] Critérios de sucesso foram definidos antes da coleta.
- [x] Questões práticas e éticas estão resolvidas.
- [x] Instrumentos estão prontos antes da Entrega 13/14.
- [x] Plano diz como dados serão analisados e apresentados.
