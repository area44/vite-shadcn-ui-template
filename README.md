# Vite + Shadcn UI Workspace

[![GitHub Pages](https://github.com/area44/vite-workspace/actions/workflows/pages.yml/badge.svg)](https://area44.github.io/vite-workspace/)

A modern, minimalist, and extremely fast template featuring **React**, **Vite 8**, **TypeScript 7**, **Tailwind CSS v4**, and **Shadcn UI** (powered by Base UI).

Fully configured with high-performance Rust-based linters and formatters (**Oxlint** & **Oxfmt**) for a developer experience that is fast and reliable.

---

## Features

- ⚡ **Vite 8** - Blazing fast Hot Module Replacement (HMR).
- 🎨 **Tailwind CSS v4** - Fast, CSS-first Tailwind engine.
- 🧩 **Shadcn UI + Base UI** - Unstyled, accessible primitives with beautiful Tailwind styles.
- 📐 **TypeScript 7** - Latest type-safe development environment.
- 🚀 **Oxlint & Oxfmt** - Lint and format your codebase in milliseconds.
- 🌐 **GitHub Pages Workflow** - Pre-configured action for easy deployment.

---

## Getting Started

### Installation

Clone the repository and install the dependencies:

```bash
git clone https://github.com/area44/vite-workspace
cd vite-workspace
pnpm install
```

### Development

Run the development server:

```bash
pnpm dev
```

Open your web browser and navigate to `http://localhost:5173`.

### Build

To build the project for production:

```bash
pnpm build
```

The production-ready assets will be generated in the `dist` directory.

### Linting & Formatting

Check and format code style with Oxlint and Oxfmt:

```bash
# Run both lint and format checks
pnpm check

# Run linting only
pnpm lint

# Run formatting only
pnpm fmt
```

---

## Adding Components

This workspace is fully initialized with the **Shadcn CLI**. You can easily add more accessible and beautifully designed UI components:

```bash
pnpm dlx shadcn@latest add <component_name>
```

For example, to add a Card or Dialog component:

```bash
pnpm dlx shadcn@latest add card
pnpm dlx shadcn@latest add dialog
```

---

## License

This project is licensed under the [MIT License](LICENSE).
