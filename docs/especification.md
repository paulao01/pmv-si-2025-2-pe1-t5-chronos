# Especificações do Projeto

## Perfis de Usuários

| ID  | Perfil                               | Descrição                                                                                      | Necessidades                                                                                  |
|-----|--------------------------------------|------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| 01  | Estudante Universitário              | Estudantes que lidam com grande volume de tarefas acadêmicas, como leituras, trabalhos, provas e atividades extracurriculares | Ferramenta prática para organizar compromissos acadêmicos, visualizar prazos e planejar o tempo de estudo |
| 02  | Jovem Profissional em Início de Carreira | Profissionais que precisam equilibrar responsabilidades profissionais com vida pessoal e social | Centralizar tarefas em um único sistema, apoiar definição de prioridades e evitar esquecimentos/atrasos |
| 03  | Trabalhador Autônomo/Freelancer      | Usuários independentes, com rotinas dinâmicas e diversificadas, alternando entre diferentes tipos de tarefas | Agenda inteligente com personalização, controle de prazos e acompanhamento de metas de curto e longo prazo |
/h1
-A aplicação será flexível para atender diferentes perfis de usuários, permitindo
personalização das funcionalidades, como categorização de atividades, definição de metas
e visualização adaptada de acordo com as necessidades específicas (estudantes,
profissionais ou autônomos).

## Personas

Persona 1 – Pedro Paulo (inspirado no exemplo do professor)

Idade: 26 anos

Profissão: Arquiteto recém-formado, autônomo

Objetivos: Deseja se organizar para conciliar rotina profissional e planos de mestrado no exterior.

Necessidades: Uma ferramenta que permita gerenciar compromissos profissionais, estudar idiomas e planejar metas de médio prazo.

Persona 2 – Júlia Martins

Idade: 20 anos

Perfil: Estudante universitária de Engenharia

Objetivos: Conciliar provas, trabalhos em grupo, estágio e atividades extracurriculares.

Necessidades: Visualização clara de prazos, categorização por disciplina, lembretes automáticos.

Persona 3 – Rafael Nunes

Idade: 28 anos

Perfil: Jovem profissional em início de carreira (área de marketing)

Objetivos: Balancear vida profissional intensa com cursos de atualização e vida social.

Necessidades: Centralização de compromissos, notificações, relatórios de desempenho semanal.

Persona 4 – Carla Souza

Idade: 32 anos

Perfil: Freelancer de design gráfico

Objetivos: Lidar com múltiplos clientes, prazos curtos e projetos variados.

Necessidades: Sistema de categorização por cores, metas de curto e longo prazo, análise visual de progresso.


## Histórias de Usuários

| Persona              | Quero/Desejo                                                                 | Para/Valor                                                                 |
|----------------------|-------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| Estudante            | Organizar minhas tarefas diárias                                              | Observar minha eficiência e gerenciar melhor meu tempo                     |
| Jovem Profissional   | Equilibrar minhas responsabilidades no trabalho                               | Ter maior controle sobre prazos e compromissos                             |
| Freelancer           | Ter uma ferramenta flexível para traçar objetivos e metas                     | Garantir maior praticidade                                                  |
| Usuário              | Categorizar atividades e compromissos por cores                               | Identificar facilmente diferentes áreas da minha vida                      |
|  autônomo            | Receber notificações antes dos meus compromissos                              | Não me atrasar ou esquecer                                                 |
| Usuário              | Dividir metas em pequenas atividades                                          | Torná-las mais alcançáveis                                                 |
| Usuário              | Visualizar gráficos de progresso                                              | Manter minha motivação                                                     |
| Usuário              | Receber resumos semanais do meu desempenho                                    | Refletir sobre minha produtividade                                         |




### Requisitos Funcionais



| ID   | Descrição                                                                                                                                                | Prioridade |
|------|----------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| RF01 | Disponibilizar uma visualização de calendário, lista ou kanban. *(Embora existam ferramentas como Google Agenda, Trello e Notion, muitas apresentam limitações, como falta de integração, excesso de complexidade ou ausência de recursos de acompanhamento de metas. A Agenda Inteligente Chronos busca oferecer uma alternativa mais centralizada, intuitiva e acessível.)* | Alta       |
| RF02 | Permitir o registro, edição e exclusão de notas ou atividades                                                                                            | Alta       |
| RF03 | Possibilitar a consulta de notas e atividades em dias anteriores e futuros                                                                               | Média      |
| RF04 | Possuir um sistema de metas para incentivar o engajamento do usuário                                                                                     | Alta       |
| RF05 | Permitir a edição e exclusão de notas e atividades cadastradas                                                                                           | Média      |
| RF06 | Disponibilizar uma tela de análise com visualizações de acompanhamento de atividade                                                                      | Baixa      |
| RF07 | Permitir categorização por cores para facilitar a distinção de tarefas                                                                                   | Média      |



### Requisitos não Funcionais



| ID    | Descrição                                                                                                                                                 | Prioridade |
|-------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| RNF01 | O funcionamento da aplicação deve depender de conexão com a internet                                                                                      | Baixa      |
| RNF02 | A aplicação deve ser hospedada em um servidor na nuvem, contemplando Front-End                                                                            | Alta       |
| RNF03 | Os dados da aplicação devem ser armazenados na máquina local                                                                                              | Baixa      |
| RNF04 | Acessibilidade: interface inclusiva, com contraste adequado e suporte a leitores de tela                                                                  | Média      |
| RNF05 | Usabilidade: interface intuitiva, permitindo fácil uso sem conhecimento técnico                                                                           | Média      |
| RNF06 | Desempenho: o sistema deve ser responsivo e possuir tempos de carregamento rápidos, garantindo uma experiência fluida ao usuário durante a navegação       | Alta       |
| RNF07 | Disponibilidade: o sistema deve permanecer disponível para uso na maior parte do tempo, com manutenções programadas e impacto mínimo para os usuários      | Alta       |



## Restrições do Projeto

| ID  | Restrição                                                                 |
|-----|----------------------------------------------------------------------------|
| 01  | O projeto deverá ser entregue até o final do semestre letivo               |
| 02  | O sistema deverá ser desenvolvido apenas com tecnologias web (HTML, CSS, JS e frameworks front-end) |
| 03  | Não será desenvolvido um módulo de backend próprio, apenas integração com serviços externos se necessário |
| 04  | O projeto deverá ser hospedado em nuvem gratuita ou de baixo custo         |
| 05  | A solução deve priorizar acessibilidade e usabilidade, mesmo com recursos limitados |
****
