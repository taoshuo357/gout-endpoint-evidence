# Endpoint-resolved gout evidence: W0 baseline

Taoshuo Yang. **GitHub target version: `v0.1.1-W0-release`** (tag pending). The W0 data and author-code deposit was published on 27 November 2026: [Zenodo DOI 10.5281/zenodo.24574321](https://doi.org/10.5281/zenodo.24574321), data version `0.1.1-W0-public-derivative`.

The deposit contains 28 files, including 22 figure archives and the [105-entry author-code ZIP](Code_W0_v0.1.1_MIT_release.zip). Its 78 original Python/R scripts are unchanged. Nineteen figure archives preserve the W0 bytes; F03, F04 and F22 are explicitly partial, with five source-associated members omitted and linked to their original providers. Use the deposit's `reviewed_22_file_manifest.tsv` and `five_source_member_omissions.tsv` for the published derivative. The root `DATA_ARCHIVE_RIGHTS.tsv` and `DATA_MEMBER_RIGHTS.tsv` document the original W0 audit, including the omitted members.

Project-authored software is MIT; source data keep their file-specific terms, including applicable ChEMBL BY-SA 3.0 and public protein BY-NC 4.0 conditions. See [LICENSING_SCOPE.md](LICENSING_SCOPE.md), [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) and the deposit's rights files. The dataset DOI identifies this mixed data-and-code deposit; it is not a separate software DOI.

Extract the code ZIP to obtain `Code_release/`. Historical `source_analysis/` scripts retain their original path/dependency assumptions. The portable `figure_scripts/` layer redraws frozen results using exact archive identities and hashes; full replay requires the five omitted inputs through the documented source routes. Historical local checks covered six modules and 24 plates; clean-environment installation and cross-platform statistical reproduction remain untested.

This is the 5 November 2026 W0 scientific snapshot with its later licensing patch. Subsequent E15–E19 analyses and model training require separate releases. The old reserved record `23969076` remains an unpublished historical draft; cite `24574321` for these public data. [PUBLICATION_STATUS.md](PUBLICATION_STATUS.md) records verification and the pending GitHub tag.
