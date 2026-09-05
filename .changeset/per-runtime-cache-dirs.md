---
"blume": patch
---

Keep Astro's and Vite's caches inside the hidden `.blume` runtime instead of under its `node_modules`, which is a junction into Blume's package directory. Two projects that resolve the same Blume install (a monorepo building docs and a sandbox in parallel) previously shared one content data store, so pages of whichever build lost the race rendered as 404s.
