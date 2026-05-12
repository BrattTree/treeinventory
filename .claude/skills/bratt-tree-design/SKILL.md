---
name: bratt-tree-design
description: Use this skill to generate well-branded interfaces and assets for Bratt Tree Company (family-owned professional tree service in the Twin Cities, "Legendary Home Service Branding" by KickCharge), either for production or throwaway prototypes/mocks/decks/social. Contains essential design guidelines, colors, type, fonts, logos, and mascot art. The live website at www.bratttree.com is the canonical UI reference.
user-invocable: true
---

Read the `README.md` file within this skill, and explore the other available files (`colors_and_type.css`, `assets/`, `preview/`, `fonts/`, `SKILL.md`).

If creating visual artifacts (slides, mocks, social posts, throwaway prototypes), copy assets out of `assets/` and create static HTML files for the user to view — link `colors_and_type.css` for tokens, and reference component patterns in `preview/` for canonical button/card/ribbon styling. For full marketing-site UI reference, look at the live site at **www.bratttree.com** — the design system here pairs with that as canonical UI.

If working on production code, you can copy assets and read the rules here to become an expert in designing with this brand. Honor the brand book exactly: the orange / lime / bark color triad, the heavy-outline + drop-shadow "badge" aesthetic, ALL-CAPS display type, and "warm, plain-spoken neighbor" voice. Never reach for emoji, gradients, or generic stock imagery — the mascot and brand illustrations are the voice.

If the user invokes this skill without other guidance, ask them what they want to build or design, ask a few clarifying questions about audience and surface, and act as an expert designer who outputs HTML artifacts or production code depending on the need.

Known caveats to flag to the user:
- The licensed **Rugfish** display font is installed (`fonts/RugFishRegular.otf`). **Nunito** (Google Fonts) handles the headline and body roles per brand owner.
- For any UI question not answered by the brand book or this system, defer to **www.bratttree.com** as the canonical source of truth.
