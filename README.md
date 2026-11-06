# Marlbrook — public mirror

This repository holds the static copy of Marlbrook, the desktop and web place to
think out loud.

Nothing here is edited by hand. `.github/workflows/publish.yml` fetches the
deployed app, points its page at that deployment as the API, adds a 404 shell for
deep links, and publishes the result with GitHub Pages. To refresh the mirror
after the app changes, push any commit here or run the workflow by hand.

## Installing the desktop app (Ubuntu)

Download `Marlbrook-1.0.0-amd64.deb` from the latest release, then either
double-click it in Files, or run:

```
sudo dpkg -i Marlbrook-1.0.0-amd64.deb
sudo apt-get install -f
```

It appears in the applications grid as Marlbrook. The AppImage works too:
make it executable and run it directly.
