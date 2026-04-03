# 🟨 JavaScript & TypeScript Roadmap

> **Goal:** Master JavaScript — the language of the web — from foundational concepts to advanced TypeScript and modern frameworks.

---

## 📌 Overview

| Stage | Topics | Estimated Time |
|---|---|---|
| 🟢 Beginner | JS fundamentals, DOM, browser APIs | 4–6 weeks |
| 🟡 Intermediate | Async JS, ES6+, TypeScript, Node.js, React | 8–12 weeks |
| 🔴 Advanced | Performance, Testing, Architecture, Full-Stack | 8–12 weeks |

> 💡 **Tip:** If you're brand new to programming, complete the HTML/CSS sections of the [Web Development Roadmap](../web-development/README.md) first.

---

## 🟢 Stage 1 — Beginner

**Goal:** Write JavaScript that runs in the browser and interacts with web pages.

### 📦 Core Language Fundamentals
- ✅ Variables: `var`, `let`, `const` — differences and scoping
- ✅ Data types: `string`, `number`, `boolean`, `null`, `undefined`, `object`, `symbol`
- ✅ Operators: arithmetic, comparison (`==` vs `===`), logical, ternary
- ✅ Conditionals: `if/else`, `switch`
- ✅ Loops: `for`, `while`, `do...while`, `for...of`, `for...in`
- ✅ Functions: declarations vs expressions, arrow functions, default parameters
- ✅ Scope and closures
- ✅ Hoisting

### 📋 Data Structures
- ✅ Arrays: `push`, `pop`, `shift`, `unshift`, `splice`, `slice`
- ✅ Array iteration: `forEach`, `map`, `filter`, `reduce`, `find`, `some`, `every`
- ✅ Objects: properties, methods, bracket vs dot notation
- ✅ Destructuring (arrays and objects)
- ✅ Spread (`...`) and rest operators
- ✅ `Map`, `Set`, `WeakMap`, `WeakSet`

### 🌐 DOM Manipulation
- ✅ Selecting elements: `getElementById`, `querySelector`, `querySelectorAll`
- ✅ Modifying content: `textContent`, `innerHTML`, `setAttribute`
- ✅ Modifying styles: `classList.add`, `classList.toggle`, `style`
- ✅ Creating and removing elements: `createElement`, `appendChild`, `removeChild`
- ✅ Event listeners: `addEventListener`, event propagation (bubbling/capturing)
- ✅ Common events: click, submit, keydown, mouseover, DOMContentLoaded

### 🛠️ Beginner Projects:
- 🧮 JavaScript calculator (DOM-based)
- 📋 To-do list with add/delete/complete (Local Storage)
- 🎲 Dice roller or random quote generator
- ⏰ Stopwatch / countdown timer

---

## 🟡 Stage 2 — Intermediate

**Goal:** Write professional-grade JavaScript with modern syntax, async patterns, and TypeScript.

### ⚡ ES6+ Modern JavaScript
- ✅ Template literals
- ✅ Modules: `import` / `export` (ES Modules)
- ✅ Optional chaining (`?.`) and nullish coalescing (`??`)
- ✅ Short-circuit evaluation
- ✅ Symbol and iterators
- ✅ Generator functions
- ✅ Proxy and Reflect

### 🕐 Asynchronous JavaScript
- ✅ JavaScript event loop — call stack, Web APIs, task queue
- ✅ Callbacks and callback hell
- ✅ **Promises** — `.then()`, `.catch()`, `.finally()`, `Promise.all`, `Promise.race`
- ✅ **`async/await`** — clean async syntax
- ✅ Fetch API — making HTTP requests
- ✅ Error handling in async code

### 🟦 TypeScript
- ✅ Why TypeScript? JavaScript with types
- ✅ Type annotations: `string`, `number`, `boolean`, `any`, `unknown`, `never`
- ✅ Interfaces and type aliases
- ✅ Generics: `Array<T>`, custom generic functions
- ✅ Union and intersection types
- ✅ Enums
- ✅ Type narrowing and type guards
- ✅ `tsconfig.json` configuration
- ✅ TypeScript with React (`tsx` files, typed props)

### 🟩 Node.js & Backend JavaScript
- ✅ Node.js runtime: event-driven, non-blocking I/O
- ✅ Core modules: `fs`, `path`, `os`, `http`, `events`
- ✅ npm / yarn / pnpm — package management
- ✅ `package.json` and `node_modules`
- ✅ Building a REST API with **Express.js**
- ✅ Middleware pattern
- ✅ Working with databases from Node (PostgreSQL, MongoDB)

### ⚛️ React (Frontend Framework)
- ✅ Components, JSX, props, and state
- ✅ React hooks: `useState`, `useEffect`, `useContext`, `useRef`, `useMemo`, `useCallback`
- ✅ Event handling in React
- ✅ React Router for client-side navigation
- ✅ Lifting state up and prop drilling
- ✅ Context API and `useReducer` for state management
- ✅ Fetching data and handling loading/error states

### 🛠️ Intermediate Projects:
- 🌤️ Weather app using a public API (OpenWeatherMap)
- 🎬 Movie search app with pagination and filters
- 💬 Real-time chat app with Socket.io
- 🛒 Shopping cart with React and Context API

---

## 🔴 Stage 3 — Advanced

**Goal:** Build and ship production-quality JavaScript/TypeScript applications.

### 🏛️ Advanced JavaScript Concepts
- ✅ Prototype chain and inheritance
- ✅ `this` keyword in-depth (call, apply, bind)
- ✅ Memory management and garbage collection
- ✅ Web Workers and service workers
- ✅ WebSockets for real-time communication
- ✅ Browser storage: Cookies, LocalStorage, SessionStorage, IndexedDB
- ✅ Performance: throttling, debouncing, virtual DOM concepts

### ⚡ Next.js (Full-Stack React)
- ✅ Server-Side Rendering (SSR) vs Static Site Generation (SSG)
- ✅ App Router (Next.js 13+)
- ✅ Server Components and Client Components
- ✅ API routes / Route Handlers
- ✅ Middleware
- ✅ Image optimization and `next/image`
- ✅ Deployment to Vercel

### 🧪 Testing
- ✅ Unit testing with **Jest**
- ✅ Component testing with **React Testing Library**
- ✅ End-to-end testing with **Playwright** or **Cypress**
- ✅ Mocking APIs with `msw` (Mock Service Worker)
- ✅ Test-Driven Development (TDD) principles

### 🏗️ Architecture & Patterns
- ✅ Design patterns: Observer, Factory, Singleton, Module
- ✅ SOLID principles applied to JavaScript
- ✅ State management at scale: Zustand, Jotai, or Redux Toolkit
- ✅ Micro-frontend architecture (concepts)
- ✅ Monorepos with Turborepo or Nx

### 🛠️ Advanced Projects:
- 🌐 Full-stack SaaS app (Next.js + TypeScript + Prisma + Stripe)
- 🤖 AI-powered web app integrating OpenAI API
- 📊 Real-time dashboard with WebSockets and chart libraries
- 🎮 Browser-based game with Canvas API or Phaser.js

---

## ⏱️ Estimated Time

| Stage | Duration |
|---|---|
| Beginner | 4–6 weeks (1–2 hrs/day) |
| Intermediate | 8–12 weeks (2 hrs/day) |
| Advanced | 8–12 weeks (2–3 hrs/day) |
| **Total** | **~6–8 months** |

---

## 📚 Resources

### Free Resources:
- 🔗 [javascript.info](https://javascript.info/) — The modern JavaScript tutorial (best free resource)
- 🔗 [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) — Official Mozilla reference
- 🔗 [TypeScript Official Handbook](https://www.typescriptlang.org/docs/handbook/intro.html) — Free TypeScript docs
- 🔗 [freeCodeCamp JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/) — Structured exercises
- 🔗 [JavaScript30](https://javascript30.com/) — 30 projects in 30 days (Wes Bos, free)
- 🔗 [React Docs (react.dev)](https://react.dev/) — Official React documentation with interactive examples

### Books:
- 📖 *Eloquent JavaScript* — Marijn Haverbeke (free online, covers fundamentals well)
- 📖 *JavaScript: The Good Parts* — Douglas Crockford (essential insights)
- 📖 *You Don't Know JS* (series) — Kyle Simpson (free on GitHub, deep dive)
- 📖 *Programming TypeScript* — Boris Cherny (best TypeScript book)
- 📖 *Node.js Design Patterns* — Mario Casciaro & Luciano Mammino (advanced Node)

### YouTube Channels:
- 🎥 [Fireship](https://www.youtube.com/@Fireship) — Quick, high-quality JS/TS explainers
- 🎥 [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified) — Clear, project-based tutorials
- 🎥 [Theo (t3.gg)](https://www.youtube.com/@t3dotgg) — Modern TypeScript/Next.js ecosystem

### Practice:
- 🏋️ [JavaScript Katas (Codewars)](https://www.codewars.com/) — JS-specific challenges
- 🏋️ [Frontend Mentor](https://www.frontendmentor.io/) — Real-world UI challenges
- 🏋️ [TypeScript Exercises](https://typescript-exercises.github.io/) — Type system practice

---

## 🔮 What's Next?

- 🌐 Build full-stack apps: [Web Development Roadmap](../web-development/README.md)
- ☁️ Deploy and scale: [DevOps Roadmap](../devops/README.md)
- 🏗️ Design scalable systems: [System Design Roadmap](../system-design/README.md)

---

[⬅️ Back to Main README](../../README.md)
