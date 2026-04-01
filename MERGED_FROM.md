# Merged From

## Consolidation Notes

- Merge date: `2026-03-31`
- Merge method: `git subtree add --squash`
- Import policy: every merged repository was preserved as a frozen snapshot under the folder listed below.
- Runtime/API change: `None`. This consolidation moved repository contents but did not rewire service entrypoints, frontend routes, event contracts, or public APIs.
- Validation: Legacy import path verified in the repository and push completed. No information architecture or broken-link audit was run as part of consolidation.
- Known issues: Legacy `QuantBe-Wiki-Mint` content was backed up under `legacy-imports/QuantBe-Wiki-Mint`, but navigation, duplication cleanup, and content curation have not yet been completed.

## Imported Repositories

| Source Repository | Source Branch | Imported Path | Scope | Interface / API Change | Validation | Known Issues |
| --- | --- | --- | --- | --- | --- | --- |
| QuantBe-Wiki-Mint | main | legacy-imports/QuantBe-Wiki-Mint | Legacy Mintlify-based documentation backup. | No interface or API contract change was introduced during the consolidation step. The source repository was imported as a frozen snapshot only. | Backup path verified in target repo. | Source repo was deleted after backup; content cleanup and re-homing still need manual follow-up. |
