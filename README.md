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
- Project backups, recovery keys and permission-controlled peer collaboration.
- A separately consented safety evaluator; its pass is not an accuracy guarantee.

## Downloads

The tester prerelease is **v0.1.0-beta.1** for **Windows x64** and **Linux x64**.
macOS, Microsoft Store and Mac App Store distribution are not part of this launch.

Get the installers from the [versioned release](https://github.com/jrynks/Killshot-releases/releases/tag/v0.1.0-beta.1):

| Platform | Asset |
| --- | --- |
| Windows x64 | `Killshot-0.1.0-beta.1-win-x64.exe` |
| Linux x64 | `Killshot-0.1.0-beta.1-linux-x86_64.AppImage` |
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
- Have access to a supported model ready. Choose Killshot for VS Code or Microsoft
  Foundry as the primary connection, then a different safety evaluator. VS Code is
  needed for the live coding workspace. Hosted services can receive task
  evidence and charge for generation and evaluation. Optional provider fallback
  needs separate consent. Not all AI processing is local.
- Save the recovery key separately from the operating folder. Additional local voice and
  transcription tools require downloads. Peer networking is optional and may ask
  for firewall approval.

## Upgrading and getting help

Back up projects and save the recovery key before upgrading. Quit Killshot before
running an installer or replacing an AppImage. Moving from an alpha requires manual
installation: older updaters may not discover this repository. No downgrade
compatibility is promised. Beta update checks open downloads; they do not silently
install them.

Public issues are for non-sensitive bug descriptions. Never upload project
material, credentials, recovery keys, crash dumps or unreviewed historical logs.
No private support-upload route is established for this tester release.

## Third-party components

The release includes per-platform notices and native media source materials, plus
`Killshot-0.1.0-beta.1-image-third-party-sources.tar.gz` for the separately shipped
image libraries. That archive contains their exact upstream source versions,
build recipes, patches, licenses and hashes. Third-party modification, replacement
and relinking rights are not restricted by the proprietary evaluation terms.
