# Email assets

Public image host for the Sliide × T-Mobile weekly performance email, built by
the private `minesh-sliide/email` repo.

**This repo is public on purpose, and holds nothing else.** Email clients fetch
images as each recipient opens the message, so the files have to be reachable
without credentials. Only these four brand marks live here — the builder, the
synced sheet data and the workflow all stay in the private repo.

| File | Use | Intrinsic | Displayed at |
|---|---|---|---|
| `logo-sliide-white.png` | Sliide, on the dark/magenta header bar | 256×58 | 128×29 |
| `logo-tads-white.png` | T-Mobile Advertising Solutions, dark bar | 280×64 | 140×32 |
| `logo-sliide-ink.png` | Sliide, on a light header bar | 256×58 | 128×29 |
| `logo-tads-magenta.png` | T-Mobile Advertising Solutions, light bar | 280×64 | 140×32 |

Each is served at 2× its display size so it stays sharp on retina screens.

Base URL, set as `ASSET_HOST` in `editor-light.html`:

```
https://raw.githubusercontent.com/minesh-sliide/email-assets/main/
```

Renaming or deleting a file here breaks the header of every email already sent.
