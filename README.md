<p align="center">
  <img src="assets/vregister-01-hero.svg" alt="VRegister by VACK Studio — authentic VACK logo, small Zoiila mascot and Folia compatibility overview" width="100%" />
</p>

# VRegister

**Account registration and login management for Folia 1.21.11.** VRegister is commercial software by **VACK STUDIO**. According to the project's published description, it manages account registration, BCrypt password hashes, SQLite accounts and login sessions. Supported cracked Java clients receive native Java Dialogs before world entry.

> [!IMPORTANT]
> **Commercial / proprietary release.** This repository is a public presentation and product-information page. It does **not** contain VRegister's installable JAR or source code. Distribution and usage require separate written authorization from VACK STUDIO.

## Access routes

<p align="center">
  <img src="assets/vregister-02-client-routes.svg" alt="Diagram of the three documented access routes: native Java dialogs for supported cracked clients, FastLoginPlusFolia ownership verification for Premium, and VRegister bypass for Floodgate Bedrock" width="100%" />
</p>

VRegister presents registration/login dialogs to **supported cracked Java players**. Premium ownership verification is delegated to the matching **FastLoginPlusFolia** bridge. **Floodgate Bedrock** users bypass VRegister.

## Accounts and sessions

<p align="center">
  <img src="assets/vregister-03-account-state.svg" alt="Technical information graphic listing BCrypt password hashes, SQLite account persistence and login session management" width="100%" />
</p>

The public repository describes these functions, but does not disclose internal schemas, implementation details or customer credentials.

## Compatibility and verification

<p align="center">
  <img src="assets/vregister-04-compatibility.svg" alt="Compatibility sheet specifying Folia 1.21.11, Java 21 build target, Java 25 project environment and FastLoginPlusFolia bridge, plus current test status" width="100%" />
</p>

| Item | Published requirement or status |
| --- | --- |
| Folia | **1.21.11** |
| Java | **21 target**; project's Folia environment runs **Java 25** |
| Premium bridge | **FastLoginPlusFolia** `0.7.0-vregister.1-2c5808e` |
| Bridge dependency | **ProtocolLib** required by FastLoginPlusFolia |
| Source build / local unit tests | **Passed**, as reported for VRegister 1.0.0 |
| Live client acceptance | **Not completed** for Premium, cracked, legacy and Bedrock clients in the reported workspace |

<details>
<summary><strong>Actual in-game screenshots — evidence still needed</strong></summary>

The public repository does not currently include screenshots of the real plugin UI. Once captured from a **non-production Folia test server**, we can show the genuine screens here without fabricating gameplay or authentication dialogs.

Suggested captures: the native registration dialog, the login dialog, and a post-login screen or safe administrator status view. Use a throwaway test account and **never include passwords, authentication codes, server secrets or real player data**. Capture the Java client with **F2** while the dialog is visible and share the original PNGs.

Until those are supplied, the four informational banners above use only the current public README's claims; they are not screenshots.

</details>

## Availability

VRegister is **paid software**. Source access and installable builds are distributed privately to VACK STUDIO-approved accounts. To request access or discuss commercial terms, use the official VACK channels below. This repository does not grant redistribution or publication rights.

---

<p align="center">
  <img src="assets/vregister-05-proudly-crafted.svg" alt="Proudly crafted by VACK STUDIO with original VACK logo and tiny Zoiila-and-Chick author signature at the lower right" width="100%" />
</p>

<p align="center">
  <a href="https://builtbybit.com/members/vack-studio.891381/#latest-activity" aria-label="BuiltByBit profile"><img src="assets/builtbybit.svg" alt="BuiltByBit" width="23" height="23" /></a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://discord.gg/y45brtZBEE" aria-label="VACK Studio Discord"><img src="assets/discord.svg" alt="Discord" width="23" height="23" /></a>
</p>

<details>
<summary><strong>License &amp; rights — VACK STUDIO</strong></summary>

Copyright © 2026 VACK STUDIO. All rights reserved.

VRegister and its original documentation and artwork are proprietary. No permission to copy, modify, distribute, sublicense, resell or publish is granted without prior written authorization. Third-party components retain their own licenses.

Read the authoritative [LICENSE](LICENSE) for the complete legal notice.

</details>

<sub>Presentation artwork: source-backed, non-generative SVG. The five banners are informational graphics; no login UI or gameplay screenshot has been invented. <a href="docs/DESIGN-AUDIT.md">Design provenance and QA notes</a>.</sub>
