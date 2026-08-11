# no-faff

A vegetarian recipe site. Simple food, no life stories, no 14 ingredients you don't have.

Built with [Astro](https://astro.build).

## Running locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

The built site is written to `dist/`.

## Structure

Recipes live in `src/content/recipes/` as Markdown files. Each recipe has frontmatter for title, description, category, tags, timings, and serves.

The site has three sections: **All recipes**, **Everyday eating** (tagged `everyday`), and **Learn to cook**.
