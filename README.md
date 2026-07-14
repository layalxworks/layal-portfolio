# Layal Aljohani — Portfolio

A single-file, self-contained portfolio site: HTML, CSS, and JavaScript
all in `index.html`, with your photo embedded directly in the file (no
separate image asset to manage).

## Open it

Just double-click `index.html` — it opens in any browser, no build step,
no server, no dependencies.

## Edit the content

All your real content — contact links, projects, skills, certifications,
the typed hero roles — lives in one place: the `DATA` object near the
top of the `<script>` section at the bottom of `index.html`. Search for:

```js
const DATA = {
```

Everything else (colors, layout, animations) lives in the `<style>`
block at the top of the same file.

## Deploy it

Since it's a single static HTML file, it works as-is on:
- **Netlify / Vercel**: drag-and-drop the folder, or connect a repo
- **GitHub Pages**: push this folder to a repo and enable Pages
- **Any static host**: just upload `index.html`

## Notes

- The contact form currently opens the visitor's email client. To have
  it deliver directly to your inbox, set `FORM_ENDPOINT` in the script
  to a service like [Formspree](https://formspree.io).
- The Education & Experience section was intentionally left out since
  those details haven't been shared yet — add them back in whenever
  you're ready.
