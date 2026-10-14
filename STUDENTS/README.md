# Students — HI_ML

**Project:** HI_ML  
**Category:** MEDICAL_HEALTH  
**Upstream:** https://github.com/microsoft/hi-ml  
**Pinned commit:** `b67c1d27c6b17d8e8ff01f8c507f3cabdb307388`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `03f7cd4c45cb2522ab28d6fd88e92b7fbd1a5b9c64c6c87be46aec656f197b82`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `b67c1d27c6b17d8e8ff01f8c507f3cabdb307388`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `03f7cd4c45cb2522ab28d6fd88e92b7fbd1a5b9c64c6c87be46aec656f197b82`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
