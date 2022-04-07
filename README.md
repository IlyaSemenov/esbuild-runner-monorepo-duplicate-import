# HOWTO

```
npm i -g pnpm
pnpm i
cd packages/b
pnpm test
```

## Expected

`shared.ts` imported once.

## Actual result

`shared.ts` imported twice.
