# Summary

This is a basic to-do list app built using Vue.js and Tailwind.css as part of a [Laracasts](https://laracasts.com/) code-along course.

The course in question is: [Learn Vue 3: Step by Step](https://laracasts.com/series/learn-vue-3-step-by-step), instructed by [Jeffrey Way](https://laracasts.com/series?instructors%5B%5D=JeffreyWay).

## Install instructions

Once pulled, install npm and run: `code` npm install

You can then run this command to launch the project: `code` npm run start

This will run the _start_ script in package.json. It should be hosted and accessible in a browser from your [localhost](http://localhost:3000).

This project is not a live/published project, so the only dependencies are dev dependencies which are:

- json-server: is required for the db.json file to act as a database for the project. This is static, so while the page updates when interacting with it, refreshing the page will revert the to-do list back to it's original state.
- concurrently: allows both the site to be hosted (via npx serve) and json-server to run.
