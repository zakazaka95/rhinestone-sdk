---
'@rhinestone/sdk': patch
---

Reject EVM CAIP-2 chain ids outside the safe integer range instead of silently rounding them or converting them to infinity.
