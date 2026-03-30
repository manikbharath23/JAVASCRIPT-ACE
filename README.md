# 💻 JavaScript ACE Editor Project

This project demonstrates a **browser-based code editor** built using **JavaScript** and **Ace Editor**.  
It allows users to write, edit, and view code in the browser with syntax highlighting and themes.

---

## 📌 Project Overview

- A mini code editor similar to VS Code, implemented in the browser.  
- Features:
  - Syntax highlighting  
  - Multiple themes (dark/light)  
  - JavaScript mode  
  - Editable code area  

- Helps understand **frontend development**, **DOM manipulation**, and **library integration**.

---

## 🛠️ Technologies Used

- **HTML** – Page structure  
- **CSS** – Styling and layout  
- **JavaScript** – Functionality and Ace integration  
- **Ace Editor** – Code editor library ([ace.c9.io](https://ace.c9.io/index.html))

---

## 📂 Project Structure


JAVASCRIPT-ACE/
│── index.html # Main HTML file
│── script.js # JavaScript logic for Ace Editor
│── style.css # Styling for editor UI
│── ace.js # Ace Editor library


---

## 🔁 Workflow

1. Open `index.html` in a browser.  
2. Ace Editor initializes via `script.js`.  
3. Write/edit code in the editor container.  
4. Syntax highlighting and theme applied.  
5. Code can be edited dynamically like a mini IDE.  

---

## 📁 File Description

### `index.html`
- Main UI of the editor  
- Creates editor container  
- Loads Ace Editor library  

### `script.js`
- Initializes Ace Editor  
- Sets theme and language mode  

```javascript
var editor = ace.edit("editor");
editor.setTheme("ace/theme/monokai");
editor.session.setMode("ace/mode/javascript");
style.css
Styles the editor container
Makes the editor fullscreen and responsive
ace.js
Core Ace Editor library
Provides editor features: syntax highlighting, themes, cursor control, etc.
🔥 Concepts Implemented
DOM Manipulation – Access and modify HTML elements dynamically
Library Integration – Loaded and configured Ace Editor
Frontend Development – Combined HTML, CSS, and JS to build interactive editor
Editor Configuration – Set themes, language mode, and editor options
⚠️ Challenges Faced
Editor not loading due to wrong script path
Theme or syntax mode not applying correctly
UI responsiveness issues
🎯 Key Learnings
How to integrate third-party JavaScript libraries
Understanding Ace Editor’s configuration and modes
Creating a mini IDE in the browser
Frontend development best practices
👨‍💻 Author

Manik Bharath
GitHub: https://github.com/manikbharath23

⭐ Support

If you like this project, give it a ⭐ on GitHub!


