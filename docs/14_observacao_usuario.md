# Entrega 14 — Avaliação de usabilidade por observação de usuários

**Data:** 25/11/2026  
**Status:** ✅ Concluída  
**Responsabilidade:** Solução consolidada pela equipe — Beatriz Cristina Emerenciano e Larissa Santos Fiuza.

## Objetivo da atividade

Observar usuários representativos realizando tarefas no Hardware Quest, jogo sério voltado à aprendizagem de identificação e montagem de componentes de hardware, com o objetivo de identificar problemas de eficácia, eficiência, compreensão e satisfação que não podem ser inferidos apenas por inspeção.

A avaliação busca identificar dificuldades na utilização da interface, na compreensão das informações apresentadas e na execução das atividades de montagem dos componentes de um computador.

## A. Fluxograma do processo — equipe

![Fluxograma](../assets/14_testes/fluxograma_avaliacao.svg)

O processo de avaliação foi organizado nas seguintes etapas:

Planejamento → Recrutamento → Consentimento → Preparação → Execução das tarefas e observação → Pós-teste → Consolidação e análise → Recomendações.

## B. Procedimento de preparação e execução — equipe

### Passo 1 — Objetivos e versão avaliada

**Versão/commit/Figma:** 16/11/2026.

**Metas de usabilidade relacionadas:**

- Avaliar a facilidade de navegação e utilização da interface.
- Verificar a compreensão das informações sobre os componentes de hardware.
- Avaliar a autonomia dos usuários durante as atividades de montagem.
- Verificar a compreensão dos signos visuais, alertas e recursos de ajuda.
- Avaliar a satisfação dos usuários durante a interação com o Hardware Quest.

### Passo 2 — Participantes

| ID | Perfil | Critérios que justificam participação | Integrante responsável |
|---|---|---|---|
| U01 | Estudante de graduação em Ciência da Computação, 21 anos, 5º semestre, com conhecimento elevado de hardware e experiência prática em montagem de computadores. | Representa estudantes da área de computação que possuem conhecimento prévio sobre hardware, permitindo avaliar a qualidade da simulação, a clareza das explicações e a facilidade de utilização dos recursos disponibilizados pelo jogo. | Beatriz |
| U02 | Estudante de graduação em Engenharia de Computação, 21 anos, 6º semestre, com conhecimento básico a intermediário de hardware e experiência profissional anterior na área. | Representa estudantes da área de computação que possuem conhecimentos sobre hardware, mas que ainda podem apresentar dificuldades relacionadas à identificação e montagem de determinados componentes, permitindo avaliar a efetividade das orientações e dos recursos de interação. | Larissa |

Ambos os participantes informaram que não costumam utilizar simuladores educacionais.

Os participantes apresentam níveis distintos de conhecimento sobre hardware, possibilitando identificar diferentes percepções e dificuldades durante a interação com o Hardware Quest.

Como limitação, ambos possuem experiência prévia com hardware e encontram-se em semestres mais avançados de seus respectivos cursos, não representando integralmente o perfil de estudantes ingressantes sem experiência prática.

### Passo 3 — Consentimento e privacidade

- **Termo/registro de consentimento:**

#### Apresentação da pesquisa

Esta pesquisa faz parte do Trabalho de Conclusão de Curso (TCC) de graduação em Ciência da Computação do Centro Universitário FEI.

O objetivo é desenvolver e avaliar um jogo sério voltado à aprendizagem de identificação e montagem de componentes de hardware, analisando a usabilidade do jogo, o desempenho dos participantes e sua contribuição para a aprendizagem.

Os dados serão utilizados exclusivamente para fins acadêmicos e científicos, no desenvolvimento do Trabalho de Conclusão de Curso.

As informações serão tratadas de forma confidencial e terão acesso restrito aos pesquisadores. Os resultados poderão ser apresentados no trabalho acadêmico, mas sem a divulgação individual dos nomes e endereços de e-mail dos participantes.

A participação nesta pesquisa é voluntária. O participante poderá optar por não participar, sem qualquer prejuízo.

Ao selecionar a opção de aceite, declara que leu e compreendeu as informações apresentadas e que concorda em participar da pesquisa, autorizando o tratamento dos dados informados para as finalidades descritas neste termo.

#### Identificação dos responsáveis

Pesquisadoras responsáveis: Beatriz Cristina Emerenciano e Larissa Santos Fiuza.

Professor orientador: Rafael Gomes Alves.

Instituição: Centro Universitário FEI.

- **Gravação de tela/áudio/vídeo:** Autorização específica não registrada nas fichas de avaliação.
- **Forma de anonimização:** Identificação dos participantes pelos IDs `U01` e `U02`.
- **Local e período de armazenamento:** Não registrado nas fichas de avaliação.

### Passo 4 — Teste piloto

**Data:** 16/11/2026.

**O que foi validado:** Roteiro de avaliação e entendimento das instruções apresentadas aos participantes.

**Mudanças após piloto:** Não registradas nas fichas de avaliação.

### Passo 5 — Tarefas

| ID | Cenário/instrução apresentada | Critério de sucesso | Métricas | Ligação com modelo |
|---|---|---|---|---|
| UT01 | Você acabou de entrar no jogo Hardware Quest e quer entender melhor o que cada peça faz antes de começar. Dê uma olhada nas opções disponíveis e descubra qual é a função principal da placa-mãe. | Localizar a informação disponibilizada pelo jogo e identificar corretamente a função principal da placa-mãe. | Sucesso, tempo, erros, ajudas e satisfação. | T01/M01/F01 |
| UT02 | Utilizando os recursos disponíveis no jogo, instale a memória RAM no local adequado. | Selecionar e encaixar corretamente a memória RAM na placa-mãe. | Sucesso, tempo, erros, ajudas e satisfação. | M02 |
| UT03 | Imagine que você tentou instalar uma peça em uma posição incorreta. Descubra como o jogo informa esse problema e como você pode corrigi-lo. | Identificar o alerta apresentado pelo jogo e corrigir a ação na situação preparada. | Sucesso, tempo, erros, ajudas e satisfação. | M02 — feedback e correção |

Durante a avaliação, também foram registradas observações complementares referentes à instalação das ventoinhas, à conexão dos cabos, à identificação dos componentes e à utilização do tutorial.

### Passo 6 — Protocolo do moderador

1. Receber o participante e explicar que **o produto está sendo avaliado, não a pessoa**.
2. Apresentar o termo de consentimento.
3. Aplicar o questionário de perfil pré-teste.
4. Ler as instruções padronizadas das tarefas.
5. Observar a interação sem ensinar diretamente o caminho, registrando dificuldades e pedidos de ajuda.
6. Incentivar o participante a verbalizar seus pensamentos, expectativas e dificuldades durante a interação, utilizando a técnica *think aloud*.
7. Solicitar uma avaliação de satisfação após cada tarefa, utilizando a escala SEQ de 1 a 7.
8. Realizar a entrevista pós-teste para identificar percepções, dificuldades e sugestões de melhoria.
9. Encerrar a avaliação, agradecendo a participação e esclarecendo a finalidade acadêmica dos dados coletados.

## C. Resultados — por participante

### U01 — Estudante com conhecimento elevado em hardware

O participante possui 21 anos, cursa o 5º semestre de Ciência da Computação, possui conhecimento elevado sobre hardware e experiência prática anterior em montagem de computadores.

| Tarefa | Grau de sucesso | Erros | Tipos de erro/dificuldade | Ajudas | Tempo | Satisfação | Evidência/observação |
|---|---|---:|---|---:|---|---|---|
| UT01 | Não individualizado | NR | Nenhuma dificuldade específica registrada. | NR | NR | NR | O participante acertou todas as questões, conforme observação registrada na ficha. |
| UT02 | NR | NR | Dificuldades gerais relacionadas às colisões e à necessidade de clicar em locais específicos. | NR | NR | NR | A execução específica da instalação da memória RAM não foi individualizada na ficha. |
| UT03 | NR | NR | Nenhuma dificuldade específica registrada na tarefa de correção. | NR | NR | NR | O participante identificou a sinalização circular em vermelho e relatou não ter cometido erros na situação abordada pela entrevista. |

**NR:** Não registrado.

#### Observações complementares

O participante apresentou uma percepção positiva do Hardware Quest, comparando-o ao PC Building Simulator.

Embora tenha relatado momentos de desorientação durante a utilização do jogo, informou que as indicações disponibilizadas pelo sistema facilitaram a continuidade das atividades.

A instalação da placa-mãe no gabinete foi considerada a atividade mais fácil, enquanto a instalação das ventoinhas foi considerada a mais difícil.

O participante também destacou dificuldades relacionadas às colisões entre os componentes e à necessidade de clicar em regiões específicas para realizar determinadas ações.

**Link da gravação (se autorizado):** Não informado na ficha.

#### Resposta pós-teste

**1. Qual foi sua primeira impressão do Hardware Quest?**

O participante considerou o jogo bom, destacando sua semelhança com o PC Building Simulator.

**2. Em algum momento você ficou perdido? O que aconteceu?**

Sim. Entretanto, as indicações disponibilizadas pelo jogo facilitaram a interação e permitiram que o participante continuasse realizando as atividades.

**3. Qual tarefa foi mais fácil e qual foi mais difícil? Por quê?**

A instalação da placa-mãe no gabinete foi considerada a atividade mais fácil, enquanto a instalação das ventoinhas foi considerada a mais difícil.

**4. O que achou dos botões, ícones, textos e controles?**

O participante apresentou uma avaliação positiva, considerando o jogo leve e fluido e destacando os minijogos.

**5. Como você interpretou as mensagens de erro?**

O participante relatou não ter cometido erros na situação abordada pela pergunta e identificou a sinalização circular em vermelho.

**6. O jogo ajudou você a compreender os componentes? Como?**

Sim. Apesar de já possuir conhecimentos sobre hardware, considerou que o jogo contribuiu para a compreensão dos componentes.

**7. O que você mais gostou e menos gostou?**

O participante destacou positivamente os gráficos e as explicações disponibilizadas pelo jogo.

Como aspectos negativos, mencionou as colisões e a necessidade de clicar em locais específicos para realizar determinadas ações.

**8. Se pudesse mudar algo na interface, o que mudaria?**

Tornaria a interface mais minimalista.

**9. Usaria o jogo para estudar? Por quê?**

Sim. O participante afirmou que utilizaria o jogo como ferramenta de estudo.

**10. Qual nota de 0 a 10 daria à experiência geral? Por quê?**

Atribuiu nota **9/10**, apontando que o jogo ainda poderia apresentar maior detalhamento.

### U02 — Estudante com conhecimento básico a intermediário em hardware

O participante possui 21 anos, cursa o 6º semestre de Engenharia de Computação, possui conhecimento básico a intermediário sobre hardware e experiência profissional anterior na área.

| Tarefa | Grau de sucesso | Erros | Tipos de erro/dificuldade | Ajudas | Tempo | Satisfação | Evidência/observação |
|---|---|---:|---|---:|---|---|---|
| UT01 | Total | 0 | Nenhuma dificuldade registrada. | 0 | 00:15 | NR | Identificou corretamente a função da placa-mãe. |
| UT02 | Total | 0 | Nenhuma dificuldade registrada. | 0 | 02:00 | NR | Realizou corretamente a instalação da memória RAM. |
| UT03 | NR | NR | Não houve registro específico da execução da tarefa de correção. | NR | NR | NR | Foram registradas dificuldades complementares relacionadas à conexão dos cabos e ao encaixe dos componentes. |

**NR:** Não registrado.

O tempo de UT01 corresponde à interpretação da anotação manuscrita de 0,15 como 15 segundos.

#### Observações complementares

| Atividade | Tempo | Erros | Evidência/observação |
|---|---|---:|---|
| Instalação das ventoinhas | 00:20 | 1 | O participante não utilizou dicas. Foi observado que não era possível solicitar dicas durante o encaixe das peças. |
| Conexão dos cabos | NR | NR | Apresentou dificuldade para identificar as conexões dos fios, aguardando a resposta do sistema sem realizar tentativas aleatórias. |
| Tutorial inicial | NR | NR | O início do tutorial foi considerado confuso, sendo identificada a necessidade de melhorias na orientação inicial. |

**Duração anotada na ficha:** 13 minutos e 32 segundos.

**Link da gravação (se autorizado):** Não informado na ficha.

#### Resposta pós-teste

**1. Qual foi sua primeira impressão do Hardware Quest?**

O participante relatou estranheza inicial durante a utilização do simulador. Entretanto, considerou o jogo fácil de utilizar e suficientemente detalhado para possibilitar a aprendizagem.

**2. Em algum momento você ficou perdido? O que aconteceu?**

Sim. Apresentou dificuldades durante a identificação das conexões dos fios.

**3. Qual tarefa foi mais fácil e qual foi mais difícil? Por quê?**

A instalação dos periféricos foi considerada a tarefa mais fácil, enquanto a identificação dos componentes da placa-mãe foi considerada a mais difícil.

**4. O que achou dos botões, ícones, textos e controles?**

Considerou os elementos da interface muito bons e fáceis de compreender.

**5. Como você interpretou as mensagens de erro?**

O participante mencionou a possibilidade de solicitar dicas e relatou não ter cometido erros na situação abordada pela pergunta.

**6. O jogo ajudou você a compreender os componentes? Como?**

Sim. O participante afirmou que o jogo possibilitou a aprendizagem de diversas informações relacionadas aos componentes de hardware.

**7. O que você mais gostou e menos gostou?**

Destacou positivamente o nível de detalhamento da montagem dos componentes.

Como aspecto negativo, mencionou a limitação da movimentação da câmera.

**8. Se pudesse mudar algo na interface, o que mudaria?**

Reduziria a quantidade de botões e caixas de texto apresentadas na interface.

**9. Usaria o jogo para estudar? Por quê?**

Sim. O participante afirmou que utilizaria o Hardware Quest como ferramenta de estudo, principalmente para atividades relacionadas à faculdade.

**10. Qual nota de 0 a 10 daria à experiência geral? Por quê?**

Atribuiu nota **9/10** à experiência geral.

## D. Consolidação por tarefa

| Tarefa | Taxa de sucesso | Tempo típico | Erros recorrentes | Satisfação | Meta atendida? | Problemas prioritários |
|---|---:|---|---|---|---|---|
| UT01 | 100% dos resultados individualizados (1/1) | 00:15 | Nenhum erro registrado na tarefa. | NR | Sim, para o resultado registrado. | Melhorar a orientação inicial do usuário. |
| UT02 | 100% dos resultados individualizados (1/1) | 02:00 | Nenhum erro registrado na instalação da memória RAM. | NR | Sim, para o resultado registrado. | Revisar as áreas de interação e colisões durante a montagem geral. |
| UT03 | Não determinada | NR | Não individualizados. | NR | Não determinada. | Melhorar o feedback visual e a disponibilidade de dicas durante a montagem. |

As taxas de sucesso das tarefas UT01 e UT02 consideram exclusivamente os resultados individualizados disponíveis nas fichas de avaliação. Não foi possível calcular uma taxa consolidada considerando os dois participantes para essas tarefas.

### Consolidação geral

| Indicador | Resultado |
|---|---|
| Número de participantes | 2 |
| Avaliação geral de U01 | 9/10 |
| Avaliação geral de U02 | 9/10 |
| Média da avaliação geral | 9/10 |
| Participantes que utilizariam o jogo para estudar | 2/2 — 100% |
| Participantes que relataram auxílio na compreensão dos componentes | 2/2 — 100% |
| Participantes que sugeriram simplificação da interface | 2/2 — 100% |
| Participantes que relataram momentos de desorientação | 2/2 — 100% |
| Participantes que apresentaram dificuldades relacionadas à instalação das ventoinhas | 2/2 — 100% |

Os resultados demonstram uma percepção positiva em relação ao Hardware Quest, especialmente quanto à sua proposta educacional, às explicações e ao detalhamento das atividades de montagem.

Ambos os participantes atribuíram nota 9 à experiência geral e afirmaram que utilizariam o jogo como ferramenta de estudo.

Entretanto, também foram identificadas dificuldades relacionadas à orientação dos usuários, à organização visual da interface e à execução de determinadas atividades de montagem.

## E. Achados e recomendações

| ID | Achado | Evidência (quant. + qual.) | Impacto | Recomendação | Artefatos a revisar |
|---|---|---|---|---|---|
| AU01 | Tutorial inicial pouco intuitivo. | U02 apresentou dificuldades na compreensão inicial do tutorial, considerando-o confuso. | Alto | Reestruturar o tutorial em etapas progressivas, apresentando instruções mais claras e contextualizadas. | MoLIC, tutorial e fluxo de interação. |
| AU02 | Excesso de elementos na interface. | 2/2 participantes sugeriram simplificação da interface. U01 solicitou uma interface mais minimalista e U02 sugeriu reduzir a quantidade de botões e caixas de texto. | Médio | Simplificar a interface, priorizando os elementos necessários para cada etapa da interação. | Figma, layout e signos visuais. |
| AU03 | Dificuldades relacionadas às colisões e áreas de clique. | U01 relatou problemas com colisões e com a necessidade de clicar em locais específicos. | Alto | Revisar os colisores dos componentes, ampliar as áreas de interação e melhorar a indicação dos pontos válidos de encaixe. | Protótipo, montagem M02 e signos visuais. |
| AU04 | Limitação da movimentação da câmera. | U02 apontou a câmera muito fixa como um aspecto negativo da experiência. | Médio | Permitir maior liberdade de movimentação da câmera para facilitar a visualização dos componentes durante a montagem. | Protótipo e controles de câmera. |
| AU05 | Dificuldade na identificação das conexões dos cabos. | U02 relatou ter ficado perdido durante a conexão dos fios e apresentou dificuldades para identificar os locais adequados. | Alto | Adicionar sinalizações visuais nos conectores compatíveis e apresentar orientações contextualizadas durante a conexão dos cabos. | MoLIC, montagem M02 e signos visuais. |
| AU06 | Indisponibilidade de dicas durante determinadas etapas da montagem. | Foi registrado que U02 não conseguia solicitar dicas durante o encaixe das peças. | Alto | Disponibilizar dicas contextualizadas durante as atividades de encaixe, permitindo que o usuário solicite ajuda quando necessário. | Sistema de ajuda, MoLIC e montagem M02. |
| AU07 | Possibilidade de ampliar o detalhamento educacional. | U01 atribuiu nota 9/10 e apontou a necessidade de maior detalhamento. | Médio | Disponibilizar informações complementares sobre os componentes e suas funções de maneira opcional, evitando sobrecarregar a interface principal. | Revisão M01 e conteúdos educacionais. |
| AU08 | Dificuldade na instalação das ventoinhas. | U01 considerou a instalação das ventoinhas a atividade mais difícil. U02 apresentou um erro durante a execução dessa atividade. | Alto | Melhorar as indicações de posicionamento, revisar os encaixes e disponibilizar orientações específicas para a instalação das ventoinhas. | Montagem M02, colisores e signos visuais. |

A classificação de impacto considera a recorrência dos problemas identificados e sua potencial interferência na autonomia dos usuários durante a execução das atividades.

Os problemas classificados como de alto impacto estão principalmente relacionados à execução das tarefas, enquanto os problemas de médio impacto estão relacionados à organização visual, à liberdade de interação e ao detalhamento da experiência educacional.

## F. Comparação com a avaliação heurística

| Problema | Detectado na heurística? | Detectado por usuários? | O que aprendemos |
|---|---|---|---|
| Tutorial inicial confuso. | Não registrado | Sim | A orientação inicial precisa apresentar instruções mais claras para facilitar a adaptação dos usuários ao jogo. |
| Excesso de elementos na interface. | Não registrado | Sim | Mesmo considerando a interface compreensível, os participantes identificaram a necessidade de reduzir a quantidade de elementos visuais. |
| Dificuldades relacionadas às colisões e áreas específicas de clique. | Não registrado | Sim | A precisão exigida durante determinadas interações pode dificultar a execução das atividades. |
| Limitação da movimentação da câmera. | Não registrado | Sim | A liberdade de movimentação da câmera pode contribuir para a visualização e identificação dos componentes. |
| Dificuldade na identificação das conexões dos cabos. | Não registrado | Sim | Os usuários podem necessitar de sinalizações adicionais para identificar corretamente os pontos de conexão. |
| Indisponibilidade de dicas durante o encaixe das peças. | Não registrado | Sim | Os recursos de ajuda devem permanecer disponíveis durante as etapas em que os usuários apresentam maiores dificuldades. |
| Dificuldade na instalação das ventoinhas. | Não registrado | Sim | Uma mesma atividade pode apresentar dificuldades para usuários com diferentes níveis de conhecimento sobre hardware. |
| Necessidade de maior detalhamento educacional. | Não registrado | Sim | Informações complementares podem aumentar a contribuição do jogo para usuários com diferentes níveis de conhecimento. |

Os registros da avaliação heurística anterior não constam nas fichas utilizadas nesta entrega. Portanto, não é possível determinar quais problemas já haviam sido identificados anteriormente por meio dessa avaliação.

Entretanto, os problemas observados apresentam relação com princípios de usabilidade, especialmente:

- Visibilidade do estado do sistema.
- Controle e liberdade do usuário.
- Prevenção de erros.
- Reconhecimento em vez de memorização.
- Design estético e minimalista.
- Ajuda e documentação.

A observação dos usuários permitiu identificar dificuldades práticas de interação, principalmente relacionadas à montagem dos componentes, à movimentação da câmera, à utilização das dicas e à interpretação das orientações disponibilizadas pelo sistema.

## G. Conclusão

A avaliação de usabilidade por observação de usuários permitiu identificar aspectos positivos e oportunidades de melhoria no Hardware Quest, considerando a interação de participantes com diferentes níveis de conhecimento sobre hardware.

### 1. Quais metas de usabilidade foram atingidas?

Os resultados demonstraram uma percepção positiva quanto à facilidade de utilização do jogo, à compreensão das informações disponibilizadas e à sua contribuição para a aprendizagem.

Ambos os participantes atribuíram nota 9 de 10 à experiência geral, afirmaram que utilizariam o Hardware Quest como ferramenta de estudo e relataram que o jogo contribuiu para a compreensão dos componentes de hardware.

Nas tarefas com resultados individualizados, foi possível observar que U02 identificou corretamente a função da placa-mãe e realizou a instalação da memória RAM sem erros ou necessidade de ajuda.

Esses resultados indicam aspectos positivos relacionados à eficácia, à compreensão e à satisfação dos usuários.

Entretanto, as dificuldades observadas durante outras atividades demonstram que a autonomia dos usuários e a eficiência das interações ainda podem ser aprimoradas.

### 2. Quais problemas foram recorrentes e com quais perfis/tarefas?

Os principais problemas recorrentes estiveram relacionados à orientação dos usuários, à organização visual da interface e à instalação das ventoinhas.

Ambos os participantes relataram momentos de desorientação durante a interação com o jogo e sugeriram a simplificação da interface.

O participante U01, que possui conhecimento elevado sobre hardware, apresentou dificuldades relacionadas às colisões e à necessidade de clicar em locais específicos para realizar determinadas ações.

O participante U02, que possui conhecimento básico a intermediário, apresentou dificuldades relacionadas à compreensão inicial do tutorial, à identificação das conexões dos cabos e à movimentação da câmera.

A instalação das ventoinhas apresentou dificuldades para ambos os participantes, indicando a necessidade de revisão dessa atividade.

### 3. O que surpreendeu a equipe?

Um aspecto relevante foi a avaliação positiva do Hardware Quest por parte dos dois participantes, independentemente de seus diferentes níveis de conhecimento sobre hardware.

Mesmo o participante que já possuía conhecimento elevado sobre os componentes afirmou que utilizaria o jogo como ferramenta de estudo, indicando seu potencial de utilização também como recurso de revisão e consolidação de conhecimentos.

Outro aspecto relevante foi a coexistência de avaliações positivas sobre a interface com sugestões de simplificação visual.

Embora os participantes tenham considerado o jogo compreensível e tenham apresentado avaliações positivas, ambos identificaram oportunidades de redução da quantidade de elementos visuais apresentados.

Também chamou a atenção a dificuldade relacionada à instalação das ventoinhas, identificada nos dois perfis avaliados.

### 4. Quais mudanças são prioritárias?

Com base nos resultados obtidos, foram identificadas as seguintes mudanças prioritárias:

1. Reestruturar o tutorial inicial, apresentando instruções mais claras e progressivas.
2. Melhorar as sinalizações relacionadas à identificação e conexão dos cabos.
3. Revisar as colisões e as áreas de interação dos componentes.
4. Disponibilizar dicas contextualizadas durante o encaixe das peças.
5. Melhorar as orientações e os mecanismos de instalação das ventoinhas.
6. Simplificar a interface, reduzindo elementos visuais desnecessários.
7. Ampliar a liberdade de movimentação da câmera.
8. Disponibilizar informações complementares sobre os componentes de maneira opcional.

Essas alterações buscam aumentar a autonomia dos usuários, reduzir dificuldades durante a montagem e preservar os aspectos positivos identificados na experiência educacional.

### 5. Que limitações do teste impedem generalizações amplas?

A principal limitação da avaliação está relacionada ao número reduzido de participantes, uma vez que foram observados apenas dois usuários.

Embora ambos pertençam a cursos relacionados à área de computação, possuem experiência prévia com hardware e encontram-se em semestres mais avançados de seus respectivos cursos.

Dessa forma, os resultados não podem ser generalizados para todos os perfis do público-alvo, principalmente estudantes ingressantes que ainda não possuem experiência prática com identificação e montagem de computadores.

Além disso, nem todas as métricas previstas no roteiro foram registradas de maneira individualizada nas fichas de avaliação. A ausência de determinados registros de tempo, quantidade de erros, ajudas e satisfação por tarefa limita a realização de uma comparação quantitativa mais aprofundada.

Outra limitação refere-se à avaliação da aprendizagem. Embora os participantes tenham relatado que o jogo contribuiu para a compreensão dos componentes de hardware, essa percepção não constitui, isoladamente, uma comprovação de ganho de aprendizagem.

Apesar dessas limitações, a avaliação permitiu identificar problemas relevantes de usabilidade e obter informações que contribuem para o aprimoramento do Hardware Quest.

## Checklist

- [x] Número de participantes finais atende ao enunciado.
- [ ] Participantes representativos do público e confirmação de que não são membros da equipe.
- [x] As limitações relacionadas aos perfis dos participantes estão explícitas.
- [x] O teste avalia a interação e não confunde usabilidade do protótipo com desempenho técnico do TCC.
- [x] As tarefas utilizadas no teste possuem objetivos relacionados ao sistema.
- [ ] Há registro completo de consentimento.
- [x] Os participantes foram anonimizados.
- [x] Foi realizado teste piloto, conforme informação registrada no planejamento.
- [x] Tarefas possuem critérios de sucesso definidos antes do teste.
- [ ] Ausência de intervenções dos moderadores confirmada nos registros.
- [x] Resultados estão separados por usuário e por tarefa.
- [x] Foram registrados sucesso, erros, ajudas, tempo e satisfação quando disponíveis nas fichas.
- [x] Conclusão combina evidências quantitativas e qualitativas.
- [x] Achados geram recomendações e indicam os artefatos que devem ser revisados.
- [ ] Comparação com os registros da avaliação heurística anterior.
- [ ] Atualização da rastreabilidade nos artefatos do projeto.
