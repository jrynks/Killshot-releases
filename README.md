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

- Artemis-guided practice with fictional evidence and a first-project handoff.
- Workshop canvases, source readers and Brain provenance.
- Model-assisted workshops, research and conversations with visible activity.
- Recording/transcription review against originals before sharing.
- A live VS Code connection rather than an exported Build Kit.
- Bundled Killshot extension 0.1.3, using Copilot tools and MCP instead of the
  deprecated `@killshot` chat participant.
- Optional project-level VS Code AI sharing between connected peers.
- Project backups, recovery keys and permission-controlled peer collaboration.
- A separately consented safety evaluator; its pass is not an accuracy guarantee.

## Downloads

The tester prerelease is **v0.1.0-beta.2** for **Windows x64** and **Linux x64**.
macOS, Microsoft Store and Mac App Store distribution are not part of this launch.

Get the installers from the [versioned release](https://github.com/jrynks/Killshot-releases/releases/tag/v0.1.0-beta.2):

| Platform | Asset |
| --- | --- |
| Windows x64 | `Killshot-0.1.0-beta.2-win-x64.exe` |
| Linux x64 | `Killshot-0.1.0-beta.2-linux-x86_64.AppImage` |
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
  This tester binary uses the Ubuntu 24.04 runtime baseline; older distributions
  may not load its native components.
  User namespaces must also be permitted. Ubuntu 24.04 may need an
  administrator-approved AppArmor profile for the specific AppImage. Killshot
  refuses to run with Chromium sandboxing disabled; do not disable system protections.
- To configure your own model connection, choose Killshot for VS Code as the
  primary connection, then a different safety evaluator. VS Code also powers
  the live coding workspace. Hosted services can receive task
  evidence and charge for generation and evaluation. Optional provider fallback
  needs separate consent. Not all AI processing is local.
- Peers can join without configuring their own model. Shared AI is optional and
  requires an enabled, available provider. Authorized task evidence and images
  can be processed on the selected project peer's device and its
  configured model/evaluator services. Review sharing controls and those services'
  terms before using it.
- **Known model-setup limitation:** Microsoft Foundry appears in the primary
  picker, but the runtime still rejects it as primary. Use VS Code as primary
  for this beta.
- Save the recovery key separately from the operating folder. Additional local voice and
  transcription tools require downloads. Peer networking is optional and may ask
  for firewall approval.

## VS Code extension setup

If using VS Code on this device, install it before creating your first local
Killshot profile. Killshot includes the platform-specific extension and its
integrity manifest, installs
the verified VSIX automatically, and updates an older extension previously
installed by that app profile. Normal setup needs no separate VSIX download.
Retry from **Settings > VS Code** if installation needs attention.

Use normal Copilot Agent chat with `#killshotProjects`, `#killshotReadProject`
and `#killshotSearchProject`, or an approved MCP client. Do not select
`@killshot`; that deprecated chat entry is removed in extension 0.1.3.
Live project context requires Killshot to be open and unlocked.
If the old entry remains after upgrading, save your work and restart VS Code.

## Upgrading and getting help

Back up projects and save the recovery key before upgrading. Quit Killshot before
running an installer or replacing an AppImage. Moving from an alpha requires manual
installation: older updaters may not discover this repository. No downgrade
compatibility is promised. Beta update checks open downloads; they do not silently
install them.

**Unresolved tester report:** a Windows tester saw **Workspace locked / The local
service stopped**. Its cause has not been established, and beta.2 does not claim
to fix it. This is separate from extension installation. Keep the existing
workspace; do not delete or recreate it to troubleshoot the extension. Use
**Show diagnostics folder** in Killshot's system-tray menu to collect startup
details, and review/redact them before sharing through an appropriate channel.

Public issues are for non-sensitive bug descriptions. Never upload project
material, credentials, recovery keys, crash dumps or unreviewed historical logs.
No private support-upload route is established for this tester release.

## Third-party components

The release includes per-platform notices and native media source materials, plus
`Killshot-0.1.0-beta.2-image-third-party-sources.tar.gz` for the separately shipped
image libraries. That archive contains their exact upstream source versions,
build recipes, patches, licenses and hashes. Third-party modification, replacement
and relinking rights are not restricted by the proprietary evaluation terms.
