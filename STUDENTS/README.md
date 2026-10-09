# Students — CLIP_AS_SERVICE_PRIOR_DOCS

**Project:** CLIP_AS_SERVICE_PRIOR_DOCS  
**Category:** ONLINE_RETAIL  
**Upstream:** https://github.com/jina-ai/clip-as-service  
**Pinned commit:** `03410570d4398084f5ca5c88ad968248e0f3fc5d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `94f719a267f0255759cc7b59e7e1ddefeccf1fc713a24cd094a2c2358cfddf3d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `03410570d4398084f5ca5c88ad968248e0f3fc5d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `94f719a267f0255759cc7b59e7e1ddefeccf1fc713a24cd094a2c2358cfddf3d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
