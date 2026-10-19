# Matriz de rastreabilidade de IHC

A matriz deve ser atualizada ao longo do semestre. Ela ajuda a demonstrar que a interface não surgiu arbitrariamente e registra **como o conhecimento da equipe evoluiu**.

Para projetos cujo TCC não previa interface, esta matriz é especialmente importante: deve ficar visível a passagem da **contribuição técnica do TCC** para um **cenário de uso plausível**, e desse cenário para as decisões de interação.

## 1. Derivação do escopo de IHC a partir do TCC

| Elemento | Registro da equipe | Evidência/justificativa | Estado |
|---|---|---|---|
| Tema do TCC | Analise de estudos |  F - Documento/TCC | definido |
| Resultado técnico esperado | Sistema e análise| H - análise o ganho da tecnologia desenvolvida para o aprendizado do usuário | definido |
| O TCC previa interface? | sim  |  F -Telas para interação de aprendizado sobre os componentes de hardware e montagem | definido |
| Capacidade/contribuição central |  através de uma revisão e montagem interativo de montagem de Hardware Auxiliar as pessoas a aprender sobre hardware e nanalise o ganho que essa interação fornece para aprendizado para o usuário| H | definido |
| Possíveis beneficiários/stakeholders | Pessoas sem vínculo com a área de TI (com ou sem formação em outras áreas) e sem nenhum conhecimento prévio sobre hardware ou montagem, estudantes de TI, autodidatas ou profissionais formados na área com conhecimento apenas básico/superficial de hardware, sem experiência prática bem-sucedida em montagem.| H | definido|
| Usuário escolhido para IHC |  Pessoas sem vínculo com a área de TI (com ou sem formação em outras áreas) e sem nenhum conhecimento prévio sobre hardware ou montagem, estudantes de TI, autodidatas ou profissionais formados na área com conhecimento apenas básico/superficial de hardware, sem experiência prática bem-sucedida em montagem| F | denifido|
| Objetivo principal do usuário | Aprender sobre os componentes e montagem de hardware | H - Hardware é um assunto que pode ser trabalhoso de ser estudado principalmente para iniciantes  o objetivo é aulixar estudantes e pessoas leigas que estão iniciando seu aprendizado sobre harwdware | definido|
| Contexto de uso adotado | Analisar o ganho do jogo sério desenvolvido no aprendizado do usuário | H}} | definido |
| Interface/recorte de IHC | Tela de revisão e montagem.| F | definido |
| Relação com o TCC | protótipo demonstrativo | definido |

> Se o escopo de IHC mudar ao longo do semestre, preserve a decisão anterior no histórico e registre **qual evidência motivou a mudança**.

## 2. Registro de hipóteses e lacunas da Entrega 1

Use esta tabela para itens importantes marcados como `[H]` ou `[?]`. Preserve o histórico: não apague uma hipótese refutada.

| ID | Afirmação / dúvida inicial | Tipo | Por que importa | Como/onde investigar | Evidência obtida | Estado atual | Impacto no projeto |
|---|---|---|---|---|---|---|---|
| H01 | O Sériis Game contribui para o aprendizado dobre identificação dos componentes e montagem de hardware | H  | {{importa sabermos se o projeto contribui em aprendizado aos usuários}} | Entrega 1 | {{ PENDENTE}} | aberta e refinada | {{alto}} |
| H02 | {{Os estudantes com ou sem experiência tecnologica conseguem utilizar o Sérios Game com facilidade}} | H  | {{Importa saber se os métodos de usabilidade que aplicaremos corrobora para uma boa experi|ência e facilidade de interação para o usuário que busca aprender sobre hardware}} | {{Entrega 1}} | {{Pendente}} | aberta | {{alto}} |

## 3. Rastreabilidade entre contribuição técnica, necessidades e artefatos

| ID | Capacidade do TCC utilizada | Necessidade/problema | Persona | Cenário problema | Objetivo/tarefa | HTA/GOMS/CTT | Cenário de interação / signos | MoLIC | Tela(s) Figma | Heurística / problema | Tarefa no teste | Decisão/melhoria |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R01 | {{ex.: recomendação de otimização}} | {{...}} | {{P01}} | {{C01}} | {{T01}} | {{links}} | {{...}} | {{M01}} | {{F01...}} | {{V01 ou —}} | {{UT01}} | {{...}} |
| R01 | {{ex.: recomendação de otimização}} | {{...}} | {{P01}} | {{C01}} | {{T01}} | {{links}} | {{...}} | {{M01}} | {{F01...}} | {{V01 ou —}} | {{UT01}} | {{...}} |
| R02 |  |  |  |  |  |  |  |  |  |  |  |  |

## 4. Rastreabilidade de padrões de interface

Use esta tabela quando o projeto incorporar padrões como dashboard, relatório, histórico, filtros ou administração. O objetivo é **justificar o padrão**, não apenas listar telas.

| ID da tela/fluxo | Padrão de interface | Objetivo/tarefa que justifica | Informação/ação principal | Evidência de necessidade | Artefatos relacionados |
|---|---|---|---|---|---|
| F01 | dashboard | {{T01}} | {{...}} | {{H01/evidência...}} | {{C01/M01}} |
| F02 | histórico com filtros | {{T02}} | {{...}} | {{...}} | {{...}} |
| F03 | administração/CRUD | {{T03}} | {{...}} | {{...}} | {{...}} |

## 5. Registro de mudanças de escopo

| Data | O que mudou | Evidência/feedback que motivou | Artefatos afetados | Responsável |
|---|---|---|---|---|
| {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |

## Como usar

- Use identificadores estáveis (`H01`, `P01`, `C01`, `T01`, `M01`, `F01`, `UT01`).
- Quando uma necessidade/problema tiver origem em hipótese da Entrega 1, cite o ID correspondente.
- Em TCC sem interface original, pelo menos uma linha deve mostrar claramente **como uma capacidade técnica chega até uma tarefa de usuário e uma tela/fluxo**.
- Uma linha pode se desdobrar quando um objetivo possui múltiplos caminhos.
- Não force relação inexistente: se algo ainda não foi modelado, marque `PENDENTE`.
- Ao remover uma funcionalidade, registre a decisão em vez de apagar silenciosamente o histórico.
- Dashboard, CRUD, filtros e relatórios só devem aparecer quando houver objetivo/tarefa que os justifique.
