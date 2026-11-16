# Entrega 9 — Modelo conceitual e design centrado na comunicação

**Data:** {{dd/mm/aaaa}}  
**Status:** 🟨 em andamento  
**Responsabilidade:** soluções individuais, com consolidação da equipe para mapa de objetivos e esquema de signos.

## Objetivo da atividade

Passar do cenário de problema para uma concepção da interação, explicitando objetivos, tópicos de conversa, falas e signos que a interface deverá comunicar/manipular.

## Transformando resultados técnicos em conceitos compreensíveis

Em TCCs algorítmicos ou orientados a dados, esta entrega deve evitar que a interface exponha apenas estruturas internas do código. Identifique os **conceitos e signos que fazem sentido para o usuário**.

Exemplos:

- `query plan`, custo estimado, recomendação e impacto para um DBA;
- modelo, dataset, versão, execução e métrica para engenheiro de IA;
- período, indicador, grupo, tendência e filtro para gestor/analista;
- alerta, severidade, evidência, responsável e status para analista de segurança.

Se um termo técnico for necessário, modele como será comunicado, explicado e relacionado à tarefa.

Dashboards, relatórios, filtros e CRUDs devem aparecer no modelo conceitual por meio dos **objetivos, signos e conversas** que justificam sua existência.

## 1. Cenários de interação

Para cada cenário de problema, produza uma versão em que a solução já pode ser descrita. **Destaque claramente o texto alterado** em relação ao cenário original.

### CI01 — {{etapa de revisão}}

**Autor(a):** {{Beatriz Cristina Emerenciano — 22.222.041-0}}  
**Origem:** cenário problema {{C01}}

Cenário original (problema):

Lucas, estudante de Ciência da Computação, acessa o jogo para aprender sobre montagem de hardware. Ao entrar na etapa de revisão, encontra uma lista de componentes, mas tem dificuldade para compreender a função de cada um. Na etapa de montagem, não entende claramente onde deve encaixar cada peça e acaba selecionando componentes incorretos. Quando isso acontece, não recebe informações suficientes para compreender o erro, ficando em dúvida sobre como continuar.

Cenário revisado (com soluções):

Lucas, estudante de Ciência da Computação, acessa o jogo para aprender sobre montagem de hardware. Ao entrar na etapa de revisão, encontra uma lista organizada dos componentes disponíveis. Ao selecionar um deles, visualiza uma imagem acompanhada de uma descrição objetiva e das principais funções do componente, facilitando sua identificação e compreensão.

Na etapa de montagem, o jogo destaca visualmente a região em que o próximo componente deve ser encaixado e apresenta três opções de peças para seleção. Lucas escolhe o componente que considera correto e o arrasta até a área indicada. Caso selecione uma peça incorreta, o jogo apresenta um feedback visual informando que a escolha não corresponde ao local indicado e permite uma nova tentativa. Quando o encaixe está correto, o componente é integrado à montagem e o jogo avança para a próxima etapa. Ao concluir a atividade, Lucas visualiza sua pontuação final.
### Diferenças relevantes

| Alteração | Por que foi necessária | Evidência/artefato que justifica |
|---|---|---|
| {{Inclusão de imagens, descrições e funções dos componentes na etapa de revisão.}} | {{Facilitar a identificação e a compreensão dos componentes por usuários iniciantes.}} | {{Protótipo da etapa de revisão e fluxo de telas P01–P04.}} |
| {{Destaque visual da região de encaixe na etapa de montagem.}} | {{Orientar o usuário sobre o local em que o componente deve ser inserido, reduzindo dúvidas durante a atividade.}} | {{Protótipo da etapa de montagem e fluxo de telas P05–P09.}} |

### CI01 — {{etapa de montagem}}

**Autor(a):** {{Larissa Fiuza Santos — 22.123.042-8}}  
**Origem:** cenário problema {{C02}}

Cenário original (problema):

Mariana, 32 anos, trabalha como analista administrativa e deseja aprender mais sobre os componentes de hardware para conseguir compreender melhor o funcionamento do computador utilizado na empresa. Ao acessar o jogo, ela tenta iniciar a etapa de montagem, mas percebe que não possui conhecimento suficiente para reconhecer os componentes apresentados. Durante a atividade, Mariana fica em dúvida sobre a função de cada peça e não sabe como identificar qual delas deve selecionar. Além disso, por não ter experiência com jogos que utilizam movimentação de objetos, apresenta dificuldade para arrastar os componentes até os locais indicados.

Cenário revisado (com soluções):
Mariana, 32 anos, trabalha como analista administrativa e deseja aprender mais sobre os componentes de hardware para conseguir compreender melhor o funcionamento do computador utilizado na empresa. Ao acessar o jogo, decide iniciar pela etapa de revisão, na qual encontra uma lista organizada dos componentes de hardware. Ao selecionar cada componente, visualiza uma imagem acompanhada de uma descrição e das suas principais funções, permitindo que compreenda melhor as características das peças antes de iniciar a montagem.
### Diferenças relevantes

| Alteração | Por que foi necessária | Evidência/artefato que justifica |
|---|---|---|
| {{Apresentação de três opções de componentes para seleção.}} | {{Permitir que o usuário pratique o reconhecimento e a escolha dos componentes adequados.}} | {{Descrição da mecânica de montagem do jogo.}} |
| {{Feedback visual para seleções incorretas.}} | {{Informar o resultado da ação e permitir que o usuário compreenda que precisa realizar uma nova tentativa.}} | {{Requisito de prevenção e recuperação de erros e fluxo de estados da montagem.}} |
| {{Apresentação da pontuação final.}} | {{Permitir que o participante visualize seu resultado ao concluir a atividade.}} | {{Requisito funcional da etapa de montagem.}} |


## 2. Design centrado na comunicação

**Nome do cenário:** {{CI01}}

| Tópico > subtópico | Falas e signos envolvidos | Intenção/efeito esperado |
|---|---|---|
| {{objetivo}} | U: Quero aprender a identificar os componentes de hardware e entender como realizar a montagem de um computador.| {{Expressar a necessidade da usuária de adquirir conhecimentos básicos sobre hardware por meio do jogo.}} |
| > {{Acessar o jogo}} | {{U: Vou acessar o jogo para começar a aprender.D: Menu principal com as opções "Revisar componentes" e "Jogar".}} | {{Permitir que a usuária compreenda as opções disponíveis e identifique como iniciar sua aprendizagem.}} |
| > {{subtópico}} | {{Consultar os componentes}} | {{...}} |
| > {{subtópico}} | {{U: Não conheço muito bem essas peças. Quero entender para que servem.D: Lista de componentes com opções como gabinete, placa-mãe, memória RAM, HD, fonte de alimentação e placa de vídeo.}} | {{Apresentar os componentes de maneira organizada, facilitando sua identificação e consulta.}} |
| > {{Visualizar informações}} | {{U: Vou selecionar a memória RAM para entender sua função.D: Exibição de imagem, descrição e principais funções da memória RAM, acompanhadas de uma opção para retornar à lista.}} | {{Permitir que Mariana compreenda as características e funções dos componentes antes de iniciar a montagem.}} |

**Nome do cenário:** {{CI02}}

| Tópico > subtópico | Falas e signos envolvidos | Intenção/efeito esperado |
|---|---|---|
| > {{Iniciar a montagem}} | {{U: Agora quero colocar em prática o que aprendi.D: Botão "Jogar" e apresentação da mesa com o computador e os componentes disponíveis.}} | {{Indicar como iniciar a atividade prática e estabelecer uma transição entre a revisão e a montagem.}} |
| > {{Identificar o local de encaixe}} | {{U: Qual peça devo colocar primeiro e onde devo encaixá-la?D: Destaque visual da região de encaixe e apresentação de três opções de componentes.}} | {{Orientar a usuária visualmente, facilitando a identificação do local em que o próximo componente deve ser inserido.}} |
| > {{Selecionar e arrastar o componente}} | {{U: Vou selecionar a peça que acredito ser correta e arrastá-la até a região indicada.D: Indicação visual das peças disponíveis e da área de destino para o encaixe.}} | {{Permitir que a usuária realize a interação de seleção e movimentação do componente utilizando o mouse ou o toque na tela.}} |
| > {{Lidar com uma seleção incorreta}} | {{U: Escolhi uma peça, mas ela não corresponde ao local indicado. Como posso continuar?D: Mensagem de feedback informando que o componente selecionado está incorreto e permitindo uma nova tentativa.}} | {{Comunicar o erro de maneira compreensível e permitir que a usuária retome a atividade sem precisar reiniciá-la.}} |
| > {{Confirmar o encaixe correto}} | {{U: Consegui encaixar o componente corretamente.D: Feedback visual indicando o encaixe correto e apresentação da próxima etapa da montagem.}} | {{Reforçar o acerto realizado e orientar a continuidade da atividade.}} |
| > {{Finalizar a montagem}} | {{U: Concluí a montagem dos componentes.

D: Tela de conclusão com a pontuação obtida na atividade.}} | {{Informar que a atividade foi concluída e permitir que a usuária visualize seu desempenho.}} |

**Convenção:** `U` = usuário; `D` = preposto do designer/sistema, conforme a abordagem de Engenharia Semiótica adotada na disciplina.

## 3. Mapa de objetivos

Cada integrante apresenta seu mapa e a equipe cria um **mapa consolidado**, eliminando duplicidades e resolvendo conflitos de nomenclatura.

![Mapa consolidado](../assets/09_modelo_conceitual/mapa_objetivos.svg)

### Dicionário de objetivos

| ID | Objetivo | Persona(s) | Cenário(s) | Prioridade |
|---|---|---|---|---|
| O01 | {{...}} | {{P01}} | {{CI01}} | {{...}} |

## 4. Esquema conceitual de signos

Consolide as informações em **uma tabela única**.

| Grupo | Signo | Origem | Observações/semântica | Tipo de conteúdo | Restrição | Valor padrão | Prevenção | Recuperação |
|---|---|---|---|---|---|---|---|---|
| Credenciais | usuário | domínio | {{...}} | texto | não nulo | — | {{...}} | {{...}} |

### Regras para os signos

- Use o vocabulário do domínio do usuário.
- Evite duplicar o mesmo conceito com nomes diferentes.
- Diferencie informação fornecida pelo usuário, produzida pelo sistema e derivada do domínio.
- Registre prevenção e recuperação apenas quando fizer sentido; explique as siglas usadas.

## Síntese

Quais objetivos/tópicos/signos deverão necessariamente aparecer nos diagramas MoLIC?

## Checklist

- [ ] Cenários de interação mostram alterações em relação aos cenários de problema.
- [ ] Cada solução individual identifica autor e cenário de origem.
- [ ] Tópicos/falas/signos são coerentes com objetivos do usuário.
- [ ] Mapas individuais foram consolidados.
- [ ] O esquema de signos está em uma tabela única e sem duplicações conceituais.
- [ ] Nomes de objetivos/signos serão reutilizados na Entrega 10.
- [ ] Em TCC técnico, signos representam conceitos do domínio compreensíveis ao usuário, não apenas variáveis/estruturas internas.
- [ ] Padrões como dashboard, relatório, filtros, administração e CRUD possuem objetivos e signos correspondentes.
- [ ] A interface comunica não só o resultado técnico, mas também seu significado para a tarefa.
