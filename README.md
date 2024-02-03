# Astro studies: i18n on 4.30

## Features

* [ ] Change `html` lang argument
* [ ] Configure `ltr` and `rtl`
* [ ] Explain Astro internal variables
* [ ] Work with different scripts (examples: arab, hindi, mandarin, japanese)
* [ ] Good title/subtitle support
* [ ] Language fallback
* [ ] Timezone support 😨
* [ ] Suppport different date and time settings (12/24 hour format, dd/mm vs mm/dd)
* [ ] Markdown support
* [ ] Language switcher component
* [ ] Use translatable strings and files
* [ ] Load locale based on user preference (ssr)
* [ ] Subdomains
* [ ] Try a CMS

## FAQ

Common questions will be added here.

<details>
  <summary>What can you do with i18n in Astro?</summary>
</details>
<details>
  <summary>What Astro doesn't do for you?</summary>
</details>
  <summary>How can I use this template?</summary>
  This is not a template, but you can use the code to inspire your i18n approaches.
</details>
<summary></summary>
<details>
  <summary>Why don't use use `_____`?</summary>
  Probably because I didn't have time to try `_____`.
</details>

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
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
