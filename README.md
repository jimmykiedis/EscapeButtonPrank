# 🎯 Escape Button – Web Prank

<p align="center">
  <a href="https://jimmykiedis.github.io/EscapeButtonPrank/">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-FF4B4B?style=for-the-badge" alt="Live Demo">
  </a>
  <br>
  <em>Click the button to access the live demo.</em>
</p>

---

## 🎯 Objective

Create a simple and fun web experience that uses user interaction to build a prank based on a button that tries to escape whenever the user approaches it.

The project aims to practice fundamental front-end development concepts, especially **DOM manipulation, mouse events, dynamic positioning, and random value generation with JavaScript**.

---

## ✨ Features

- ❓ Display of a question with answer options.
- ✅ **"Yes"** button that redirects the user to a link defined in the project.
- 🏃 **"No"** button that runs away when the cursor approaches it.
- 🎲 Random position generation for the button.
- 📐 Dynamic positioning based on the browser window dimensions.
- 😈 Humorous interaction based on the difficulty of clicking the **"No"** button.
- 🌐 Live demonstration available through GitHub Pages.

---

## 🛠 How to Use the Repository

### 📥 1. Clone the Repository

```bash
git clone https://github.com/jimmykiedis/EscapeButtonPrank.git
cd EscapeButtonPrank
```

### 🔗 2. Configure the "Yes" Button Link

Open the project's main HTML file and look for the configuration block near the beginning of the code:

```html
<script>
    // ==========================================================
    // CONFIGURATION: replace the link below with the desired URL
    // If you cloned this repository, edit only this line:
    // ==========================================================
    const LINK_SIM = "https://www.youtube.com/watch?v=hPGu1a3PGTg";
    // ==========================================================
```

Change only the value of the `LINK_SIM` constant to the URL you want to open when the user clicks the **"Yes"** button.

For example:

```javascript
const LINK_SIM = "https://your-link-here.com";
```

### ▶️ 3. Run the Project

After configuring the link, open the project's main HTML file directly in your browser.

The project does not require any dependencies or server configuration to run locally.

### ✏️ 4. Customize the Project

You can modify the HTML, CSS, and JavaScript files to customize:

- The question displayed on the page.
- Button labels.
- The URL associated with the **"Yes"** button.
- The appearance and positioning of the elements.
- The behavior of the **"No"** button.
- Animations and visual effects.

> **Tip:** For quick customization, the `LINK_SIM` constant is the main configuration that needs to be changed.

---

## 🏗️ Implementation Strategy

The application uses a simple structure based on **HTML, CSS, and JavaScript**, separating the visual structure from the interaction logic.

### Interface (HTML/CSS)

Responsible for the structure and presentation of the page, including:

- The question displayed to the user.
- Answer buttons.
- Page layout.
- Element styling.
- Visual positioning of the components.

### Logic and Interaction (JavaScript)

JavaScript controls the behavior of the **"No"** button through interaction events.

When the cursor moves over the button:

1. The button receives `absolute` positioning.
2. The available browser window dimensions are calculated.
3. Random coordinates are generated.
4. The button is repositioned to a new location within the visible area.

This approach uses direct manipulation of CSS properties through the **DOM**, without requiring external libraries or frameworks.

---

## 🛠️ Technologies

- **HTML5** — Page structure and interface elements.
- **CSS3** — Element styling and positioning.
- **JavaScript (Vanilla JS)** — Application logic, events, and button movement.
- **DOM API** — Runtime manipulation of HTML elements.
- **GitHub Pages** — Hosting for the project's live demonstration.

---

## 📁 Suggested Structure

```text
EscapeButtonPrank/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

The structure can be expanded as new features are added to the project.

---

## 📄 License

Feel free to use, edit, and share! Spread love wherever you go. 🫡
