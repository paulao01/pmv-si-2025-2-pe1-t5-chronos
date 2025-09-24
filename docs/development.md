# Programação de Funcionalidades

## ✅ Requisitos Atendidos

As tabelas a seguir apresentam os **Requisitos Funcionais** e **Não Funcionais**, relacionando o escopo do projeto com os artefatos criados.

### 🔹 Requisitos Funcionais

| ID    | Descrição do Requisito                                                   | Responsável       | Artefato Criado            |
|-------|--------------------------------------------------------------------------|------------------|-----------------------------|
| RF-001| Disponibilizar visualização em calendário, lista ou kanban                | Lucas Oliveira   | `calendar.html`, `kanban.js` |
| RF-002| Permitir o registro, edição e exclusão de notas ou atividades             | Diego Teixeira   | `tasksController.js`, `form.html` |
| RF-003| Possibilitar a consulta de notas e atividades em dias anteriores e futuros| Richard Smanhoto | `calendar.js`               |
| RF-004| Possuir um sistema de metas para incentivar o engajamento do usuário      | Jennifer Vieira  | `goals.js`, `progressBar.js` |
| RF-005| Disponibilizar tela de análise com gráficos de acompanhamento             | Paulo Henrique   | `charts.js`                 |
| RF-006| Permitir categorização por cores para facilitar a distinção de tarefas    | Diego Miranda    | `categories.js`, `style.css` |

---

### 🔹 Requisitos Não Funcionais

| ID     | Descrição do Requisito                                                                 | Responsável       | Artefato Criado            |
|--------|-----------------------------------------------------------------------------------------|------------------|-----------------------------|
| RNF-001| O funcionamento da aplicação deve depender de conexão com a internet                   | Lucas Oliveira   | Deploy em GitHub Pages/Vercel |
| RNF-002| A aplicação deve ser hospedada em um servidor na nuvem                                 | Diego Teixeira   | Configuração em Vercel/Netlify |
| RNF-003| Os dados da aplicação devem ser armazenados na máquina local                           | Richard Smanhoto | `localStorage.js`           |
| RNF-004| Acessibilidade: interface inclusiva, com contraste adequado e suporte a leitores de tela| Jennifer Vieira  | `style.css` (WCAG 2.1 + ARIA) |
| RNF-005| Usabilidade: interface intuitiva, permitindo fácil uso sem conhecimento técnico         | Paulo Henrique   | Layout responsivo em `index.html` |
| RNF-006| Desempenho: sistema responsivo e com carregamento rápido                               | Diego Miranda    | Código otimizado em JS, imagens comprimidas |
| RNF-007| Disponibilidade: sistema acessível com manutenções programadas                         | Equipe Chronos   | Configuração em ambiente de deploy |

