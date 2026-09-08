# 🛒 Diversos da Derguiana - Loja Online Premium (Protótipo)

![Status do Projeto](https://img.shields.io/badge/Status-Protótipo%20Funcional-green)
![Licença](https://img.shields.io/badge/Licença-Proprietária-red)

> **"Qualidade que a sua família merece, de África para a sua casa."**
> Protótipo de loja virtual (Frontend) premium, 100% responsivo, inspirado nas cores institucionais da marca, com foco em conversão via WhatsApp e excelência em UX/UI.

---

## 📑 Índice
- [📖 Sobre o Projeto](#-sobre-o-projeto)
- [✨ Funcionalidades](#-funcionalidades)
- [🛠️ Stack Tecnológica](#️-stack-tecnológica)
- [🚀 Como Executar](#-como-executar)
- [🎨 Identidade Visual](#-identidade-visual)
- [📱 Otimização Mobile](#-otimização-mobile)
- [🔒 Segurança & SEO](#-segurança--seo)
- [📷 Demonstração](#-demonstração)
- [🤝 Licença & Contato](#-licença--contato)

---

## 📖 Sobre o Projeto
Este projeto consiste em um protótipo visual e funcional de uma loja virtual (Single Page Application) desenvolvido para a marca **Diversos da Derguiana**. O objetivo é apresentar aos decisores uma simulação realista da plataforma, destacando a facilidade de compra para o cliente final e a alta conversão através da integração direta com o WhatsApp.

---

## ✨ Funcionalidades
A plataforma simula uma experiência de e-commerce completa:

### 💻 Interface & Experiência do Usuário (UI/UX)
- **Homepage Institucional:** Hero Banner rotativo com CTAs estratégicos.
- **Design Responsivo:** Adaptação perfeita para PC, Tablets e Telemóveis (Mobile First).
- **Modo Claro/Escuro:** Alternância de tema em tempo real (Dark Mode).
- **Multilíngue:** Estrutura preparada para tradução (PT/EN).
- **Acessibilidade:** Botões amplos, alto contraste e foco visível em elementos interativos.

### 🛍️ Catálogo & Compras
- **Catálogo Dinâmico:** Grid de produtos renderizado via JavaScript.
- **Busca Inteligente:** Filtragem instantânea por nome ou categoria.
- **Filtros Avançados:** Filtro por Categoria e Ordenação por Preço (Crescente/Decrescente).
- **Carrinho Lateral (Drawer):** Atualização em tempo real com controle de quantidade (+/-), remoção de itens, cálculo automático de subtotal, frete e descontos.
- **Cupom de Desconto:** Sistema funcional para aplicação de cupons (Ex: `DERGUIANA10`).

### 📲 Integração & Checkout
- **Checkout Seguro:** Formulário modal para coleta de dados do cliente (Nome, Telefone, Localização, Pagamento).
- **Pedido via WhatsApp:** Gera automaticamente uma mensagem formatada e detalhada, abrindo diretamente o WhatsApp para o número **+244 932 730 411**.
- **Botão Flutuante:** Atalho permanente para suporte via WhatsApp.
- **Rastreamento Simulado:** Geração de código de pedido com tela de sucesso (simulando sistema de entregas).

---

## 🛠️ Stack Tecnológica
Este é um protótipo de Frontend puro, sem dependências externas ou necessidade de build:

- **HTML5:** Estrutura semântica e acessível.
- **CSS3:** Flexbox, Grid Layout, Variáveis CSS (Theming) e Media Queries.
- **JavaScript (Vanilla ES6+):** Manipulação de DOM, lógica de carrinho, filtros e integração com APIs externas (WhatsApp).

---

## 🚀 Como Executar
Não requer instalação de dependências (sem npm, node_modules ou bundlers).

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/diversos-da-derguiana.git
