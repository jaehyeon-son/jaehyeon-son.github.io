# jaehyeon-son.github.io

Personal academic homepage, served by GitHub Pages at https://jaehyeon-son.github.io.

The theme is a trimmed-down fork of [academicpages](https://github.com/academicpages/academicpages.github.io), itself based on the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) Jekyll theme (© Michael Rose, MIT License; see LICENSE).

## Layout

- `_pages/about.md` — the single-page site content (about, publications, education, etc.)
- `_config.yml` — site metadata and the author sidebar (name, photo, links)
- `_sass/_publications.scss` — styles for the publication and CV lists on the home page
- `seetraceact/` — standalone static project page for SeeTraceAct, served at `/seetraceact/`

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
