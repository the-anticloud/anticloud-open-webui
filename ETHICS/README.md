# Ethics — OPEN_WEBUI

**Project:** OPEN_WEBUI  
**Category:** FRONTIER_HARNESSES  
**Upstream:** https://github.com/open-webui/open-webui  
**Pinned commit:** `8bd8b4fac5e059578ac0c74b3c18d11139f88b7d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dbb36bd4ec991f67781f37a87f77b0cf3b2dfc9b55d87a04e2b402ddfcaa4655`  
**Date:** October 2026

## Position

OPEN_WEBUI is packaged for offline deployment with a verifiable audit trail. The
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
