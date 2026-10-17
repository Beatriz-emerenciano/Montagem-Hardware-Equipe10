# Entrega 1 — Conhecendo o projeto, o usuário e o problema

**Data:** 13/08/2026
**Status:** 🟩 concluída
**Responsabilidade:** 1 solução consolidada por equipe

## Objetivo da atividade

Reinterpretar o tema do TCC sob a perspectiva de Interação Humano-Computador e construir um **entendimento comum entre os integrantes da equipe**.

A disciplina utiliza preferencialmente o tema do TCC para os exercícios de IHC. Isso vale tanto para TCCs que já preveem uma interface quanto para trabalhos cujo resultado principal é algoritmo, modelo, API, biblioteca, análise de dados, infraestrutura, estudo experimental ou outro artefato técnico.

> **Importante:** a interface projetada na disciplina é um artefato de aprendizagem de IHC. Ela **não se torna automaticamente uma obrigação do TCC**. Sua incorporação ao trabalho de conclusão depende de decisão da equipe e do orientador.

Antes de preencher, leia [`../GUIA_ESCOPO_IHC.md`](../GUIA_ESCOPO_IHC.md).

Nesta primeira semana a equipe **não deve começar desenhando telas**. Primeiro deverá compreender:

- o que o TCC realmente produz;
- quem poderia obter valor dessa contribuição;
- quais pessoas interagem, administram, configuram, interpretam ou são afetadas;
- o que essas pessoas precisam alcançar;
- como atividades relacionadas acontecem hoje;
- problemas, limitações e contexto;
- alternativas existentes;
- qual recorte de interação fará sentido para a disciplina.

Ao final desta entrega, a equipe deve diferenciar:

- **tema do TCC** × **escopo formal do TCC** × **escopo de IHC da disciplina**;
- **objetivo do projeto** × **objetivo do usuário**;
- **problema do usuário** × **solução tecnológica**;
- **fato conhecido** × **hipótese** × **lacuna de conhecimento**;
- **capacidade técnica** × **forma de uso dessa capacidade**;
- **funcionalidade** × **atividade/resultado que o usuário precisa alcançar**;
- **usuário direto** × **stakeholders**.

---

## Como classificar as respostas

Sempre que a resposta fizer uma afirmação sobre usuários, problemas, atividades, necessidades, contexto ou mercado, use:

- **[F] Fato conhecido** — existe evidência/fonte.
- **[H] Hipótese** — afirmação plausível que ainda precisa ser investigada.
- **[?] Não sabemos ainda** — lacuna relevante.

Quando usar `[F]`, informe a origem. Hipóteses prioritárias devem receber IDs (`H01`, `H02`...) e também ser registradas em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

> **Exemplo:** `[H] H01 — DBAs considerariam útil comparar automaticamente o plano atual de execução com uma recomendação produzida pelo algoritmo.`

Uma hipótese explicitada é melhor do que uma suposição escondida.

---

# 0. Identificação do TCC e da equipe

## 0.1 Membros

| Nome completo | Matrícula | GitHub | 

| Beatriz Cristina Emerenciano| 22.222041-0 | Beatriz-emerenciano |

|Larissa Santos Fiuza|22.123.042-8|LarissaFiuza7

## 0.2 Título atual do TCC

 Desenvolvimento de um jogo sério e estudo experimental de abordagens combinadas para ensino de montagme de hardware.

## 0.3 Orientador(a)

Rafael Gomes Alves

## 0.4 Qual é o resultado principal atualmente previsto no TCC?

Marque e descreva:

- [x] sistema/aplicação interativa;
- [ ] algoritmo;
- [ ] modelo de IA/ML/LLM;
- [ ] biblioteca/API/framework;
- [ ] análise de dataset;
- [x] estudo/benchmark/avaliação experimental;
- [ ] infraestrutura/backend;
- [ ] componente embarcado/IoT;
- [ ] outro: {{...}}.

**Descrição:** 
Estudo experimental de abordagens combinadas sendo jogo sério e tutorial para ensino da montagem de hardware.

## 0.5 O TCC já previa desenvolvimento de interface com usuário?

- [x] Sim, a interface já faz parte do TCC.
- [ ] Parcialmente; existe alguma interação, mas ainda não está bem definida.
- [ ] Não. O TCC é predominantemente técnico e não previa interface.

**Explique o que está formalmente previsto no TCC:** Desenvolver um jogo sério e a partir disto realizar um estudo experimental  de abordagen de ensino voltadas para montagem de hardware.

> Esta resposta serve para separar o compromisso do TCC do projeto da disciplina. Mesmo quando a opção for **não**, a equipe irá definir uma interface para exercitar IHC.

# 1. Entendendo a contribuição do projeto

## 1.1 Explique o TCC em uma frase, sem citar linguagem de programação, framework ou banco de dados.

Desenvolvimento de um Jogo Sério Aplicado ao Aprendizado e Medição de Desempenho de Estudantes.

## 1.2 Qual situação, atividade ou problema do mundo real motivou o TCC?

[H] H01 - Muitas pessoas não sabem ou conseguem identificar corretamente as peças de um computador nem compreender a ordem e a forma correta de montagem, o que dificulta o aprendizado e aumenta a chance de erros durante o processo.

## 1.3 Qual é a **capacidade/contribuição central** produzida pelo TCC?

[H]Nosso TCC propõe, o desenvolvimento de um jogo sério para aprendizado e treinamento de reconhecimento de componentes principais para conseguir realizar montagem de hardware, o sistema permite o usuário identificar, explorar e compreender os principais componentes de um computador, além de realizar a montagem atravém de uma plataforma de jogo e/ou combinada com tutorial. A solução visa democratizar o acesso ao conhecimento técnico, antendendo desde iniciantes até aqueles que buscam consolidar conhecimentos básicos de forma prática e inovadora e compreender qual a melhor abordagem para absorver este conhecimento.

## 1.4 O que se espera que esteja diferente **para pessoas, organizações ou processos** se essa contribuição for bem-sucedida?

[H] H02 - A abordagem de aprendizado.

## 1.5 O que é mérito técnico/científico do TCC e o que seria uma possível aplicação prática?

| Mérito/contribuição técnica | Possível aplicação/valor em uso |

 A contribuição visa democratizar o acesso ao conhecimento técnico, antendendo desde iniciantes até aqueles que buscam consolidar conhecimentos básicos de forma prática e inovadora através do desenvolvimento e avaliação de um Serious Game Web 3D voltado ao ensino de conceitos e procedimentos básicos de montagem de computadores, utilizando recursos de computação gráfica e gamificação para promover aprendizagem interativa.


# 2. Entendendo as pessoas envolvidas

## 2.1 Quem interage diretamente com o produto, se já existe interface prevista? - 
[H] H01 - Pessoas sem vínculo com a área de TI (com ou sem formação em outras áreas) e sem nenhum conhecimento prévio sobre hardware ou montagem.(Usuário final)
[H] Estudantes de TI, autodidatas ou profissionais formados na área com conhecimento apenas básico/superficial de hardware, sem experiência prática bem-sucedida em montagem.(Usuário final)


## 2.2 Quem poderia **usar, configurar, administrar, operar, interpretar ou tomar decisões** a partir da contribuição técnica?

Considere perfis profissionais e stakeholders, não apenas consumidores finais.

| Perfil | Relação com a contribuição | O que faria | Status/evidência |
|---|---|---|---|
| {{DBA / analista / gestor / técnico / pesquisador / usuário final...}} | {{...}} | {{...}} | F / H / ? |
|{{ Usuário primário}} | Utilizaria o Serious Game para aprender conceitos de hardware, identificar componentes e praticar virtualmente a montagem de computadores e ganhar confiança para realizar a atividade de montar um hardware de modo seguro.}} | {{Interagir com o sistema(jogo)}} | H|





## 2.3 Existem pessoas afetadas que não usariam a interface diretamente?

| Stakeholder | Como é afetado | Usa interface? | Status/evidência |
|---|---|---|---|
| {{...}} | {{...}} | sim/não | {{...}} |
|{{Pessoa que já possuem conhecimento e prática sólidas de montagem de hardware}}|{{Esse perfil em contato com o jogo terá apenas a experiência de usabilidade. }}| sim |{{[H]}}| 

## 2.4 Que características desses perfis podem influenciar a interação?

Considere conhecimento do domínio, experiência tecnológica, frequência de uso, necessidades de acessibilidade, responsabilidade profissional, familiaridade com métricas, linguagem técnica, urgência etc.

{{[F/H/?] ...}}

{{[H] - Conhecimento prévio sobre hardware: usuários iniciantes ou provenientes de outras áreas podem não reconhecer componentes como placa-mãe, memória RAM e processador, nem compreender suas funções e seus locais de instalação. Isso pode aumentar a dificuldade na execução das tarefas de identificação e posicionamento. }}

{{[H] -Experiência tecnológica: mesmo que os usuários tenham familiaridade com computadores, smartphones e navegadores, isso não significa que saibam realizar a montagem de um computador. É necessário distinguir a experiência geral com tecnologia do conhecimento específico sobre hardware..}}

{[[H] -Familiaridade com interfaces interativas: usuários que já utilizaram jogos ou aplicações com interação por arrastar e soltar podem compreender mais rapidamente as ações necessárias. Aqueles sem essa experiência podem precisar de instruções iniciais claras e de indicações visuais sobre como interagir com os componentes..}}

{{[H] - Compreensão da linguagem técnica: termos específicos de hardware podem dificultar a compreensão das instruções. A utilização de linguagem simples, acompanhada de imagens, representações visuais e explicações sobre as funções dos componentes, pode facilitar a interpretação das informações.}}

{{[H] -Capacidade de relacionar informações e representações visuais: usuários sem conhecimento prévio podem apresentar maior dificuldade para associar a descrição de um componente à sua aparência tridimensional e à posição em que deve ser instalado. A etapa de revisão explicativa poderá apoiar esse processo, cuja contribuição será investigada no estudo.}}

{{[H] Necessidade de orientação e feedback: usuários iniciantes podem precisar de indicações sobre as ações disponíveis, confirmação de posicionamentos corretos e mensagens compreensíveis quando cometerem erros. O feedback deve ajudar o usuário a entender o resultado de sua ação e, quando necessário, orientar sua próxima tentativa.  }}

{{[H] Experiência com aprendizagem autodidata: usuários acostumados a estudar sozinhos podem ter diferentes estratégias para buscar informações, repetir explicações e aprender por tentativa e erro. A possibilidade de consultar os conteúdos e receber feedback pode favorecer a autonomia durante a atividade. }}

{{[H] Acessibilidade e condições de uso: diferenças de visão, coordenação motora, familiaridade com dispositivos e tamanho de tela podem influenciar a seleção e o posicionamento dos componentes. Por isso, a interface deve considerar legibilidade, alvos de interação adequados, instruções claras e compatibilidade com diferentes dispositivos.  }}


# 3. Entendendo objetivos e atividades

## 3.1 O que o usuário está tentando conseguir no mundo real?
[H]{O objetivo real do usuário não é simplesmente jogar ou arrastar peças na tela. É adquirir conhecimento e desenvolver confiança para compreender como os componentes de um computador são identificados e montados. O jogo sério é o meio que você propõe para apoiar esse objetivo.}  

{{[F/H/?] ...}}

## 3.2 Quais são as atividades mais importantes?

| ID | Atividade/objetivo | Quem realiza | Frequência/criticidade inicial | Status/evidência |
|---|---|---|---|---|
| A01 | {{Etapa de  revisão e aprender sobre os componentes de hardware}} | {{Usuário final}} | {{media/alta}} | {{H}} |
| A03 | {{ Etapa de montagem Identificar componentes de um computador}} | {{usuário final}} | {{alta}} | {{H}} |

## 3.3 Qual atividade parece mais frequente? Por quê?

{{[F/H/?] ...}}

[H] A01 - Montagem - Pois essa etapa é a principal de nosso projeto é nessa etapa onde o usuário terá maior interação e obterá resultados de aprendizado e desempenho. 

## 3.4 Qual parece mais crítica? Que consequência existe se for mal executada?

 ## 3.4 Qual parece mais crítica? Que consequência existe se for mal executada?

[H] A etapa mais crítica é a montagem virtual dos componentes de hardware, especialmente a identificação e o posicionamento de cada componente no local correto. Essa etapa exige que o usuário compreenda as informações apresentadas na revisão e tutorial e consiga relacioná-las à representação visual dos componentes e às suas respectivas posições na placa-mãe.

Caso a tarefa seja mal executada, o usuário poderá posicionar componentes incorretamente, confundir peças com características semelhantes ou apresentar dificuldades para compreender a relação entre cada componente e sua função. Isso pode prejudicar a aprendizagem e dificultar a aquisição de conhecimentos básicos sobre montagem de computadores.

Além disso, se a interface não apresentar instruções claras ou feedback adequado, o usuário poderá não compreender por que sua tentativa está incorreta, repetir os mesmos erros e sentir frustração ou desmotivação durante a atividade

# 4. Entendendo o problema ou processo atual

## 4.1 Como essas atividades são realizadas hoje, antes da interface imaginada na disciplina?

Pode existir software concorrente, linha de comando, planilha, notebook, script, painel técnico, processo manual, consulta a logs, análise visual, troca de mensagens, decisão por especialista etc.

{{[F/H/?] ...}}

{{[H] Atualmente, o aprendizado sobre hardware é atravéz de cursos presenciais, videos tutorias na internet,livros didáticos.}}


## 4.2 O que é difícil, demorado, confuso, repetitivo, arriscado ou pouco transparente?

{{[F/H/?] ...}}

[H] O que pode ser difícil, demorado ou confuso para o usuário durante a utilização do jogo sério é identificar os componentes de hardware, compreender suas funções e reconhecer o local correto de posicionamento no ambiente virtual. Para usuários iniciantes, a ausência de conhecimentos prévios pode dificultar a associação entre as informações apresentadas na etapa de revisão e a execução das tarefas de montagem.

[H]Portanto, o projeto deve buscar reduzir essas dificuldades por meio de representações visuais compreensíveis, instruções objetivas, áreas de posicionamento identificáveis e feedback claro após cada tentativa, favorecendo a autonomia do usuário e a compreensão das tarefas de montagem virtual.

## 4.3 Que informações o profissional precisa interpretar para tomar decisão?

{{[F/H/?] ...}}

[H] Aprendizagem equivocada, incapacidade de concluir uma montagem, dano físico em uma situação real, perda de confiança ou necessidade de ajuda
## 4.5 Conte uma situação concreta.

Escreva uma pequena narrativa com pessoa, objetivo, atividade, contexto, dificuldade e consequência. **Não descreva ainda a futura solução.**

{{[F/H/?] narrativa...}}

{{[H] Um estudante iniciante que recentemente comprou um hardware e quer montar um computador durante uma aula prática de hardware. Ele identifica corretamente a memória RAM, mas possui dúvidas sobre quais slots da placa-mãe devem ser utilizados e sobre a orientação correta para encaixar o componente. Como não tem experiência suficiente para tomar a decisão sozinho, consulta o material fornecido e solicita auxílio ao professor. Enquanto aguarda a orientação, a atividade fica interrompida. Em uma situação diferente, caso o estudante prossiga sem identificar corretamente o procedimento, poderá realizar a instalação de maneira inadequada e precisar desfazer a etapa para corrigir o erro. A dificuldade em compreender o procedimento pode aumentar o tempo necessário para concluir a atividade e prejudicar a confiança do estudante.}}

## 4.6 Que evidência existe hoje?

| Evidência/fonte | O que sustenta | Limitação |
|---|---|---|

|F|{{Materiais didáticos, tutoriais e vídeos sobre montagem de computadores}}|{{Demonstram como o conteúdo é atualmente apresentado aos estudantes}}|{[Normalmente são materiais passivos, com menor possibilidade de interação e prática}}|

|F|{{Curso técnico de informática}}|[{Sustenta a necessidade de conhecimento sobre identificação, função e instalação dos componentes}}|{{Pode abordar métodos tradicionais e exclusivos de quem realiza o curso presencial}}|

---

# 5. Entendendo o contexto de uso

## 5.1 Onde e em quais situações a interação poderia ocorrer?

{{[F/H/?] ...}}
{{[H] A interação com o Serious Game poderá ocorrer em diferentes contextos de aprendizagem, como salas de aula, laboratórios de informática, ambientes de estudo e na residência do estudante. Por ser uma aplicação Web, o usuário poderá acessar o sistema por meio de um navegador, permitindo que as atividades sejam realizadas tanto individualmente quanto como atividade complementar orientada por um professor,  poderá ser utilizado antes de uma atividade prática com componentes físicos, durante atividades de aprendizagem ou como forma de revisão do conteúdo.}}

## 5.2 Em quais dispositivos/equipamentos?

{{[F/H/?] ...}}

{{[F] Os principais dispositivos considerados são smartphones, tablets e computadores/notebooks.}}

## 5.3 Existem condições físicas relevantes?

Considere iluminação, ruído, mobilidade, conexão, privacidade, uso compartilhado, interrupções, pressão de tempo etc.

{{[F/H/?] ...}}
{{[H] Precisa ser estudado.}}

Dispositivo prioritário:** investigar se computador/notebook deve ser o foco inicial e se o uso móvel é realmente necessário e viável para manipulação 3D

## 5.4 Existem fatores sociais ou organizacionais?

Considere papéis, chefias, equipes, permissões, aprovação, responsabilidade profissional, auditoria, turnos e colaboração.

{{[F/H/?] ...}}

{{[F] Equipe - Larissa responsável pelo desensenvolvimento e Beatriz responsável pelos testes e analise de resultados, organizado por turno e colaboração de ambas.}}

## 5.5 Existe necessidade de histórico, rastreabilidade ou auditoria?

{{[F/H/?] ...}}

{[[H]{ estamos estudando a necessidade}}

{[[H] Durante a avaliação do TCC, dados relacionados ao desempenho dos participantes poderão ser registrados para posterior análise dos resultados, respeitando os procedimentos definidos para a pesquisa.}}

## 5.6 Um erro pode produzir consequência relevante? Qual?

{{[F/H/?] ...}}

{{[H] aprendizagem equivocada, incapacidade de concluir uma montagem, dano físico em uma situação real, perda de confiança ou necessidade de ajuda}}

---

# 6. Entendendo mercado e alternativas existentes

> Nesta entrega faça apenas um **levantamento inicial**. A análise aprofundada ocorre na Entrega 2.



## 6.1 Como pessoas resolvem problemas semelhantes hoje?

| Alternativa atual | Quem usa | Para quê | Status/evidência |
|---|---|---|---|
|Levar as peças a um técnico para que ele realize a montagem ou assistir vídeos tutoriais no Youtube| Qualquer usuário que não tenha conhecimento técnico para realizar a montagem sem auxilio | Para realizar a montagem de um computador para usar em casa, seja para pesquisa, para jogar e diversos usos pessoais | F |

## 6.2 Existem produtos que atuam na mesma área, mesmo sem serem equivalentes ao TCC?

{{[F/H/?] ...}}
{{[F] PC Building Simulator, que permite simular montagem e reparo e apresenta instruções passo a passo para iniciantes. }}
https://store.steampowered.com/app/621060/PC_Building_Simulator/ }}


## 6.3 Quais interfaces profissionais esse público já conhece?

Exemplos possíveis: ferramentas de banco, IDEs, consoles de nuvem, dashboards, plataformas de dados, ferramentas de monitoramento, painéis de IA, sistemas administrativos.

{{[H] > PC Building Simulator}}


## 6.4 O que essas soluções parecem fazer bem?

{{[F/H/?] ...}}

{{ H - Como principal ajudar a solução de revisão onde o usuário pode vizualizar as peças  de hardware modeladas e saber sua função dos componentes principais para assim conseguir seguir com a etapa de montagem}}

## 6.5 O que parecem fazer mal, dificultar ou não atender?

{{[F/H/?] ...}}
{ Realizar a interação de montagem d ehardaew sem realizar uma revisão, isso poderá implicar em má compreensão}}

## 6.6 Que padrões de interface ou vocabulário parecem familiares a esse público?

{{[F/H/?] ...}}

{{[H] Para usuários iniciantes, termos técnicos podem não ser completamente familiares, sendo necessário apresentar explicações simples e contextualizadas durante o processo de aprendizagem.}}

{{[H] Para usuários iniciantes elementos comuns de jogos, como "Iniciar", "Próxima fase", "Pontuação", "Concluir", "Tentar novamente", "Acerto" e "Erro", menu, ferramentas tendem a ser familiares para usuários que possuem experiência com jogos digitais de celulares.}}

---

# 7. Derivando o escopo de IHC da disciplina

## 7.1 Escolha o caminho do projeto

### Caminho A — TCC já possui interface

Explique qual parte da interface será usada como recorte da disciplina e por que esse fluxo é relevante.

[H]{{O recorte da interface será o fluxo de aprendizagem e montagem virtual de componentes de hardware, desde a seleção de um componente no jogo até sua identificação, visualização das informações, posicionamento no local correto e recebimento de feedback sobre a ação realizada.}}

[H]{{O recorte da interface será o fluxo de aprendizagem e montagem virtual de componentes de hardware, desde a seleção de um componente até sua identificação, visualização das informações, posicionamento no local correto e recebimento de feedback. Esse fluxo é relevante por representar a principal interação do estudante com o Serious Game e estar diretamente relacionado ao objetivo de ensinar conceitos e procedimentos básicos de montagem de computadores. Além disso, permite avaliar aspectos de IHC, como aprendizagem, clareza, feedback, prevenção de erros e facilidade de interação.}}

### Caminho B — TCC não possui interface prevista

Faça o exercício de transferência de uso:

> **Imagine que o TCC foi concluído com sucesso e uma empresa, laboratório ou organização quer transformar a contribuição em algo utilizável. Quem precisaria interagir com ela e para quê?**

Responda:Não aplicável

1. quem poderia contratar/adotar a solução? {{}}
2. quem seria o usuário direto? {{}}
3. quem administraria/configuraria? {{}}
4. quem interpretaria resultados? {{}}
5. quem tomaria decisões? {{}}
6. quais dados/entradas seriam necessários? {{}}
7. quais resultados deveriam ser compreendidos? {{}}
8. que erros/rupturas seriam possíveis? {{}}

## 7.2 Qual perfil será priorizado no projeto de IHC?

[H]{{Estudantes/autodidatas iniciantes sobre montagem de hardware e pessoas sem vínculo com a área de TI (com ou sem formação em outras áreas) e sem nenhum conhecimento prévio sobre hardware ou montagem.}}

**Por que esse perfil foi escolhido?** [H]{{Acreditamos que esses perfis possuem maior dificuldade por apresentar pouco ou nenhum conhecimento sobre o tema.}}

## 7.3 Qual objetivo desse usuário será priorizado?

[H]{{**Objetivo geral**

Desenvolver e avaliar o ganho/impacto nos usuários com a interação com um jogo sério em plataforma web para a montagem de hardware virtual, investigando se a inclusão de uma etapa de revisão explicativa antes do jogo está associada a diferenças no desempenho de estudantes iniciantes durante a identificação e o posicionamento dos componentes com o objetivo de o usuário ganhar confiança em realizar a atividade e conseguir comprrender e montar o computador corretamente.}}

## 7.4 Que interface será explorada na disciplina?

[F]Complete: para alcançar o objetivo principal: aprender a identificar os componentes de hardware, compreender suas funções e reconhecer seus locais de instalação.

Interface do menu principal
 Navegação 
Apresenta as opções de acesso às funcionalidades do jogo:
- Tutorial: aprender a utilizar a interface.
- Revisão: conhecer os componentes.
- Jogar: iniciar a montagem virtual.
Objetivo de IHC: permitir que o usuário compreenda as opções e encontre facilmente a funcionalidade desejada.

. Interface do tutorial de utilização
 Orientação 
Explica como selecionar, arrastar e soltar os componentes e como interpretar as mensagens do jogo.
Objetivo de IHC: ensinar os controles e reduzir as dificuldades de interação, especialmente para pessoas sem experiência com jogos 3D.

. Interface de revisão dos componentes
 Consulta e exploração 
Exibe os modelos 3D, nomes, funções e descrições dos componentes. O usuário poderá explorar visualmente as peças antes de montar o computador.
Objetivo de IHC: facilitar a identificação e a compreensão dos componentes por meio de informações textuais e visuais.

Interface de montagem virtual
 Interface principal 
Apresenta a bancada ou o gabinete em 3D, os componentes disponíveis e os locais de destino. O usuário seleciona uma peça e a arrasta até o local correto.
Objetivo de IHC: possibilitar a prática de identificação e posicionamento, com instruções passo a passo e indicação de acertos ou erros.

Interface de feedback e resultados
 Avaliação do desempenho 
Apresenta a pontuação, o progresso, os acertos e os erros cometidos, além de uma opção para continuar ou reiniciar a atividade.
Objetivo de IHC: ajudar o usuário a compreender seu desempenho e identificar pontos que precisam de revisão.

> **Para fins da disciplina de IHC, será projetada uma interface que permita a `{{perfil}}` utilizar `{{capacidade/resultado do TCC}}` para `{{objetivo}}`, no contexto de `{{situação}}`.**

{{Para fins da discplina de IHC, será projetada uma interface que permita o usuário,utilizar uma plataforma tutorizada/montagem de montagem de hardware para o objetivo de desenvolver conhecimentos e solidificar os conhecimentos a respeito de hardware e analisar a eficácia da metodologia aplicada com conceitos de interface para obter esse resultado }}

## 7.5 Qual é a relação dessa interface com o TCC?

- [x] Já fazia parte do TCC.
- [x] É um aprofundamento de algo parcialmente previsto.
- [ ] É uma extensão conceitual criada para a disciplina.
- [ ] É um protótipo demonstrativo de aplicação potencial.
- [ ] Outra: {{...}}.

> **Declaração:** a interface desenvolvida nesta disciplina é um artefato de aprendizagem de IHC baseado no tema do TCC. Sua inclusão ou implementação no TCC somente ocorrerá se isso for posteriormente decidido pela equipe e pelo orientador.

---

# 8. Levantando possibilidades de interação — sem desenhar ainda

A equipe pode registrar possibilidades para investigação. **Não significa que todas serão implementadas.**

Marque apenas as que parecem plausíveis e explique o objetivo correspondente.

| Possibilidade | Pode fazer sentido? | Objetivo/tarefa que justificaria | Evidência atual |
|---|---|---|---|
| Dashboard/visão geral | tsim | {{sim}} | {{questionário para analise comparativa de resultados}} | {{H}}|
| Configuração/parametrização | ?| {{ ?}} | {{Não sabemos}} |{{?}}|
| Entrada/upload/seleção de dados | ? | {{?}} | {{interação do usuário com a gamificação}} |{{H}]|
| Acompanhamento de processamento | sim | {{sim}} | {{não sabemos mas acreditamos que não}}|{{H}} |
| Relatório/resultados | sim | {{sim|{{análise de resultados de desempenhos dos usuários no jogo}} |{{H}}|
| Histórico com busca/filtros | não | {{não}} | {{não se aplica}} | ?|
| Comparação de resultados | sim | {{sim}} | {{comparar os resultados da inteção do usuário com o jogo}} |H|
| Explicabilidade/detalhamento | ? | {{?}} | {{?}} |
| Administração/configurações globais | sim | {{sim}} | {{para contrução da gamificação}} | {H}
| Usuários/perfis/permissões | talvez | {{sim}} | {{para separar e identificar o perfil de quem é usuário e quem é o administrador do jogo}} |H|
| CRUD de entidade do domínio | ? | {{?}} | {{}} | ?|
| Auditoria/logs | ? | {{?}} | {?}} | ? |
| Alertas/ocorrências | ?| {{?}} | {{}} | ?|
| Ajuda/documentação | talvez | {{sim}} | {{para endimento e funcionamento do jogo}} | H|

> **Atenção:** “login + dashboard + CRUD” não é uma solução universal. Cada padrão deve surgir de uma tarefa real.

---

# 9. Benefícios e ações iniciais

## 9.1 Qual benefício concreto o projeto de IHC pretende oferecer?

| Benefício esperado | Problema/necessidade | Usuário | Status/evidência |
|---|---|---|---|
| {{Transmitir conhecimento de hardware ao usuários e com estudo experimental verificar a eficácia da metodologia}} | {{usuários que necessitam ou tem dificuldade de adquerir conhecimento sobre hardware}} | {{pessoas que não possuem conhecimento ou possuem pouco conhecimento sobre hardware}} | {{F}} |

## 9.2 Que ações o usuário deverá conseguir realizar?

| ID | O usuário precisa conseguir... | Para alcançar... | Prioridade inicial |
|---|---|---|---|
| F01 | {{ação}} | {{objetivo}} | alta/média/baixa |
| ID | O usuário precisa conseguir... | Para alcançar... | Prioridade inicial |
|---|---|---|---|
| F01 | Acessar o Serious Game pelo navegador | Iniciar as atividades de aprendizagem sobre hardware | Alta |
| F02 | Acessar um tutorial sobre os componentes de hardware | Aprender a identificar os componentes e compreender suas funções | Alta |
| F03 | Visualizar os componentes em um ambiente 3D interativo | Reconhecer suas características e partes principais | Alta |
| F04 | Selecionar um componente de hardware | Identificar corretamente o componente apresentado | Alta |
| F05 | Consultar informações sobre um componente | Compreender sua função e sua utilização no computador | Alta |
| F06 | Arrastar e posicionar um componente no local indicado | Praticar virtualmente a montagem do computador | Alta |
| F07 | Receber feedback após uma ação | Saber se realizou corretamente ou incorretamente a atividade | Alta |
| F08 | Avançar pelas etapas de uma atividade de montagem | Aprender a sequência básica de montagem dos componentes | Alta |
| F09 | Repetir uma atividade após um erro | Corrigir seus erros e reforçar o aprendizado | Média |
| F10 | Visualizar sua pontuação ou progresso | Acompanhar seu desempenho durante as atividades | Média |
| F11 | Concluir desafios ou fases do jogo | Verificar seu domínio dos conteúdos apresentados | Média |
| F12 | Retomar seu progresso | Continuar as atividades sem precisar reiniciar todo o jogo | Média |

## 9.3 Tecnologias/restrições já definidas no TCC

A tecnologia aparece **agora**, depois do entendimento do uso.

| Tecnologia/restrição | Por que existe | Possível impacto na interação |
|---|---|---|
| {{...}} | {{...}} | {{...}} |
## 9.3 Tecnologias/restrições já definidas no TCC

A tecnologia aparece **agora**, depois do entendimento do uso.

| Tecnologia/restrição | Por que existe | Possível impacto na interação |
|---|---|---|
| Aplicação Web | Permitir que o Serious Game seja acessado diretamente pelo navegador | Facilita o acesso em diferentes dispositivos, sem necessidade de instalação |
| JavaScript | Linguagem utilizada no desenvolvimento da aplicação e das interações | Permite implementar as mecânicas do jogo e responder às ações do usuário |
| Three.js | Permitir a criação e interação com o ambiente 3D no navegador | Exige interação com objetos 3D, como seleção, movimentação e posicionamento dos componentes |
| Modelos 3D | Representar visualmente os componentes de hardware | Permite que o usuário visualize e manipule os componentes de forma mais próxima de uma montagem real |
| Blender | Realizar ajustes e preparação dos modelos 3D utilizados na aplicação | Pode influenciar o nível de detalhamento e desempenho dos modelos apresentados |
| LocalStorage | Armazenar informações simples sobre o progresso do usuário no navegador | Permite retomar atividades e manter informações como progresso, pontuação e etapas concluídas sem um servidor |
| Restrição de acesso via navegador | O jogo será executado em navegadores compatíveis, dependendo de recursos gráficos disponíveis | O desempenho da aplicação pode variar conforme o dispositivo e o navegador utilizado |
| Sem necessidade de câmera ou AR | Reduzir a complexidade do projeto e manter o foco na aprendizagem e montagem virtual | A interação ocorre diretamente na tela, sem necessidade de reconhecimento de objetos ou uso da câmera |
---

# 10. Hipóteses e dúvidas prioritárias

| ID | Hipótese/dúvida | Por que importa | Como poderá ser investigada |
|---|---|---|---|
| H0| {{}} | {{...}} | Entrega 2/3/7/... |
| H01 | O uso do Serious Game Web 3D pode contribuir para o aprendizado sobre identificação e montagem de componentes de hardware | Verificar se a aplicação cumpre seu objetivo educacional | Aplicação de pré-teste e pós-teste de conhecimento com os participantes |
| H02 | A interação com os componentes em um ambiente 3D pode facilitar a compreensão das etapas de montagem | Verificar se a interação prática virtual contribui para a compreensão do conteúdo | Observação do desempenho dos participantes durante as atividades e aplicação de questionário |
| H03 | O feedback imediato pode auxiliar o usuário a identificar e corrigir seus erros durante as atividades | Verificar se o feedback contribui para o aprendizado e para a execução correta das atividades | Análise dos erros, tentativas e evolução do desempenho durante o jogo |
| H04 | Usuários iniciantes conseguem utilizar o Serious Game sem dificuldades significativas | Verificar se a aplicação possui usabilidade adequada para o público-alvo | Teste de usabilidade e questionário após a utilização do jogo |

Registre em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

---

# 11. Síntese da equipe

| Pergunta | Síntese atual |
|---|---|
[F]| Qual é a contribuição central do TCC? | {{O problema que motivacional desse projeto é que pessoas iniciantessem com pouco ou nenhum conhecimento e prática em hardware podem apresentar dificuldades para identificar os componentes internos de um computador, compreender suas funções e entender como eles são posicionados durante a montagem. A falta de experiência prática pode dificultar a associação entre o conhecimento teórico e a aplicação desses conceitos em uma atividade de montagem.
A contribuição deste trabalho consiste no desenvolvimento de um jogo sério  em plataforma web, implementado em JavaScript, que integra interação tridimensional, manipulação de componentes por arrastar e soltar, validação de posicionamento e feedback sobre as ações realizadas. A solução será direcionada a pessoas iniciantes ou leigas em montagem de computadores, permitindo explorar visualmente os principais componentes de hardware e praticar seu posicionamento em um ambiente virtual.

[H]|Além do desenvolvimento tecnológico, o trabalho investigará os resultados da utilização do sistema por meio de uma avaliação experimental com pré-teste e pós-teste e um grupo de comparação. Serão analisadas a variação do conhecimento dos participantes, a taxa de acertos e erros nas tarefas de montagem e a usabilidade da aplicação e o ganho dessa ferramento para seu conhecimento sobre o tema. |
| O TCC já previa interface? | {{sim}} |

| Quem é o usuário prioritário de IHC? |[H] {{Estudantes de TI, autodidatas ou profissionais formados na área com conhecimento apenas básico/superficial de hardware, sem experiência prática  em montagem e Pessoas sem vínculo com a área de TI (com ou sem formação em outras áreas) e sem nenhum conhecimento prévio sobre hardware ou montagem.}} |

| O que ele precisa alcançar? |[H] {{adquerir conhecimentos e experiência  básicos em identificação e montagem hardware para o ganho de sua confiaçã e idependencia em sua atividade}} |

| Qual problema/atividade será estudado? |[H] {{O problema é a dificuldade do usuario em compreender a realiação da atividade de montar um hardware e identificar os componentes/será estudada a forma de aborda uma solução que atenda esse probblema de compreesão} |
| Como isso acontece hoje? |[H] {{Hoje esse aprendizado concentra-se em a pessoa pesquisar informações em Aulas teóricas e materiais didáticos,videos tutoriais na internet, prática com montagem em casa ou em laboratórios.}} |

| Qual é o contexto de uso? |[H] {O contexto é o usuário desenvolver interese em aprender montar harwdware e ao pesquisar em como adquerir esse conhecimento encontrar dificuldade para contruir esse conchecimento}} |

| Que interface/recorte será explorado? |[F] {{montagem de hardware e revisão}} |
| Como a interface se relaciona ao TCC? | {{ A montagem de hardware é o coração do nosso projeto, é por meio dela que pretendemos corresponder a solução do problema.}} |
| Quais pontos ainda são hipóteses? 

### Delimitação

**Dentro do escopo de IHC:** {{sim}}  
**Fora do escopo de IHC:** {{não}}  
**Dentro do escopo formal do TCC:** {{sim}}  
**Interface da disciplina será implementada no TCC?**  sim  — {{ háveratotalmente a necessidade de interação gráfica}} 

---

# 12. Como esta entrega alimenta as próximas

- **Entrega 2:** verifica mercado, concorrentes e interfaces profissionais representativas.
- **Entrega 3:** detalha perfis e contexto.
- **Entrega 4:** aprofunda situações problemáticas.
- **Entrega 5:** modela tarefas centrais.
- **Entrega 6:** experimenta alternativas em baixa fidelidade.
- **Entrega 7:** investiga hipóteses com dados.
- **Entrega 8:** define restrições e metas de usabilidade.
- **Entregas 9–11:** transformam o recorte em modelo de interação e protótipo.
- **Entregas 12–14:** avaliam a interface construída na disciplina.

A Entrega 1 é uma **fotografia inicial do conhecimento**. Ela pode e deve ser revisada quando surgirem evidências.

---

# 13. Relação com INOVA e comunicação do projeto

Prepare uma explicação de até três frases:

1. **Problema/atividade humana:** {{ Dificuldade de estudantes iniciantes em identificar componentes de hardware, compreender suas funções e aprender as etapas básicas de montagem de um computador, especialmente quando possuem pouca oportunidade de realizar práticas com equipamentos reais.}}
2. **Contribuição técnica do TCC:** {{ Desenvolvimento de um Serious Game Web 3D que permite ao estudante aprender sobre componentes de hardware e praticar virtualmente etapas básicas de montagem, por meio de tutorial, interação com modelos 3D, desafios e feedback imediato.}}
3. **Como uma pessoa poderia utilizar essa contribuição:** {{O estudante pode acessar o jogo pelo navegador, consultar o tutorial e revisão, identificar os componentes, visualizar suas funções e realizar atividades interativas de montagem, recebendo feedback sobre suas ações e acompanhando seu progresso.}}

Essa síntese ajuda a apresentar o projeto para público não especializado sem reduzir seu mérito técnico.

---

# Checklist de qualidade

- [x] Está clara a diferença entre tema do TCC, escopo formal do TCC e escopo de IHC.
- [x] A equipe declarou se o TCC já previa interface.
- [ ] Se não previa, foi derivado um usuário plausível e um objetivo de uso.
- [x] A interface de IHC não foi apresentada como obrigação automática do TCC.
- [x] A contribuição do TCC foi descrita sem começar por tecnologias de implementação.
- [x] Usuários diretos e stakeholders foram diferenciados.
- [x] Foram considerados profissionais que configuram, administram, interpretam ou decidem, quando pertinente.
- [x] Objetivo do usuário não foi confundido com objetivo do projeto.
- [x] Processo/problema atual foi descrito antes da solução.
- [x] Existe situação concreta de uso/problema.
- [x] Contexto físico, social/organizacional, dispositivos e consequências de erro foram considerados.
- [x] Mercado/alternativas existentes foram levantados inicialmente.
- [x] Possibilidades como dashboard, relatório, histórico, filtros e CRUD foram tratadas como hipóteses de solução, não como requisitos automáticos.
- [x] Cada possibilidade de interface tem um objetivo/tarefa que poderia justificá-la.
- [x] Afirmações relevantes estão marcadas `[F]`, `[H]` ou `[?]`.
- [ ] Hipóteses prioritárias receberam IDs e foram para a rastreabilidade.
- [x] O recorte de IHC é viável para modelar, prototipar e avaliar no semestre.
- [x] A equipe consegue explicar problema humano → contribuição computacional → forma de uso.
