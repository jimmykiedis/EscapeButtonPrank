# 🎯 Botão Fugitivo – Web Prank

<p align="center">
  <a href="https://jimmykiedis.github.io/EscapeButtonPrank/">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-FF4B4B?style=for-the-badge" alt="Live Demo">
  </a>
</p>

Uma clássica pegadinha da internet desenvolvida em **HTML, CSS e JavaScript**.

O projeto consiste em uma página interativa onde o botão "Não" foge do cursor do usuário, tornando praticamente impossível clicar nele 😈.

---

## 📖 Sobre o Projeto

Este projeto foi criado como uma brincadeira interativa inspirada em memes e pegadinhas populares da internet.

A proposta é simples:

* O usuário recebe uma pergunta.
* O botão **"Sim"** redireciona para um link.
* O botão **"Não"** se move aleatoriamente pela tela quando o cursor se aproxima.

O foco do projeto foi praticar:

* Manipulação do DOM
* Eventos de mouse (`onmouseover`)
* Posicionamento dinâmico de elementos
* Geração de posições aleatórias na tela
* Estruturação básica de uma página web

---

## 🛠️ Tecnologias Utilizadas

* 🌐 HTML5
* 🎨 CSS3
* ⚡ JavaScript (Vanilla JS)

---

## ⚙️ Como Funciona

Quando o usuário passa o mouse sobre o botão "Não":

1. O JavaScript altera sua posição para `absolute`
2. Calcula limites da janela (`window.innerWidth` e `window.innerHeight`)
3. Gera coordenadas aleatórias
4. Move o botão para um novo ponto da tela

Trecho principal da lógica:

```javascript
function moveButton() {
    const btn = document.getElementById('noButton');
    btn.style.position = 'absolute';
    const maxWidth = window.innerWidth - btn.offsetWidth;
    const maxHeight = window.innerHeight - btn.offsetHeight;
    const randomX = Math.random() * maxWidth;
    const randomY = Math.random() * maxHeight;
    btn.style.left = `${randomX}px`;
    btn.style.top = `${randomY}px`;
}
```

---

## 🚀 Como Executar

1. Baixe o arquivo `.html`
2. Abra no navegador
3. Tente clicar no botão "Não"
4. Falhe miseravelmente 😌

---

## 🎓 Conceitos Praticados

* Eventos de interação
* Manipulação dinâmica de estilo
* Responsividade básica
* Experiência do usuário (UX humorística)

---

## 📌 Observações

Este projeto tem fins exclusivamente recreativos e educacionais.

Ideal para:

* Praticar JavaScript básico
* Demonstrar manipulação de eventos
* Fazer seus amigos passarem raiva por 30 segundos

---

## 💡 Possíveis Melhorias Futuras

* 🎵 Sons ao tentar clicar
* 📱 Melhor adaptação para mobile
* 🧠 Aumentar velocidade conforme o tempo passa
* 🎨 Animações suaves com `transition`
* 🏆 Contador de tentativas

---
