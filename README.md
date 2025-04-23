# Strukit UI Theme

**Smart. Fast. Yours.**

Strukit is a flexible, performance-focused UI theme architecture for building beautiful, customizable websites using Astro and Tailwind. Designed for developers and freelancers who want to build faster, smarter, and with less friction.

## 🚀 Features

- ⚡ **Performance First** – Uses Astro islands and lightweight components.
- 🎨 **Fully Customizable** – Switch fonts, palettes, spacing, and themes easily.
- 🧱 **Composable Components** – Atomic structure with provider-based UI wrappers.
- 🌐 **SEO-Ready** – Accessible, clean markup with full meta support.
- 📦 **Framework-Agnostic Wrappers** – Use Material, Flowbite or your own.
- 📁 **Scalable Architecture** – Structured for growth and future SaaS integration.

## 🧩 Components

Strukit is built with flexibility in mind. You can use:
- Native Astro + Tailwind components
- Lightweight Alpine.js islands
- React-based components where interactivity is needed

## 🔮 Project Vision

> In the future, Strukit will power a low-code platform that helps local businesses and startups launch fast, well-designed websites.  
> For now, it’s a dev-first theme to build from confidently and efficiently.

## 📌 Roadmap

- [ ] Base component system with theme switcher
- [ ] Custom Tailwind tokens and theme config
- [ ] Wrappers for multiple UI libraries (Material, Flowbite, etc.)
- [ ] Interactive components via islands
- [ ] Layout templates (landing, ecommerce, portfolio...)
- [ ] CLI or config loader (Strukit config)
- [ ] Starter templates for rapid bootstrapping

## 🛠 Local Setup

```bash
pnpm install
pnpm dev


## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
