# Experimental tester data handling

This unsigned Killshot beta is for voluntary evaluation with fictional or
synthetic material only. Formal organizational privacy/legal and Responsible AI
launch reviews are pending. Do not use personal, confidential, regulated or
business-critical data, or treat this notice as a compliance certification.

## What stays on your device

Killshot keeps project records, originals, held AI work and backups in encrypted
local storage. Credentials use native protected storage. Local encryption does
not make data sent to a model service private from that service. Keep your
recovery key separately; losing both protected access and the key can make
projects unrecoverable.

Additional local speech tools and models require downloads from their configured upstream
hosts. Those hosts receive ordinary connection/request metadata.

## What can leave your device

- **Your primary connection and model service (including VS Code or a linked account):** authorized prompts, project/source
  evidence, images or frames, tool context and generated responses.
- **Optional account linking:** the selected provider handles sign-in and receives
  ordinary authorization, model-list and usage requests. Account grants and tokens
  are stored in the encrypted local vault. Linked ChatGPT uses eligible plan quota;
  the unofficial SuperGrok subscription route may be denied or revoked. Never
  share one-time codes, tokens or screenshots containing them in public support.
- **Your separately consented safety evaluator:** task evidence and proposed
  output/tool arguments, plus images when separately authorized.
- **Optional fallback models, image services, JEV, MCP/plugins and connected
  sources:** data authorized for the features you enable and use. These are not
  universally on-device services.
- **Peers, exports and backups:** records you explicitly share or export. Copies
  on another device cannot be recalled by deleting your own copy.
- **Optional project AI sharing:** authorized task evidence, prompts, images,
  tool context and proposed output can pass through the selected project peer's
  device and its configured model/evaluator services. The peer's provider
  credentials are not distributed as part of model requests; this does not
  prevent the receiving device or its services from processing the task data.
  Review project AI-sharing controls and the serving provider's terms and charges.
- **GitHub:** ordinary download/update-check and public-issue metadata. Update
  discovery does not upload project contents. Public issues are public.

Provider accounts, retention, training use, locations, transfers and charges are
governed by the services you select. Review their terms before connecting. The
beta does not promise zero retention or no training for arbitrary endpoints.
Model generation and safety evaluation can both incur charges.

## Control, retention and deletion

Use the application's connection, consent and sharing controls. Withdrawing
evaluator consent stops that connection and removes its saved configuration/key;
withdrawing fallback consent disables access but can retain an encrypted
destination draft. Cancelling AI work is not deletion. There is no automatic
age-based purge promised for retained project evidence or AI receipts.

Locking a workspace stops access; it does not delete it. Project, operating-folder,
credential and backup copies may need separate deletion. Provider-side deletion
must be requested from that provider. Uninstall intentionally retains application
data and your operating folder. Keep only synthetic test data until formal
retention/deletion and privacy review is complete.

Operational logs are local. Old logs, crash dumps and support bundles can still
contain sensitive information; do not post them publicly without reviewing and
redacting them. This release does not establish a private support-upload route.

## Publisher and contact

The tester release is maintained by [jrynks](https://github.com/jrynks) at
[Killshot-releases](https://github.com/jrynks/Killshot-releases).
Use its issues for non-sensitive bug descriptions and questions only. Do not
send personal data, project material, credentials, recovery keys or raw logs.
