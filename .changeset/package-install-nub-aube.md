---
"blume": patch
---

Add `nub` and `aube` tabs to the `package-install` block, alongside npm, pnpm, yarn, and bun. The commands come from the same maintained agent tables as the existing tabs, so `npx …` becomes `nubx …` and `aube dlx …`, `npm ci` becomes a frozen install, and global installs keep their `-g` form. An install block may also be written with a `nub`, `nubx`, or `aube` command as its input.
