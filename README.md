# Flowers HTML

Frontend development sandbox for the Flowers platform. Use this repo to build pages, POCs, modules, and widgets as standalone HTML/CSS/JS.

## Purpose

This repo is a **temporary workspace** for front-end developers to iterate quickly without needing the full .NET stack. Once work is reviewed and approved, HTML/CSS/JS will be pulled into [flowers-app](https://github.com/joshuaangulo-flowers/flowers-app).

## Guidelines

- **Vanilla JS only** — no frameworks, no npm, no build tools
- **No dependencies** — CDN links are OK for fonts/icons, but keep it minimal
- **One folder per feature** — e.g., `dashboard/`, `onboarding/`, `planning-tree/`
- **Each feature should be self-contained** — open `index.html` in a browser and it works
- **Match the design system** — see below

## Design System

| Token | Value |
|-------|-------|
| Primary font | `'Cormorant Garamond', serif` |
| Body font | `'Jost', sans-serif` |
| Navy | `#1a2332` |
| Gold | `#c9a96e` |
| Cream | `#faf8f4` |
| White | `#ffffff` |
| Text dark | `#2a2a2a` |
| Text light | `#8a8a8a` |

> These are based on the Rempla prototype. Final design tokens may evolve — check with the team before starting new work.

## Folder Structure

```
flowers-html/
├── README.md
├── shared/              # Shared CSS, fonts, icons
│   └── base.css
├── dashboard/           # Dashboard pages
│   └── index.html
├── onboarding/          # Onboarding flow
│   └── index.html
└── planning-tree/       # Planning tree widget
    └── index.html
```

## Workflow

1. Create a folder for your feature
2. Build it as standalone HTML
3. Push to this repo
4. Team reviews
5. Approved work gets integrated into `flowers-app`

## Related Repos

- [flowers-app](https://github.com/joshuaangulo-flowers/flowers-app) — .NET 10 application (where this HTML ends up)
- [flowers-docs](https://github.com/joshuaangulo-flowers/flowers-docs) — Project documentation & ADRs
