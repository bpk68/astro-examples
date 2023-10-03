# Astro with GraphQL

In this example repo, you get the bare bones Astro starter pack, coupled with a simple GraphQL implementation using GraphQL Yoga and Apollo Client.

Astro is set to SSR mode to enable its API endpoint abilities, necessary to handle incoming GraphQL requests.

For a full walkthrough and tutorial on this project, check out [this blog post](https://robkendal.co.uk/blog/how-to-build-astro-site-with-graphql/) on my website.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── components/
│       └── CartRow.astro
│   └── data/
│       └── cart.ts
│       └── types.ts
│   └── lib/
│       └── apollo-client.ts
│   └── styles/
│       └── main.css
│   └── pages/
│       └── index.astro
│     └── api/
│         └── graphql.ts
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name. This project just has the one page, a homepage, located at `/pages/index.astro`.

There's nothing special about `src/components/`, but that's where you can put any Astro/React/Vue/Svelte/Preact components.

The `src/data` directory holds some types and dummy data we can use with GraphQL.

In `src/lib` there's a really simple implemenation of Apollo Client, used to physically call our GraphQL endpoint.

With the `/src/pages/api/graphql.ts` file, this is where the GraphQL action happens. It uses GraphQL Yoga to create a schema, and defines a `POST` endpoint to handle incoming API requests.
