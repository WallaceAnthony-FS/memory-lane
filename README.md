# Memory Lane
Assignment 1.6 for WDV463

### **Objective:** Deploy a static website to function as a blog or journal

### **Key topics:**

- Choosing suitable technology
- Working with React or HTML for page structure
- Utilizing a Headless CMS, Markdown, or other format for data
- Utilizing CSS, TailwindCSS, Styled Components, or another styling solution
- Managed through GitHub
- Hosted via GitHub or a PaaS provider such as Netlify or Heroku

### **Overview**:

You will deploy a static website with customized styling and structure that will be content filled with at least 3 short posts on topics related to technology, something you've learned related to your studies recently, or a resource that you would like to review and share your thoughts on that is related to your studies.

## **Assignment specifications:**
1. Create your own layout

    I recommend managing expectations and keeping the layout simple and clear

2. Create your own CSS

    Style your website to be unique to you.

3. Create your own JavaScript

    JavaScript interactions are not the focus of this project, but meaningful uses will be recognized

4. Deploy Your Site

    We want to see this live on the web!

5. Site Features:

  - At least one page that shows all posts. For example, this may be a home page or an archive page.

  - A layout for the posts to populate when individually visited

  - The ability to navigate between the generated pages

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
