# Entrega 6 — Prototipação em papel

**Data:** {{15/10/2026}}  
**Status:** 🟩 concluída
**Responsabilidade:** 1 solução integrada por equipe

## Objetivo da atividade

Externalizar rapidamente ideias de interação em baixa fidelidade para explorar alternativas antes de investir em detalhes visuais. O valor da atividade está no **ciclo construir → simular → observar → revisar**, não na beleza do desenho.

## 1. Escopo do protótipo

**Personas:** {{Persona 1 – Lucas, 22 anos estudante de Ciência da Computação, autodidata e interessado em hardware e computadores. Busca ampliar seus conhecimentos por meio de estudos independentes e recursos interativos.}}  
**Cenários/tarefas cobertos:** {{{Utiliza o jogo em casa ou na faculdade, principalmente pelo notebook, durante os estudos ou como complemento às aulas de arquitetura de computadores e hardware/ etapa de revisão e montagem}}  
**Objetivos principais:** {{Conseguir identificar cada componente de hardware e entender suas funçoes e compreender a montagem}}

**Personas:** { Mariana,32 anos,Analista administrativa, com interesse em aprender sobre hardware para compreender melhor o funcionamento dos computadores e adquirir conhecimentos que permitam realizar procedimentos básicos de identificação e manutenção.}}  
**Cenários/tarefas cobertos:** {{{Utiliza o jogo em casa ou no trabalho nas horas livres, principalmente pelo notebook, durante os estudos ou como complemento às aulas de arquitetura de computadores e hardware/ etapa de revisão e montagem}}  
**Objetivos principais:** {{Conseguir identificar cada componente de hardware e entender suas funçoes e compreender a montagem}}


## 1.1 Possíveis famílias de interface

Escolha apenas o que for coerente com tarefas e cenários. Para TCCs técnicos, o protótipo pode explorar:

- **dashboard** para monitoramento e tomada de decisão;
- **configuração/parametrização** para preparar algoritmo/modelo/processo;
- **entrada/seleção de dados** com validação;
- **acompanhamento de execução** com progresso, fila, cancelamento e recuperação;
- **relatório/resultados** com explicação, gráficos e exportação;
- **histórico** com busca, filtros, ordenação e detalhes;
- **comparação** entre execuções, versões, algoritmos ou períodos;
- **administração** de usuários, papéis, permissões ou entidades do domínio;
- **auditoria/logs** traduzidos para o perfil;
- **alertas/ocorrências** com ação de resposta.

> Não desenhe todas essas telas por obrigação. O objetivo da baixa fidelidade é experimentar a **estrutura da interação** necessária para as tarefas priorizadas.

## 2. Fluxos escolhidos

| Fluxo | Tarefa/objetivo | Por que foi priorizado |
 **entrada/seleção de dados** com validação;
 **acompanhamento de execução** com progresso, fila, cancelamento e recuperação;
|---|---|---|
| PF01 |{{ Acessar a etapa de revisão e consultar os componentes de hardware, visualizando suas imagens, descrições e funções. | Foi priorizado por ser uma etapa fundamental para a aprendizagem, permitindo que o usuário conheça e identifique os componentes de hardware antes de realizar a montagem do computador. Além disso, possibilita que o usuário consulte as informações no próprio ritmo. |
| PF02 | Iniciar a etapa de montagem, identificar a região indicada pelo sistema, selecionar o componente de hardware correto e arrastá-lo até o local correspondente para realizar o encaixe, repetindo o processo até concluir a montagem. | Foi priorizado por representar a principal atividade prática do jogo sério, permitindo que o usuário aplique os conhecimentos adquiridos sobre os componentes de hardware. Também possibilita avaliar o desempenho durante a montagem, considerando a identificação das peças, a escolha dos componentes corretos e a execução das etapas.}} |

|PF02| {{ indicada pelo sistema, selecionar o componente de hardware correto e arrastá-lo até o local correspondente para realizar o encaixe, repetindo o processo até concluir a montagem.
Foi priorizado por representar a principal atividade prática do jogo sério, permitindo que o usuário aplique os conhecimentos adquiridos sobre os componentes de hardware. Também possibilita avaliar o desempenho durante a montagem, considerando a identificação das peças, a escolha dos componentes corretos e a execução das etapas.}}|

## 3. Telas e estados

- Numere as telas/estados (`P01`, `P02`...).
- Indique controles que mudam o estado.
- Mostre pelo menos caminhos principais e estados de erro/retorno relevantes.

![Protótipo](../assets/06_prototipos/prototipo_fluxo_01.svg)

## 4. Simulação / walkthrough

Realize uma simulação com uma pessoa que não participou da elaboração dessas telas. Um colega pode ser usado **para essa iteração formativa**, mas isso não substitui os participantes finais da Entrega 14.

| Observação | Tela/ação | Evidência | Consequência para o design |
|---|---|---|---|
| {{O usuário encontrou facilmente a opção de revisão no menu principal.}} | {{P01 – Acesso à revisão.}} | {{Conseguiu acessar a etapa sem precisar de orientação.}} | {{Manter a disposição atual do botão de revisão.}} |
| {{O usuário teve dificuldade para identificar que os componentes da lista eram botões selecionáveis.}} | {{P02 – Lista de componentes.}} | {{Precisou clicar em diferentes elementos para descobrir como acessar as informações.}} | {{Melhorar a aparência dos botões, destacando-os como elementos interativos.}} |
| {{O usuário conseguiu consultar as informações, mas teve dificuldade para encontrar a opção de retornar à lista.}} | {{P03 – Informações do componente.}} | {{Procurou o botão de retorno antes de conseguir continuar a consulta.}} | {{Destacar o botão “Voltar” e manter sua posição consistente.}} |
| {{O usuário compreendeu a região iluminada, mas teve dificuldade para arrastar o componente até o local correto.}} | {{P05 – Seleção e movimentação.}} | {{Realizou mais de uma tentativa para encaixar a peça.}} | {{Melhorar o destaque da área de encaixe e fornecer instruções mais claras.}} |
| {{O usuário não compreendeu imediatamente a mensagem apresentada após uma escolha incorreta.}} | {{P06 – Estado de erro.}} | {{Demonstrou dúvida sobre como continuar a montagem.}} | {{Apresentar mensagens de erro mais explicativas e uma opção clara de nova tentativa.}} |

## 5. Alterações após a simulação

| Antes | Problema | Depois | Justificativa |
|---|---|---|---|
| {{Botões de componentes apresentados apenas com seus nomes.}} | {{O usuário pode não perceber que os elementos são selecionáveis.}} | {{Adicionar destaque visual aos botões, com imagens ou ícones dos componentes.}} | {{Facilitar a identificação das opções disponíveis e melhorar a interação.}} |
| {{Botão de retorno pouco destacado na tela de informações.}} | {{O usuário pode ter dificuldade para retornar à lista de componentes.}} | {{Posicionar o botão “Voltar” em local visível e padronizado.}} | {{Melhorar a navegação entre as telas da etapa de revisão.}} |
| {{Região de encaixe apresentada apenas com iluminação.}} | {{O usuário pode não compreender imediatamente onde deve inserir a peça.}} | {{Adicionar uma instrução curta, como “Arraste o componente até a área destacada”.}} | {{Tornar a tarefa mais compreensível, principalmente para iniciantes.}} |
| {{Mensagem de erro genérica após uma escolha incorreta.}} | {{O usuário pode não compreender o motivo do erro nem como continuar.}} | {{Apresentar uma mensagem explicativa e a opção “Tentar novamente”.}} | {{Facilitar a recuperação de erros e evitar que o usuário fique sem saber como prosseguir.}} |

## Checklist

- [x] O protótipo cobre tarefas relevantes da Entrega 5.
- [x] Cada tela/estado pode ser justificado por uma tarefa, decisão ou informação necessária.
- [x] O projeto não criou dashboard/CRUD/login apenas para parecer “completo”.
- [x] Telas/estados estão numerados e navegáveis na documentação.
- [x] Há pelo menos uma simulação/walkthrough documentado.
- [] Críticas não foram apenas listadas: geraram decisão de revisão.
- [x] O protótipo continua em baixa fidelidade; detalhes visuais não mascaram problemas de fluxo.
