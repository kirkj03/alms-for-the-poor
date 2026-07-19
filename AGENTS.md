# AGENTS.md

## Cursor Cloud specific instructions

This repository is an **asset / brand library**, not a software application. It contains only:

- Image assets: `.png` / `.jpg` brand art (PFPs, banners, ritual posts, memes, concept art).
- Markdown docs: `README.md` (folder guide), `01-identity/CHARACTER_PROMPTS.md` (style lock + regen prompts), `02-rituals-cult/meme-formats/TAGLINES.md` (caption combos).

There is **no application code, package manager, build system, test suite, lint config, or runnable service**. Consequently:

- Nothing to install — there are no dependencies. The startup update script is intentionally a no-op.
- There is no `build`, `lint`, `test`, `dev`, or `start` command. Do not fabricate one.
- "Running the product" means viewing/editing the image assets and their accompanying markdown docs. Verify assets with an image viewer or `file <path>` (all PNG/JPG are real raster images, not Git LFS pointers).
- When adding or regenerating identity art, follow the style/face/negative locks in `01-identity/CHARACTER_PROMPTS.md` and keep banners at exactly 1500×500.
- **Asset canvas:** browse all images + copy captions via `gallery/`. Open `gallery/index.html` as a static file, or run `python3 -m http.server 8765` and open `http://localhost:8765/gallery/`. Public URL (when Pages is enabled): `https://kirkj03.github.io/alms-for-the-poor/`. Caption map is `gallery/captions.json`; inventory is `gallery/inventory.json` (re-embed into `gallery/index.html` after big inventory/caption changes so the static file stays in sync). Deploy workflow: `.github/workflows/deploy-pages.yml` (pushes to `main`).
