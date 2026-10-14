# Ethics — TREE_SITTER_PRIOR_DOCS

**Project:** TREE_SITTER_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/tree-sitter/tree-sitter  
**Pinned commit:** `e825b75bcf550d3771da7c22526afee336754626`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5b6a87390c5acc53289b66ebf6ad0a329aadd1a74b8e69dda2c219c0cea57e32`  
**Date:** October 2026

## Position

TREE_SITTER_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
