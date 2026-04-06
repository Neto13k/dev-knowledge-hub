# 🧠 Dev Knowledge Hub

Este repositório documenta como utilizo IA de forma controlada no desenvolvimento de software, utilizando documentação oficial como fonte primária para tomada de decisão técnica.

O foco não é geração de código, mas entendimento, validação e construção baseada em fontes confiáveis.

> ⚠️ **Nota de Evolução:** Este repositório e meus Notebooks de IA estão em constante
> atualização e expansão conforme novas tecnologias e padrões são integrados ao meu
> fluxo de trabalho.

---

## 💡 A Filosofia por Trás deste Repositório

A maioria dos desenvolvedores que usa IA hoje cai em um dos dois extremos:

- **Ignora a IA** e perde produtividade navegando em documentações extensas manualmente.
- **Depende demais da IA** e escreve código sem entender o que está fazendo.

Este repositório documenta um terceiro caminho: usar IA como uma **camada de busca
inteligente sobre documentações oficiais**, mantendo o domínio técnico em cada decisão.

Cada Notebook deste projeto foi alimentado exclusivamente com documentação oficial.
Isso significa que cada resposta gerada tem uma fonte verificável — sem achismos,
sem conteúdo desatualizado, sem alucinações sem base.

---

## 🔄 Workflow de Desenvolvimento com IA

1. Definição do problema
2. Consulta no NotebookLM (fontes oficiais)
3. Validação na documentação original
4. Comparação de abordagens
5. Implementação manual
6. Revisão crítica com IA

> A IA é utilizada como suporte à decisão, não como fonte final de código.

---

## 🔬 Exemplo Real

Problema: tipar corretamente uma resposta de API no Axios com TypeScript

Processo:
1. Consulta no NotebookLM sobre tipagem no Axios
2. Validação na documentação oficial do Axios e TypeScript
3. Comparação entre uso de interfaces e tipos genéricos
4. Definição da abordagem mais segura

Decisão:
- Uso de tipagem explícita com interfaces
- Evitar uso de `any`
- Integração direta com React

Resultado:
- Código tipado com segurança
- Melhor previsibilidade de dados
  
👉 Todas as respostas são baseadas exclusivamente nas documentações carregadas no Notebook.

---

## 🧠 Prompts Engine

Este projeto inclui uma biblioteca de prompts projetada para:

- forçar respostas baseadas em documentação
- reduzir respostas genéricas
- estruturar análise de problemas técnicos

Os prompts são parte essencial do fluxo e garantem consistência no uso da IA.

---

## 🌐 Notebook Fullstack Geral

Mantenho um **Notebook Geral** no NotebookLM que engloba todas as stacks do ecossistema
Fullstack. Ele é o cérebro que conecta as pontas e responde perguntas de integração entre
tecnologias.

**O que consigo fazer com ele:**
- Planejar como o **SQL** via **Node/Express** é tipado no **TypeScript** e consumido
  pelo **Axios** no **React**
- Entender o fluxo completo de autenticação do **JWT** do backend até o frontend
- Consultar o [roadmap.sh](https://roadmap.sh) integrado para orientar os próximos
  passos de aprendizado
- Tomar decisões arquiteturais com base em documentação oficial, não em opinião

> 💡 Este é o único Notebook que inclui o [roadmap.sh](https://roadmap.sh) como fonte,
> funcionando como bússola de evolução técnica dentro do ecossistema.

[🔗 Acessar Notebook Fullstack Geral](https://notebooklm.google.com/notebook/41d7c1ca-6849-4d95-b9e1-436125ed6859)

---

## 📂 Estrutura do Projeto
```
/dev-knowledge-hub
│
├── README.md
│
├── /0-Dev-Tools
│   ├── /Git
│   ├── /Postman
│   └── /VS-Code
│
├── /1-Fundamentos
│   ├── /HTML-CSS
│   ├── /JavaScript
│   ├── /TypeScript
│   └── /Sass-Tailwind
│
├── /2-Frontend
│   ├── /React
│   └── /Axios
│
├── /3-Backend
│   ├── /Node-Express
│   ├── /JWT-Security
│   └── /SQL-Postgres-MySQL
│
├── /4-Prompts-Engine
│
└── /5-Soft-Skills
    ├── /Clean-Code
    └── /Conventional-Commits
```
---

## 🛠 Estrutura de Estudos por Módulo

### [🔧 0. Dev Tools](./0-Dev-Tools)

Ferramentas que sustentam o fluxo de trabalho diário de qualquer desenvolvedor.
Antes de escrever a primeira linha de código, é necessário dominar o ambiente.

| Módulo | Notebook | Documentação Oficial |
|--------|----------|---------------------|
| [Git](./0-Dev-Tools/Git/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/f954de78-d707-4018-a4a1-a98a2b628805) | [git-scm.com](https://git-scm.com/docs/git/pt_BR) |
| [Postman](./0-Dev-Tools/Postman/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/1526531b-fe58-410c-930a-da3a27db3983) | [learning.postman.com](https://learning.postman.com/docs) |
| [VS Code](./0-Dev-Tools/VS-Code/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/e63b23ea-c11f-4a7b-bd2d-4c5fe5d4bdcc) | [code.visualstudio.com](https://code.visualstudio.com/docs) |

---

### [🏗️ 1. Fundamentos & Linguagens](./1-Fundamentos)

A base que sustenta tudo. Não existe frontend sólido sem HTML/CSS bem entendido,
nem backend confiável sem JavaScript dominado. TypeScript adiciona a camada de
segurança de tipos que o mercado exige.

| Módulo | Notebook | Documentação Oficial |
|--------|----------|---------------------|
| [HTML & CSS](./1-Fundamentos/HTML-CSS/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/b8c134bd-f64a-4d22-a9cf-32e690291351) | [MDN HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML) / [MDN CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS) |
| [JavaScript](./1-Fundamentos/JavaScript/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/84694740-b597-4b70-9410-9cebc05deb90) | [MDN JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) |
| [TypeScript](./1-Fundamentos/TypeScript/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/5f30eee2-f0de-4582-a0db-5f0c1858428b) | [typescriptlang.org](https://www.typescriptlang.org/pt/docs/) |
| [Sass & Tailwind](./1-Fundamentos/Sass-Tailwind/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/cbb324b4-5681-4451-beca-843bef368361) | [Tailwind](https://tailwindcss.com/docs/installation/using-vite) / [Sass](https://sass-lang.com/documentation/) |

---

### [⚛️ 2. Frontend](./2-Frontend)

O ecossistema client-side centrado em React. Aqui estão as ferramentas para construir
interfaces reativas, gerenciar formulários com validação robusta e consumir APIs de
forma eficiente e tipada.

| Módulo | Notebook | Documentação Oficial |
|--------|----------|---------------------|
| [React](./2-Frontend/React/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/d6360985-b4d0-4c55-adc2-b73acb5d063e) | [react.dev](https://react.dev) / [React Router](https://reactrouter.com/home) / [Hook Form](https://react-hook-form.com/docs) |
| [Axios](./2-Frontend/Axios/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/c3067b5b-c131-45be-b04b-855ae9a303de) | [axios-http.com](https://axios-http.com/ptbr/docs/intro) |

---

### [🚀 3. Backend](./3-Backend)

O ecossistema server-side. Do servidor HTTP com Express à segurança com JWT, passando
pela modelagem e consulta de dados com SQL. Esta é a camada que garante que os dados
trafeguem com segurança entre o banco e o frontend.

| Módulo | Notebook | Documentação Oficial |
|--------|----------|---------------------|
| [Node & Express](./3-Backend/Node-Express/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/e3ccd255-9c72-4a95-adcb-95e26e8f6e56) | [Node.js](https://nodejs.org/docs/latest/api/) / [Express](https://expressjs.com/) |
| [JWT Security](./3-Backend/JWT-Security/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/e545cb28-511b-4c4b-9357-e468929583b6) | [jwt.io](https://jwt.io/introduction) |
| [SQL](./3-Backend/SQL-Postgres-MySQL/README.md) | [🔗 Acessar](https://notebooklm.google.com/notebook/c70b472a-b26a-4351-93a4-c8329f3d6332) | [PostgreSQL](https://www.postgresql.org/docs/) / [MySQL](https://dev.mysql.com/doc/) / [W3Schools SQL](https://www.w3schools.com/sql/) |

---

### [🤖 4. Prompts Engine](./4-Prompts-Engine)

A biblioteca de prompts que torna este sistema eficiente. Prompts genéricos geram
respostas genéricas. Cada prompt aqui foi pensado para um contexto específico —
erro, aprendizado, revisão ou integração — reduzindo ruído e evitando alucinações.

[📖 Acessar Biblioteca de Prompts](./4-Prompts-Engine/README.md)

---

### [🤝 5. Soft Skills](./5-Soft-Skills)

Código que funciona é o mínimo. Código que outros desenvolvedores conseguem ler,
manter e evoluir é o diferencial. Esta seção documenta os padrões de engenharia
que guiam cada decisão de escrita e versionamento neste repositório.

| Módulo | O que cobre |
|--------|------------|
| [Clean Code](./5-Soft-Skills/Clean-Code/README.md) | Nomes, funções, DRY, KISS, YAGNI e Single Responsibility |
| [Conventional Commits](./5-Soft-Skills/Conventional-Commits/README.md) | Tipos, escopos, regras e exemplos por situação |

---

## ▶️ Como usar este repositório

1. Escolha um módulo (React, Node, SQL, etc.)
2. Acesse o Notebook correspondente pela tabela do módulo
3. Utilize os prompts da pasta [/4-Prompts-Engine](./4-Prompts-Engine/README.md)
4. Faça perguntas com contexto real do seu código
5. Aplique o aprendizado e evolua

> Este repositório é uma ferramenta ativa de aprendizado — não leitura passiva.

---

## 📊 Resultado do Método

- Decisões baseadas em documentação oficial
- Redução de tentativa e erro
- Código com maior previsibilidade
- Menor dependência de respostas genéricas de IA
  
---

## 🔄 Atualização das Fontes

As documentações utilizadas são carregadas manualmente no NotebookLM.

Isso garante:
- Controle total sobre as fontes
- Confiabilidade do conteúdo
- Rastreabilidade das respostas

⚠️ A atualização das documentações não é automática. As fontes são revisadas
periodicamente para acompanhar novas versões das tecnologias.

---

## 🎯 O que este projeto demonstra

- Método estruturado de aprendizado com IA e documentação oficial
- Visão fullstack real — do banco de dados à interface
- Uso responsável de IA como ferramenta de busca, não de geração cega de código
- Maturidade técnica com Clean Code e Conventional Commits desde o início
- Capacidade de tomar decisões baseadas em fontes verificáveis

> Mais do que mostrar código pronto, este repositório mostra **como decisões técnicas
> são tomadas**.

---

*"O código é o resultado, a documentação é o mapa e a organização é o caminho."*
