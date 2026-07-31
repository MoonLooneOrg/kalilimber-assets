# kalilimber-assets

Public image assets for the [KaliLimber](https://github.com/MoonLooneOrg/KaliLimber) app.
Served to the app via the jsDelivr CDN (jsDelivr only serves public repos, which is why
these live outside the private app repo).

## Layout

```
content/
  covers/     # article cover images (master 1600x1000, 16:10, palette-agnostic, no text)
  diagrams/   # instructional diagrams (e.g. kalimba note layout)
```

## Usage

Reference an image by its jsDelivr URL, pinned to a commit or tag so the CDN cache
cannot serve a stale version:

```
https://cdn.jsdelivr.net/gh/MoonLooneOrg/kalilimber-assets@<commit-or-tag>/content/covers/<file>.png
```

During authoring you may use `@main`; pin to a commit SHA for release builds.
