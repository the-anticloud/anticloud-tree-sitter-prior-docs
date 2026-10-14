# Educators — TREE_SITTER_PRIOR_DOCS

**Project:** TREE_SITTER_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/tree-sitter/tree-sitter  
**Pinned commit:** `e825b75bcf550d3771da7c22526afee336754626`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5b6a87390c5acc53289b66ebf6ad0a329aadd1a74b8e69dda2c219c0cea57e32`  
**Date:** October 2026

## Teaching with TREE_SITTER_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `5b6a87390c5acc53289b66ebf6ad0a329aadd1a74b8e69dda2c219c0cea57e32` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
