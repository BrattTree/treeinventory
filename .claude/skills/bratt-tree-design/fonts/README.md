# Fonts

The original Bratt Tree brand fonts are commercial licenses and **not redistributable** in this design-system folder.

| Brand role | Font | Status |
|---|---|---|
| Logo / display | **Rugfish** (`RugFishRegular.otf`) | ✅ Installed, wired via `@font-face` in `colors_and_type.css` |
| Headline / signage | **Nunito** (Google Fonts, weight 900) | ✅ Headline role — brand-approved |
| Body / UI | **Nunito** (Google Fonts, 400/600/700/800) | ✅ Body role |

**Rugfish** is the brand's signature distressed display face — used on the `BRATT TREE` wordmark and any oversized signage. It's the one font you *must* use to be on-brand.

**Fagun** (the brand book's stated headline face, used on the "TREE SERVICE" ribbon) is still substituted. If you have the Fagun license file (from Adobe Fonts or otherwise), drop it here and add an `@font-face` block to `colors_and_type.css`:

```css
@font-face {
  font-family: "Fagun";
  src: url("fonts/Fagun-Regular.woff2") format("woff2");
}
```

The `--font-headline` stack already lists Fagun ahead of the substitute, so installation is a one-line job.
