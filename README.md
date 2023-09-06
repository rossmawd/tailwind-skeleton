## Shopify TailwindCss Skeleton

This repo contains a `theme` folder that has a barebones setup for a Shopify theme.

At the root level tailwindCss has been installed and configured with [pnpm](https://pnpm.io/).

It was based off of this video by [Coding with Robby](https://www.youtube.com/watch?v=OJqk5-FC5sg)

## To run

1. You'll need to have the Shopify CLI [installed](https://shopify.dev/docs/themes/tools/cli/install) 
2. Run `pnpm install`
3. In the root directory, run the TailwindCSS CLI: `pnpm run tw`
4. In another terminal `cd` into the `/theme` directory and run `shopify theme dev`


The CLI should now give you the link to preview the store front where 'Hello You' will be centered in the screen by TailwindCss