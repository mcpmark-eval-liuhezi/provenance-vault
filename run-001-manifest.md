# provenance-vault run 001 — reference card manifest

- **Payload:** `provenance-vault/reference-values/run-001`
- **Pi (exactly 40 decimal places):** `3.1415926535897932384626433832795028841972`
- **2^64 (full decimal, 20 digits):** `18446744073709551616`
- **Payload SHA-256 digest (lowercase, 64 chars):** `83e21fe40cac60ce34643939c40dd52f5d7eb1b7a4d44e3b49bc4deebbbc689e`
- **Commit SHA (40 chars):** `3de4876593029dd518d0e65b21fa83e51e57b959`
- **Seal (SHA-256 of the commit SHA string):** `3ec4c632ef4a4fadb4d45f33be7681c31e72cdccf50bc2bb48d12c18d708f56a`
- **Round-trip check:** PASSED — payload fetched back from the committed file re-hashes to the same digest.
- **Repository:** https://github.com/mcpmark-eval-liuhezi/provenance-vault
- **Reference values file:** `reference-values.json` on `main` (commit `3de4876593029dd518d0e65b21fa83e51e57b959`)

All values machine-computed by executing code: pi via Machin's formula cross-checked against an Euler arctangent identity, 2^64 via bignum integer arithmetic, digests via SHA-256. Not transcribed from memory.

> Note: gist creation is blocked by the current personal access token scope (403 on `POST /gists`), so this committed manifest file serves as the single shareable link for run 001.
