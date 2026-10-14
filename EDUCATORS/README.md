# Educators — CORDOVA_PLUGIN_CAMERA

**Project:** CORDOVA_PLUGIN_CAMERA  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `acc35a89e7ac1276c3f4b238592c1167e4ce475b`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `4c129244fb1a97e9ee67529a606de4a08fbfda2d14c973aaa7344cf03cfd0a2d`  
**Date:** October 2026

## Teaching with CORDOVA_PLUGIN_CAMERA

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `4c129244fb1a97e9ee67529a606de4a08fbfda2d14c973aaa7344cf03cfd0a2d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
