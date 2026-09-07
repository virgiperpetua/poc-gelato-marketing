# poc-gelato-marketing

> **Primary:** GitHub (`virgiperpetua/poc-gelato-marketing`). GitLab (`virginia-perpetua/poc-gelato-marketing`) is a mirror.

Public marketing site for **Churn Sheet** (`poc-gelato-app`).

## Stack

| Layer | Choice |
| --- | --- |
| Site | Astro SSG |
| Styles | Tailwind 4 + Virginia Perpetua `--vp-*` tokens (vendored) |
| Hosting | GitHub Pages (`gh-pages` / Actions) |

## Local

```sh
pnpm install
pnpm dev
```

```sh
pnpm build
```

## Related

- Live site: https://gelato.virgiperpetua.com/
- Live app: https://virgiperpetua.github.io/poc-gelato-app/
- App source: https://github.com/virgiperpetua/poc-gelato-app
- Tokens: https://github.com/virgiperpetua/tokens
- Personal site: https://virgiperpetua.com

Outbound URLs live in [`src/config.ts`](./src/config.ts).
