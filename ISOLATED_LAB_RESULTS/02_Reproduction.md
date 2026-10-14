# Reproduction

```
cd E:\fenta\Downloads\The Anticloud\ANTICLOUD_REPOS\SOFTWARE_DEVELOPMENT\TREE_SITTER_PRIOR_DOCS\anticloud
python tools\run_bench.py --out BENCH.json --quiet   # pass 1: generate BENCH.json (checks that cite it as evidence)
python tools\run_bench.py --out BENCH.json --quiet   # pass 2: record (deterministic re-run)
python tools\run_bench.py --out E:\fenta\Downloads\The Anticloud\ANTICLOUD_REPOS\SOFTWARE_DEVELOPMENT\TREE_SITTER_PRIOR_DOCS\ISOLATED_LAB_RESULTS\04_Evidence\16_checks_report.json
```

Exit code 0 only when all 16 checks PASS. The report JSON at the
--out path carries each check's own evidence object.

- BENCH.json SHA3-256: `d13c8b1e309a3150f884a145aff01a57cd3b1b3ee766b25d8b1ccb8cf91aa14d`
- Evidence report SHA3-256: `d13c8b1e309a3150f884a145aff01a57cd3b1b3ee766b25d8b1ccb8cf91aa14d`
- run_bench_output.txt SHA3-256: `a6a843334c3c85bbb50ab464c0289ffb5b997d36dfff99b1a91909b4665d2e62`
