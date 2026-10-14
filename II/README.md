# Independent Insurance — HI_ML

**Project:** HI_ML  
**Category:** MEDICAL_HEALTH  
**Upstream:** https://github.com/microsoft/hi-ml  
**Pinned commit:** `b67c1d27c6b17d8e8ff01f8c507f3cabdb307388`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `03f7cd4c45cb2522ab28d6fd88e92b7fbd1a5b9c64c6c87be46aec656f197b82`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | HI_ML with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `03f7cd4c45cb2522ab28d6fd88e92b7fbd1a5b9c64c6c87be46aec656f197b82`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
