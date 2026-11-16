# Entrega 10 — MoLIC

**Data:** {{16/11/2026}}  
**Status:** ⬜ não iniciada  
**Responsabilidade:** 1 solução completa por integrante

## Objetivo da atividade

Modelar a interação como uma **conversa entre usuário e preposto do designer**, oferecendo visão global dos caminhos que permitem ao usuário atingir seus objetivos — incluindo alternativas e rupturas relevantes. MoLIC não deve ser reduzida a um fluxograma de telas.

> Use a **notação MoLIC ensinada na disciplina**. Este template foca critérios de qualidade e não substitui a legenda/notação apresentada em aula.

## Atenção a TCCs sem interface original

O MoLIC não modela o algoritmo por dentro. Ele modela a **conversa de interação necessária para que uma pessoa use a contribuição**.

Exemplos de conversas:

- usuário escolhe dados/parâmetros → sistema valida → usuário inicia análise → sistema comunica processamento → usuário interpreta resultado;
- usuário consulta histórico → refina filtros → abre execução → compara com outra;
- administrador seleciona perfil → altera permissão → sistema comunica consequências → administrador confirma/cancela;
- analista recebe alerta → examina evidências → classifica ocorrência → registra decisão.

Modele também rupturas plausíveis: entrada inválida, falha de processamento, ausência de resultado, permissão insuficiente, filtro sem resultados, conflito de alteração, cancelamento ou necessidade de recuperação.

## M01 — {{eTAPA DE MONTAGEM/Permitir que o usuário acesse a etapa de revisão e consulte os componentes de hardware (gabinete, placa-mãe, memória RAM, HD, fonte de alimentação e placa de vídeo), visualizando suas imagens, descrições e funções, com o propósito de aprender a identificar cada componente e compreender sua finalidade no computador.}}

**Autor(a):** {{LLarissa Fiusa Santos — 22.123.042-8}}  
**Cenário de interação de origem:** {{CI01}}  
**Objetivo(s):** {{O01}}  
**Tarefa(s) relacionada(s):** {{T01}}  
**Signos relevantes:** {{Botão "Revisar componentes", Lista de componentes,Imagem do componente, Nome do componente,Descrição do componente,Função do componente}}

## M02 — {{Realizar a montagem simulada de um computador./Permitir que o usuário realize a montagem simulada de um computador, identificando a região indicada pelo sistema, selecionando o componente de hardware correto entre as opções disponíveis e arrastando-o até o local correspondente para efetuar o encaixe. Ao longo da atividade, o usuário recebe feedback sobre suas ações e, ao concluir a montagem, visualiza sua pontuação.}}

**Autor(a):** {{LLarissa Fiusa Santos — 22.123.042-8}}  
**Cenário de interação de origem:** {{CI02}}  
**Objetivo(s):** {{O02}}  
**Tarefa(s) relacionada(s):** {{T02}}  
**Signos relevantes:** {{Botão "Jogar",Mesa de montagem, Gabinete, Região iluminada, Modelos 3D dos componentes, Três opções de componentes,Cursor do mouse ou gesto de toque,Animação de encaixe,Mensagem de erro,Mensagem de acerto,Indicador de progresso, Pontuação final}}

### Diagrama

![MoLIC M01](../assets/10_molic/molic_m01.svg)

**Fonte editável:** {{adicione aqui o link para o arquivo : molic montagem: https://drive.google.com/file/d/1NMjWdBKqKFU0f4sPV2rXT7oDgdLMuyp8/view?usp=sharing


MoLic da etapa de revisão: https://drive.google.com/file/d/1CY_-l1XKoY2p5lRNNJuCNSYNmeq2ucHu/view?usp=sharing
}}


### Leitura do diagrama

Diagrama MoLIC – Etapa de Revisão (gco: Compreender componentes de hardware)Caminho Principal (Fluxo Direto de Revisão):
A conversa inicia a partir de um acesso ubíquo (menu disponível em qualquer momento da interação), quando o usuário seleciona a opção de revisar (u: revisar componentes), abrindo o objetivo final de compreender os componentes de hardware (gco: Compreender componentes de hardware). O usuário entra na cena Consultar lista de componentes, onde o sistema (preposto) apresenta a lista com o nome e a miniatura das peças disponíveis (Placa-mãe, Memória RAM, SSD/HD, CPU, Fonte e Gabinete). Ao escolher um item (u: selecionar componente X), a conversa transita para a cena Examinar componente, na qual são exibidos o nome, a imagem, a descrição e a função da peça selecionada. Após a leitura, o usuário pode acionar u: iniciar montagem (gco: Montar computador), o que encerra a conversa atual de revisão (gcc: Compreender componentes de hardware) e inicia a etapa prática.   Caminho Alternativo (Consulta a Outros Componentes):
Estando na cena Examinar componente, partindo da pressuposição de que o usuário pode querer explorar outras peças antes de montar o computador (pressup: usuario deseja consultar outro componente), ele pode emitir a fala de transição u: voltar para lista. Esse fluxo contínuo retorna à cena Consultar lista de componentes, permitindo repetir a inspeção com outros itens.   Caminho de Ruptura (Falha de Carregamento):
Caso ocorra uma falha técnica na exibição dos dados da peça dentro da cena Examinar componente, dispara-se uma fala de transição de ruptura representada pela linha tracejada ([TA] d: erro ao carregar detalhes do componente). Esse desvio comunica o problema ao usuário e retorna à própria cena para que a visualização seja recarregada ou tentada novamente. 

Diagrama MoLIC – Etapa de Montagem (gco: Montar computador)Caminho Principal (Montagem Bem-Sucedida):
A interação começa pelo ponto de entrada (●) através da ação u: iniciar montagem, estabelecendo a meta gco: Montar computador. Na cena Montar computador, o preposto apresenta o gabinete, a região destacada para encaixe e a lista com os 3 componentes (orientar etapa), enquanto o usuário seleciona, arrasta e solta uma peça (posicionar peca). Ao soltar o componente (u: soltar componente), o fluxo passa por dois processamentos internos do sistema (■):   O primeiro valida o encaixe (d: componente encaixado com sucesso).   O segundo verifica a condição de término (precond: todos os componentes encaixados).
Quando todas as peças estão posicionadas, o sistema informa d: montagem concluida e conduz o usuário à cena Visualizar resultado da montagem, onde são exibidos a pontuação final e o resumo de acertos (ver desempenho). Por fim, o usuário seleciona u: concluir, encerrando a conversa relacionada à meta (gcc: Montar computador) no ponto de encerramento (◎).   Caminho Alternativo (Iteração entre Componentes Pendentes):
Após um encaixe bem-sucedido, se o segundo processamento do sistema identificar que ainda faltam peças (precond: existem componentes pendentes), ele segue um fluxo contínuo de retorno para a cena Montar computador, atualizando a barra de progresso e destacando a próxima região de encaixe (d: atualizar progresso e destacar proxima regiao) até que os 3 componentes sejam concluídos.   Caminho de Ruptura (Erro de Encaixe ou Posicionamento):
Durante a validação no primeiro processamento do sistema, se o usuário escolher a peça errada ou soltá-la fora da zona válida, ocorre uma ruptura comunicada pelo preposto via linha tracejada ([TA] d: componente incorreto ou fora da area de encaixe). O fluxo retorna imediatamente à cena Montar computador, permitindo que o usuário se recupere do erro e tente posicionar o componente novamente. 

#### Caminho principal

1. {{Caminho principal — Etapa de Revisão (gco: Compreender componentes de hardware)Acesso ubíquo (menu) → Cena Consultar lista de componentes: O usuário aciona u: revisar componentes (gco: Compreender componentes de hardware), entrando na cena onde o sistema exibe a lista com nome e miniatura das peças (ver componentes).   Cena Consultar lista de componentes → Cena Examinar componente: O usuário escolhe uma peça (u: selecionar componente X) para visualizar seu nome, imagem, descrição e função (ver detalhes).   Cena Examinar componente → Ponto de encerramento (◎): O usuário seleciona u: iniciar montagem (gco: Montar computador), encerrando a conversa de revisão (gcc: Compreender componentes de hardware) e iniciando a próxima etapa.   }}
2. {{Caminho principal — Etapa de Montagem (gco: Montar computador)Ponto de abertura (●) → Cena Montar computador: O usuário inicia a interação (u: iniciar montagem / gco: Montar computador), visualizando o gabinete, a área destacada e os componentes disponíveis (orientar etapa), e realiza a ação de selecionar, arrastar e soltar uma peça (posicionar peca).   Cena Montar computador → Processamento do sistema 1 (■): Ao emitir u: soltar componente, o sistema valida internamente se a peça e a posição estão corretas.   Processamento do sistema 1 (■) → Processamento do sistema 2 (■): Com o encaixe validado (d: componente encaixado com sucesso), o sistema verifica se todos os componentes da etapa já foram posicionados.   Processamento do sistema 2 (■) → Cena Visualizar resultado da montagem: Atendida a pré-condição (precond: todos os componentes encaixados), o sistema confirma d: montagem concluida e exibe a pontuação final e o resumo de acertos (ver desempenho).}}

#### Alternativas e rupturas
Alternativas e rupturas — Etapa de Revisão 

| Situação | Onde ocorre | Como o usuário percebe | Caminho de recuperação/saída |
|---|---|---|---|
| {{SituaçãoOnde ocorreComo o usuário percebeCaminho de recuperação/saídaConsulta a outro componente (Examinar componente}} | {{O usuário decide explorar outra peça (pressup: usuario deseja consultar outro componente) e visualiza/aciona a opção u: voltar para lista}} | {{feedback}} | {{A transição contínua retorna à cena Consultar lista de componentes, exibindo novamente todos os itens disponíveis (ver componentes).}} |
| {{Falha ao carregar detalhes (ruptura)}} | {{Na cena Examinar componente}} | {{O preposto emite um alerta de ruptura ([TA] d: erro ao carregar detalhes do componente) informando a falha técnica na exibição.}} | {{O fluxo tracejado de recuperação retorna à própria cena Examinar componente para recarregar os dados da peça.}} |

Alternativas e rupturas — Etapa de Montagem
| {{Componente incorreto ou fora da área (ruptura)}} | {{No Processamento do sistema 1 (■)}} | {{O preposto comunica a ruptura por meio da fala [TA] d: componente incorreto ou fora da area de encaixe}} | {{A seta tracejada retorna imediatamente à cena Montar computador, permitindo que o usuário corrija a peça ou o posicionamento.}} |
| {{Existem componentes pendentes (fluxo alternativo / repetição)}} | {{No Processamento do sistema 2 (■) após encaixe válido}} | {{O sistema confirma o acerto (d: componente encaixado com sucesso) e atualiza a interface (d: atualizar progresso e destacar proxima regiao).}} | {{A transição contínua retorna à cena Montar computador (precond: existem componentes pendentes) para o encaixe da próxima peça até completar os 3 componentes.}} |


### Checklist específico de modelagem

- [ ] Existe **ponto de abertura** coerente com o início do objetivo.
- [ ] As **cenas de conversa** representam tópicos/assuntos, não nomes de páginas apenas.
- [ ] As transições/falas deixam claro o que o usuário ou o sistema comunica.
- [ ] Há **ponto(s) de encerramento** para objetivos concluídos/abandonados quando aplicável.
- [ ] Processamentos do sistema estão representados conforme a notação adotada em aula, sem “inventar” fala do usuário.
- [ ] Rupturas (breakdowns) relevantes têm feedback e caminho de recuperação, não becos sem saída.
- [ ] Acessos ubíquos/atalhos só aparecem quando semanticamente justificáveis.
- [ ] O diagrama cobre caminhos alternativos importantes, e não apenas o “happy path”.
- [ ] Nomes de objetivos, tópicos e signos são coerentes com a Entrega 9.
- [ ] O diagrama é legível em tamanho normal no GitHub.
- [ ] O MoLIC representa a conversa usuário–sistema, não o fluxo interno do algoritmo.
- [ ] Processamento, filtros, administração, relatórios e históricos incluem retornos/rupturas quando relevantes.

> Repita M02, M03... para todos os integrantes.

## Consolidação da equipe

### Cobertura dos objetivos

| Objetivo | MoLIC que cobre | Lacunas/duplicidades | Decisão |
|---|---|---|---|
| O01 | M01 | {{...}} | {{...}} |

### Preparação para o Figma

Liste os estados/telas que serão necessários **a partir das conversas modeladas**, incluindo feedback, confirmação, erro e recuperação.

## Erros frequentes a evitar

- desenhar apenas caixas com nomes de telas e setas de navegação;
- não modelar falhas, cancelamento, volta ou recuperação;
- usar rótulos genéricos (“Tela 1”, “Processo 2”) sem tópico de conversa;
- criar no Figma fluxos que não existem no MoLIC;
- diagrama sem legenda/fonte editável e com texto ilegível.
