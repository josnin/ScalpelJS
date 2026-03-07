# 🪓 ScalpelJS

**Surgical DOM updates with Vanilla JavaScript.**

ScalpelJS is a lightweight ecosystem for building modern **Web Component applications** while keeping most of your code in **plain Vanilla JavaScript**.

Instead of introducing heavy abstractions, ScalpelJS adds small utilities that solve the exact pain points of working with the DOM.

No Virtual DOM.  
No template compilers.  
No proprietary syntax.

Just precise, predictable updates to the real DOM.

Keywords: Web Components, Custom Elements, Reactive JavaScript, Vanilla JS Framework, Lightweight Frontend Framework, Virtual DOM Alternative

---

## Quick Start

Create a new ScalpelJS project:

```bash
npx create-scalpeljs@latest 
```

Then start the development server

```bash
cd my-scalpeljs-app
npm install
npm run dev
```

The CLI sets up a ready-to-use development environment with Vite and the ScalpelJS ecosystem.

---

## Manual Installation

If you prefer to integrate ScalpelJS into an existing project:

```bash
npm install scalpeljs@latest
```

---

# What is ScalpelJS?

ScalpelJS is a **curated distribution** built on top of several lightweight libraries that work together seamlessly.

Instead of installing multiple libraries individually, ScalpelJS provides a **single entry point** that integrates them into a cohesive stack for building Web Component applications.

---

# The Ecosystem

ScalpelJS brings together a set of focused tools designed to work naturally with Web Components.

| Package | Purpose |
|------|------|
| [`redgin`](https://www.npmjs.com/package/redgin) | Reactive Web Component engine |
| [`redgin-store`](https://www.npmjs.com/package/redgin-store) | Global state management with persistence |
| [`jong-router`](https://www.npmjs.com/package/jong-router) | Lightweight client-side router |
| [`pao-form`](https://www.npmjs.com/package/pao-form) | Declarative form handling and validation |

These libraries remain independently usable, but ScalpelJS provides a **unified developer experience**.

---

# CLI

To quickly start a new ScalpelJS project:

| Package | Purpose |
|------|------|
| [`create-scalpeljs`](https://www.npmjs.com/package/create-scalpeljs) | Official project scaffolding tool |

Run:

```bash
npx create-scalpeljs@latest
```

---

# Why ScalpelJS?

## Surgical Reactivity

ScalpelJS updates **only the exact DOM nodes that change**.

Instead of diffing Virtual DOM trees, ScalpelJS performs **direct DOM updates** for predictable performance.

---

## Native by Design

ScalpelJS builds directly on browser standards:

- Custom Elements
- ES Modules
- Native DOM APIs

No proprietary runtime layer.

---

## Vanilla JavaScript First

ScalpelJS keeps most of your application code **plain JavaScript**.

Rather than replacing the platform, it introduces small helper functions that solve specific problems:

- reactive state updates
- DOM binding
- component lifecycle handling
- state synchronization

---

## Lightweight and Transparent

Without a Virtual DOM or complex runtime, ScalpelJS applications remain:

- lightweight
- predictable
- easy to debug

---

# Philosophy

ScalpelJS follows a simple principle:

> Fix the limitations of Vanilla JavaScript without replacing it.

Many modern frameworks introduce entirely new programming models, compilers, and rendering engines.

ScalpelJS takes a different approach.

Instead of abstracting the browser away, ScalpelJS **enhances the platform**.

The core philosophy is **surgical updates**:

- update only what changes
- avoid expensive diffing
- keep logic explicit
- remain close to native browser APIs

The goal is simple:

Write applications that feel like **clean Vanilla JavaScript**, but with the precision and ergonomics of a modern framework.

---

# When to Use ScalpelJS

ScalpelJS is ideal for developers who:

- prefer browser-native technologies
- want fine-grained control over the DOM
- dislike heavy framework abstractions
- want predictable performance
- enjoy writing Vanilla JavaScript

---

# Contributing

Contributions are welcome.

If you'd like to improve ScalpelJS:

1. Fork the repository
2. Make your changes
3. Submit a pull request

---

# Support

If you encounter issues or have feature requests, please open an issue:

https://github.com/josnin/scalpeljs/issues
