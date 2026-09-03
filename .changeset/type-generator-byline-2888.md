---
"emdash": patch
---

Fixes the type generator so generated collection interfaces include `byline?: BylineSummary | null` alongside `bylines`, matching runtime hydration by `getEmDashEntry` and `getEmDashCollection`.

