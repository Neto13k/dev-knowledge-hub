# 🧹 Clean Code | Dev Knowledge Hub

> Princípios de código limpo aplicados ao ecossistema Fullstack.

---

## 📌 Princípios Fundamentais

### Nomes com significado
```javascript
// ❌ Ruim
const x = 30;
function fn(a, b) {}

// ✅ Bom
const idadeMinima = 30;
function calcularIdade(dataNascimento, dataAtual) {}
```

### Funções com responsabilidade única
```javascript
// ❌ Ruim
function salvarUsuario(dados) {
  // valida, salva e envia email ao mesmo tempo
}

// ✅ Bom
function validarUsuario(dados) {}
function salvarUsuario(dados) {}
function enviarEmailBoasVindas(email) {}
```

### Evitar comentários desnecessários
```javascript
// ❌ Ruim
// incrementa i em 1
i++;

// ✅ Bom — o código se explica sozinho
proximoItem++;
```

### Evitar código morto
```javascript
// ❌ Ruim
function antigaFuncao() {} // não usada mas continua no código

// ✅ Bom — delete o que não usa
```

---

## 📌 Regras Práticas

| Regra | O que significa |
|-------|----------------|
| **DRY** | Não repita código — extraia em funções |
| **KISS** | Mantenha simples — evite complexidade desnecessária |
| **YAGNI** | Não implemente o que não precisa agora |
| **Single Responsibility** | Cada função/classe faz apenas uma coisa |

---

## 📌 Estrutura de Arquivos
✅ Um arquivo por responsabilidade
✅ Nomes de arquivos descritivos
✅ Imports organizados no topo
✅ Exports explícitos no final

---

*Módulo parte do [Dev Knowledge Hub](../../README.md)*