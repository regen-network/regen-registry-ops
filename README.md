# Regen Registry Ops

*Migration notice*:
- This repository is now included in the [Regen Registry Standards][1] under
  `ops/`. Previously we were using SHACL schema stored in the [Regen Registry Standards][1] repository to validate JSON-LDs stored in this repo. In merging these two repos we hope to make it easier for users to validate JSON-LD   against their corresponding SHACL schema.

Welcome to Regen Registry Ops. This repo contains the metadata for all
projects, credit classes, and credit batches live on Regen Ledger, and should
be used in conjunction with SHACL schemas defined in [Regen Registry
Standards][1] to generate IRIs for querying metadata based on its content hash.
Metadata should be stored in JSON-LD files copied from the Regen Registry
Standards repo with the appropriate information and filled in with the
appropriate information. 

[1]: https://github.com/regen-network/regen-registry-standards
