# NumeriX Lab 🧪

> **An interactive educational website for learning Numerical Methods** — from simple analogies to live visualizations, step-by-step animations, and runnable code.

---

## 🌐 Live Preview

Open `numerical.html` in any browser — no installation needed.

```
Just double-click numerical.html → opens in browser ✅
```

Or with VS Code Live Server → `http://127.0.0.1:5500/numerical.html`

---

## 📚 Methods Covered

| #   | Method                        | Category               |
| --- | ----------------------------- | ---------------------- |
| 01  | Bisection Method              | Root Finding           |
| 02  | False Position (Regula Falsi) | Root Finding           |
| 03  | Newton-Raphson                | Root Finding           |
| 04  | Lagrange Interpolation        | Interpolation          |
| 05  | Euler's Method                | Differential Equations |
| 06  | Runge-Kutta (RK4)             | Differential Equations |
| 07  | Trapezoidal Rule              | Numerical Integration  |
| 08  | Simpson's 1/3 Rule            | Numerical Integration  |
| 09  | Gauss-Seidel Method           | Linear Systems         |

---

## ✨ Features

- 💡 **Concept tab** — simple real-world analogies + formal math definitions
- ⚡ **Playground tab** — live interactive inputs, run the algorithm instantly
- 💻 **Code tab** — clean syntax-highlighted JavaScript with comments
- 📊 **Live Charts** — Chart.js graphs (tangent lines, shaded areas, convergence plots)
- 📋 **Iteration Tables** — step-by-step numerical output
- ⏭ **Step-by-step mode** — animate iterations one at a time
- ✅ **Progress tracker** — sidebar marks each method as completed
- 🌗 **Dark / Light mode** — toggle in sidebar
- 📱 **Fully responsive** — works on mobile and desktop

---

## 🛠️ Tech Stack

| Tool                                        | Purpose                             |
| ------------------------------------------- | ----------------------------------- |
| HTML / CSS / JS                             | Core — no framework needed          |
| [Chart.js 4.4.1](https://www.chartjs.org/)  | Interactive graphs                  |
| [Math.js 12.4.0](https://mathjs.org/)       | Parsing user-typed math expressions |
| Google Fonts (Syne + JetBrains Mono + Lora) | Typography                          |

> 100% frontend — no backend, no build step, no npm install required.

---

## 🚀 Getting Started

### Option 1 — Just open it

```
Double-click numerical.html
```

### Option 2 — VS Code + Live Server

1. Open the folder in VS Code
2. Install the **Live Server** extension (by Ritwick Dey)
3. Click **"Go Live"** in the bottom-right corner
4. Opens at `http://127.0.0.1:5500/numerical.html`

---

## 📁 Project Structure

```
project_numerical/
│
├── numerical.html     ← entire website (single file)
└── README.md          ← you are here
```

Everything is in one self-contained HTML file — styles, scripts, and content all included.

---

## 🎓 How to Use

1. **Pick a method** from the left sidebar
2. Read the **Concept tab** — understand the idea before the math
3. Go to **Playground tab** — enter your own function and values
4. Click **▶ Run All** to see the full solution, or **⏭ Step** to animate it
5. Check the **iteration table** to see how the answer improves each step
6. Read the **Code tab** to see the clean implementation

---

## 📸 Preview

```
┌─────────────────────────────────────────────────┐
│  NumeriX Lab                                    │
│  ─────────────────────────────────────────────  │
│  01 Bisection    │  💡 Concept  ⚡ Playground  │
│  02 False Pos    │                              │
│  03 Newton-R     │  f(x) = x³ - x - 2          │
│  04 Lagrange     │  a = 1    b = 2              │
│  05 Euler        │                              │
│  06 RK4          │  [▶ Run]  [⏭ Step]  [↺]    │
│  07 Trapezoid    │                              │
│  08 Simpson's    │  📊 Live Graph               │
│  09 Gauss-Seidel │  📋 Iteration Table          │
└─────────────────────────────────────────────────┘
```

---

## 🧩 Extending the Project

Want to add a new method? Each method follows this pattern:

```html
<!-- 1. Add nav item in sidebar -->
<a href="#mymethod" class="sb-item" data-sec="mymethod">
  <span class="num">10</span> My Method
</a>

<!-- 2. Add section in main content -->
<section class="method-section" id="mymethod" data-num="10">
  <!-- Concept, Playground, Code tabs -->
</section>
```

```javascript
// 3. Add the algorithm in the <script> tag
function runMyMethod() {
  // your implementation
  markDone("mymethod"); // marks ✓ in sidebar
}
```

---

## 📄 License

Free to use for educational purposes.

---

_Built with ❤️ for students learning Numerical Analysis_
