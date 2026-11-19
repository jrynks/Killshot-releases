# Killshot v0.1.0-beta.1

**Unsigned experimental tester prerelease. Not production-qualified. Formal
legal/privacy and independent Responsible AI launch reviews remain pending.**

Killshot connects project evidence to workshop decisions, a PRD you review and a
live VS Code coding workspace. This beta brings together:

- Preparation, Discover, Disrupt, Design, Develop and Preview, with editable
  workshop canvases and a shared PRD.
- Artemis onboarding, a fictional tutorial and a first-project checklist.
- Brain evidence exploration with distinct source-grounded and inferred concepts.
- Chat, Swarm and Assemble for model-assisted product work and conversations.
- Recording/source review, interruption recovery and permission-controlled sharing.
- Encrypted local storage, separate recovery keys and portable project backups.
- VS Code as the primary model connection, optional consented provider fallback,
  and a distinct, separately consented safety evaluator.

## Downloads

- `Killshot-0.1.0-beta.1-win-x64.exe`
- `Killshot-0.1.0-beta.1-linux-x86_64.AppImage`
- `SHA256SUMS.txt` and required redistribution notices/materials.
- `Killshot-0.1.0-beta.1-image-third-party-sources.tar.gz` with the image libraries'
  upstream sources, build recipes, patches and licenses.

Only Windows x64 and Linux x64 are in this tester release. Packages are unsigned.
Automated native checks run on Windows Server 2022 and Ubuntu 24.04 x64; consumer
OS coverage, interactive wizard testing and every upgrade/recovery path are not
claimed. Unsigned packages may trigger protection warnings. Verify
the release origin and hashes, and do not disable OS or organizational protections.
Checksums are not publisher authentication.

The Linux binary uses the Ubuntu 24.04 runtime baseline. Older distributions may
not load its native components.

## Setup, updates and limits

Connect VS Code model access and a different safety-check model. Hosted generation
and evaluation can cost money and receive authorized project evidence. A safety
pass does not prove accuracy. Additional local voice/transcription models download separately;
Linux needs an unlocked supported keyring. Peer networking/firewall approval is optional.

**Known issue:** Microsoft Foundry appears in the primary connection picker, but
the runtime still rejects it as primary. Use VS Code as primary for this beta.

Back up projects and save the recovery key before upgrading. Install manually when
moving from an alpha; the old updater may still point at the private source
repository. Quit before installation or AppImage replacement. Update notices never
install automatically, and downgrade compatibility is not promised.

Use fictional or synthetic material only, not personal, confidential, regulated
or business-critical data. Review the [evaluation terms](https://github.com/jrynks/Killshot-releases/blob/main/LICENSE)
and [tester data-handling notice](https://github.com/jrynks/Killshot-releases/blob/main/PRIVACY.md).
Do not post project material, secrets or unreviewed logs in public issues.
