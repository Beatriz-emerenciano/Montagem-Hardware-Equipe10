# Entrega 8 — Ciclo de vida e engenharia de usabilidade

**Data:** {{05/11/2026}}  
**Status:**🟩 concluída 
**Responsabilidade:** 1 solução por equipe

## Objetivo da atividade

Transformar o conhecimento acumulado sobre usuários, tarefas, plataforma e contexto em princípios e **metas de usabilidade verificáveis**, mantendo o caráter iterativo do projeto.

## Delimitação do sistema interativo

Antes das características da plataforma, separe:

| Camada | O que pertence ao projeto | O que será avaliado em IHC |
|---|---|---|
| contribuição técnica do TCC | {{modelo}} | interface de etapa de revisão e montagem(Jogo) |
| camada de interação da disciplina | {{interface}} |acessibilidade |
| dados simulados | {{layout}} | {{usabilidade}} |

Em um protótipo de disciplina, é aceitável simular processamento ou resultados quando a implementação técnica não estiver integrada, desde que isso seja declarado e a simulação seja suficiente para avaliar a interação.

## 1. Características da plataforma

| Característica | Descrição | Consequência para IHC |
|---|---|---|
| Software | {{O jogo será desenvolvido como uma aplicação web, utilizando HTML para estruturar as telas, CSS para estilizar a interface, JavaScript para implementar as interações e Three.js para renderizar os modelos tridimensionais dos componentes de hardware.}} | {{A interface deve apresentar organização visual, navegação simples e elementos interativos de fácil identificação. Também deve funcionar adequadamente em navegadores compatíveis, sem exigir que o usuário instale um programa específico.}} |
| Hardware/dispositivos | {{O jogo poderá ser acessado por computadores e notebooks, utilizando mouse e teclado, e por dispositivos móveis, utilizando a tela sensível ao toque. O desempenho dependerá das características do dispositivo utilizado.}} | {{A interface deve considerar diferentes tamanhos de tela e formas de interação. Os componentes devem ser apresentados de maneira visível, e as ações de seleção e arrastar e soltar devem ser adaptadas tanto ao mouse quanto ao toque.}} |
| Capacidades | {{O jogo oferece duas funcionalidades principais: uma etapa de revisão, que apresenta imagens, descrições e funções dos componentes, e uma etapa de montagem, na qual o usuário seleciona e arrasta os componentes para os locais indicados. Também apresenta feedback sobre os encaixes e pontuação ao final da atividade.}} | {{As funcionalidades devem ser apresentadas de forma intuitiva, permitindo que o usuário compreenda as instruções, identifique os componentes e realize as ações sem dificuldades. O feedback deve informar se a escolha realizada está correta ou incorreta.}} |
| Restrições | {{O jogo depende de um navegador compatível com os recursos utilizados no desenvolvimento. A visualização dos modelos tridimensionais também pode exigir dispositivos com capacidade gráfica adequada. Além disso, telas muito pequenas podem dificultar a visualização e a movimentação dos componentes.}} | {{É necessário considerar a compatibilidade com diferentes navegadores e dispositivos, além de evitar excesso de informações na tela. Os elementos interativos devem possuir tamanho adequado e as instruções devem ser claras para usuários iniciantes.}} |
| Conectividade/latência | {{Por ser uma aplicação web, o primeiro acesso e o carregamento de imagens, modelos tridimensionais e demais arquivos podem depender de uma conexão com a internet. A velocidade de carregamento pode variar conforme a conexão utilizada.}} | {{A interface deve informar quando o conteúdo estiver sendo carregado, evitando que o usuário pense que o jogo deixou de responder. Sempre que possível, os arquivos devem ser otimizados para reduzir o tempo de carregamento e tornar a navegação mais fluida.}} |
| Segurança/privacidade | {{O jogo tem finalidade educacional e não necessita coletar informações pessoais para permitir a realização das atividades. A avaliação acadêmica poderá utilizar formulários separados para coletar respostas dos pré-testes, pós-testes e questionário SUS.}} | {{Deve-se evitar solicitar dados pessoais desnecessários durante a utilização do jogo. As instruções sobre a pesquisa e a coleta de dados devem ser apresentadas de maneira transparente, garantindo que os participantes compreendam a finalidade das informações coletadas.}} |
| Volume de dados/histórico | {{jogo trabalha com um conjunto limitado e previamente definido de componentes de hardware, como gabinete, placa-mãe, memória RAM, HD, fonte de alimentação e placa de vídeo. Não foi prevista, até o momento, a utilização de um banco de dados com histórico individual dos jogadores.}} | {{Como a quantidade de informações é reduzida, não há necessidade de implementar mecanismos complexos de busca, filtros ou paginação. Os componentes podem ser apresentados diretamente em uma lista organizada, facilitando a consulta e a navegação.}} |
| Tempo de processamento | {{O processamento está relacionado principalmente ao carregamento e à renderização dos modelos tridimensionais, à movimentação dos componentes e à verificação dos encaixes durante a montagem.}} | {{As interações devem apresentar respostas rápidas, principalmente durante o arrastar e soltar. Quando houver processamento ou carregamento mais demorado, é importante fornecer feedback visual para indicar que o sistema está executando uma ação.}} |
| Papéis/permissões | {{O jogo possui como usuário principal o participante, que acessa as etapas de revisão e montagem. Não foi prevista, até o momento, a existência de diferentes níveis de acesso, contas de usuários ou painel administrativo.}} | {{A interface deve priorizar o acesso direto às atividades, sem exigir cadastro ou autenticação desnecessária. A navegação deve ser simples e permitir que o participante compreenda como iniciar, realizar e concluir as atividades.}} |

## 2. Princípios gerais do projeto

Inclua apenas normas, leis, padrões e princípios realmente relevantes, explicando **como** afetam o projeto. Não transforme esta seção em lista de links.

| Princípio/norma | Aplicabilidade ao contexto | Decisão/requisito decorrente | Fonte |
|---|---|---|---|
| Contexto de uso | {{O jogo será utilizado por estudantes de Ciência da Computação iniciantes e pessoas autodidatas interessadas em aprender sobre hardware. O acesso poderá ocorrer por computadores, notebooks ou dispositivos móveis, em ambientes como casa e faculdade. Os usuários poderão consultar informações sobre os componentes e realizar atividades práticas de montagem.}} | {{esenvolver uma interface simples e intuitiva, com instruções claras e linguagem acessível para iniciantes. Considerar diferentes tamanhos de tela e formas de interação, como mouse e toque. Organizar as etapas de revisão e montagem de maneira que o usuário consiga compreender e executar as atividades.}} | Entregas 1 e 3; ISO 9241-11:2018.|
| LGPD, se aplicável | {{A legislação é aplicável à pesquisa caso sejam coletados dados pessoais dos participantes, como endereços de e-mail ou informações que permitam identificá-los, inclusive por meio dos formulários de pré-teste, pós-teste e avaliação SUS.}} | {{Coletar somente os dados necessários para os objetivos da pesquisa, informar aos participantes a finalidade da coleta e restringir o acesso às respostas. Evitar a solicitação de informações pessoais desnecessárias e apresentar os resultados de maneira que os participantes não sejam identificados.}} | {{Lei nº 13.709/2018, especialmente art. 6º; Autoridade Nacional de Proteção de Dados (ANPD).}} |
| Acessibilidade | {{Por ser uma aplicação web, o jogo deve considerar usuários com diferentes capacidades e necessidades de interação. As informações são apresentadas por textos, imagens e modelos tridimensionais, enquanto a montagem exige interação por arrastar e soltar.}} | {{Utilizar textos legíveis, contraste adequado entre texto e fundo, descrições textuais para imagens informativas, botões identificáveis e instruções claras. Evitar transmitir informações somente por cores. Considerar alternativas de interação para usuários que tenham dificuldade em utilizar o mouse ou a tela sensível ao toque.}} | {{W3C – Web Content Accessibility Guidelines (WCAG) 2.2.}} |
| {{Princípio/norma	Aplicabilidade ao contexto	Decisão/requisito decorrente	Fonte
Contexto de uso	O jogo será utilizado por estudantes de Ciência da Computação iniciantes e pessoas autodidatas interessadas em aprender sobre hardware. O acesso poderá ocorrer por computadores, notebooks ou dispositivos móveis, em ambientes como casa e faculdade. Os usuários poderão consultar informações sobre os componentes e realizar atividades práticas de montagem.	Desenvolver uma interface simples e intuitiva, com instruções claras e linguagem acessível para iniciantes. Considerar diferentes tamanhos de tela e formas de interação, como mouse e toque. Organizar as etapas de revisão e montagem de maneira que o usuário consiga compreender e executar as atividades.	Entregas 1 e 3; ISO 9241-11:2018.
LGPD – Lei Geral de Proteção de Dados Pessoais	A legislação é aplicável à pesquisa caso sejam coletados dados pessoais dos participantes, como endereços de e-mail ou informações que permitam identificá-los, inclusive por meio dos formulários de pré-teste, pós-teste e avaliação SUS.	Coletar somente os dados necessários para os objetivos da pesquisa, informar aos participantes a finalidade da coleta e restringir o acesso às respostas. Evitar a solicitação de informações pessoais desnecessárias e apresentar os resultados de maneira que os participantes não sejam identificados.	Lei nº 13.709/2018, especialmente art. 6º; Autoridade Nacional de Proteção de Dados (ANPD). 
Senado Federal+1
Acessibilidade – WCAG 2.2	Por ser uma aplicação web, o jogo deve considerar usuários com diferentes capacidades e necessidades de interação. As informações são apresentadas por textos, imagens e modelos tridimensionais, enquanto a montagem exige interação por arrastar e soltar.	Utilizar textos legíveis, contraste adequado entre texto e fundo, descrições textuais para imagens informativas, botões identificáveis e instruções claras. Evitar transmitir informações somente por cores. Considerar alternativas de interação para usuários que tenham dificuldade em utilizar o mouse ou a tela sensível ao toque.	W3C – Web Content Accessibility Guidelines (WCAG) 2.2. 
W3C+1
Usabilidade –}} | {{O jogo tem como objetivo permitir que usuários iniciantes aprendam a identificar componentes de hardware e realizem uma montagem simulada. Portanto, é importante avaliar se conseguem executar as atividades com eficiência, eficácia e satisfação.}} | {{Organizar a navegação de forma simples, apresentar orientações durante as atividades e fornecer feedback sobre as ações realizadas. Avaliar a usabilidade por meio do questionário SUS e observar o desempenho dos participantes durante a utilização do jogo.}} | {{ISO 9241-11:2018 – Usability: Definitions and concepts.}} |
| {{Prevenção e recuperação de erros}} | {{Na etapa de montagem, o usuário precisa selecionar o componente correto entre as opções apresentadas e encaixá-lo na região indicada. Como o público-alvo é composto por iniciantes, podem ocorrer escolhas incorretas ou dificuldades durante a interação.}} | {{Apresentar indicações visuais da região de encaixe, fornecer mensagens de feedback quando uma peça estiver incorreta e permitir que o usuário tente novamente. As mensagens devem explicar o resultado da ação sem gerar confusão ou impedir a continuidade da atividade}} | {{Princípios de usabilidade de Nielsen – prevenção de erros e reconhecimento, diagnóstico e recuperação de erros.}} |

## 3. Metas de usabilidade

Usabilidade deve ser discutida **no contexto de uso**. Metas quantitativas devem dizer o que será medido, em qual tarefa, com qual população e qual limite será considerado aceitável.

### 3.1 Metas qualitativas

| Meta | Para quem/tarefa | Evidência desejada | Justificativa |
|---|---|---|---|
| {{Compreensão das informações sobre os componentes de hardware.}} | {{Usuários iniciantes que realizarem a T01 – Revisão.}} | {{fala/observação}} | {{Relatos dos participantes indicando que compreenderam as imagens, descrições e funções dos componentes apresentados.}} |
|Facilidade para localizar e consultar os componentes.|Usuários iniciantes que realizarem a T01 – Revisão.|Observação de que os participantes conseguem identificar os componentes na tela e acessar suas informações sem dificuldades.|A organização da interface deve facilitar a navegação e permitir que o usuário consulte os componentes de maneira independente.|
|Clareza das instruções da montagem.|Usuários iniciantes que realizarem a T02 – Montagem.|Relatos e observações indicando que os participantes compreenderam qual componente selecionar e onde realizar o encaixe.|As instruções precisam ser claras para evitar dúvidas durante a execução da atividade prática.|
|Compreensão dos feedbacks apresentados pelo jogo.|Usuários iniciantes que realizarem a T02 – Montagem.|Observação de que os participantes compreendem quando uma peça foi encaixada corretamente ou quando precisam realizar uma nova tentativa.|O feedback deve orientar o usuário durante a atividade, permitindo reconhecer erros e corrigir suas ações.|
|Percepção de facilidade de uso e satisfação.|Todos os participantes que utilizarem o jogo.|Comentários sobre facilidade de navegação, compreensão dos comandos e experiência geral, complementados pelas respostas do questionário SUS.|Identificar aspectos positivos e dificuldades percebidas durante a utilização do jogo.|
|---|---|---|---|

### 3.2 Metas quantitativas

| ID | Dimensão | Métrica | Tarefa/escopo | Meta | Como medir | Justificativa |
|---|---|---|---|---|---|---|
| MU01 | eficácia | taxa de conclusão sem ajuda | T01-T01 – Acessar a etapa de revisão e consultar os componentes de hardware. | ≥ {{x}}% | teste observado | {{Verificar se a interface permite que usuários iniciantes acessem e consultem as informações dos componentes de forma independente.}} |
| MU02 | eficiência | tempo mediano | T02 – Realizar a montagem simulada do computador, selecionando e encaixando os componentes corretamente. | {{≤ 10 minutos}} | Utilização de cronômetro, registrando o tempo entre o início e a conclusão da montagem..| {{Verificar se a interface permite que usuários iniciantes acessem e consultem as informações dos componentes de forma independente.}} |
| MU03 | satisfação | Pontuação média da escala SUS | T01–T03 – Utilização geral do jogo, incluindo revisão e montagem. | ≥ {{≥ 68 pontos}} | questionário | {{Aplicação do questionário System Usability Scale (SUS) após a utilização do jogo e cálculo da pontuação média dos participantes..}} |

### 3.3 Priorização das metas (se exigida na disciplina)

Se o professor solicitar porcentagens que somem 100%, trate-as como **peso de prioridade**, não como métrica de usabilidade.

| Meta | Peso de prioridade | Justificativa |
|---|---:|---|
| MU01 | {{40%}}% | {{Prioridade em verificar se os usuários conseguem realizar as tarefas de revisão e consultar os componentes sem auxílio, demonstrando que conseguem utilizar as funcionalidades propostas.}} |
| **Total** | **100%** | |

## 4. Como o ciclo será iterado

Explique que artefatos serão revisitados após protótipos e avaliações.

## Checklist

- [x] Capacidades e restrições têm impacto de IHC explicitado.
- [x] Está claro o limite entre contribuição técnica do TCC e camada interativa da disciplina.
- [x] Resultados/processamento simulados no protótipo foram explicitados.
- [x] Metas de usabilidade avaliam a interação, não substituem métricas técnicas do TCC.
- [x] Normas/princípios estão contextualizados, não apenas copiados.
- [ ] Metas quantitativas são mensuráveis e associadas a tarefas/público.
- [x] Eficácia, eficiência e satisfação são consideradas quando pertinentes.
- [ ] Metas poderão ser verificadas nas Entregas 12–14.
