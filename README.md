# Node Library & Application Examples

This repo includes examples of how to configure a Node.js library or application, with up-to-date options and best
compatibility.

Each example targets Node.js v16 (a.k.a gallium) as that is the latest LTS release.

## Examples:

### Base

The `init` branch establishes best practices and provides configuration that other branches extend. It provides a good
example of the base configuration required for a modern Node.js package.

### ESM Library

The `library-esm` branch contains an example setup for a Node.js library that is exported as an ESM module, using modern
JS syntax. TypeScript types are shipped alongside.

### ESM Library & CommonJS Library

The `library-esm-and-cjs` branch extends the `library-esm` branch by adding an example setup for shipping CommonJS
alongside the existing ESM code and TS declarations.

### Application

The `application` branch contains an example of a Node.js application. (Meaning it has a "start" command and runs
itself, rather than being imported like a library is.) The application builds to modern JS, with ESM code.
