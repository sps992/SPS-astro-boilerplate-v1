# Forked From Astro minimal template

## 🚀 Project Structure

Astro project, has the following folders and files:

```
/
├── public/
├── src/
│    pages/
│       └── index.astro
|    storyblok/
|      └── [components]
|    styles/
|      └── tailwind.css
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Put all Astro components in `src/components/`.

All StoryBlok components in `src/storyblok`

Any static assets, like favicons, can be placed in the `public/` directory. All component assets like header images, should be uploaded to the Storyblok media library.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Documentation
 [Astro](https://docs.astro.build) or jump into [Discord server](https://astro.build/chat).
[@astrojs/tailwind](https://docs.astro.build/en/guides/integrations-guide/tailwind/).
[Storyblok](https://www.storyblok.com/docs).
[@storyblok/astro helpful post](https://www.storyblok.com/mp/announcing-storyblok-astro).
