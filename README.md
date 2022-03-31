# Svelte Demo x Correlaid

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Prerequisites 
The only thing we need to run this is node.

- Windows:
  - https://nodejs.org/en/download/
- Mac:
  - `brew install node`
- Linux:
  - `sudo apt-get install -y nodejs`

## Creating a project

If you plan to start from scratch in the future, here is how to get the same skeleton as in this repo:

```bash
# create a new project in the current directory
npm init @svelte-add/kit@latest
npx svelte-add@latest tailwindcss
```
## Clone this repo

To be able to follow along, please clone the repo:

```bash
git clone https://github.com/svelte-add/svelte-add.git
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.
