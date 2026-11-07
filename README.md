# Quote data

This branch holds the data the Ziyarat quotes app saves. The app writes here on its own through the GitHub API:

- `rates.json`: the shared rate card
- `quotes/<id>.json`: one file per saved quote

Don't merge this branch into `main` and don't delete it. The app itself lives on `main`.
