# tailwind-boilerplate
Simple boilerplate to build organized projects using Tailwind, PostCSS and Parcel without a JS framework.

## Installation
1. Clone this repository
2. Run `npm install` to install dependencies
3. Run `npm run start` and start building

## Commands
Scripts in `package.json` that are not mentioned here are internal and not meant to be run manually.

### npm run clean
*Warning - this is a Windows 10 implementation. Change to `rm -rf dist .cache` on unix or linux platforms.*

Deletes the `.cache` and `dist` folders.  Will throw an error if they don't exist.

### npm run start

Runs a local development instance of the project.

### npm run build

Builds a production release in the `dist` folder.
