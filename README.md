# D0pam1ne documentation

The documentation site for D0pam1ne, built with [Mintlify](https://mintlify.com) and deployed to
`docs.d0pam1ne.blackhatethicalhacking.com`.

## Structure

- `docs.json` — site config and navigation.
- `*.mdx` — the pages, grouped into folders (`getting-started/`, `recon/`, `attacks/`, ...).
- `images/` — screenshots, named by the page they belong to.
- `favicon.svg`, `images/logo.svg` — brand assets.

## Preview locally

```bash
npm i -g mint
mint dev
```

Then open http://localhost:3000.

## Deploy

Connect this repo to Mintlify and point the custom domain at `docs.d0pam1ne.blackhatethicalhacking.com`.
If the docs live in a subfolder of another repo, set that subfolder as the Mintlify content root.

## Screenshots

Screenshots were captured from D0pam1ne Pro and named by feature. To refresh one, replace the file in
`images/<section>/<name>.png` and keep the same name, no page edits needed.
