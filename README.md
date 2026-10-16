# Dietary fat and eating disorder revision resources

This is an author-review archive of retained analyses and supporting aggregate results. It is not a claim that every archived script reproduces the final manuscript without additional inputs or reconciliation.

## Contents

- `code/` contains retained NHANES, XGBoost, MR, transcriptomic, TWAS, colocalization, regulatory and cell-type workflows.
- `data/` contains supplementary tables and aggregate source outputs, not individual-level NHANES or human brain participant records.
- `docs/` records provenance, input requirements and release status.

## Reproduction boundary

Run scripts from the repository root. Machine-specific `D:/Codex/` prefixes have been relocated to `./project/`; preserve the project `Workspaces/`, `outputs/` and `scratch/` subtrees under that directory when reconstructing inputs. Obtain original third-party datasets from their official repositories rather than assuming they are bundled. A script collection is not a tested end-to-end runner. Python files were syntax checked; computational analyses were not rerun for this packaging step.

The final manuscript labels and effect estimates remain the author-approved authority. The NHANES adjustment sets were confirmed from the numerically matching archive, whose original quantitative exposure code uses protein-named variables. The author instructed that final manuscript fat labels be retained. These source variables have not been silently renamed or presented as independently reproduced fat estimates. MR legacy outcome/exposure file labels also require the final manuscript mapping. See `docs/provenance.md` before execution.

## Data sources

NHANES 2005–March 2020 (CDC), GSE262138, GSE236077, GTEx v8/PredictDB, PGC AN 2019, FinnGen and the official references in the manuscript are reused third-party resources. Respect their access conditions. No raw GWAS, sequencing data, participant records, browser data, credentials or authentication files are included.

## Status

Private author-review package. A public repository URL or permanent DOI must not be claimed before an actual verified release. No new licence is asserted for third-party code or data. Meta-analysis and QCA collaborator source code/data are not included and were not reconstructed.
