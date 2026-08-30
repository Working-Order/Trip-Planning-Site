# The October List — live edition

The trip-decision dashboard for Solomon & Roni's October 2026 trip, served by GitHub Pages
from this repository: **https://working-order.github.io/Trip-Planning-Site/**

- `index.html` is the whole app (single file: markup, styles, code, the spreadsheet engine
  and a built-in snapshot of the research workbook).
- Nothing personal lives here. Reactions, notes, checklists and the shared workbook are
  written by the app into the **private** `Trip-Planning` repository under `data/`, using a
  fine-grained token that each laptop keeps in its own browser. This page works read-only
  for anyone who finds it and shows only the built-in research snapshot.
- To update the app: replace `index.html`, commit, push. GitHub Pages redeploys in a minute
  or two. Planning state is untouched by an app update — it never lived in this file.
