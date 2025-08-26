# 🧠 TypeScript Playground

> Um repositório para Praticar TypeScript com desafios progressivos, boas práticas e foco em SOLID, POO e outras boas práticas.

---

## 🚀 Sobre o projeto

Este repositório é um ambiente de **estudos práticos em TypeScript**, estruturado como um playground de desafios organizados por **nível de dificuldade** e **conceito técnico**.

Criei este repositório para praticar **TypeScript** e provavelmente farei para outras linguagens e ferramentas.

---

## 🎯 Objetivo

Criar uma trilha de aprendizado contínua em TypeScript, com foco em:

- ✅ Tipagem estática e segura
- 🧱 Estruturas e sintaxe avançadas
- 🏛️ Programação orientada a objetos (POO)
- 🔧 Princípios SOLID
- 🧪 Testes automatizados (com Jest)
- 📐 Arquitetura limpa e escalável
- 💎 Código limpo e legível (Clean Code)

---

## 🧩 Como funciona

Cada desafio está dentro de uma pasta própria, com o seguinte padrão:

/playgrounds/ <br>
01-nome-do-desafio/ <br>
├── desafio.md ← Explicação do desafio <br>
└── index.ts ← Sua solução aqui <br>


Cada `desafio.md` inclui:

- Descrição clara do problema
- Objetivo técnico
- Critérios de aceitação
- Dicas para ajudar na resolução

---

## 📊 Estrutura de Níveis

Dentro da pasta `playgrounds/`, você encontrará subpastas organizadas por dificuldade:

### 🟢 1. Beginner
- Para quem **está começando agora** no TypeScript.
- Desafios introdutórios focados em:
  - Sintaxe básica (`let`, `const`, tipos primitivos).
  - Funções simples.
  - Estruturas de controle (if, for, while).
- Objetivo: **entender a linguagem e perder o medo de começar**.

---

### 🟡 2. Intermediate
- Para quem já **domina o básico** e quer se aprofundar.
- Desafios intermediários focados em:
  - Tipagem avançada (`interfaces`, `type aliases`, `enums`).
  - Manipulação de arrays e objetos.
  - Módulos e import/export.
  - Introdução a **Programação Orientada a Objetos**.
- Objetivo: **construir projetos pequenos e sólidos**.

---

### 🟠 3. Advanced
- Para quem já tem boa experiência e quer **resolver problemas complexos**.
- Desafios avançados focados em:
  - **Generics** e utilitários avançados.
  - **Mapped Types**, **Utility Types**.
  - Tratamento de erros com precisão.
  - Arquitetura de projetos maiores.
- Objetivo: **aprender a lidar com abstrações e escrever código reutilizável**.

---

### 🔴 4. Expert
- Para quem quer pensar como um **arquiteto de software**.
- Desafios desafiadores focados em:
  - **Design Patterns** aplicados em TypeScript.
  - **SOLID** na prática.
  - Estruturas de dados e algoritmos complexos.
  - Criação de **mini frameworks e libs próprias**.
- Objetivo: **se preparar para cenários de mercado e entrevistas técnicas avançadas**.

---

## 🚀 Como Usar
1. Entre na pasta do nível desejado.
2. Leia o `README.md` do desafio para entender o problema.
3. Resolva o exercício no arquivo `.ts`.
4. Execute com:
   ```bash
   npx ts-node-dev playgrounds/<nivel>/<desafio>/index.ts
5. Compare sua solução com a resolução proposta (quando disponível).

## 📌 Observação
Os níveis não são uma prisão: você pode pular entre eles conforme sua necessidade.
Mas a recomendação é seguir na ordem para garantir um aprendizado contínuo e sólido.

---

## 🧠 Trilha de desafios

| Módulo         | Conteúdo Principal                         | Status   |
|----------------|---------------------------------------------|----------|
| 01 - Fundamentos | Variáveis, tipos, tuplas, enums             | 🔜 Em breve |
| 02 - Funções     | Tipagem de funções, generics                | 🔜 Em breve |
| 03 - POO         | Classes, encapsulamento, métodos            | 🔜 Em breve |
| 04 - SOLID       | Aplicação de princípios SOLID               | 🔜 Em breve |
| 05 - Arquitetura | Clean Code, divisão de camadas, reuso       | 🔜 Em breve |
| 06 - Testes      | Testes com Jest, TDD                        | 🔜 Em breve |

---
## 🤝 Contribuições
Contribuições são bem-vindas! Siga as instruções no arquivo CONTRIBUTING.md.

## 📦 Instalação e uso

```bash
# Clone o repositório
git clone https://github.com/BlueBeagBB/typescript-playground.git
cd typescript-playground

# Instale as dependências (caso tenha)
npm install

# Rode os arquivos individualmente
npx ts-node playgrounds/01-variaveis-e-tipos/index.ts

