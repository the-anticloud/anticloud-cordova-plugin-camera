# Ethics — CORDOVA_PLUGIN_CAMERA

**Project:** CORDOVA_PLUGIN_CAMERA  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `acc35a89e7ac1276c3f4b238592c1167e4ce475b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4c129244fb1a97e9ee67529a606de4a08fbfda2d14c973aaa7344cf03cfd0a2d`  
**Date:** October 2026

## Position

CORDOVA_PLUGIN_CAMERA is packaged for offline deployment with a verifiable audit trail. The
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
