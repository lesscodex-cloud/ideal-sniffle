# SaaS Landing Page Kit

## Product overview
A ready-to-launch SaaS landing page built with Astro and Tailwind CSS, designed for fast iteration, strong performance, and easy customization for marketing teams and developers.

### Features
- Responsive, accessible layout optimized for conversions.
- Modular sections (hero, features, pricing, FAQ, CTA) for quick edits.
- Tailwind-based theming for rapid visual customization.
- Astro-powered static output for fast load times and SEO.

## Local development
### Prerequisites
- Node.js 18+ (LTS recommended)
- npm (or pnpm/yarn)

### Setup
```bash
npm install
```

### Run locally
```bash
npm run dev
```

## Project structure
```
/
├─ src/
│  ├─ components/   # Core UI components and section blocks
│  ├─ layouts/      # Page shells and shared layout wrappers
│  ├─ pages/        # Route-based pages (index, etc.)
│  └─ styles/       # Global styles and Tailwind entry points
├─ public/          # Static assets
└─ astro.config.mjs # Astro configuration
```

## Build and deploy
### Build
```bash
npm run build
```

### Preview locally
```bash
npm run preview
```

### Environment variables
This project does not require environment variables by default. If you add integrations
(analytics, forms, or CMS), define variables in a `.env` file and reference them in
Astro with `import.meta.env`.
