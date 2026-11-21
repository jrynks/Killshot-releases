# Killshot beta

**Experimental unsigned tester beta. Not production-qualified. Formal
legal/privacy and independent Responsible AI launch reviews are pending.**

Turn project evidence into workshop decisions, a reviewed PRD and a live VS Code
coding workspace.

Killshot brings Preparation, Discover, Disrupt, Design, Develop and Preview into
one encrypted desktop workspace. Keep source citations close to decisions, explore
grounded and inferred concepts in Brain, work on canvases, and use Artemis, Chat,
Swarm and Assemble to move the work forward with human review.

## In this beta

- Artemis guides you through 22 short steps in five chapters, from setup to a
  first-project readiness check. Extra detail is optional.
- Workshop child-note arrows prefer straight paths and fewer turns around cards,
  without moving your notes.
- Global and Project settings group related controls into cards and section tabs.
  **Change model** opens the primary model picker; the Skills library shows each
  workflow once in a connected, numbered step path.
- Model-assisted workshops, research and conversations with visible activity.
- Recording/transcription review against originals before sharing.
- A live VS Code connection rather than an exported Build Kit.
- Bundled Killshot extension 0.1.3, using Copilot tools and MCP instead of the
  deprecated `@killshot` chat participant.
- Optional project-level VS Code AI sharing between connected peers.
- Project backups, recovery keys and permission-controlled peer collaboration.
- A separately consented safety evaluator; its pass is not an accuracy guarantee.

## Downloads

The tester prerelease is **v0.1.0-beta.3** for **Windows x64** and **Linux x64**.
macOS, Microsoft Store and Mac App Store distribution are not part of this launch.

Get the installers from the [versioned release](https://github.com/jrynks/Killshot-releases/releases/tag/v0.1.0-beta.3):

| Platform | Asset |
| --- | --- |
| Windows x64 | `Killshot-0.1.0-beta.3-win-x64.exe` |
| Linux x64 | `Killshot-0.1.0-beta.3-linux-x86_64.AppImage` |
| Verification | `SHA256SUMS.txt` and required third-party notices/materials |

Use the [releases page](https://github.com/jrynks/Killshot-releases/releases),
not `/releases/latest`, to find beta prereleases. This is a downloads-only
repository; application source is not published here.

## Before installing

- Read the [evaluation terms](LICENSE) and [tester data-handling notice](PRIVACY.md).
  Use fictional or synthetic material only, not personal, confidential, regulated
  or business-critical data. Formal launch reviews are pending.
- Both installers are unsigned. Automated checks run on Windows Server 2022 and
  Ubuntu 24.04 x64; this is not a claim that every consumer OS or upgrade path has
  been qualified. Report compatibility problems without sensitive attachments.
- Compare the exact download with `SHA256SUMS.txt`. Checksums detect changed bytes;
  they do not establish publisher identity. Unsigned Windows builds can trigger
  SmartScreen or organizational blocks. If blocked, stop and request review rather
  than disable protections.
- On Linux, make the verified AppImage executable and run it. Keep a working,
  unlocked GNOME Keyring or KWallet; setup stops if protected storage is unavailable.
  The binary uses the Ubuntu 24.04 runtime baseline. Older distributions may not
  load its native components. User namespaces must also be permitted. Ubuntu 24.04 may need an
  administrator-approved AppArmor profile for the specific AppImage. Killshot
  refuses to run with Chromium sandboxing disabled; do not disable system protections.
- Choose a primary connection and a different, separately consented safety evaluator.
  Killshot for VS Code remains the default. Eligible ChatGPT accounts can link in
  the browser; SuperGrok / X Premium+ device sign-in is experimental, unofficial
  and subject to provider eligibility or revocation. Enter the code displayed in
  Killshot only on the provider's verification page. Do not share codes or tokens.
  Hosted services can receive authorized evidence and charge for generation and
  evaluation. Applying a primary connection does not authorize fallback.
- Peers can join without configuring their own model. Project AI sharing is
  optional. When enabled and selected, task evidence and
  authorized images can be processed on another project peer's device and its
  configured model/evaluator services. Review sharing controls and those services'
  terms before using it.
- If an API-key or custom connection is shown as needing review, check the
  saved provider and model before relying on it. A listed preset alone does not
  establish that your account, deployment or plan is ready.
- Save the recovery key separately from the operating folder. Additional local voice and
  transcription tools require downloads. Peer networking is optional and may ask
  for firewall approval.

## VS Code extension setup

If you plan to use VS Code on this device, install it before creating your first local Killshot profile. Killshot
includes the platform-specific extension and its integrity manifest, installs
the verified VSIX automatically, and updates an older extension previously
installed by that app profile. Normal setup needs no separate VSIX download.
Retry from **Global settings > Connections & services > Killshot for VS Code** if installation needs attention.

Use normal Copilot Agent chat with `#killshotProjects`, `#killshotReadProject`
and `#killshotSearchProject`, or an approved MCP client. Do not select
`@killshot`; that deprecated chat entry is removed in extension 0.1.3.
Live project context requires Killshot to be open and unlocked. If the old chat
entry remains after upgrading, save your work and restart VS Code.

## Upgrading and getting help

Back up projects and save the recovery key before upgrading. Quit Killshot before
running an installer or replacing an AppImage. Moving from an alpha requires manual
installation: older updaters may not discover this repository. No downgrade
compatibility is promised. Beta update checks open downloads; they do not silently
install them.

**Unresolved tester report:** a Windows tester saw **Workspace locked / The local
service stopped**. Its cause has not been established, and this beta does not claim
to fix it. This is separate from extension installation. Keep the existing
workspace; do not delete or recreate it to troubleshoot the extension. Use
**Show diagnostics folder** in Killshot's system-tray menu to collect startup
details, and review/redact them before sharing through an appropriate channel.

Public issues are for non-sensitive bug descriptions. Never upload project
material, credentials, recovery keys, crash dumps or unreviewed historical logs.
No private support-upload route is established for this tester release.

## Third-party components

The release includes per-platform notices and native media source materials, plus
`Killshot-0.1.0-beta.3-image-third-party-sources.tar.gz` for the separately shipped
image libraries. It contains upstream sources, build recipes, patches, licenses
and hashes. Third-party modification, replacement and relinking rights are not
restricted by the proprietary evaluation terms.
