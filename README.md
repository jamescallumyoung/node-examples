# Node Library & Application Examples

This repo includes examples of how to configure a Node.js library or application, with up-to-date options and best
compatibility.

## Application

This branch includes the example for creating an Application with support for ESM.

## Features

- modern `yarn`: version >=3.2
- Yarn plug and play enabled
- TypeScript
- Emitted JS is ES2021
- ESM modules, not CommonJS or older
- Minimum Node version >=16 (lts/gallium)
- NVM .nvmrc file provided
- Build script
- tsc's importHelpers is enabled, with tslib

## Non-Features

- no linting or code formatting

## Next steps

You may want to add linting and formatting to the project.

You may want to disable TypeScript's `importHelpers` in `tsconfig.json` if you don't need the bundled helpers. If you
disable `importHelpers`, you should remove the `tslib` dependency too.
