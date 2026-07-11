# JS Framework Showcase

![Repo Size](https://img.shields.io/github/repo-size/asmashahzadi764-alt/js-framework-showcase)
![Last Commit](https://img.shields.io/github/last-commit/asmashahzadi764-alt/js-framework-showcase)
![Frameworks](https://img.shields.io/badge/frameworks-13-blueviolet)
![Made with JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Made with TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)

A collection of starter setups for major JavaScript/TypeScript frontend frameworks and build tools, each isolated in its own folder within this repository.

## Contents

| Folder | Framework/Tool | Type | Official Docs |
|---|---|---|---|
| `react-app` | ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black) | Library (Component-based, Virtual DOM) | [react.dev](https://react.dev) |
| `angular-app` | ![Angular](https://img.shields.io/badge/-Angular-DD0031?logo=angular&logoColor=white) | Full Framework (MVC, TypeScript-first) | [angular.dev](https://angular.dev) |
| `vue-app` | ![Vue](https://img.shields.io/badge/-Vue.js-4FC08D?logo=vue.js&logoColor=white) | Progressive Framework | [vuejs.org](https://vuejs.org) |
| `svelte-app` | ![Svelte](https://img.shields.io/badge/-Svelte-FF3E00?logo=svelte&logoColor=white) | Compiler (no virtual DOM) | [svelte.dev](https://svelte.dev) |
| `preact-app` | ![Preact](https://img.shields.io/badge/-Preact-673AB8?logo=preact&logoColor=white) | Lightweight React alternative | [preactjs.com](https://preactjs.com) |
| `solid-app` | ![Solid](https://img.shields.io/badge/-SolidJS-2C4F7C?logo=solid&logoColor=white) | Fine-grained reactive library | [solidjs.com](https://www.solidjs.com) |
| `qwik-app` | ![Qwik](https://img.shields.io/badge/-Qwik-AC7EF4?logo=qwik&logoColor=white) | Resumable framework | [qwik.dev](https://qwik.dev) |
| `astro-app` | ![Astro](https://img.shields.io/badge/-Astro-BC52EE?logo=astro&logoColor=white) | Content-focused, island architecture | [docs.astro.build](https://docs.astro.build) |
| `ember-app` | ![Ember](https://img.shields.io/badge/-Ember.js-E04E39?logo=emberdotjs&logoColor=white) | Full Framework (convention over configuration) | [emberjs.com](https://emberjs.com) |
| `lit-app` | ![Lit](https://img.shields.io/badge/-Lit-324FFF?logo=lit&logoColor=white) | Native Web Components library | [lit.dev](https://lit.dev) |
| `marko-app` | ![Marko](https://img.shields.io/badge/-Marko-3399CC?logo=markdown&logoColor=white) | Server-first UI language | [markojs.com](https://markojs.com) |
| `vanilla-app` | ![JavaScript](https://img.shields.io/badge/-Vanilla_JS-F7DF1E?logo=javascript&logoColor=black) | No framework, plain JS | [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/JavaScript) |
| `vite-app` | ![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=white) | Build tool (not a framework) | [vite.dev](https://vite.dev) |

## Running a project

Each folder is an independent, self-contained project. To run any of them:

```bash
cd <folder-name>
npm install
npm run dev
```

Then open the local server URL shown in the terminal (usually `http://localhost:5173`, or `http://localhost:4200` for Angular).

## Comparison

| Framework | Rendering Approach | Language | Learning Curve | Best Suited For |
|---|---|---|---|---|
| React | Virtual DOM | JS/JSX | Moderate | Large, interactive SPAs; huge ecosystem |
| Angular | Real DOM + Change Detection | TypeScript | Steep | Enterprise-scale applications |
| Vue | Virtual DOM | JS/Template syntax | Easy | Rapid development, small to mid apps |
| Svelte | Compiles to vanilla JS (no runtime VDOM) | JS/Template syntax | Easy | Performance-critical, lightweight apps |
| Preact | Virtual DOM (smaller footprint) | JS/JSX | Moderate | Projects needing React-like API, smaller bundle |
| Solid | Fine-grained reactivity, no VDOM | JSX | Moderate | High-performance reactive UIs |
| Qwik | Resumability (no hydration) | JSX | Moderate | Fast-loading, large content sites |
| Astro | Islands architecture, mostly static | JS/JSX/Multiple | Easy | Content-heavy sites, blogs, marketing pages |
| Ember | Real DOM, convention-based | JS | Steep | Long-term, structured large apps |
| Lit | Native Web Components | JS/TS | Easy | Reusable, framework-agnostic components |
| Marko | Server-first, streaming rendering | Marko syntax | Moderate | High-traffic e-commerce/server-rendered apps |
| Vanilla JS | Direct DOM manipulation | JS | Easy (but verbose at scale) | Small scripts, learning fundamentals |
| Vite | N/A (build tool, not a UI framework) | N/A | Easy | Fast dev server & bundling for any framework above |

## Learning Takeaways

- **React** – JSX syntax, component composition, and how the virtual DOM diffing model drives updates.
- **Angular** – Structured, opinionated architecture with dependency injection, modules, and TypeScript-first development.
- **Vue** – Template-based syntax that stays close to plain HTML, with a gentle learning curve for beginners.
- **Svelte** – Compilation shifts reactivity to build time, eliminating the need for a virtual DOM at runtime.
- **Preact** – Achieving a React-compatible API in a fraction of the bundle size.
- **Solid** – Fine-grained reactivity where only the specific DOM nodes affected by state changes update.
- **Qwik** – The concept of resumability, where apps skip hydration and load JavaScript only on interaction.
- **Astro** – Island architecture, shipping minimal JavaScript by rendering most content as static HTML.
- **Ember** – Convention-over-configuration philosophy and its impact on long-term project maintainability.
- **Lit** – Building framework-agnostic UI using native Web Components and the Shadow DOM.
- **Marko** – Server-first rendering with streaming HTML for fast time-to-first-byte.
- **Vanilla JS** – Working directly with the DOM API without abstraction layers.
- **Vite** – Modern build tooling with instant dev server startup via native ES modules.

## Author

**Asma Shahzadi**