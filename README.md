# Master Hub

A single page that links to all your other websites. No build step, no dependencies — just `index.html`.

## Using it

Open `index.html` (or host the folder anywhere: GitHub Pages, Netlify, Vercel…).

- **Add a site:** click **+ Add site**, type the address (e.g. `example.com`), done. Name and description are optional.
- **Edit / remove:** click **Edit** at the bottom, then use ✎ or ✕ on a card.
- **Search:** press `/`, type, hit `Enter` to open the first match.

## Sync across browsers

The list is stored in `sites.json` in this repo, so every browser shows the same sites.

- **Viewing** needs nothing.
- **Adding/editing** from a browser: tap **Sync** once and paste a GitHub fine-grained token
  (only this repo, *Contents: Read and write*). Changes are committed to `main` automatically.

To host it, enable GitHub Pages: repo **Settings → Pages → Deploy from branch → `main` / root**.
