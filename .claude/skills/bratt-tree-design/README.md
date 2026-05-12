# Bratt Tree Company — Design System

> Professional tree services for healthier, safer landscapes. Certified arborists. Clear pricing. Family-owned since 1991.

This folder is the **design system + brand kit** for Bratt Tree Company. It captures the visual foundations, typography, color, iconography, and reusable UI components you need to design anything on-brand: marketing pages, decks, social posts, vehicle wraps, internal docs.

It is built from the official brand package delivered by **KickCharge Creative** (the "Legendary Home Service Branding" firm Bratt Tree hired in 2024–25).

---

## Index

| File | What it is |
|---|---|
| `README.md` | This file. Brand context + content + visual foundations + iconography. |
| `SKILL.md` | Agent-Skill manifest — lets Claude Code load this as a packaged skill. |
| `colors_and_type.css` | All design tokens: colors, type scale, spacing, radii, shadow, motion. |
| `fonts/` | Webfont fallbacks + notes on the licensed brand fonts. |
| `assets/` | Logos, mascot, badges, watermark, raster brand art. |
| `preview/` | Small HTML cards that populate the Design System tab in this project. |
| `_source/` | Original source files (brand guide PDF, launch-meeting PPTX, font specimens). Reference only — not for direct use. |

## Sources used to build this system

- `1_Branding & Logos/bratt-tree-logo-guide-book.pdf` — the official KickCharge brand book (12 pp). The authoritative source for logo color values, type names, safe-zone rules, misuse, and file formats. Copied to `_source/` for reference.
- `1_Branding & Logos/Branding Launch Meeting.pptx` — the internal slide deck Connor Bratt used to roll out the new brand internally. Provides the company history and rebrand narrative below. Copied to `_source/`.
- `1_Branding & Logos/logo/`, `logotype/`, `mascot/`, `mascot circle/` — every approved logo variant (PNG, JPG, EPS, PDF) in full-color, 1-color, and grayscale. Web-resolution PNGs are copied to `assets/`.
- `1_Branding & Logos/Stationary/` — letterhead, business cards, envelope artwork (AI + bleed PDFs). Not embedded — included by reference.
- `1_Branding & Logos/Vehicle Wraps/` — vehicle-wrap layouts for the company fleet (Ford Escape, etc.).

No website codebase or Figma file was provided — the brand-system rules here come straight from the supplied brand book and assets. The live Bratt Tree website (`www.bratttree.com`) is the canonical UI reference.

---

## Company Context

Bratt Tree Company is a family-owned, full-service tree care firm.

- **Founded:** 1991 by Jon Bratt.
- **Current ownership:** In 2017 Connor (Jon's son-in-law) bought the company and has been growing it aggressively since.
- **M&A:** Several smaller local tree companies have been folded into the Bratt Tree umbrella over the years.
- **Services:** Tree trimming, tree removal, stump grinding, cleanup, storm response.
- **Credentials:** Fully licensed and insured. ISA-Certified arborists on staff.
- **Positioning:** "Professional. Trusted. Family-owned. The top shop in town." Premium-but-friendly — not the cheapest, but the most professional, with the best equipment.
- **Rebrand motivation:** Per the launch deck — "All of the tree companies look the same: green tree + block letters. We wanted something special." KickCharge delivered a mascot-driven, badge-style identity that reads more like a beloved old-school home-services brand (think Mike's Carpet Cleaning, Stanley Steemer) than a generic landscaping vendor.

---

## CONTENT FUNDAMENTALS

The Bratt Tree voice is **warm, direct, and proud of the craft**. It sounds like a neighbor who happens to know everything about trees — not a corporate landscaper, not a startup, not a folksy stereotype.

### Tone

- **Friendly, confident, plain-spoken.** Short declarative sentences. No marketing fog.
- **Trade-pride.** They are arborists, climbers, and operators of serious equipment — the copy can lean into that without bragging.
- **Local & familial.** "Family-owned since 1991." "Your neighborhood arborists." It is OK to drop "we" and "our crew" liberally.
- **Reassuring on safety.** Licensed, insured, ISA-Certified, guaranteed — these are repeated trust signals. Lean on them in any decision-point copy (quotes, CTAs, footer).
- **Never cute, never twee.** The mascot is the cute part. The words are workmanlike.

### Casing

- **Headlines & buttons: TITLE CASE** or, for short emphatic blocks, **ALL CAPS** (matches the logo's "BRATT TREE / TREE SERVICE" treatment).
- **Body: sentence case.**
- **Banner / ribbon labels: ALL CAPS** with extra letter-spacing (echoes the orange "TREE SERVICE" ribbon).

### Person

- **We / our / us** for the company. ("We've been doing this since 1991." "Our crew shows up on time, in uniform, with the right gear.")
- **You / your** for the customer. ("Your trees deserve a real arborist." "Get your free estimate.")
- Avoid third-person corporate voice ("Bratt Tree Company provides…"). Use it only in legal / press copy.

### Specific examples (real-feeling, on-brand)

| Surface | Voice |
|---|---|
| Hero headline | **TREES ARE OUR BUSINESS. SAFETY IS OUR PROMISE.** |
| Subhead | Family-owned since 1991. ISA-Certified arborists, clear pricing, and a crew that cleans up after itself. |
| CTA primary | **GET A FREE ESTIMATE** |
| CTA secondary | See what we do → |
| Trust strip | LICENSED • INSURED • ISA-CERTIFIED • SATISFACTION GUARANTEED |
| Service-card body | When a storm rolls through, we're the call you make at 5 AM. 24/7 emergency response across the metro. |
| About snippet | Three generations of climbers, one phone number. |
| Quote-confirm | Thanks — we got it. A real human will call you back within the business day. |
| 404 | Looks like that branch isn't here. |

### Things to avoid

- ❌ Buzzwords ("synergistic," "holistic tree-care solutions").
- ❌ Emoji in marketing copy (the brand uses iconographic illustration instead; see ICONOGRAPHY).
- ❌ Aggressive sales urgency ("ACT NOW!! 50% OFF!!"). The brand is premium-but-approachable.
- ❌ Stock photography of generic businesspeople. Use real crew, real trucks, real trees.

---

## VISUAL FOUNDATIONS

The Bratt Tree visual identity is **"badge & mascot"** — a deliberate counter-trend to the flat-green-tree-plus-block-letters that dominates the trade. It reads loud, retro, hand-made, and friendly.

### Colors

The palette is **warm, woody, and confident**, anchored on three poles:

1. **Wood-grain dark brown** (`--bt-bark` `#26190E`) — the panel background of the logo. Used for surfaces, hero blocks, footers. Functions as the brand's "black."
2. **Signature orange** (`--bt-orange` `#EB4C1B`) — the ribbon, CTAs, primary accent. High-energy, used sparingly so it pops.
3. **Sun-bright yellow-green keyline** (`--bt-lime` `#E9E71D`) — the outer halo around every logo lockup. Functions as the brand's "highlight" — small, glowing, always paired with a dark stroke.

Supporting woods (rust, clay, tan, sand) come from the bark-grain palette and read as natural, organic, lived-in. Cool teals (`#0096AA`, `#188CB2`) appear only in the halftone-dot pattern inside the mascot circle — treat them as accent-only.

### Typography

- **Display:** *Rugfish* — heavy, slightly distressed, hand-lettered. Used for `BRATT TREE`. Echoes a vintage shop-sign feel. **Installed** via `@font-face` (see `fonts/RugFishRegular.otf`).
- **Headline / signage:** *Nunito* (heavy 900) — the brand's chosen headline face. Used for section titles, the "TREE SERVICE" ribbon, signage. Rounded humanist sans that pairs cleanly with the heavy Rugfish display and the warm wood palette without competing.
- **Body:** No specific body face shipped with the brand kit — we use *Nunito* as a friendly humanist sans that pairs with the warm woods without competing.
- **Casing:** all-caps + tight tracking for display; sentence case + relaxed tracking for body.
- See `fonts/README.md` — Google Fonts substitutes are in use; flag if pixel fidelity matters.

### Spacing & rhythm

- **8-px base grid.** Tokens `--space-1` (4) through `--space-10` (128). Most layouts breathe with `--space-6` (32) or `--space-7` (48) between sections.
- **Generous vertical padding** on hero / section blocks — this is a confident brand, not a packed corporate site.
- Section gutters: 64–96 px on desktop, 32 px on mobile.

### Backgrounds

- **Solid cream** (`--bt-cream` `#FFF8EC`) is the default page background — a paper-bag warmth that flatters the wood palette.
- **Solid dark brown** (`--bt-bark`) panels and footers — high contrast, the brand's preferred "dark mode."
- **Halftone dot textures** in teal — used as accent inside circular badges and behind mascots, never as full-page wallpaper.
- **Wood-grain raster** — only inside the logo panel. Don't try to recreate it on the page; reference imagery of real wood (the watermark in `assets/watermark.png` is the only stock pattern).
- **No gradients.** This brand is explicitly anti-gradient — flat fills, hard edges, weighty outlines. The only "gradient" allowed is a soft cream→bone for very subtle paper depth.

### Borders & outlines

- **Heavy dark outlines** are a signature — almost every brand element sits inside a `2–4 px` `--bt-ink` stroke, often with a `--bt-lime` outer keyline ring (see `--sh-keyline`).
- **Pill / shield shapes** with rounded `22–32 px` radii echo the logo silhouette.
- **No 1-px hairlines on hero or marketing surfaces** — they read flimsy against this palette. Use them for table dividers in dense UI only.

### Shadows & elevation

- **Stamped/badge shadow** — a `6 px` offset matte shadow plus a soft drop (`--sh-badge`) makes cards feel die-cut and stuck to the page.
- **Generic card** uses `--sh-2` for a calm, paper-weight lift.
- **No glassy / glossy / neumorphic shadows.** This is a sign-shop brand, not a fintech.

### Corner radii

- **Buttons / inputs:** `--r-3` (14 px) — friendly without being cute.
- **Cards:** `--r-4` (22 px) — echoes the badge silhouette.
- **Logo badges & hero shields:** `--r-badge` (32 px).
- **Pills:** full radius `--r-pill`.

### Cards

The canonical Bratt Tree card matches the live website:
- **Fill:** white → soft yellow vertical gradient (`linear-gradient(180deg, #FFFFFF 0%, #FBF5C8 100%)`) — subtle paper depth, white at top, warming downward.
- **3 px lime keyline** (`--bt-lime` `#E9E71D`) — echoes the outer halo on the logo.
- **18 px corners.**
- **No drop shadow.** Cards are flat — the lime keyline does the visual lifting against the dark wood background.
- **Title:** Nunito 900, dark brown (`#3D2B14`), sentence/title case.
- **Body:** Nunito 400, warm brown (`#4A3826`), ~14 px.
- Featured / accent variant: swap the lime keyline for `--bt-orange` keeping everything else identical.

### Hover / press states

- **Hover:** darken the fill 5–8% (`--accent-hover`). For ghost (outlined) buttons, invert: fill the button with ink, drop the outline. **No translate, no shadow lift** — buttons stay flat and planted.
- **Press:** darker still (`--accent-press`). A subtle `0.98` scale is OK; no shadow tricks.
- **Focus:** `3 px` `--bt-lime` outer outline, `2 px` offset. Visible, on-brand, and accessible.

### Animation

- **Sparing and snappy.** `--t-fast` (120 ms) for hover, `--t-base` (200 ms) for entrances.
- **Easing:** `--ease-out` for nearly everything; `--ease-bounce` only on mascot reveals or playful confirmations.
- **No parallax. No long fade-ins. No scroll-jacking.** The brand is confident and direct.

### Transparency & blur

- Used **rarely**. The brand is opaque, weighty, sign-painted.
- Acceptable: a 90% dark-brown veil over a photographic hero so headline text reads. Avoid backdrop-blur, frosted-glass, etc.

### Imagery vibe

- **Warm, sunny, mid-day**, slight saturation boost. Real trucks, real crew in red/orange plaid + safety yellow + dark denim — the mascot's outfit echoes how the actual crew should appear.
- **No black & white**, no cool/blue grading, no moody nighttime tree photos.
- **Grain:** light film grain OK on hero photography. Halftone dots OK as an illustrative overlay.

### Layout rules

- **Sticky top nav** with brown background + cream type — high contrast, always present.
- **Anchored CTA** (orange pill) in the top right of the nav.
- **Trust-strip ribbon** directly under the hero — always orange, always all-caps.
- **Footer** is always the dark wood brown with a mascot watermark.

---

## ICONOGRAPHY

Bratt Tree does **not** use a generic icon library out of the box. The brand book treats illustration as a first-class asset (the mascot is the centerpiece). For UI work, we adopt a **two-tier approach**:

1. **Brand illustrations / mascot** — use the supplied PNG assets in `assets/`. These are the hero visuals.
2. **Functional UI icons** — use **Lucide** (CDN) as a substitute for any small inline UI iconography (nav, form, status). Lucide's friendly, mid-stroke, rounded-cap style pairs cleanly with the warm-but-confident brand without fighting the badge aesthetic.

### What's in `assets/`

| File | Purpose |
|---|---|
| `logo-color.png` | Primary signature — mascot + wordmark + ribbon. Use on cream or dark surfaces. |
| `logotype-color.png` | Wordmark + ribbon only (no mascot). Use when the mascot reads as redundant. |
| `mascot-color.png` | The bear-with-chainsaw mascot alone. Marketing accents, social. |
| `mascot-circle-color.png` | Mascot inside the teal-halftone circle. Social profile avatars, badges. |
| `logo-color-flat.jpg` | JPG version of the primary logo on white. Use only where transparency is impossible. |
| `social-1080.jpg` | Square social profile (1080×1080) — Instagram, Facebook avatars. |
| `logo-grayscale.jpg` / `mascot-grayscale.jpg` | Single-color versions for newspaper, fax, embroidery. |
| `watermark.png` | Subtle wordmark watermark for backgrounds and stationery. |

### Iconography rules

- **No emoji** in marketing or product copy. The brand has its own visual language — use the mascot or an illustration before reaching for ✅ or 🌳.
- **No hand-drawn one-off SVGs** that compete with the logo's distressed style — they will fight the mascot. Stick to Lucide for UI.
- **Stroke weight:** Lucide default (1.5 px at 24 px). Color: `currentColor` so it inherits the dark-brown ink color by default.
- **Sizes:** 16, 20, 24, 32 — never finer. The brand is bold; sub-16 px icons read as ornamental, not informational.
- **Unicode glyphs / arrows:** OK in tight inline contexts (`→`, `↗`, `✓`). Always in the dark-ink color, never colored.
- **For service-tier illustrations** (a tree, a stump, a chainsaw, a truck): commission them in the mascot's style — heavy outlines, flat fills, sunny palette. Do not generate them in this kit.

---

## Caveats for designers

- Font substitution is partly resolved: **Rugfish is installed**. **Fagun is still substituted** with `Alfa Slab One`. Drop the licensed Fagun file in `fonts/` for full pixel fidelity.
- The brand book gives logo and color authority. Spacing, motion, hover states, and component rules are *consistent with the brand voice* but were extended for digital UI — cross-check against `www.bratttree.com` when in doubt.
