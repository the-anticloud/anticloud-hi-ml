# Educators — HI_ML

**Project:** HI_ML  
**Category:** MEDICAL_HEALTH  
**Upstream:** https://github.com/microsoft/hi-ml  
**Pinned commit:** `b67c1d27c6b17d8e8ff01f8c507f3cabdb307388`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `03f7cd4c45cb2522ab28d6fd88e92b7fbd1a5b9c64c6c87be46aec656f197b82`  
**Date:** October 2026

## Teaching with HI_ML

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `03f7cd4c45cb2522ab28d6fd88e92b7fbd1a5b9c64c6c87be46aec656f197b82` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
