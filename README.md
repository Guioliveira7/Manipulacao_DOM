# 🖱️ Manipulação de DOM com JavaScript

Este é um projeto simples que demonstra como manipular eventos de um campo de formulário usando JavaScript puro (Vanilla JS). O objetivo é alterar dinamicamente a cor de fundo de um campo de input com base em interações do usuário.

## 🎯 Funcionalidades

- Muda a cor do campo para **amarelo** ao ganhar foco.
- Valida o conteúdo ao perder o foco (`blur`):
  - **Vermelho** se o texto tiver menos de 3 caracteres.
  - **Verde** se o texto for válido.
- Também é possível validar com uma função externa `validaCampo()`.

## 📁 Estrutura

```plaintext
index.html         # Página com campo de input
script          # Código JavaScript com os eventos e validações
