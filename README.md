# Nuxt Template

This is a **Nuxt 3** starter template pre-configured with **Tailwind CSS**, **Pinia**, and **TypeScript** to speed up
development.

## 🚀 Features

- **[Nuxt 3](https://nuxt.com/)** – Modern Vue framework for seamless SSR, SSG, and API routes.
- **[Tailwind CSS](https://tailwindcss.com/)** – Utility-first CSS framework for rapid UI development.
- **[Pinia](https://pinia.vuejs.org/)** – Lightweight and intuitive state management for Vue applications.
- **[TypeScript](https://www.typescriptlang.org/)** – Statically typed JavaScript for better code quality.
- **[Eslint Nuxt](https://eslint.nuxt.com/packages/module)** – Code linting for better code quality.

## 📦 Installation

Clone the repository and install dependencies:

```sh
git clone https://github.com/AndreasMarkopoulos/andram-nuxt-template.git
cd andram-nuxt-template
pnpm install # or npm install / yarn install
```

## 🛠️ Usage

Start the development server:

```sh
pnpm dev # or npm run dev / yarn dev
```

Build for production:

```sh
pnpm build # or npm run build / yarn build
```

Preview the built app:

```sh
pnpm preview # or npm run preview / yarn preview
```

## 📂 Project Structure

```
/YOUR_PROJECT
│── .nuxt/           # Nuxt build directory (generated)
│── node_modules/    # Installed dependencies
│── public/          # Static assets
│── assets/          # Unprocessed static files (e.g., styles, images)
│── components/      # Vue components
│── composables/     # Reusable functions (auto-imported)
│── layouts/         # Page layouts
│── pages/           # Nuxt page routes
│── plugins/         # Vue/Nuxt plugins
│── store/           # Pinia stores
│── types/           # TypeScript definitions
│── nuxt.config.ts   # Nuxt configuration
│── tailwind.config.ts # Tailwind CSS configuration
│── tsconfig.json    # TypeScript configuration
│── package.json     # Project dependencies and scripts
```

## ⚙️ Configuration

### Pinia

Store files are located in the `store/` directory. Create and use stores like this:

```ts
// store/example.ts
import {defineStore} from 'pinia'

export const useExampleStore = defineStore('example', {
    state: () => ({
        count: 0
    }),
    actions: {
        increment() {
            this.count++
        }
    }
})
```

### TypeScript

TypeScript is enabled by default. Type definitions should be placed in the `types/` directory.

### Eslint

Eslint is installed with the default configurations and rules

## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](./LICENSE) for details.

---

💡 _Happy coding!_ 🚀

