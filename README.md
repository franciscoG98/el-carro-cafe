# Astro Starter Kit: Basics

## Setup
```
git clone (repo url)
cd el-carro-cafe
npm install
npm run dev
```

## Overview

The idea of this project is to make a QR menu for a local food truck. Only to avoid the client asking about prices and content of products, and make the interaction with the owner faster I want this and that, done. I implemented my idea with Astro and Contenful, Astro because it's fast and light, and also wanted to learn something new, and I thought in Contenful because if I give access to the cms to the owner he can easily take care of his menu, change prices and add or take out products. The product card (which is the only component of this site - I know it's a landing) contains a title, picture, price, description, and 2 booleans that define if the product is apt for vegan or celiac people.

You can see the website [here](https://elcarrocafe.netlify.app/)

![QR to go to the deployed site](./public/qr-elcarrocafe.svg "El Carro Café").


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

## Contenful

[Astro and Contenful](https://docs.astro.build/en/guides/cms/contentful/)

.env
```
CONTENTFUL_SPACE_ID=YOUR_SPACE_ID
CONTENTFUL_DELIVERY_TOKEN=YOUR_DELIVERY_TOKEN
CONTENTFUL_PREVIEW_TOKEN=YOUR_PREVIEW_TOKEN
```



