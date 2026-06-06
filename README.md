# tsl-textures-ts-types
TypeScript types for tsl-textures

This repo is a development and staging area for the tsl-textures type declarations.

Periodically the updates from this repository are pushed to DefinitelyTyped and released in the @types/tsl-textures npm package.

The idea of having a separate development and staging area for the tsl-textures type declarations was inspired by https://github.com/three-types/three-ts-types which does the same thing for the three.js type declarations. That repo was used as a guide for this one.

## Testing

DefinitelyTyped-style tests are in `types/tsl-textures/tsl-textures-tests.ts`. This file is never run, only type-checked, to catch regressions in the existing type declarations.

To run the tests, do the following:

```
pnpm install
pnpm run test
```
