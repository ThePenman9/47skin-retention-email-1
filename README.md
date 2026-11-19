# 47 Skin | First Steps Email Experience — rebuilt

A React + Vite portfolio demo. First view is a simulated inbox. Only the 47 Skin email opens; all unrelated emails are intentionally inert. The opened email includes the exact supplied copy, a live back button, and the authentic photographed product packaging. Search, navigation, and starring work in the React version.

## Run

```sh
npm install
npm run dev
```

For production:

```sh
npm run build
npm run preview
```

Import into Vercel as Vite; output directory `dist`. Project name suggestion: `47skin-first-steps-rebuilt`.

## Important

- React/Vite dependencies are hosted by npm. `npm install` needs access to npm or a configured dependency mirror.
- A self-contained **static fallback inbox and email** is built into `index.html`; it displays working navigation even if the React bundle is unavailable or fails. For a dependency-free local preview, open `index.html` through a static server; images need the `/assets` root mapped to `public/assets` (use `preview-standalone.html` for a file you can open directly).
- The portrait is an editorial AI illustration, **not a real customer**. The product image is copied from the authentic packaging photo the user previously supplied.
- CTA uses the previously supplied official serum product-page URL `https://47skin.com/products/anti-blemish-scar-repair-serum`, as no new URL was in this brief.
- Speculative portfolio work, not an email sent or approved by 47 Skin.
