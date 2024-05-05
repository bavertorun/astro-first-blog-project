## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/bavertorun/astro-first-blog-project.git
    ```

2. Navigate into the project directory:

    ```bash
    cd astro-first-blog-project
    ```

3. Install dependencies:

    ```bash
    npm install
    ```


## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── BlogPost.astro
│   ├── layouts/
│   │   ├── BaseLayout.astro
│   │   └── MarkdownPostLayout.astro
│   └── pages/
│       ├── index.astro
│       └── posts/
│           ├── javascript-binary-search-algorithm.md
│           ├── javascript-bubble-sort-algorithm.md
│           └── javascript-linear-search-algorithm.md
└── package.json

```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

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

