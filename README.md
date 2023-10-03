# Astro starter kits and examples

This repo contains a growing list of example [Astro](https://astro.build) sites with various connections. For example, you can connect up Astro with GraphQL for a fullstack app.

Here's the current list:

- [Astro with GraphQL](./astro-graphql/) (simplified)
- [Astro with GraphQL](./astro-prisma-graphql/), Prisma and MongoDB
- ...more to come
-

## Using the official starter kit(s)

If you're looking for a simple, empty starting point with the latest versions of [Astro](https://astro.build) then you'll be better off visiting the [official Astro documenation](https://docs.astro.build) and finding the new Astro command below:

```sh
npm create astro@latest -- --template minimal
```

## 🧞 Commands

The following commands are common to all projects and examples in this repo, unless otherwise stated.

All commands are run from the root of the project, from a terminal:

> Note that we're using `pnpm` here as it's the preferred package manager, but you can use regular ol' `npm` or `yarn` if you prefer.

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `pnpm install`         | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |
