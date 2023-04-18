# ByteMyBrief's SvelteKit Template

This is a simple template that integrates Tailwind, Skeleton UI, and TablerIcons
for you. Additionally, it includes the
[typescript-svelte-plugin](https://github.com/sveltejs/language-tools/tree/master/packages/typescript-plugin)
for those of you who use Neovim.

**It is meant to be as minimal as possible.**

> Please see [Tailwind's](https://tailwindcss.com/),
> [Skeleton's](https://www.skeleton.dev/), and
> [Tabler Icons'](https://tabler.io/) own documentation for further information.

## Developing

Once you've created a project and installed dependencies with `npm install` (or
`pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an
> [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
