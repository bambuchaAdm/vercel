---
'@vercel/oidc': patch
---

Upgrade `jose` to `^6.2.5` (fixes AIKIDO-2026-584205) and load it with a dynamic `import()` so the CommonJS build no longer fails with `ERR_REQUIRE_ESM` on runtimes without `require(esm)`.
