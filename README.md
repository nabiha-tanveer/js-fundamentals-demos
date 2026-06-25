# JavaScript Fundamentals — 3 Demo Projects

Three small interactive demos built with **vanilla JavaScript** covering core JS concepts.

---

## 📁 Projects

### 1. Counter App (`counter.html`)
An interactive counter with increment, decrement, and reset functionality.

**Concepts demonstrated:**
- **Closures** — `createCounter()` factory function with private `count` variable
- **DOM Manipulation** — dynamically updating display, CSS classes, and history dots
- **Events** — button click listeners and keyboard events (`ArrowUp`, `ArrowDown`, `r`)
- **var hoisting** — `var count` declared inside function scope

---

### 2. To-Do App (`todo.html`)
A full-featured task manager with filtering and statistics.

**Concepts demonstrated:**
- **Hoisting** — `addDefaultTasks()` called before its declaration (function declaration hoisting)
- **Closures (IIFE)** — `taskIdGenerator` uses an Immediately Invoked Function Expression with a private `_id` variable
- **DOM Manipulation** — dynamically creating/removing `<li>` elements
- **Event Delegation** — single listener on `<ul>` handles clicks for all tasks
- **Scope** — `let` vs `var` scoping differences

---

### 3. Quiz App (`quiz.html`)
A 7-question JavaScript knowledge quiz with async loading and a results screen.

**Concepts demonstrated:**
- **Promises** — custom `delay(ms)` function returns a `new Promise`
- **async/await** — `loadQuestion()` and next-button handler use `async/await`
- **Promise chaining** — `.then()` syntax used for initialization
- **DOM Manipulation** — dynamic question/option rendering, conic-gradient score ring
- **Events** — click handlers, disabled state management

---

## 🚀 How to Run

No build tools needed — just open any `.html` file in your browser:

```bash
# Option 1: Double-click the file in your file manager

# Option 2: Use VS Code Live Server extension

# Option 3: Python simple server
python -m http.server 3000
# Then open http://localhost:3000
```

---

## ✅ Acceptance Criteria Coverage

| Criteria | Covered In |
|---|---|
| Understands scope, closures, hoisting | All three demos (especially counter + todo) |
| Can manipulate the DOM and handle events | All three demos |
| Built at least 2 small interactive demos | ✅ 3 demos built |
| Understands how promises work | Quiz app (`delay()` + `async/await`) |

---

## 🛠 Technologies

- HTML5
- CSS3 (Grid, Flexbox, CSS variables, animations)
- Vanilla JavaScript (ES6+)
