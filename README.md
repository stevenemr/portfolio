<img src="./src/images/logo-white.svg">

I made this portfolio to showcase my projects, work and education and contact information. This website is made with Astro, TailwindCSS and AlpineJS.

## Project Structure

Inside of this project, you'll see the following folders and files:

```text
├── public/
├── src/
│   └── components/
│   └── images/
│   └── layouts/
│   └── pages/
│   └── styles/
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

In the `globals.ts` file, you can export functions and variables that need to be shared over different files.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |