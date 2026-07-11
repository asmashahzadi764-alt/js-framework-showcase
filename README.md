<div align="center">

# 🧩 JS Framework Showcase

### *A structured collection of frontend framework and build-tool setups, comparing how different JavaScript ecosystems approach component architecture, rendering, and state management.*

<p>

<a href="https://github.com/asmashahzadi764-alt/js-framework-showcase">
<img src="https://img.shields.io/badge/📂_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/>
</a>

</p>

</div>

---

## 📖 About This Repository

Most tutorials teach one framework in isolation, which makes it hard to see how they actually differ. This repository takes the opposite approach — the **same kind of small app, rebuilt across 13 different frontend frameworks and build tools**, so the differences in syntax, rendering strategy, and mental model are easy to compare side by side.

Each folder is a standalone, runnable project.

---

## 📑 Table of Contents

- [Tech Stack](#-tech-stack)
- [Folder Structure](#-folder-structure)
- [Getting Started](#-getting-started)
- [How They Compare](#-how-they-compare)
- [Key Concepts by Framework](#-key-concepts-by-framework)
- [Author](#-author)

---

## 💻 Tech Stack

<p align="center">

![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/-Angular-DD0031?logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?logo=vue.js&logoColor=white)
![Svelte](https://img.shields.io/badge/-Svelte-FF3E00?logo=svelte&logoColor=white)
![Preact](https://img.shields.io/badge/-Preact-673AB8?logo=preact&logoColor=white)
![SolidJS](https://img.shields.io/badge/-SolidJS-2C4F7C?logo=solid&logoColor=white)
![Qwik](https://img.shields.io/badge/-Qwik-AC7EF4?logo=qwik&logoColor=white)
![Astro](https://img.shields.io/badge/-Astro-BC52EE?logo=astro&logoColor=white)
![Ember.js](https://img.shields.io/badge/-Ember.js-E04E39?logo=emberdotjs&logoColor=white)
![Lit](https://img.shields.io/badge/-Lit-324FFF?logo=lit&logoColor=white)
![Marko](https://img.shields.io/badge/-Marko-3399CC?logo=markdown&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
![npm](https://img.shields.io/badge/-npm-CB3837?logo=npm&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white)

</p>

---

## 📁 Folder Structure

<table>
<tr><th>Folder</th><th>Framework</th><th>Category</th><th>Docs</th></tr>

<tr><td><code>react-app</code></td><td>React</td><td>Component library, Virtual DOM</td><td><a href="https://react.dev">react.dev</a></td></tr>
<tr><td><code>angular-app</code></td><td>Angular</td><td>Full framework, TypeScript-first</td><td><a href="https://angular.dev">angular.dev</a></td></tr>
<tr><td><code>vue-app</code></td><td>Vue.js</td><td>Progressive framework</td><td><a href="https://vuejs.org">vuejs.org</a></td></tr>
<tr><td><code>svelte-app</code></td><td>Svelte</td><td>Compiler, no virtual DOM</td><td><a href="https://svelte.dev">svelte.dev</a></td></tr>
<tr><td><code>preact-app</code></td><td>Preact</td><td>Lightweight React alternative</td><td><a href="https://preactjs.com">preactjs.com</a></td></tr>
<tr><td><code>solid-app</code></td><td>Solid.js</td><td>Fine-grained reactivity</td><td><a href="https://www.solidjs.com">solidjs.com</a></td></tr>
<tr><td><code>qwik-app</code></td><td>Qwik</td><td>Resumable framework</td><td><a href="https://qwik.dev">qwik.dev</a></td></tr>
<tr><td><code>astro-app</code></td><td>Astro</td><td>Island architecture</td><td><a href="https://docs.astro.build">docs.astro.build</a></td></tr>
<tr><td><code>ember-app</code></td><td>Ember.js</td><td>Convention-based framework</td><td><a href="https://emberjs.com">emberjs.com</a></td></tr>
<tr><td><code>lit-app</code></td><td>Lit</td><td>Native Web Components</td><td><a href="https://lit.dev">lit.dev</a></td></tr>
<tr><td><code>marko-app</code></td><td>Marko</td><td>Server-first UI language</td><td><a href="https://markojs.com">markojs.com</a></td></tr>
<tr><td><code>vanilla-app</code></td><td>Vanilla JS</td><td>No framework, plain JS</td><td><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">MDN</a></td></tr>
<tr><td><code>vite-app</code></td><td>Vite</td><td>Build tool, not a UI framework</td><td><a href="https://vite.dev">vite.dev</a></td></tr>

</table>

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org) (LTS version recommended)
- npm (comes bundled with Node.js)

### Clone the Repository

```bash
git clone https://github.com/asmashahzadi764-alt/js-framework-showcase.git
cd js-framework-showcase
```

Each folder listed above is a standalone project. To run any of them, `cd` into it and start the dev server:

```bash
cd react-app        # or angular-app, vue-app, svelte-app, etc.
npm install
npm run dev
```

The terminal will print your local server URL — usually `localhost:5173`, or `localhost:4200` for Angular.

---

## ⚖️ How They Compare

| | Rendering | Language | Learning Curve | Best Suited For |
|---|---|---|---|---|
| **React** | Virtual DOM | JS / JSX | Moderate | Large interactive SPAs |
| **Angular** | Real DOM + change detection | TypeScript | Steep | Enterprise-scale apps |
| **Vue** | Virtual DOM | Templates | Easy | Rapid development |
| **Svelte** | Compiled, no runtime VDOM | Templates | Easy | Lightweight, fast apps |
| **Preact** | Virtual DOM (smaller footprint) | JS / JSX | Moderate | React-like API, smaller bundle |
| **Solid** | Fine-grained reactivity | JSX | Moderate | High-performance UIs |
| **Qwik** | Resumable, no hydration | JSX | Moderate | Fast-loading, content-heavy sites |
| **Astro** | Islands, mostly static | JS / JSX / Multiple | Easy | Blogs, marketing pages |
| **Ember** | Real DOM, convention-based | JS | Steep | Long-term structured apps |
| **Lit** | Native Web Components | JS / TS | Easy | Reusable, framework-agnostic UI |
| **Marko** | Server-first, streaming | Marko syntax | Moderate | High-traffic, server-rendered apps |
| **Vanilla JS** | Direct DOM manipulation | JS | Easy | Fundamentals, small scripts |
| **Vite** | — build tool — | — | Easy | Dev server & bundling for any of the above |

---

## 🧠 Key Concepts by Framework

- **React** — component composition, virtual DOM diffing
- **Angular** — dependency injection, modules, TypeScript-first structure
- **Vue** — template syntax close to plain HTML
- **Svelte** — reactivity handled at compile time, no runtime virtual DOM
- **Preact** — React-compatible API in a smaller bundle
- **Solid** — fine-grained reactivity, updating only what changes
- **Qwik** — resumability, skipping hydration entirely
- **Astro** — island architecture, minimal shipped JavaScript
- **Ember** — convention-over-configuration
- **Lit** — framework-agnostic UI via native Web Components and Shadow DOM
- **Marko** — server-first rendering with streaming HTML
- **Vanilla JS** — direct DOM manipulation, no abstraction layer
- **Vite** — instant dev server startup via native ES modules

---

<div align="center">

## 👩‍💻 Author

**Asma Shahzadi**

<p>

<a href="https://linkedin.com/in/asma-shahzadi-313291376">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/asmashahzadi764-alt">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>

</div>