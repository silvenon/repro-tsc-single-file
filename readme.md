# Repro: TypeScript's `tsc` Command

```sh
yarn # install dependencies
```

```sh
yarn tsc --noEmit # passes
yarn tsc --noEmit index.ts # fails
```
