# JSgood

**The Surgical Web Component Framework.**  
JSgood is a high-performance, lightweight ecosystem designed for developers who want the power of a modern framework with the simplicity of standard Web Components. 

No Virtual DOM. No heavy abstractions. Just **Good JS**.

---

## The Ecosystem

JSgood is a complete, modular stack designed to work together seamlessly:

*   **CLI [create-jsgood](https://www.npmjs.com/package/create-jsgood)**: The official project generator. One command to rule them all.
*   **Core [redgin](https://www.npmjs.com/package/redgin)**: The reactive Web Component engine.
*   **Store [redgin-store](https://www.npmjs.com/package/redgin-store)**: Global state management with LocalStorage persistence and surgical logging.
*   **Router [jong-router](https://www.npmjs.com/package/jong-router)**: Light-speed, client-side navigation.
*   **Form [pao-form](https://www.npmjs.com/package/pao-form)**: Effortless validation and form handling.

---

## Getting Started

You don't need to install libraries one by one. The **JSgood CLI** scaffolds your project, configures Vite, and installs the entire ecosystem (Store, Router, Forms) automatically.

### 1. Scaffold your project
Run the following command in your terminal:

```bash
npx create-jsgood@latest
```

# Why JSgood?
* Surgical Reactivity: Directly updates the specific DOM nodes that changed. No expensive "diffing" or Virtual DOM overhead.
* Native Standards: Built on Custom Elements and ES Modules. Your code is future-proof and browser-native.
* Memory Safe: Built-in protection against "Zombie Listeners" via the Auto-Unsubscribe pattern in the Store.
* Developer Choice: Use the CLI for professional projects, or go "Zero-Build" using CDNs for rapid prototyping
## Help

Need help? Open an issue in: [ISSUES](https://github.com/josnin/JSgood/issues)


## Contributing
Want to improve and add feature? Fork the repo, add your changes and send a pull request.


