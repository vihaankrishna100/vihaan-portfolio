# vihaan.dev

Personal site. One static page, no framework, no build step.

- `index.html` — the whole site, content and styles inline.

## Run it

```bash
python3 -m http.server 4000
# http://localhost:4000
```

## Deploy

```bash
vercel deploy --prod
```

`vercel.json` serves the directory as static output.
