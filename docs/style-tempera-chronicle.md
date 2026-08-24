# Tempera Chronicle Visual Style

> **⚠️ SUPERSEDED:** This page is archived. New generations use **[Oil Chronicle](style-oil-chronicle.md)** style. See `docs/style-oil-chronicle.md` for current production style.

## Overview

**Tempera Chronicle** is the locked visual aesthetic for the *Monna Vanna* AI film adaptation. It evokes Renaissance fresco and early panel painting, creating a cinematic illustration style that is **stylized, painterly, and deliberately not photorealistic.**

This style is optimized for **Seedance 2**, which explicitly rejects photorealism in favor of artistic control and illustrative clarity.

## Why Seedance 2

Seedance 2 is designed to:
- Reject uncanny-valley hyperrealism
- Prioritize artistic composition and heroic staging
- Support illustrated, painterly, and hand-textured visual styles
- Avoid the depth-of-field bokeh and skin-pore obsession of photorealistic AI models

Tempera Chronicle leans into these strengths, treating each frame as a **painted history panel** rather than a simulated photograph.

## Master STYLE SUFFIX

**Every image prompt for this production MUST end with this exact STYLE SUFFIX:**

```
Tempera Chronicle style, Renaissance fresco-influenced cinematic illustration, painted history panel, tempera and oil texture, clear heroic staging, controlled brush planes, stylized not photoreal, illustrated film frame, late 15th-century Tuscany, ochre limestone iron-grey torch-amber palette, hard directional painted light, dignified moral clarity
```

### What This Suffix Does

- **"Tempera Chronicle style"** — Brands the look, anchors the aesthetic across all shots
- **"Renaissance fresco-influenced cinematic illustration"** — Signals painterly cinema, not photography
- **"painted history panel"** — Each frame is a composed illustration, like Ghirlandaio or Masaccio
- **"tempera and oil texture"** — Matte, chalky, hand-applied surface quality
- **"clear heroic staging"** — Figures are legible, dignified, not cluttered or naturalistic
- **"controlled brush planes"** — Deliberate, constructed depth, not simulated camera DOF
- **"stylized not photoreal"** — Explicit rejection of hyperrealism
- **"illustrated film frame"** — Cinema as moving painting
- **"late 15th-century Tuscany"** — Historical texture anchor (architecture, costume, lighting)
- **"ochre limestone iron-grey torch-amber palette"** — Earthy, warm stone, candlelit interiors, siege atmosphere
- **"hard directional painted light"** — Single-source drama (torch, candle, dawn), not soft fill
- **"dignified moral clarity"** — Maeterlinck's tone: noble, tense, morally serious

## Master NEGATIVE Prompt

**Every image prompt MUST include this NEGATIVE to reject unwanted aesthetics:**

```
photorealistic, hyperrealistic, DSLR photo, 8k skin pores, uncanny valley skin, CGI realism, modern photography, depth-of-field bokeh porn, romantasy soft glow, anime, manga, Disney, cartoon slapstick, neon, cyberpunk, modern clothing, smartphones, meme composition, glossy game render, oversexualized pose, nude explicit, lingerie, beauty-filter face
```

### Additional NEGATIVE for Mantle Scenes

When Giovanna appears in her mantle (Act II), **add these terms to the NEGATIVE** to enforce the throat-to-floor cloak with dignified implication only:

```
nude, bare shoulders, cleavage, sheer cloak, transparent fabric, exposed skin under mantle
```

### What the NEGATIVE Rejects

- **Photorealism:** "photorealistic, hyperrealistic, DSLR photo, 8k skin pores, uncanny valley skin, CGI realism"
- **Modern photography tropes:** "depth-of-field bokeh porn, beauty-filter face"
- **Wrong genres:** "romantasy soft glow, anime, manga, Disney, cartoon slapstick, neon, cyberpunk"
- **Anachronism:** "modern clothing, smartphones, meme composition"
- **Wrong tone:** "oversexualized pose, nude explicit, lingerie, glossy game render"

## Color Palette

**Ochre limestone iron-grey torch-amber:**

- **Ochre:** Warm earth, Tuscan clay, sunbaked walls
- **Limestone:** Pale stone, marble accents, Pisan architecture
- **Iron-grey:** Armor, shadows, siege exhaustion
- **Torch-amber:** Candlelight, braziers, dawn through shutters

Avoid:
- Neon or saturated digital colors
- Cool cyan-blue "cinematic" grading
- Soft pastel romantasy palettes

## Lighting

**Hard directional painted light:**

- Single dominant source (candle, torch, window)
- Strong shadows with clear edges (fresco tradition)
- No soft fill, no three-point studio lighting
- Chiaroscuro when dramatically appropriate (Caravaggio influence acceptable)

Avoid:
- Flat even lighting
- Soft-box beauty light
- Depth-of-field bokeh glow
- Lens flares or modern camera artifacts

## Composition & Staging

**Clear heroic staging:**

- Figures arranged for moral and dramatic legibility
- Frontal or three-quarter poses, not candid snapshots
- Deliberate symmetry or asymmetry (like a painted altarpiece or history panel)
- Architectural framing (doorways, columns, tent posts)

Avoid:
- Casual snapshot composition
- Over-the-shoulder shaky-cam realism
- Cluttered backgrounds
- Meme-style reaction framing

## Texture & Surface

**Tempera and oil texture, controlled brush planes:**

- Matte, chalky surface (egg tempera feel)
- Visible brushwork acceptable, but controlled (not impasto chaos)
- Depth through overlapping planes, not DOF blur
- Cloth folds like Botticelli or Ghirlandaio (structured, not photographic drape)

Avoid:
- Glossy digital render sheen
- Soft airbrushed gradients
- Photographic fabric simulation
- Uncanny-valley skin detail

## Mantle Visual Rules

When depicting Giovanna's mantle (Act II):

1. **Cloak is throat-to-floor** — covers from neck to feet
2. **Heavy fabric** — wool or velvet weight, opaque
3. **Implication only** — the moral weight is in what is *not shown*
4. **Dignified, not titillating** — Maeterlinck's intent is sacrifice and vulnerability, not spectacle

**NEGATIVE must include:** nude, bare shoulders, cleavage, sheer cloak, transparent fabric, exposed skin under mantle

## Reference Touchstones

**Visual ancestors (for vibe, not direct copying):**

- **Domenico Ghirlandaio** — Clear staging, Florentine interiors, dignified figures
- **Masaccio, *Brancacci Chapel*** — Serious, heroic, morally weighted
- **Piero della Francesca** — Geometric clarity, controlled light
- **Early Botticelli** (before *Primavera*) — Structured folds, noble restraint
- **Benozzo Gozzoli** — Processional clarity, Tuscan palette

**NOT:**
- Romantic academic painting (too soft, too sentimental)
- Baroque drama (too dynamic, too fleshy)
- Pre-Raphaelite (too detailed, too literal)
- Fantasy book covers (too glossy, too modern)

## Paste-Ready Template

For any new shot prompt, structure it like this:

```
[SHOT DESCRIPTION: character action, setting, mood]

[CHARACTER DETAILS from looks/characters.md if relevant]

[SPECIFIC COMPOSITION NOTES: angle, framing, light source]

Tempera Chronicle style, Renaissance fresco-influenced cinematic illustration, painted history panel, tempera and oil texture, clear heroic staging, controlled brush planes, stylized not photoreal, illustrated film frame, late 15th-century Tuscany, ochre limestone iron-grey torch-amber palette, hard directional painted light, dignified moral clarity

NEGATIVE: photorealistic, hyperrealistic, DSLR photo, 8k skin pores, uncanny valley skin, CGI realism, modern photography, depth-of-field bokeh porn, romantasy soft glow, anime, manga, Disney, cartoon slapstick, neon, cyberpunk, modern clothing, smartphones, meme composition, glossy game render, oversexualized pose, nude explicit, lingerie, beauty-filter face
```

## Do Not Deviate

This style lock is **director-approved and final.** Do not:
- Substitute "cinematic" for photorealistic grading
- Add modern photography tropes (bokeh, lens flares, shallow DOF)
- Soften the palette into romantasy pastels
- Introduce anime, Disney, or cartoon influences
- Chase hyperrealism or 8K skin-pore detail

The goal is **illustrated film** — cinema as moving painting, not simulated photography.
