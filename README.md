# Node Library & Application Examples

This repo includes examples of how to configure a Node.js library or application, with up-to-date options and best compatibility.

## ESM Library

This branch includes the example for creating a library with support for ESM.

## Features

- modern `yarn`: version >=3.2
- Yarn plug and play enabled
- TypeScript
- Emitted JS is ES2021
- ESM modules, not CommonJS or older
- Minimum Node version >=16 (lts/gallium)
- NVM .nvmrc file provided

## Non-Features

- no linting or code formatting
- no publish command

## Next steps

You may want to add linting, formatting, and publishing to the project.

You may also want to add `tslib` and set `importHelpers: true` in `tsconfig.json`. This can reduce code duplication in
the build output in some cases.
