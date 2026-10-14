# Ethics — CLIP_AS_SERVICE_PRIOR_DOCS

**Project:** CLIP_AS_SERVICE_PRIOR_DOCS  
**Category:** ONLINE_RETAIL  
**Upstream:** https://github.com/jina-ai/clip-as-service  
**Pinned commit:** `03410570d4398084f5ca5c88ad968248e0f3fc5d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `94f719a267f0255759cc7b59e7e1ddefeccf1fc713a24cd094a2c2358cfddf3d`  
**Date:** October 2026

## Position

CLIP_AS_SERVICE_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
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
