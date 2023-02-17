# [sharmainelim.github.io](https://sharmainelim.github.io)

This is my personal site, made for funsies.

## Set up for local development

Right now, this site is made up of HTML pages, SASS files, and Javascript files
in the `src/` folder.

If you already have Node.js set up
([See front-end tooling documentation](docs/frontend-tooling.md)):

- run `npm install` to install the dependencies, and then
- run `npm run dev`.

You should now be able to access the site at http://localhost:5173/.

## Deploy to GitHub Pages

All commits pushed to the `main` branch will trigger the deployment workflow,
which will:

- compile the HTML, JS, and SASS files,
- copy the built files into the branch that Pages use (`gh-pages`).
