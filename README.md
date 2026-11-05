# Endpoint-resolved gout evidence code

Repository: https://github.com/taoshuo357/gout-endpoint-evidence  
Snapshot label and target tag: **v0.1-W0-review**

[Download the source ZIP](./Code_W0_review.zip?raw=1) · [Archive file manifest](./Code_W0_package_manifest.json) · [Citation](./CITATION.cff)

The source archive contains **94 files** under `Code_W0_review/`: 68 original statistical/model scripts in `source_analysis/`, 13 files in the public `figure_scripts/` layer, and provenance and rights/citation records. The 94 entries in the manifest describe the ZIP contents. Download and extract the ZIP to obtain the analysis and plotting directories; this repository root distributes the archive and its metadata.

## Archive integrity

`Code_W0_review.zip` is **402,726 bytes**.

SHA256:

```text
cd4df0e9a0a178efa2d3440a78d8bd3ad3dcb6ff4a0aa41e85332664f2bfe235
```

The accompanying manifest records each archive entry's size, SHA256 and Git blob SHA1.

## Redraw the frozen figure outputs

Place the separately supplied `Fig01_SourceData.zip`–`Fig22_SourceData.zip` files in a sibling directory named `Zenodo_upload_22_files/`:

```text
project/
  Code_W0_review/
    source_analysis/
    figure_scripts/
    provenance/
  Zenodo_upload_22_files/
    Fig01_SourceData.zip
    ...
    Fig22_SourceData.zip
```

Install the dependencies recorded in `figure_scripts/requirements.txt`, then run:

```bash
cd Code_W0_review/figure_scripts
python strict_bundle_smoke.py
```

The recorded modulewise strict-bundle checks redrew **24 figure plates** from exact SHA-verified archived inputs. `publicity_readiness.json` contains the module results and read receipts; `figure_scripts/README.md` documents the resolver and export settings. These checks redraw frozen statistical outputs. The original statistical/model sources retain their original input and path assumptions.

## Rights and data record

Author-source rights are reserved pending the authors' code-licence selection. `LICENSE_NOTICE.md` and `THIRD_PARTY_NOTICES.md` inside the ZIP distinguish author code, external software and dataset-specific reuse terms.

Data-record status at preparation of this snapshot: DOI **10.5281/zenodo.23969076** is **reserved, not registered or published**. It is a data identifier, separate from this code archive.
