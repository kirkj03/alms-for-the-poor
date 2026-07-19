# Alms for the Poor ($ALMS) — Asset Library

Brand lock: cult sticker fox + `bowl stays out`  
Motto: bowl stays out · dignity optional

## Folder guide

### `01-identity/` — profile face
- **`primary/`** → ship these (PFP + 3:1 banner)
- **`alternates/`** → yellow/MSP / older PFP variants
- **`CHARACTER_PROMPTS.md`** → prompts + style lock for regenerating the fox

### `02-rituals-cult/` — official timeline posts
Same styling as PFP/banner. Use for:
- `alms-hours/`
- `confession-booth/`
- `empty-bowl-countdown/`
- `join-parish/`
- `reverse-shill/`

### `03-shitpost-spice/` — replies & chaos only
MS Paint / potato / wojak. Do **not** use as PFP or ritual announcements.

### `04-archive-concepts/` — early explorations
Pixar/cinematic/beggar studies. Reference only unless a rare lore post.

## Quick ship checklist
1. `01-identity/primary/pfp-cult-sticker.png`
2. `01-identity/primary/banner-3x1-cult.png`
3. Ritual images from `02-rituals-cult/`
4. Spice from `03-shitpost-spice/` when replying

## Asset canvas (browse + copy captions)

**Live (GitHub Pages):** [https://kirkj03.github.io/alms-for-the-poor/](https://kirkj03.github.io/alms-for-the-poor/)  
*(requires Pages enabled — see below)*

**Local static file:** open `gallery/index.html` in a browser.

**Local server:**

```bash
python3 -m http.server 8765
```

Then open [http://localhost:8765/gallery/](http://localhost:8765/gallery/)

- Filter by folder / “ship” / replies
- Click image to enlarge
- One-click copy for paths + taglines
- Caption map lives in `gallery/captions.json` (edit anytime)

### Enable GitHub Pages (one-time)

1. Repo must be **public** (free Pages) *or* you need GitHub Pro/Team for private Pages.
2. GitHub → **Settings → Pages**
3. Build and deployment → Source: **GitHub Actions**
4. Merge to `main` (or run the `Deploy GitHub Pages` workflow). Site publishes to the URL above.
