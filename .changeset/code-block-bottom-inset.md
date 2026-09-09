---
"blume": patch
---

Remove the extra vertical space at the bottom of code blocks. The scrolling code element carries a small bottom inset so a horizontal scrollbar thumb stays off the last line's descenders, but that inset was added on top of the block's padding, so every block, including a one-line install command, sat 0.375rem taller than the space above the text. The block now gives up the same amount below the code element, so the text sits an even 1rem from the top and bottom edges and the scrollbar gap is unchanged.
