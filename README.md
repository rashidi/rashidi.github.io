# rashidi.github.io

Personal site of Rashidi Zin, built with [Antora](https://antora.org/).

## Structure

- `docs/antora.yml` — Antora component descriptor
- `docs/modules/ROOT/` — AsciiDoc content (`pages/`) and navigation (`nav.adoc`)
- `ui/` — custom Antora UI (theme): page layouts (`layouts/`) and styles (`css/`)
- `antora-playbook.yml` — Antora playbook used to build the site
- `package.json` — Antora build tooling

## Build locally

```sh
npm install
npm run build
```

The generated site is written to `build/site`.

## Deployment

The site is built and published to GitHub Pages automatically on every push to
`main` via the workflow in `.github/workflows/pages.yml`.
