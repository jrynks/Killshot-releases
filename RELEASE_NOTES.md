# Killshot v0.1.0-beta.2

**Unsigned experimental tester prerelease. Not production-qualified. Formal
legal/privacy and independent Responsible AI launch reviews remain pending.**

## Changed since beta.1

- Bundle Killshot for VS Code 0.1.3. Remove the deprecated `@killshot` chat
  participant that the current Copilot harness rejects; retain supported project
  tools, authenticated MCP and the live-context document reader.
- Keep automatic verified VSIX installation for new local profiles and bundled
  updates for previously enrolled profiles. Use normal Copilot Agent chat with
  `#killshotProjects`, `#killshotReadProject` and `#killshotSearchProject`.
  If the old chat entry remains, save your work and restart VS Code.
- Include the latest project-peer collaboration and optional VS Code-backed AI
  sharing changes from mainline.
- Clarify extension setup, sharing data flows and the unresolved Windows
  workspace-service startup report. No speculative storage/recovery fix is included.

## Included workflows

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

- `Killshot-0.1.0-beta.2-win-x64.exe`
- `Killshot-0.1.0-beta.2-linux-x86_64.AppImage`
- `SHA256SUMS.txt` and required redistribution notices/materials.
- `Killshot-0.1.0-beta.2-image-third-party-sources.tar.gz` with the image libraries'
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

For your own model connection, configure VS Code access and a different safety-check
model. Peers can join without a local model configuration. Hosted generation
and evaluation can cost money and receive authorized project evidence. A safety
pass does not prove accuracy. Additional local voice/transcription models download separately;
Linux needs an unlocked supported keyring. Peer networking/firewall approval is optional.
Optional project AI sharing sends authorized task evidence to the selected peer
and its configured model/evaluator services; those services' terms and charges apply.
Linux also needs permitted user namespaces; Ubuntu 24.04 may require an
administrator-approved AppArmor profile for this AppImage. Killshot refuses
disabled Chromium sandboxing rather than silently bypassing it.

**Known issue:** Microsoft Foundry appears in the primary connection picker, but
the runtime still rejects it as primary. Use VS Code as primary for this beta.

**Unresolved tester report:** **Workspace locked / The local service stopped**
on Windows is not diagnosed or claimed fixed by this release. The VS Code
extension's automatic installation was confirmed separately. Keep the existing
workspace and use **Show diagnostics folder** in Killshot's system-tray menu to
collect startup details. Do not delete/recreate the workspace or post unreviewed
logs publicly.

Back up projects and save the recovery key before upgrading. Install manually when
moving from an alpha; the old updater may still point at the private source
repository. Quit before installation or AppImage replacement. Update notices never
install automatically, and downgrade compatibility is not promised.

Use fictional or synthetic material only, not personal, confidential, regulated
or business-critical data. Review the [evaluation terms](https://github.com/jrynks/Killshot-releases/blob/main/LICENSE)
and [tester data-handling notice](https://github.com/jrynks/Killshot-releases/blob/main/PRIVACY.md).
Do not post project material, secrets or unreviewed logs in public issues.
