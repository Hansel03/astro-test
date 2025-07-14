# Helpless Halo - Astro Landing Page

A modern, responsive landing page built with Astro featuring multiple sections including hero, team, pricing, FAQ, and more.

## ✨ Features

- 🎨 Modern, responsive design with SCSS styling
- 🚀 Built with Astro for optimal performance
- 📱 Mobile-first responsive layout
- 🧩 Modular component architecture
- ⚡ Fast loading times with static site generation

## 🏗️ Components

- **Navbar** - Navigation header
- **Hero** - Landing section with call-to-action
- **SideBySide** - Feature comparison section
- **Team** - Team member showcase
- **Steps** - Process or workflow steps
- **Stats** - Key statistics display
- **Pricing** - Pricing plans and options
- **FAQ** - Frequently asked questions
- **Footer** - Site footer with links

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   ├── favicon.svg
│   └── global.scss
├── src/
│   ├── assets/
│   │   ├── astro.svg
│   │   └── background.svg
│   ├── components/
│   │   ├── FAQ/
│   │   │   ├── FAQ.astro
│   │   │   └── FAQ.scss
│   │   ├── Footer/
│   │   │   ├── Footer.astro
│   │   │   └── Footer.scss
│   │   ├── Hero/
│   │   │   ├── Hero.astro
│   │   │   └── Hero.scss
│   │   ├── Navbar/
│   │   │   ├── Navbar.astro
│   │   │   └── Navbar.scss
│   │   ├── Pricing/
│   │   │   ├── Pricing.astro
│   │   │   └── Pricing.scss
│   │   ├── SideBySide/
│   │   │   ├── SideBySide.astro
│   │   │   └── SideBySide.scss
│   │   ├── Stats/
│   │   │   ├── Stats.astro
│   │   │   └── Stats.scss
│   │   ├── Steps/
│   │   │   ├── Steps.astro
│   │   │   └── Steps.scss
│   │   └── Team/
│   │       ├── Team.astro
│   │       └── Team.scss
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
├── tsconfig.json
└── README.md
```

Each component is organized in its own folder with both the Astro component file and its corresponding SCSS styles for better maintainability.

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

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

## 🛠️ Technologies Used

- **Astro** - Static site generator
- **SCSS** - Enhanced CSS with variables, nesting, and mixins
- **TypeScript** - Type-safe JavaScript

## 📦 Dependencies

- `astro`: ^5.11.0 - The main framework
- `sass-embedded`: ^1.89.2 - SCSS compilation support

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
