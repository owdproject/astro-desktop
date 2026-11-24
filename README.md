# Astro Desktop

An experimental Open Web Desktop host. The static page is rendered by Astro. A browser script attaches the Astro adapter's custom element to a shared desktop instance and opens a draggable About window.

```sh
cd template
pnpm install
pnpm dev
```

Use `pnpm build` for static output. The starter uses the published core and a local source snapshot of the [Astro adapter](https://github.com/owdproject/astro/tree/52f930994cd9cc5bb1f9a079e5b54d8b69c1691d). The snapshot keeps installation independent of the upstream Git package build. Replace it with a registry dependency when the adapter is released.

The `template/` folder is self-contained. This experiment runs with project scripts. It has no control panel integration yet.
