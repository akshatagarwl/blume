---
"blume": patch
---

Drop the strip of empty space above code blocks inside `<CodeGroup>`, `<Tabs>`, `<Steps>`, `<Callout>` and the other flush contexts. The 2.5rem top inset added to keep the copy button off a long first line read as a rendering bug over a one-line install command. A code switcher (a `<CodeGroup>`, a `ts2js` fence, code-only `<Tab>`s) now hosts a single copy button in its tab strip that copies whichever panel is showing, and every other bar-less block keeps the plain 1rem inset with enough end padding on the scrolling code that a long first line's tail clears the overlay button.
