# Educators — OPEN_WEBUI

**Project:** OPEN_WEBUI  
**Category:** FRONTIER_HARNESSES  
**Upstream:** https://github.com/open-webui/open-webui  
**Pinned commit:** `8bd8b4fac5e059578ac0c74b3c18d11139f88b7d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dbb36bd4ec991f67781f37a87f77b0cf3b2dfc9b55d87a04e2b402ddfcaa4655`  
**Date:** October 2026

## Teaching with OPEN_WEBUI

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `dbb36bd4ec991f67781f37a87f77b0cf3b2dfc9b55d87a04e2b402ddfcaa4655` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
