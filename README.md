# @x12i/authix-types usage example

Shared TypeScript contracts and Zod schemas for Authix Token Infrastructure.

This consuming application demonstrates **validate incoming json and report contract errors** using the published npm package, pinned to `1.0.2`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- A consumer needs the following capability: Shared TypeScript contracts and Zod schemas for Authix Token Infrastructure.
- A producer and consumer of authix data need to share the published type or validation contract before exchanging payloads.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/authix-types)
- [Implementation monorepo](https://github.com/x12i/authix)
- [Reviewed package source](https://github.com/x12i/authix/tree/dc63d85812526248b1dade3f25131205c36be51f/packages/token-types)

The current source snapshot has a different manifest version from the pinned npm dependency. This example is validated against the installed npm release.

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.
