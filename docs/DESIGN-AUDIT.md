# VRegister README design audit

## Purpose
Make the real, commercial `zoiila/VRegister` GitHub page reflect the approved VACK source-first design. This is **presentation-only**; this public repository has no plugin binary or source code.

## Grounding
All VRegister claims in the banners and README come from the previous public `README.md` at commit `30ecc95007912806f82c2b6f188da0f624e4a7d2`. The proprietary `LICENSE` is untouched. The marketing page does not represent independent test evidence.

## Asset provenance
- Real VACK logo (embedded PNG) from the owner's approved VACK GitHub Skill Lab v24 Hero.
- Real tiny Zoiila B Edge Sitter (embedded PNG) from the same approved Hero.
- Approved VACK v24 **Proudly Crafted** author-signature footer copied unchanged.
- BuiltByBit and Discord brand SVGs from the previously approved VACK presentation assets.
- The old `assets/vregister-banner.svg` is preserved for comparison.
- All newly authored banner layout and text use deterministic SVG; no AI image generation.

## Editorial choices / anti-slop QA
- Typography-led hero and three *different* content structures: three access routes, technical responsibility ledger and compatibility verification sheet.
- Original branding only. Restrained slate and muted violet; no fake user-interface screenshots, fake API credentials or generic product feature tiles.
- Use a readable layout at narrow README widths. SVG text uses Inter/Arial fallbacks; final live GitHub browser Dark/Light and mobile tests remain open.
- Real Java screenshot evidence is **not available** in the public repo. Do not convert placeholders to invented images.

## Acceptance before merge
- [ ] Review all five banner renders on GitHub in Dark and Light, and small mobile widths.
- [ ] Confirm authentic logo and small mascot alignment, no clipping or broken fonts.
- [ ] Confirm legal notice identical to the original `LICENSE`.
- [x] Add authentic client captures after verifying no password is visible; maintain originals separately.
- [ ] Confirm external links and selected exact version/build values with the plugin maintainer.
- [ ] Receive user approval to merge.

## Design references
Used the publicly documented critique and anti-AI-slop principles from `pbakaus/impeccable` for manual review; did not install or execute an unverified CLI in this repository.


## 18 November 2026 — Real client captures and art refinements

- The owner supplied the real Minecraft Java **Register Dialog**, **Login Dialog**, and the **Auto logged in** chat message. Stored two quality-optimized JPEG display copies at 720 px width and the unchanged original PNG chat snippet; original screenshots retained outside the public repo.
- These images show client UI and the message, **not independent proof** of every Premium/cracked/legacy/Bedrock authentication path.
- The user's artifact report established VRegister 2.2.0 and patched FastLoginPlusFolia compilation and unit tests; these are documented as reported evidence, not re-run here.
- Moved the original embedded Zoiila mini mascot up to sit closer to the hero card top edge. Authentic skin and logo pixels unchanged.
- Introduced restrained warm gold, sea-green, mint, teal and blue in addition to the core VACK violet/white typography.
- Added blue GitHub links to verified upstream FastLoginPlus, Floodgate, Geyser, ProtocolLib and Folia. The links are in Markdown rather than SVG `img` because GitHub SVG images are not reliable clickable maps.
- Added official GeyserMC icon copied from `GeyserMC/Geyser/core/src/main/resources/assets/geyser/icon.png` for the Floodgate/Bedrock route; **not a fabricated Mojang Bedrock logo**.
- Added CC0 SQLite/OpenJDK visual marks from `simple-icons/simple-icons` and manually drawn minimal lock/session symbols, without AI image generation.
- Actual browser GitHub dark/light and narrow-width visual inspection remains **NOT TESTED**.
