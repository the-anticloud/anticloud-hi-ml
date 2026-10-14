# Ethics — HI_ML

**Project:** HI_ML  
**Category:** MEDICAL_HEALTH  
**Upstream:** https://github.com/microsoft/hi-ml  
**Pinned commit:** `b67c1d27c6b17d8e8ff01f8c507f3cabdb307388`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `03f7cd4c45cb2522ab28d6fd88e92b7fbd1a5b9c64c6c87be46aec656f197b82`  
**Date:** October 2026

## Position

HI_ML is packaged for offline deployment with a verifiable audit trail. The
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
