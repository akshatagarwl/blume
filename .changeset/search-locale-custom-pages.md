---
"blume": patch
---

Scope search to the active language on every page of a multi-locale site. The search dialog derived its locale filter from the header's language-switcher entries, which only content pages receive, so custom pages built on `PageLayout`, the changelog index, the 404 page, and the API reference shell searched every language and hid the "All languages" toggle. The filter now reads the resolved i18n settings directly.
