# NodeJS/Express/Typescript template

This is just a fast template to use for setting up a Typescript/Express project without a ton of moving parts.

## How to use

Technically you can clone this repo and run `npm i`, or create a repo on github using the template feature. If you're using it for your own project you'll have to change the origin.

When you run `npm run dev` it is using nodemon with ts-node to run the `src/index.ts` file live.

`npm run start` will run `index.js` in the `dist/` directory (you have to `npm run build` first).

Before running make sure you create a `.env` file and define the `PORT` environment variable.
