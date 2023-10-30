# WordCamp Europe, Torino 2024

> Resources for the WCEU 2024 website.
>
>Initially to host the styles used on the WCEU 2024 website, but also for any >documentation or assets related to the event.

## Prerequisites
- [Node/NPM](https://nodejs.org/en/download/)
- [Yarn](https://www.npmjs.com/package/yarn) (optional)
- [NVM](https://github.com/nvm-sh/nvm) or [N](https://github.com/tj/n) (optional)

> Note: [@wordpress/scripts](https://developer.wordpress.org/block-editor/reference-guides/packages/packages-scripts/) requires Node.js 14.0.0 or later, and npm 6.14.4 or later. It is not compatible with older versions.

## Install
 	npm install

## Development

While working on the project, you might need to rebuild the CSS or JavaScript ( to include more files ).

To build, run:

	npm run build

If you want to watch for changes, run:

	npm run start

### Linting

This project has eslint, stylelint, and phpcs set up for linting the code. This ensures all developers are working from the same style. To check your code before pushing it to the repo, run:

	npm run lint:css
