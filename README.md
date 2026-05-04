# smarttvrc-site

Static site for the **Remote SmartTV** mobile app — landing page + privacy policy.

Hosted on GitHub Pages → **<https://smarttvrc.aiotx.vn/>**.

## Layout

```
docs/                      # GitHub Pages source (Settings → Pages → main /docs)
├── CNAME                  # smarttvrc.aiotx.vn
├── index.html             # Landing (EN)
└── privacy/
    ├── index.html         # Privacy Policy (EN)
    ├── vi.html            # Vietnamese
    ├── ja.html            # Japanese
    ├── ko.html            # Korean
    └── zh.html            # Simplified Chinese
```

URLs:
- Landing → `/`
- Privacy (EN) → `/privacy/`
- Privacy (other langs) → `/privacy/{vi,ja,ko,zh}.html`

## Editing

Pure static HTML with inline CSS — no build step. Edit a file, push to `main`,
GitHub Pages redeploys in ~1 minute.

## Backend

Backend code (license + sharing service planned for v1.5) lives in a separate
**private** repo (`smarttvrc-server`, to be created). This repo is intentionally
public-only because GitHub Pages on the free tier requires a public source.
