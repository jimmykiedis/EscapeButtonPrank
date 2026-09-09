# 🎯 Botão Fugitivo – Web Prank

<p align="center">
  <a href="https://jimmykiedis.github.io/EscapeButtonPrank/">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-FF4B4B?style=for-the-badge" alt="Live Demo">
  </a>
  <br>
  <em>Clique no botão para acessar a demonstração.</em>
</p>

---

## 🎯 Objetivo

Criar uma experiência web simples e divertida, utilizando a interação do usuário para desenvolver uma pegadinha baseada em um botão que tenta escapar quando o usuário se aproxima.

O projeto tem como objetivo praticar conceitos fundamentais de desenvolvimento front-end, especialmente **manipulação do DOM, eventos de mouse, posicionamento dinâmico e geração de valores aleatórios com JavaScript**.

---

## ✨ Funcionalidades

- ❓ Exibição de uma pergunta com opções de resposta.
- ✅ Botão **"Sim"** que redireciona o usuário para um link definido pelo projeto.
- 🏃 Botão **"Não"** que foge quando o cursor se aproxima.
- 🎲 Geração de posições aleatórias para o botão.
- 📐 Posicionamento dinâmico considerando as dimensões da janela do navegador.
- 😈 Interação humorística baseada na dificuldade de clicar no botão **"Não"**.
- 🌐 Demonstração disponível através do GitHub Pages.

---

## 🛠 Como utilizar o repositório

### 📥 1. Clone o repositório

```bash
git clone https://github.com/jimmykiedis/EscapeButtonPrank.git
cd EscapeButtonPrank
```

### 🔗 2. Configure o link do botão "Sim"

Abra o arquivo HTML principal do projeto e procure, no início do código, pelo bloco de configuração:

```html
<script>
    // ==========================================================
    // CONFIGURAÇÃO: troque o link abaixo pelo endereço desejado
    // Se você clonou este repositório, edite apenas esta linha:
    // ==========================================================
    const LINK_SIM = "https://www.youtube.com/watch?v=hPGu1a3PGTg";
    // ==========================================================
```

Altere apenas o valor da constante `LINK_SIM` para o endereço que deseja abrir ao clicar no botão **"Sim"**.

Por exemplo:

```javascript
const LINK_SIM = "https://seu-link-aqui.com";
```

### ▶️ 3. Execute o projeto

Após configurar o link, abra o arquivo HTML principal diretamente no navegador.

O projeto não requer instalação de dependências ou configuração de servidor para funcionar localmente.

### ✏️ 4. Personalize o projeto

Você pode modificar os arquivos HTML, CSS e JavaScript para personalizar:

- Pergunta exibida na página.
- Textos dos botões.
- Link associado ao botão **"Sim"**.
- Aparência e posicionamento dos elementos.
- Comportamento do botão **"Não"**.
- Animações e efeitos visuais.

> **Dica:** para uma personalização rápida, a constante `LINK_SIM` é a principal configuração que precisa ser alterada.

---

## 🏗️ Estratégia de implementação

A aplicação utiliza uma estrutura simples baseada em **HTML, CSS e JavaScript**, separando a estrutura visual da lógica de interação.

### Interface (HTML/CSS)

Responsável pela estrutura e apresentação da página, incluindo:

- Pergunta apresentada ao usuário.
- Botões de resposta.
- Layout da página.
- Estilização dos elementos.
- Posicionamento visual dos componentes.

### Lógica e interação (JavaScript)

O JavaScript controla o comportamento do botão **"Não"** através de eventos de interação.

Quando o cursor passa sobre o botão:

1. O botão recebe posicionamento `absolute`.
2. As dimensões disponíveis da janela são calculadas.
3. São geradas coordenadas aleatórias.
4. O botão é reposicionado para uma nova posição dentro da área visível.

Essa abordagem utiliza a manipulação direta de propriedades CSS através do **DOM**, sem necessidade de bibliotecas ou frameworks externos.

---

## 🛠️ Tecnologias

- **HTML5** — Estrutura da página e dos elementos da interface.
- **CSS3** — Estilização e posicionamento dos elementos.
- **JavaScript (Vanilla JS)** — Lógica da aplicação, eventos e movimentação do botão.
- **DOM API** — Manipulação dos elementos HTML em tempo de execução.
- **GitHub Pages** — Hospedagem da demonstração do projeto.

---

## 📁 Estrutura sugerida

```text
EscapeButtonPrank/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

A estrutura pode ser expandida conforme novas funcionalidades sejam adicionadas ao projeto.

---

## 📄 Licença

Sinta-se à vontade para usar, editar e compartilhar! Espalhe amor por onde for. 🫡
