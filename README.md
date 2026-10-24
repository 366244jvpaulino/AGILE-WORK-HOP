🚀 Agile WorkShop — Aula 01: Landing Page Scrum

Mostrar Imagem Mostrar Imagem Mostrar Imagem Mostrar Imagem Mostrar Imagem Mostrar Imagem

📌 Segundo Commit — Simulação do fluxo Scrum + Git/GitHub através da criação de uma landing page sobre o Framework Scrum.

📋 Informações Gerais
🏷️ Item	📝 Detalhe
👥 Grupo	Aluno 1 e Aluno 2
📅 Data da Sprint	10/10/2026
⏱️ Duração	2 sprints simulados
🌿 Branch base	main
🎯 Objetivo

Simular o fluxo Scrum + Git/GitHub criando uma landing page sobre o Framework Scrum, com:

🌿 Ramificações (branches) separadas para HTML5 e CSS3
🔗 Uma sprint posterior de integração e validação
🤝 Trabalho paralelo com responsabilidades claras entre os integrantes
✅ Definição de Concluído (DoD)

Para considerar a atividade concluída, o grupo deve cumprir:

 📌 Sprint 1 personalizado com tarefas separadas para HTML5 e CSS3
 🌿 Branch feature/html5-scrum-aluno-1 criada a partir de main
 🌿 Branch feature/css3-scrum-aluno-2 criada a partir de main
 📄 index.html criado em HTML5 puro (sem class, sem id e sem link para CSS)
 🎨 assets/css/styles.css criado com CSS3 responsivo e seletores planejados
 💬 Commits com mensagens claras no padrão Conventional Commits
 🔀 Pull Requests abertos para main
 👀 Cada PR revisado por outra pessoa
 🧩 Ramos da Sprint 1 integrados na main
 🔗 Sprint 2 criada para integrar HTML + CSS
 🏷️ Classes, ids e link do CSS aplicados no HTML durante a integração
 🧪 Validação registrada pelos 2 alunos
 🎤 Landing page demonstrada na Sprint Review
 🔄 Retrospectiva preenchida em RETROSPECTIVE.md
🗺️ Fluxo de Trabalho (Git Flow)
gitGraph
   commit id: "main inicial"
   branch feature/html5-scrum-aluno-1
   branch feature/css3-scrum-aluno-2
   checkout feature/html5-scrum-aluno-1
   commit id: "feat: estrutura HTML5"
   checkout feature/css3-scrum-aluno-2
   commit id: "feat: estilos CSS3"
   checkout main
   merge feature/html5-scrum-aluno-1 id: "PR HTML aprovado"
   merge feature/css3-scrum-aluno-2 id: "PR CSS aprovado"
   branch feature/integracao-html-css-validacao
   commit id: "feat: integra CSS ao HTML"
   commit id: "docs: VALIDACAO.md"
   checkout main
   merge feature/integracao-html-css-validacao id: "Entrega final"
🏃 Sprint 1 — Criação Separada dos Artefatos

🎯 Objetivo: demonstrar trabalho paralelo em branches independentes, com responsabilidades claras.

#	📌 Tarefa	📝 Descrição	👤 Responsável	🌿 Branch	📊 Status	✔️ Critérios de Aceitação
1	🧱 Criar estrutura HTML5 da landing page	Criar index.html com conteúdo sobre Scrum usando semântica HTML5, sem class, sem id e sem link para CSS.	Aluno 1	feature/html5-scrum-aluno-1	⬜ A fazer	Arquivo abre no navegador, comunica o tema Scrum e preserva HTML puro para integração futura.
2	🎨 Criar estilos CSS3 responsivos	Criar assets/css/styles.css com layout mobile-first, variáveis CSS, grid/flex, hover/focus e seletores planejados.	Aluno 2	feature/css3-scrum-aluno-2	⬜ A fazer	CSS contém ganchos como .site-header, .hero, .roles-grid, .events-timeline, .artifacts, .cta-section e #scrum-framework.
3	🔍 Revisar PR de HTML5	Avaliar semântica, conteúdo e ausência de classes/ids no HTML.	Aluno 2	PR da branch HTML	⬜ A fazer	PR revisado com comentário objetivo e aprovação ou solicitação de ajuste.
4	🔍 Revisar PR de CSS3	Avaliar responsividade, organização, seletores planejados e aderência ao tema visual.	Aluno 1	PR da branch CSS	⬜ A fazer	PR revisado com comentário objetivo e aprovação ou solicitação de ajuste.
5	🔀 Integrar entregas da Sprint 1	Realizar o merge dos PRs aprovados na main.	Aluno 1 e Aluno 2	main	⬜ A fazer	main contém HTML e CSS como arquivos separados, ainda sem integração funcional completa.
🔗 Sprint 2 — Integração e Validação

🎯 Objetivo: conectar os artefatos da Sprint 1, validar a entrega e demonstrar a página final.

#	📌 Tarefa	📝 Descrição	👤 Responsável	🌿 Branch	📊 Status	✔️ Critérios de Aceitação
6	🌱 Criar branch de integração	Criar feature/integracao-html-css-validacao a partir da main com os merges da Sprint 1.	Aluno 1	feature/integracao-html-css-validacao	⬜ A fazer	Branch criada a partir da main atualizada com HTML e CSS.
7	🧩 Integrar CSS ao HTML	Adicionar <link rel="stylesheet" href="assets/css/styles.css"> e aplicar classes/ids planejados no HTML.	Aluno 1 e Aluno 2	feature/integracao-html-css-validacao	⬜ A fazer	HTML passa a usar os hooks definidos no CSS e a página carrega os estilos corretamente.
8	🧪 Validar integração e responsividade	Testar a landing page no navegador: conferir âncoras, carregamento do CSS e responsividade em 📱 celular, 📲 tablet e 🖥️ desktop.	Aluno 1	feature/integracao-html-css-validacao	⬜ A fazer	Validação registrada em VALIDACAO.md, incluindo resultados e observações.
9	👀 Revisar entrega integrada	Conferir a página: comunicação do Scrum, papéis, eventos, artefatos, benefícios e chamada final (CTA).	Aluno 2	PR da branch de integração	⬜ A fazer	PR revisado com foco em qualidade visual, conteúdo e funcionamento.
10	🎤 Sprint Review (Demonstração)	Apresentar fluxo Git, arquivos criados, PRs, integração e landing page em funcionamento.	Aluno 1 e Aluno 2	main	⬜ A fazer	Entrega demonstrada e evidências registradas, sem pendências no backlog.
🧾 Evidências de Git e GitHub
👤 Pessoa	🛠️ Entrega	🔖 Commit (link/hash)	🔀 Pull Request	👀 Revisado por	🧩 Merge realizado?
Aluno 1	Criar HTML5 puro			Aluno 2	⬜
Aluno 2	Criar CSS3 responsivo			Aluno 1	⬜
Aluno 1 e Aluno 2	Integrar HTML + CSS			Aluno 2	⬜
Aluno 1	Validar integração			Aluno 1	⬜
🎤 Sprint Review
🔗 Link do repositório público

Adicionar link aqui

▶️ Como executar ou acessar a landing page

Descrever aqui (ex.: abrir index.html no navegador ou link do GitHub Pages)

🏆 Principais entregas demonstradas
🌿 Branch HTML5 com index.html puro
🎨 Branch CSS3 com folha de estilo responsiva separada
🔗 Branch de integração com HTML conectado ao CSS
📱 Validação da responsividade e do conteúdo
🚧 Itens incompletos ou fora do escopo
❌ Não há JavaScript nesta atividade
📄 A página é estática e focada na prática de Scrum + Git
📝 Observações e Bloqueios

💡 A separação entre HTML sem hooks e CSS com seletores foi planejada intencionalmente para criar uma atividade real de integração na Sprint 2.

⚠️ A comunicação entre os responsáveis deve ser reforçada antes da integração, para alinhar nomes de classes, ids e a estrutura esperada.

💬 Padrão de Commits

Utilizamos Conventional Commits:

Tipo	Uso	Exemplo
✨ feat	Nova funcionalidade	feat: cria estrutura HTML5 da landing page
🎨 style	Estilos/CSS	style: adiciona layout responsivo mobile-first
📚 docs	Documentação	docs: registra validação em VALIDACAO.md
🐛 fix	Correção de erro	fix: corrige link do CSS no index.html
♻️ refactor	Refatoração	refactor: organiza variáveis CSS
👥 Equipe
👤 Integrante	🎯 Foco
Aluno 1	🧱 HTML5 • 🌱 Branch de integração • 🧪 Validação
Aluno 2	🎨 CSS3 • 👀 Revisão da entrega integrada
<p align="center">Feito com 💙 durante o <strong>Agile WorkShop</strong> · Scrum + Git/GitHub</p>
