## Next.js + Tailwind CSS + TypeScript + Shadcn/UI Starter and Boilerplate

Minimal starter to kick off a modern web app with Next.js 15 (App Router), React 19, TypeScript, Tailwind v4, and Shadcn/UI. Includes path aliasing, Biome linting/formatting, and a Cursor-friendly setup.

### Features

- **⚡️ Next.js 15 (App Router)**: Modern structure using `src/app`
- **⚛️ React 19**: Latest React features
- **⛑ TypeScript**: Strict mode enabled
- **💨 Tailwind CSS v4**: Latest utility-first CSS
- **📦 Shadcn/UI**: Ready to add UI components
- **📈 Path Alias `@/*`**: Absolute imports via `tsconfig.json`
- **🧹 Biome (Lint & Format)**: One tool for linting and formatting (`pnpm lint`, `pnpm format`)
- **🆕 Cursor Rules**: Rules for a better AI pairing experience

### Prerequisites

- Node.js 18+ (LTS recommended)
- pnpm 9+

## Getting Started

### 1) Create a project from this template

Using `create-next-app` with pnpm:

```bash
pnpm create next-app -e https://github.com/asyarbre/next-ts-cursor-starter next-ts-cursor-starter
```

Or clone directly:

```bash
git clone https://github.com/asyarbre/next-ts-cursor-starter.git
cd next-ts-cursor-starter
```

### 2) Install dependencies

Using pnpm is recommended.

```bash
pnpm install
```

### 3) Run the development server

```bash
pnpm dev
```

Open `http://localhost:3000` to view the app.

