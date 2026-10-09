# Educators — CLIP_AS_SERVICE_PRIOR_DOCS

**Project:** CLIP_AS_SERVICE_PRIOR_DOCS  
**Category:** ONLINE_RETAIL  
**Upstream:** https://github.com/jina-ai/clip-as-service  
**Pinned commit:** `03410570d4398084f5ca5c88ad968248e0f3fc5d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `94f719a267f0255759cc7b59e7e1ddefeccf1fc713a24cd094a2c2358cfddf3d`  
**Date:** October 2026

## Teaching with CLIP_AS_SERVICE_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `94f719a267f0255759cc7b59e7e1ddefeccf1fc713a24cd094a2c2358cfddf3d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
