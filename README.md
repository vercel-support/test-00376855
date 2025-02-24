# test Hono deployment

```
pnpm install
pnpm run start
```

## Push to Vercel with:

```
vercel login
vercel deploy --prod
```

_remove `--prod` to push to Preview_

## Build locally and then push to Vercel

```
vercel build && vercel deploy --prebuilt --prod
```
