# Entrega 2 — Público-alvo e análise de concorrência

**Data:** {{27/08/2026}}  
**Status:** 🟩 concluída
**Responsabilidade mínima:** cada integrante analisa pelo menos 1 concorrente/interface representativa; a equipe produz síntese comparativa.

## Objetivo da atividade

Compreender soluções do mesmo domínio **e também interfaces familiares ao público-alvo**. O objetivo não é copiar telas, mas identificar convenções, padrões, affordances percebidas, problemas recorrentes, expectativas e oportunidades de design.

> **Concorrente não precisa ser idêntico ao produto.** Pode atuar na mesma área, resolver objetivo semelhante ou disputar a mesma necessidade. Quando não houver concorrente direto, use produtos análogos e softwares que o público já utiliza.

### Para TCCs que não previam interface

Não procure apenas um “concorrente do algoritmo”. Investigue **interfaces profissionais que materializam atividades semelhantes** às que o usuário escolhido precisaria realizar.

Exemplos:

- TCC de banco de dados → consoles de administração, ferramentas para DBA, monitoramento e análise de consultas;
- TCC de LLM/ML → painéis de experimentos, gestão de modelos/datasets, comparação de métricas, revisão de resultados;
- TCC de análise de dados → dashboards, ferramentas de BI, filtros, relatórios e exploração;
- TCC de infraestrutura/API → portais administrativos, observabilidade, logs, gestão de credenciais e uso;
- TCC de cibersegurança → consoles de alertas, triagem, histórico e auditoria.

A pergunta é: **“que convenções esse perfil já conhece para executar tarefas equivalentes?”**

## Entrada obrigatória da Entrega 1

Retome o mapa inicial de alternativas e produtos citado na Entrega 1. Aqui a equipe deixa de trabalhar apenas com impressão inicial e passa a **investigar sistematicamente** cada solução.

| Item citado na Entrega 1 | Tipo | Por que foi citado | Status inicial | Decisão nesta entrega |
|---|---|---|---|---|
| {{...}} | concorrente / análogo / ferramenta cotidiana / processo manual | {{...}} | F / H / ? | analisar / descartar com justificativa |
|Pc Building Simulator| concorrente | Possui objetivos semelhantes | F | analisar|
|IA MANUS | análogo | possui ideia semelhante| F| analisar|

Se uma hipótese da Entrega 1 for confirmada ou refutada durante esta análise, atualize `H01`, `H02`... em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

## 1. Público-alvo desta análise

{{O público-alvo do jogo é composto por indivíduos iniciantes que desejam aprender conceitos básicos de hardware de computadores e processos de montagem de computadores.
Esse grupo inclui estudantes em início de formação acadêmica na área de computação, tecnologia da informação e áreas correlatas, bem como pessoas autodidatas interessadas em adquirir conhecimentos sobre componentes de hardware e montagem de computadores..}}

## 2. Concorrentes diretos/indiretos

### Análise C01 — {{Pc Building Simulator}}

**Autor(a):** {{Beatriz Cristina Emerenciano — 22.222.041-0}}  
**Tipo:** direto   
**Link oficial:** {{https://store.epicgames.com/p/pc-building-simulator-2?lang=pt-BR}}  
**Data de acesso:** {{17/09/2026}}

### Análise C02 — {{produto}}

**Autor(a):** {{Larissa dos Santos Fiuza — matrícula}}  
**Tipo:**  indireto  
**Link oficial:** {{https://manus.im/pt-br/playbook/pc-builder}}  
**Data de acesso:** {{10/09/2026}}

#### Contexto e proposta

{{ A proposta de ambas concorrências é auxiliar no aprendizado e  montagem de hardware mas ambas possuem diferentes propostas, o  PC building simulator é voltada para a gamificação(jogo sério) em modelagem 3d, enquanto Manu é voltada pra uma assistente de  IA omo auxiliar  na configuração para montagem de hardware.}}

#### Funcionalidades relevantes

| Funcionalidade | Como é realizada | Evidência/print | Observação de IHC |
|---|---|---|---|
| {{ tela menu}} | {{  O usuário interage com botões opcionais de iniciar jogo, recomeçar e continuar,sair,opções para configurações }} | <img width="1038" height="583" alt="image" src="https://github.com/user-attachments/assets/d233be6a-d3b4-44bb-a038-14e5537c7f3b" />
` | {{componentes descritivos,chamativos e claros}} |
| {{tela de execução de montagem de hardware}} | {{o usuário interage arrastando os componentes do hardware no gabinete acompanhado de um cheklist de validaçãod e etapas }} | <<img width="1045" height="589" alt="image" src="https://github.com/user-attachments/assets/22639920-e648-4cee-aecf-2f3ddf6e5d61" />
| {{tela de execução de montagem de hardware}} | {{abaixo da tela há botões de interação }} | <img width="796" height="456" alt="image" src="https://github.com/user-attachments/assets/9967fb65-3d44-4dec-8001-e075ec9c77a2" />
 />
/>


#### Experiência do usuário e opiniões

Segundo avaliações do software concorrente PC Building, de modo geral, o softare é  bom, principalmente para quem é iniciante e busca aprender sobre os componentes e a montagem de hardware, porém para usuários que já possuem experiência pode ser repetitivo e cansativo, e a grande critica foi o execesso de propaganda duranda a interatividade com o software.

#### Preço/modelo de negócio

{{ PC Building - 77 reais }}

#### Padrões e tendências percebidos

{{Grande interatividade com imagem que ocupa a tela inteira  seguido de textos  descritivos a atividade e interação do usuário com aquela imagem.}}

#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
| {{Centralização de imagens e texto na tela}} | {{imagens e textos, posiiconamentos dos botões de interação}} | {{aplicaremos a distribuição dos elementos como imagens,textos e botões em nosso jogo}} |

> Repita a subseção para C02, C03... até atender à quantidade da equipe.

## 3. Softwares que o público-alvo usa no cotidiano

Analise interfaces que moldam a expectativa do público, mesmo que não sejam concorrentes.

| Software | Por que o público usa | Padrões relevantes | Prints | O que aprender |
|---|---|---|---|---|
| {{Pc Building Simulator}} | {{Para aprender aprender a montar um hardware,realizar manutenção e gestão de maneira simulada}} | {{Navegação}} | {{https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZAvVqq-UFgaMIfZUpOH2X91StONhzcVWuIzlbPbmToTROygr_c0nybHA&s=10}} | {{passo a passo da montagem dos componentes de hardware, manutenbilidade e gestão}} |

## 3.1 Padrões de interface relevantes ao escopo de IHC

Registre somente padrões encontrados nas soluções analisadas e que possam ter relação com objetivos reais da equipe.

| Padrão observado | Produto(s) | Para qual tarefa serve | Vantagem percebida | Risco/limitação | Aplicável ao nosso escopo? |
|---|---|---|---|---|---|
| dashboard | {{Pc building Simulator}} | {{centralização de imagens e informações}} | {{analisar}} | {{analisar}} | {{sim}}|
| relatório | {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |
| histórico + filtros | {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |
| administração/CRUD | {{ Pc buildin Simulator}} | {{crud do nosso jogo}} | {{gestão de configuração do jogo}} | {{analizar}} | {{sim}} |
| comparação de resultados | {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |

> O objetivo não é concluir “todo concorrente tem dashboard, então teremos um”. O padrão só será adotado se apoiar uma tarefa rastreável.

## 4. Síntese comparativa da equipe

| Critério | C01 | C02 | C03 | Oportunidade para o projeto |
|---|---|---|---|---|
| Navegação | oportunidade para o projeto|  
| Feedback/estado | Oportunidade para o projeto 
| Prevenção/recuperação de erro |  |  |  |  |
| Terminologia |  |  |  |  |
| Acessibilidade |  |  |  |  |
| Eficiência | Oportunidade para o projeto  |

## 5. Recomendações derivadas

Liste recomendações com origem explícita.

- **RC01:** {{recomendação}} — derivada de {{C01/C02/evidência}}.
- **RC02:** {{}}

## Referências

{{fontes dos produtos, avaliações e literatura}}

## Checklist

- [x] O mapa inicial de alternativas da Entrega 1 foi revisitado e aprofundado.
- [x] Hipóteses relevantes sobre mercado/padrões foram atualizadas na rastreabilidade quando surgiram evidências.
- [] Há pelo menos uma análise completa por integrante.
- [x] Cada análise contém prints legíveis da interface.
- [x] Prints mostram telas/estados relevantes, não apenas logos/homepage.
- [x] Foram analisados concorrentes e/ou interfaces representativas ao público.
- [ ] Em TCC sem interface original, foram investigadas ferramentas profissionais análogas às atividades do usuário escolhido.
- [x] Padrões como dashboard, relatório, filtros e CRUD foram analisados como soluções para tarefas, não como requisitos automáticos.
- [ ] Opiniões de UX têm fonte.
- [ ] A síntese compara critérios comuns e produz recomendações.
- [x] Não há “copiar porque o concorrente faz”; há justificativa de adequação ao público/contexto.
