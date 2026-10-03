# Next.js 3D Project

A modern **Next.js 16** landing page with rich motion effects, interactive visuals, and 3D-ready integrations.

## Features

- Animated hero with scroll-driven frame sequence playback
- Modern UI built with reusable React components
- Smooth motion and transitions powered by Framer Motion
- 3D/visual ecosystem support via Spline and Cobe dependencies
- Tailwind CSS v4 styling setup

## Tech Stack

- Next.js 16
- React 19 + TypeScript
- Tailwind CSS 4
- Framer Motion
- Lucide React
- Spline Runtime (`@splinetool/react-spline`, `@splinetool/runtime`)

## Getting Started

### 1) Install dependencies

```bash
pnpm install
```

### 2) Run development server

```bash
pnpm dev
```

Open `http://localhost:3000` in your browser.

## Available Scripts

- `pnpm dev` – Start development server
- `pnpm build` – Build for production
- `pnpm start` – Run production build
- `pnpm lint` – Run ESLint

## Project Structure

```text
app/
  components/      # Main page sections (Hero, About, Services, etc.)
  globals.css      # Global styles
  layout.tsx       # App layout
  page.tsx         # Main page composition
components/ui/     # Shared UI primitives
lib/utils.ts       # Utility helpers
public/            # Static assets (including hero frames)
```

## Notes

- The hero animation uses image frames from `public/hero-frames/`.
- Adjust section content in `app/components/*` to customize the landing page quickly.
