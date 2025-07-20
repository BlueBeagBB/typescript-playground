# 🤝 Contribuindo com o TypeScript Playground

Obrigado por se interessar em contribuir! Este repositório é um ambiente de aprendizado colaborativo e modular, onde qualquer pessoa pode adicionar desafios, melhorar a estrutura ou corrigir problemas.

## 📌 Regras Gerais

- Todos os desafios devem:
  - Estar organizados dentro da pasta `/playgrounds`.
  - Conter um arquivo `desafio.md` explicando o objetivo.
  - Conter um `index.ts` com a base ou solução do desafio.
- O código deve estar em **TypeScript** e seguir **boas práticas de programação**.
- Use tipagem explícita sempre que possível.

---

## 🗂️ Estrutura Recomendada

Ao criar um novo desafio:

```
playgrounds/
└── XX-nome-do-desafio/
    ├── desafio.md
    └── index.ts
```

Exemplo:
```
playgrounds/
└── 04-generics/
    ├── desafio.md
    └── index.ts
```

### 📘 desafio.md (modelo)

```markdown
# Desafio XX — Nome do Desafio

## 🎯 Objetivo
Descreva claramente o que deve ser feito.

## 📚 Conceitos aplicados
Liste os principais conceitos TypeScript usados.

## ✅ Critérios de Aceitação
Explique o que define que o desafio foi resolvido corretamente.

## 💡 Dica
Inclua alguma orientação útil, se necessário.
```

---

## 🧪 Testes e Validação

Se o desafio envolver lógica crítica, adicione um `test.ts` com exemplos ou testes (usando Jest ou código puro).

---

## 🧼 Padrões de Código

- Utilize `eslint` e `prettier`.
- Prefira nomeclaturas claras e significativas.
- Use boas práticas como **SOLID**, **POO** e **funções puras** quando aplicável.

---

## 🚀 Como enviar uma contribuição

1. Fork este repositório.
2. Crie uma branch com sua feature: `git checkout -b feat/novo-desafio`
3. Commit suas alterações: `git commit -m "feat: adiciona desafio sobre interfaces"`
4. Push para sua branch: `git push origin feat/novo-desafio`
5. Abra um Pull Request!

---

## 💬 Dúvidas ou sugestões?

Abra uma [Issue](https://github.com/seu-usuario/typescript-playground/issues) para discutir novas ideias ou reportar bugs.

Agradecemos sua colaboração. Vamos codar! 🚀
