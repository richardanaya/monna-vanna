# Oil Chronicle — style lock (supersedes Tempera Chronicle)

**Status:** Locked 2026-08-24 after Richard skipped the fresco-vs-oil question. The generated face locks in `assets/looks/` are **academic oil / history-painting**. Do not fight them with the old fresco suffix.

**Tempera Chronicle is retired** for this production. Leave `docs/style-tempera-chronicle.md` in the repo as archive, or retitle it "superseded." New gens use **this** page only.

---

## What it is

**Oil Chronicle** = 19th-century academic history painting used as cinema stills.

- Visible brush, canvas grain, warm varnish, ochre / iron / torch-amber.
- Faces readable. Costume weight. Room and tent as painted space.
- **Not** a flat fresco panel. **Not** Piero-plane stylization. **Not** photoreal / DSLR / 8k skin.

Heroic clarity still holds: she decides; the camera does not apologize.

---

## Production Aspect Ratio: 2.39:1 (CinemaScope)

**Locked 2026-08-25.** All new cinema stills and title cards use **2.39:1** (CinemaScope).

- **Fal size for 2.39:1**: `image_size: {"width": 1920, "height": 800}` (both multiples of 16)
- **Existing face locks** in `assets/looks/` stay as-is (4:3 portrait studies)
- **Do not generate 4:3 portraits** for new cinema frames

---

## Master STYLE SUFFIX (paste on every new prompt)

```
Oil Chronicle style, academic history painting, oil on canvas, visible brush and canvas grain, 19th-century historical painting, cinematic painted still, late 15th-century Tuscany, ochre limestone iron-grey torch-amber, hard directional painted light, dignified moral clarity, stylized not photoreal
```

## Master NEGATIVE (every new prompt)

```
photorealistic, hyperrealistic, DSLR photo, 8k skin pores, uncanny valley skin, CGI realism, modern photography, depth-of-field bokeh, romantasy soft glow, anime, manga, Disney, cartoon, neon, cyberpunk, modern clothing, smartphones, meme composition, glossy game render, oversexualized pose, nude explicit, lingerie, beauty-filter face, fresco flat planes, tempera panel, poster caption, title banner, text, watermark, logo, EX AMICO, TEMPERA CHRONICLE
```

**Do not paste the old Tempera Chronicle / fresco-influenced suffix onto new gens.** It fights these locks.

---

## Face locks (use these, don't reinvent)

| File | Lock |
|---|---|
| `assets/looks/giovanna-mantle.png` | Night / camp approach. Mantle **throat-to-floor, face only.** |
| `assets/looks/giovanna-day.png` | Day option (court neckline — not the high-neck sheet; keep unless regen). |
| `assets/looks/guido.png` | Master Guido. |
| `assets/looks/marco.png` | Master Marco. |
| `assets/looks/prinzivalle-camp.png` | **Master Prinzivalle face.** No text. |
| `assets/looks/prinzivalle-tent.png` | Same man, doublet / lamp. Match camp face; don't spawn a third. |
| `assets/looks/vedio.png` | Florentine clerk, papers, tent. |
| `assets/looks/trivulzio.png` | Working face only (costume still too martial vs Sutro commissioner). |
| `assets/looks/borso.png` | Supporting. |
| `assets/looks/torello.png` | Supporting. |

---

## Still locked (not style)

- Sutro 1904 word-for-word. US PD: `docs/pd-source.md`.
- Mantle visuals: implication only. If a gen opens the cloak: `nude, bare shoulders, cleavage, sheer cloak`.
- No captions, nameplates, Latin mottos, or "Oil Chronicle" banners **on the image**.
- Prinzivalle is **Gianello** (Venice childhood), not "ex amico di Guido."

---

## Next

Act I keyframes from these faces — **hold until Richard asks.**
