# Astro Portfolio

Welcome to this Astro portfolio project built with Astro and Tailwind CSS. It is designed to showcase a personal page with sections for experience, skills, and social links.

##  What this project includes

- Static website built with `Astro`.
- Styling with `Tailwind CSS` and variable fonts using `@fontsource-variable/onest`.
- Reusable components in `src/components`.
- Main layout in `src/layouts/Layout.astro`.
- Home page in `src/pages/index.astro`.
- Static assets in `public/`.

##  Main project structure

```text
.
├── astro.config.mjs
├── package.json
├── pnpm-lock.yaml
├── public/
│   └── ...
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Badge.astro
│   │   ├── ButtonGo.astro
│   │   ├── Experience.astro
│   │   ├── ExperienceItem.astro
│   │   ├── Header.astro
│   │   ├── SectionConteiner.astro
│   │   ├── SocialPill.astro
│   │   └── icons/
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
└── README.md
```

##  Available commands

Run these commands from the project root:

| Command | Description |
| --- | --- |
| `pnpm install` | Installs project dependencies |
| `pnpm dev` | Starts the local development server |
| `pnpm build` | Builds the production site into `./dist/` |
| `pnpm preview` | Previews the built site locally |
| `pnpm astro -- --help` | Shows help for the Astro CLI |

##  Key dependencies

- `astro` - framework for fast, static websites.
- `tailwindcss` - utility-first CSS framework.
- `@tailwindcss/vite` - Tailwind integration for Vite.
- `@fontsource-variable/onest` - variable font support.

##  How to contribute

1. Clone the repository.
2. Run `pnpm install`.
3. Edit components in `src/components` or the home page in `src/pages/index.astro`.
4. Test your changes with `pnpm dev`.

##  Notes

- Make sure you are using Node.js `>=22.12.0`.
- To change the content or visual identity, edit `src/styles/global.css` and the existing components.
