# nrahman.cyou — personal website

Single-page personal site for **nrahman.cyou**, built as one self-contained
`index.html`. No build step, no dependencies.

## How to edit

Open `index.html` and look for the comments:

- `EDIT: your intro text` — hero heading and tagline
- `EDIT: your about text` — about section
- `EDIT: your skills` — skill chips
- `EDIT: swap in your own projects` — project cards
- `EDIT: COLORS HERE` — theme colors (top of the `<style>` block)

Save the file, then push — Vercel deploys automatically (once Git integration
is connected).

## Deploy

```sh
# from this folder
vercel deploy --prod
```

## Structure

```text
.
├── index.html   # the entire site (HTML + CSS + a tiny script)
└── README.md
```
