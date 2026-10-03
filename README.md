# Assignment 3 - JavaScript Form Validation

A responsive user registration form with comprehensive client-side form validation built using HTML5, CSS3, and Vanilla JavaScript with Regular Expressions.

## 🚀 Live Demo
- **Live URL:** [https://Avdgq2577.github.io/Assignment-3-JsFormValidation/](https://Avdgq2577.github.io/Assignment-3-JsFormValidation/)
- **Repository:** [https://github.com/Avdgq2577/Assignment-3-JsFormValidation](https://github.com/Avdgq2577/Assignment-3-JsFormValidation)

---

## 📌 Features & Validation Rules
- **Full Name Validation:** Mandatory field with a minimum requirement of 3 characters.
- **Email Validation:** Validates standard email address formats using Regex (`/^[^\s@]+@[^\s@]+\.[^\s@]+$/`).
- **Phone Number Validation:** Enforces exactly 10 numeric digits using Regex (`/^[0-9]{10}$/`).
- **Password Security Check:** Minimum requirement of 8 characters.
- **Immediate Inline Feedback:** Displays distinct error text beneath each input when requirements fail.
- **Success State & Reset:** Prevents default page reloads (`preventDefault`), triggers a success confirmation upon full validation, and resets input fields.

---

## 🛠️ Tech Stack
- **HTML5:** Semantic form inputs, labels, and error containers.
- **CSS3:** Styled input boxes, error styling, centered layout, and button transitions.
- **JavaScript (ES6):** Event listener on submit, RegEx matching, conditional error handling, and form control.

---

## 📂 Project Structure
```text
Assignment-3-JsFormValidation/
├── index.html     # Registration form markup, CSS styles, and validation logic
├── .gitignore     # Git ignore rules
└── README.md      # Project documentation
```

---

## 💻 Getting Started Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Avdgq2577/Assignment-3-JsFormValidation.git
   ```

2. **Navigate to the directory:**
   ```bash
   cd Assignment-3-JsFormValidation
   ```

3. **Open the project:**
   Open `index.html` in any web browser.

---

## 🌐 Deployment
Deployed on **GitHub Pages** directly from the `main` branch.
