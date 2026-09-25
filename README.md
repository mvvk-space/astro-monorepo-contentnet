# Astro Monorepo — Multiple Sites

Uses Astro and Turbo to manage multiple sites. Clone this repo to serve as your local development environment for creating an Astro multisite.

**Repository:** [mvvk-space/astro-monorepo-contentnet](https://github.com/mvvk-space/astro-monorepo-contentnet)

## Creating a new site

Creating a new site is simple — mostly copy-paste:

1. Duplicate the `_site-template` folder found in `/apps`.
2. Rename `_site-template` to the name of your site.
3. Update the `package.json` in your new `/apps` directory — all it needs is your site name and the tag that the API needs to fetch for new content.

That's it. Then make a new **theme** and give it some **new content**.

## What's here

- `apps/` — the sites (start from the `_site-template`)
- `packages/` — shared packages
- `turbo.json` — Turbo monorepo task config
- `.env-template` — required environment variables
- `scripts/` — helper scripts
- [consider-adding-from-previous.md](./consider-adding-from-previous.md) — notes on things to carry over from the previous setup