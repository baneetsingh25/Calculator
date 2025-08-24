# 🧮 Simple Calculator (HTML, CSS, JavaScript)

This is a basic calculator web app built with **HTML**, **CSS**, and **JavaScript**.  
It allows users to perform simple arithmetic operations like addition, subtraction, multiplication, and division.

---

## 🚀 Features
- Interactive button-based calculator
- Supports basic arithmetic (`+`, `-`, `*`, `/`)
- Clear button (`C`) to reset input
- Responsive UI using HTML & CSS
- Real-time updates as you click buttons

---

## 🛠️ Technologies Used
- **HTML** – for structure  
- **CSS** – for styling and layout  
- **JavaScript** – for calculator logic and interactivity  

---

## 📂 Project Structure
calculator/
│── index.html # HTML structure
│── style.css # CSS styling
│── script.js # JavaScript functionality
│── README.md # Project documentation



---

## 💻 How It Works
1. The user clicks on calculator buttons (`0-9`, `+`, `-`, `*`, `/`).
2. JavaScript captures the button clicks using `addEventListener`.
3. Input is displayed inside a text box (`<input>`).
4. When `=` is clicked, the expression is evaluated and the result is shown.
5. Pressing `C` clears the input field.

---

## 📸 Demo Screenshot
<img width="901" height="868" alt="image" src="https://github.com/user-attachments/assets/b86ccade-c806-4b6e-a9c0-242d5a188247" />
 

---

## ▶️ How to Run
1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Start clicking buttons to perform calculations.

---

## ⚠️ Note
Currently, the calculator uses **`eval()`** in JavaScript to evaluate expressions.  
While fine for a demo project, `eval()` can be unsafe for production apps.  
For better security, you can replace it with a **math parser library** or implement custom evaluation logic.

---

## ✨ Future Improvements
- Add support for decimal numbers.
- Implement keyboard input support.
- Improve UI with advanced CSS (dark mode, animations).
- Replace `eval()` with a safe math expression parser.

---

## 📜 License
This project is open-source and free to use.
