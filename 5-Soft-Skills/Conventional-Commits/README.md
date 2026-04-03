# 📝 Conventional Commits | Dev Knowledge Hub

> Lista de commits convencionais organizados por situação.

---

## 📌 Estrutura do Commit
tipo(escopo): mensagem curta e direta

---

## 📌 Tipos e Quando Usar

### feat — Nova funcionalidade
```bash
feat(auth): add login with JWT
feat(user): add profile page
feat(api): add endpoint for password reset
```

### fix — Correção de bug
```bash
fix(auth): fix token expiration error
fix(form): fix validation on empty fields
fix(api): fix 500 error on user creation
```

### docs — Documentação
```bash
docs(readme): add project description
docs(git): add README
docs(api): update endpoint documentation
```

### style — Formatação e estilo
```bash
style(button): fix indentation
style(global): apply prettier formatting
style(navbar): reorder CSS properties
```

### refactor — Refatoração
```bash
refactor(auth): simplify token validation logic
refactor(user): extract validation to separate function
refactor(api): reorganize middleware structure
```

### test — Testes
```bash
test(auth): add unit tests for login
test(user): add integration tests for profile
test(api): add tests for error handling
```

### chore — Tarefas gerais
```bash
chore(deps): update dependencies
chore(env): add .env.example file
chore(git): add .gitignore
```

### perf — Performance
```bash
perf(query): optimize user search query
perf(images): add lazy loading
perf(api): add cache to frequent requests
```

### ci — Integração contínua
```bash
ci(github): add deploy workflow
ci(lint): add eslint pipeline
```

### build — Build e dependências
```bash
build(vite): update vite config
build(docker): add Dockerfile
```

---

## 📌 Regras Rápidas

| Regra | Exemplo |
|-------|---------|
| Mensagem em inglês | `fix(auth): fix token error` |
| Letra minúscula | `feat(user)` não `Feat(User)` |
| Sem ponto no final | `add README` não `add README.` |
| Seja direto | `add login` não `adding the login feature` |

---

*Módulo parte do [Dev Knowledge Hub](../../README.md)*