# Students — OPEN_WEBUI

**Project:** OPEN_WEBUI  
**Category:** FRONTIER_HARNESSES  
**Upstream:** https://github.com/open-webui/open-webui  
**Pinned commit:** `8bd8b4fac5e059578ac0c74b3c18d11139f88b7d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dbb36bd4ec991f67781f37a87f77b0cf3b2dfc9b55d87a04e2b402ddfcaa4655`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `8bd8b4fac5e059578ac0c74b3c18d11139f88b7d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `dbb36bd4ec991f67781f37a87f77b0cf3b2dfc9b55d87a04e2b402ddfcaa4655`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
