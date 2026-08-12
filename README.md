# Vite Shadcn UI Template

[![GitHub Pages](https://github.com/area44/vite-shadcn-ui-template/actions/workflows/pages.yml/badge.svg)](https://area44.github.io/vite-shadcn-ui-template/)

A modern, minimalist, and extremely fast template.

---

## Getting Started

### Installation

Clone the repository and install the dependencies:

```bash
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

This template is fully initialized with the **Shadcn CLI**. You can easily add more accessible and beautifully designed UI components:

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
