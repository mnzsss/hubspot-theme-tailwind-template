# HubSpot Tailwind CSS Starter

Starter project for building HubSpot themes with Tailwind CSS and Webpack.

### Install

Run `pnpm i` or `npm install` to install dependencies

### Scripts
- `start` : Builds project with webpack, uploads to your `defaultPortal` specified in `hubspot.config.yml` and watches for changes via [`@hubspot/webpack-cms-plugins/HubSpotAutoUploadPlugin`](https://www.npmjs.com/package/@hubspot/webpack-cms-plugins).
- `build` : Clears `/dist` contents and builds project into `/dist`.
- `deploy` : Clears `/dist` contents, builds project into `/dist`, and uploads to via [`@hubspot/cms-cli`](https://www.npmjs.com/package/@hubspot/cms-cli).
- `upload`: Uploads the `/dist` contents to your `defaultPortal` specified in `hubspot.config.yml`.

### Development

First run `pnpm hs init` to initialize the HubSpot project. Then run `pnpm start` to start the development server.

The next step you need create a website page following the instructions in the [HubSpot documentation](https://developers.hubspot.com/docs/cms/guides/getting-started#create-a-website-page).

### Tailwind CSS

This project uses Tailwind CSS for styling. You can find the configuration in `tailwind.config.js`. You can also add custom styles in `src/css/styles.css`.
