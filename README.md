# calculator
# 🧮 Maths Solver Calculator

## ✨ Features

### 📐 Algebra
- Basic arithmetic — `+` `−` `×` `÷`
- Exponents (`xʸ`), Square (`x²`), Square Root (`√`)
- Logarithm (`log₁₀`), Constants (`π`, `e`)
- Parentheses for grouped expressions

### 📊 Trigonometry
- **Standard** — `sin`, `cos`, `tan` and inverses (`sin⁻¹`, `cos⁻¹`, `tan⁻¹`)
- **Reciprocal** — `sec`, `csc`, `cot`
- **Hyperbolic** — `sinh`, `cosh`, `tanh` and inverses
- 🔄 **Degree / Radian** mode toggle

### 📈 Calculus
- **Derivative** (`d/dx`) — numerical differentiation at a given point
- **Integral** (`∫`) — trapezoidal approximation with configurable bounds
- **Limit** (`lim`) — numerical approach to a value
- Natural log (`ln`), Exponential (`eˣ`), Cube root (`∛`)
- Absolute value (`|x|`), Factorial (`x!`)

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| `0-9` `.` | Input digits |
| `+` `-` `*` `/` | Operators |
| `(` `)` | Parentheses |
| `^` | Exponent |
| `Enter` or `=` | Calculate result |
| `Backspace` | Delete last character |
| `Escape` | Clear display |

---

## 🚀 Getting Started

### Option 1 — Open directly
Just open `calculator.html` in any modern browser. That's it!

### Option 2 — Serve locally
```bash
# Using npx
npx serve public

# Or Python
python -m http.server 8000 --directory public
```

Then visit `http://localhost:8000/calculator.html`

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Structure & layout |
| **CSS3** | Styling with CSS Grid |
| **Vanilla JS** | Calculator logic & math engine |
| **Math API** | Native browser math functions |

> No frameworks. No dependencies. No build tools. Just one file.

---

## 📁 Project Structure

```
├── public/
│   └── calculator.html    # ← The entire calculator (single file)
└── README.md
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-function`)
3. Commit your changes (`git commit -m 'Add new math function'`)
4. Push to the branch (`git push origin feature/new-function`)
5. Open a Pull Request

---


<p align="center">Made with ❤️ using pure HTML, CSS & JavaScript</p>
