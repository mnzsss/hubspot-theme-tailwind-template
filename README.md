# HubSpot Tailwind CSS Starter 🚀

Jumpstart your HubSpot theme development with this Tailwind CSS and Webpack starter project.

## Installation

Run `pnpm i` or `npm install` to install project dependencies.

## Scripts
- `start`: Builds the project with Webpack, uploads to your specified `defaultPortal` in `hubspot.config.yml`, and watches for changes using 🔄 [`@hubspot/webpack-cms-plugins/HubSpotAutoUploadPlugin`](https://www.npmjs.com/package/@hubspot/webpack-cms-plugins).
- `build`: Clears `/dist` contents, then builds the project into `/dist`.
- `deploy`: Clears `/dist` contents, builds the project into `/dist`, and uploads it via 🚀 [`@hubspot/cms-cli`](https://www.npmjs.com/package/@hubspot/cms-cli).
- `upload`: Uploads the contents of `/dist` to your `defaultPortal` specified in `hubspot.config.yml`.

## Development

1. Run `pnpm hs init` to initialize the HubSpot project.
2. Start the development server with `pnpm start`.

Follow the instructions in the [HubSpot documentation](https://developers.hubspot.com/docs/cms/guides/getting-started#create-a-website-page) to create a website page.

## Tailwind CSS

This project leverages Tailwind CSS for styling. Explore and modify the configuration in `tailwind.config.js`. Customize your styles in `src/css/styles.css`.

Feel free to contribute, open issues, or submit pull requests. Happy coding! 🎉
