# Students — TREE_SITTER_PRIOR_DOCS

**Project:** TREE_SITTER_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/tree-sitter/tree-sitter  
**Pinned commit:** `e825b75bcf550d3771da7c22526afee336754626`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5b6a87390c5acc53289b66ebf6ad0a329aadd1a74b8e69dda2c219c0cea57e32`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e825b75bcf550d3771da7c22526afee336754626`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `5b6a87390c5acc53289b66ebf6ad0a329aadd1a74b8e69dda2c219c0cea57e32`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
