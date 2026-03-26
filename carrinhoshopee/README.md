# 🛒 Shopee Cart — Sistema de Carrinho no Terminal

> Desafio de Projeto — Bootcamp Node.js | DIO (Digital Innovation One)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Terminal](https://img.shields.io/badge/Interface-Terminal-black?style=flat)
![Status](https://img.shields.io/badge/Status-Completo-orange?style=flat)

---

## 📌 Sobre o Projeto

Sistema de carrinho de compras inspirado na **Shopee**, 100% executado no terminal via Node.js. Desenvolvido como desafio prático do bootcamp de Back-End da DIO, com foco na lógica de negócio, manipulação de arrays e interação com o usuário via CLI.

---

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 📦 Catálogo de produtos | 10 produtos organizados por categoria |
| ➕ Adicionar ao carrinho | Com validação de estoque |
| ✏️ Alterar quantidade | Edição individual por item |
| ❌ Remover produto | Com confirmação antes de excluir |
| 🎫 Cupons de desconto | 3 cupons (10%, 20%, frete grátis) |
| 🚚 Frete automático | Grátis para pedidos acima de R$ 200 |
| 💳 Finalizar compra | Resumo completo + número de pedido gerado |

---

## 🚀 Como Executar

### Pré-requisitos
- [Node.js](https://nodejs.org/) v14 ou superior

### Instalação e execução

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/shopee-cart-terminal.git

# Acesse a pasta
cd shopee-cart-terminal

# Execute o sistema
node index.js
```

Ou com o script npm:

```bash
npm start
```

> Nenhuma dependência externa é necessária — apenas Node.js puro! ✅

---

## 🗂️ Estrutura do Projeto

```
shopee-cart-terminal/
├── index.js       # Toda a lógica do sistema
├── package.json   # Metadados do projeto
└── README.md      # Documentação
```

---

## 🧠 Conceitos Aplicados

- **`readline`** (módulo nativo do Node.js) para input interativo no terminal
- **Promises / async-await** para fluxo assíncrono
- **Manipulação de arrays** (`push`, `splice`, `find`, `filter`, `reduce`)
- **Lógica de negócio**: cálculo de subtotal, desconto por cupom, frete condicional
- **Validações**: estoque, quantidade, itens duplicados no carrinho
- **Organização modular** com funções separadas por tela/responsabilidade
- **ANSI Escape Codes** para colorir e formatar o terminal

---

## 🎫 Cupons de Teste

| Código | Benefício |
|---|---|
| `SHOPEE10` | 10% de desconto no subtotal |
| `DESCONTO20` | 20% de desconto no subtotal |
| `FRETE` | Frete grátis |

---

## 📸 Preview

```
  ╔═══════════════════════════════════════════════════╗
  ║       🛒  SHOPEE CART  —  Sistema de Compras       ║
  ╚═══════════════════════════════════════════════════╝

  Carrinho: 3  R$ 349,70

  O que você quer fazer?

  [1]  🔍 Ver produtos disponíveis
  [2]  🛒 Ver carrinho
  [3]  ➕ Adicionar produto
  [4]  ✏️  Alterar quantidade
  [5]  ❌ Remover produto
  [6]  🎫 Aplicar cupom
  [7]  💳 Finalizar compra
  [0]  🚪 Sair
```

---

## 📚 Referências

- [Documentação Node.js — readline](https://nodejs.org/api/readline.html)
- [Desafio original — DIO](https://www.dio.me/)

---

## 👤 Autor

Feito com 🧡 por **Geo** — [LinkedIn](https://linkedin.com/in/seu-perfil) · [GitHub](https://github.com/seu-usuario)
