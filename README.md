<p align="center">
  <img src="assets/vregister-01-hero.svg" alt="VRegister by VACK Studio, with the VACK logo and Mini Zoiila mascot" width="100%" />
</p>

# VRegister <img src="assets/emoji/mini-zoiila-wave.png" alt="Mini Zoiila waving" width="29" height="29" />

**Account registration and login for [Folia 1.21.11](https://github.com/PaperMC/Folia).** VRegister gives supported Java players native Minecraft Register and Login Dialogs, BCrypt password hashing, SQLite account storage and managed login sessions.

> [!IMPORTANT]
> **Commercial plugin.** VRegister is proprietary software by **VACK STUDIO**. This public repository contains product information only; the source and installable JAR are distributed privately under written authorization.

## How authentication works

**Which sign-in flow will a player see?** <img src="assets/emoji/mini-zoiila-thinking.png" alt="Mini Zoiila thinking" width="24" height="24" />


<p align="center">
  <img src="assets/vregister-02-client-routes.svg" alt="VRegister connection paths for Java, verified Premium accounts and Floodgate Bedrock clients" width="100%" />
</p>

<table>
  <tr>
    <td align="center" width="54"><a href="https://github.com/openjdk/jdk"><img src="assets/openjdk-mark.svg" alt="OpenJDK" width="32" height="32" /></a></td>
    <td><strong>Java Edition</strong> — supported offline-mode players use VRegister's registration/login Dialogs. Premium verification is handled by the required <a href="https://github.com/Hayston1001/FastLoginPlus">FastLoginPlusFolia</a> bridge.</td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/GeyserMC/Geyser"><img src="assets/geyser-icon.png" alt="GeyserMC" width="32" height="32" /></a></td>
    <td><strong>Bedrock Edition</strong> — players connected through <a href="https://github.com/GeyserMC/Geyser">Geyser</a> and recognized using the official <a href="https://github.com/GeyserMC/Floodgate">Floodgate</a> API bypass VRegister's Java authentication screens.</td>
  </tr>
</table>

## In-game dialogs

<table>
  <tr>
    <td width="50%" align="center">
      <strong>Register Dialog</strong>
      <a href="assets/screenshots/register-dialog.jpg"><img src="assets/screenshots/register-dialog.jpg" alt="VRegister registration Dialog with password and confirmation fields" width="100%" /></a>
    </td>
    <td width="50%" align="center">
      <strong>Login Dialog</strong>
      <a href="assets/screenshots/login-dialog.jpg"><img src="assets/screenshots/login-dialog.jpg" alt="VRegister login Dialog with password field" width="100%" /></a>
    </td>
  </tr>
</table>

**Automatic login confirmation**

<p align="center">
  <a href="assets/screenshots/auto-login-chat.png"><img src="assets/screenshots/auto-login-chat.png" alt="Minecraft chat with VRegister's Auto logged in message" width="685" /></a>
</p>

## Accounts and sessions

<p align="center">
  <img src="assets/vregister-03-account-state.svg" alt="BCrypt password hashing, SQLite account persistence and login-session management" width="100%" />
</p>

VRegister uses **BCrypt** for password hashes and **SQLite** to store accounts, with sessions controlling authenticated access.

## Compatibility

<p align="center">
  <img src="assets/vregister-04-compatibility.svg" alt="Folia, Java and FastLoginPlusFolia requirements, with VRegister test status" width="100%" />
</p>

| Component | Version or requirement |
| --- | --- |
| VRegister | **2.2.0** |
| Server | [Folia 1.21.11](https://github.com/PaperMC/Folia) |
| Java | Build target **Java 21**; staging environment reported using Java 25 |
| Required Premium bridge | VRegister-specific patched [FastLoginPlusFolia](https://github.com/Hayston1001/FastLoginPlus), `0.7.0-vregister.1-2c5808e` (plugin name: `FastLoginPlus`) |
| Bridge dependency | [ProtocolLib](https://github.com/dmulloy2/ProtocolLib); **5.4.0** used in staging |
| Optional integrations | [Floodgate](https://github.com/GeyserMC/Floodgate) and [ViaVersion](https://github.com/ViaVersion/ViaVersion) |

### Notes

The VRegister-specific FastLoginPlusFolia bridge includes configuration-phase authentication support missing from stock 0.7.0 builds. Install the matching bridge and verify the dependencies before allowing players to connect. <img src="assets/emoji/mini-zoiila-teacher.png" alt="Mini Zoiila teaching" width="24" height="24" />

### Verification status

The VRegister 2.2.0 build and **6 unit tests** passed in the reported staging build. The patched FastLoginPlusFolia build passed **163 upstream tests and 5 bridge tests**, with 2 upstream tests skipped.

The Register and Login Dialogs and automatic-login message have been observed in a Java client. Full authentication acceptance, including Premium verification, legacy clients and optional Floodgate/Bedrock support, is still pending.

## Availability

VRegister is **commercial software**. Installable builds and source access are provided privately to VACK STUDIO-approved customers. For access and license terms, use the official links below.

---

<p align="center">
  <img src="assets/vregister-05-proudly-crafted.svg" alt="Proudly crafted by VACK STUDIO, with the VACK logo and Zoiila and Chick signature" width="100%" />
</p>

<p align="center">
  <a href="https://builtbybit.com/members/vack-studio.891381/#latest-activity" aria-label="BuiltByBit"><img src="assets/builtbybit.svg" alt="BuiltByBit" width="23" height="23" /></a>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://discord.gg/y45brtZBEE" aria-label="Discord"><img src="assets/discord.svg" alt="Discord" width="23" height="23" /></a>
</p>

<details>
<summary><strong>License &amp; rights — VACK STUDIO</strong></summary>
 
Copyright © 2026 VACK STUDIO. All rights reserved.

The plugin, documentation and original artwork are proprietary. Redistribution, modification or publication requires prior written authorization. See the full [LICENSE](LICENSE).

</details>
