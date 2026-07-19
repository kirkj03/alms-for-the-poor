# Alms for the Poor — Character Prompts & Style Lock

Canon files:
- PFP: `primary/pfp-cult-sticker.png`
- Banner: `primary/banner-3x1-cult.png`
- Ref copy: `../04-archive-concepts/mascot-refs/alms-fox-canon.png`

Always attach the canon PFP as a reference image when regenerating.

---

## Style lock (always include)

```
Alms cult sticker style: anthropomorphic orange fox with cream/white muzzle and inner ears,
dark charcoal/black hooded robe, thick clean white sticker outline, matte black or dark
grain background, flat graphic limited palette (orange, cream, dark hood, brown wood bowl,
white outline). NOT Pixar, NOT soft 3D, NOT photoreal Disney, NOT MS Paint unless
explicitly doing shitpost spice.
```

## Face lock (canon = peaceful)

```
EXPRESSION: calm, peaceful, neutral-zen — soft white pupil-less eyes, relaxed brows
(NOT sad/upturned/worried), gentle soft closed mouth or slight peaceful smile
(NOT frown, NOT pleading, NOT crying).
```

## Hard negatives (always include)

```
CRITICAL: plain dark hood with absolutely ZERO symbols, patches, leaves, emblems,
crosses, runes, icons, or logos. Plain empty wooden bowl with ZERO carvings, logos,
or engravings. No extra branding marks on clothing or bowl.
```

---

## 1) Canon PFP (base character)

Used to generate the locked peaceful sticker fox:

```
Alms cult sticker fox PFP. Orange fox in plain dark hooded robe, holding a plain empty
wooden bowl with both paws, chest-up, centered. Thick white sticker outline, matte black
grain background. EXPRESSION: calm peaceful zen — soft white pupil-less eyes, relaxed
brows, gentle neutral-peaceful mouth NOT frown. Plain hood NO symbols, plain bowl NO logos.
Square, readable as tiny avatar. Flat graphic cult style. No text.

Style lock + face lock + hard negatives (above).
```

Reference: attach `primary/pfp-cult-sticker.png` (or prior best peaceful variant).

---

## 2) Banner fox (for compositing)

Banner is composited at exact 1500×500 in code (not AI-cropped), using a full fox render:

```
Alms cult sticker fox ONLY, chest-up, for banner compositing. Orange fox in plain dark hood
ZERO symbols/patches, plain empty wooden bowl ZERO logos, thick clean white sticker outline,
solid pure black background. EXPRESSION: calm and peaceful — soft half-lidded white
pupil-less eyes, relaxed level brows, gentle soft peaceful closed mouth (NOT frown).
Centered with generous padding around entire character so nothing touches edges.
Flat graphic. No text.

Style lock + face lock + hard negatives.
```

Then composite onto 1500×500 with text:
- `bowl stays out` (large white)
- `$ALMS` (green, below)

---

## 3) Frown era (archived — do not use for identity)

Early cult fox (kept for history only):

```
Crypto Twitter profile picture, high contrast, simple and iconic at tiny size. Flat graphic
logo style (NOT Pixar): bold silhouette of a hooded fox head in dark green and orange,
holding a simple wooden bowl. Thick shapes, limited colors, slight grain. Sticker/street-art
stamp feel.

Later frown variant:
Orange fox in dark cultish hooded robe, pathetic sad expression with droopy pupil-less
white eyes and slight frown, holding empty brown wooden bowl. Thick white sticker outline,
matte black grainy background.
```

Archived as: `alternates/pfp-cult-sticker-frown.png`, `alternates/banner-3x1-cult-frown.png`

---

## 4) Scene / ritual character (same fox in environment)

Drop into any scene prompt:

```
Calm peaceful Alms orange fox matching canon reference: soft neutral face NOT frown,
white pupil-less eyes, plain dark hood ZERO symbols, plain empty wooden bowl ZERO logos,
thick white sticker outline. [SCENE DETAILS HERE]. Flat graphic cult sticker style.
NOT Pixar soft 3D.
```

### Example scenes that worked
- Morning sunrise casting long shadows across the empty bowl
- Sleeping with bowl on chest + dream bubble of sitting with sign `alms for the poor?`
- Serene in foreground while other RH mascots fight for #1 in background
- Empty bowl countdown on dawn path / stone steps with lantern
- Locked-in 2-panel (chill bowl → focused bowl outstretched)
- GM reply sticker with text `gm`

---

## 5) Shitpost spice (separate cast — not canon identity)

These are reply/chaos only; do not replace PFP/banner:

```
MS Paint / potato / wojak beggar energy — crude, ugly-funny, CT native.
Orange fox in green hood with empty bowl OR wojak-in-hood with bowl.
NOT polished cult sticker.
```

---

## 6) Quick regenerate checklist

1. Attach `primary/pfp-cult-sticker.png` as reference  
2. Paste **style lock + face lock + hard negatives**  
3. Add scene/action  
4. Reject any output with hood patches/leaves or sad frown for official assets  
5. For banners: generate fox on black, composite to **exact 1500×500** (avoid 16:9 center-crop)

---

## Motto / copy lock

- Motto: `bowl stays out`
- Zinger: `dignity optional`
- Ticker: `$ALMS`
- Name: Alms for the Poor
- Ritual lines: `alms granted`, `welcome to the parish`, `parish certified`
