<!-- REPO-STATUS:START -->
## Repository Status

- Status: `Active target repository`
- Role: Primary documentation repository retained after consolidation.
- Consolidation scope: absorbed repositories are preserved under `imports/` (or `legacy-imports/` for documentation backups).
- Runtime/API change from consolidation: `None`. Imported repositories were added as frozen snapshots only.
- Validation: Legacy import path verified in the repository and push completed. No information architecture or broken-link audit was run as part of consolidation.
- Known issues: Legacy `QuantBe-Wiki-Mint` content was backed up under `legacy-imports/QuantBe-Wiki-Mint`, but navigation, duplication cleanup, and content curation have not yet been completed.
- Governance files: [STATUS.md](STATUS.md), [OWNERSHIP.md](OWNERSHIP.md), [MERGED_FROM.md](MERGED_FROM.md)
<!-- REPO-STATUS:END -->

# QuantBe Knowledge Base

Primary documentation repository retained after consolidation.

## Consolidation Summary

- Consolidation date: `2026-03-31`
- Consolidation method: `git subtree add --squash`
- Imported repositories are preserved under `imports/` or `legacy-imports/` for traceability.
- No interface or API contract change was introduced by the repository consolidation step itself.
- Validation performed: Legacy import path verified in the repository and push completed. No information architecture or broken-link audit was run as part of consolidation.
- Known issues: Legacy `QuantBe-Wiki-Mint` content was backed up under `legacy-imports/QuantBe-Wiki-Mint`, but navigation, duplication cleanup, and content curation have not yet been completed.

## Imported Repositories

| Source Repository | Imported Path | Scope |
| --- | --- | --- |
| QuantBe-Wiki-Mint | legacy-imports/QuantBe-Wiki-Mint | Legacy Mintlify-based documentation backup. |

## Governance Files

- [STATUS.md](STATUS.md)
- [OWNERSHIP.md](OWNERSHIP.md)
- [MERGED_FROM.md](MERGED_FROM.md)
