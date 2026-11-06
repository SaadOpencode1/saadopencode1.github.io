# Aster — public mirror

This repository holds the static copy of Aster served at `aster.runs-at.dev`.

Nothing here is edited by hand. `.github/workflows/publish.yml` fetches the
already-deployed app, points its page at that deployment as the API, adds a
404 shell for deep links, and publishes the result with GitHub Pages. To
refresh the mirror after the app changes, either push any commit here or run
the workflow by hand from the Actions tab.

## What the app looks like

A dark, quiet home screen: a sidebar of destinations, a welcome line with the
Aster mark, one wide composer, and a row of prompt pills underneath. Settings
opens as a single centred card with its own list down the side.
