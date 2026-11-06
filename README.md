# QAT and PECTA assessment flow (Moawin)

Prototype and build spec for adding a test-type choice, QAT or PECTA, to the Moawin `/assessment` flow on Rumi. The Rawalpindi (RWP) flow is unchanged.

## Files

| File | What it is |
|---|---|
| `index.html` | The full page: a clickable phone prototype, the flow map, the QAT paper blueprint per grade and subject, how questions are made from the content, Urdu and English screen copy, build steps, and an "Everything for the bot" block. Open it in a browser. It is a single file with no build step. |
| `QAT_PECTA_Assessment_Flow.pdf` | A static copy of the same page for reading or attaching. The clickable flow only works in `index.html`. |

## View it

- Locally: open `index.html` in a browser. It loads fonts from Google Fonts, so it needs internet for the intended look.
- On GitHub Pages: Settings, Pages, deploy from the `main` branch, root folder.

## Scope

- Moawin teachers only. RWP teachers never see the new screen.
- QAT covers Maths, English and Urdu, Grades 1 to 5.
- Curriculum is unchanged. QAT questions come from the same Punjab textbooks used for PECTA, only from the units the teacher picks.
- Grade 1 marks are inferred from the content book and the Grade 2 shape. Grade 3 mark splits and Urdu Grades 2 and 3 splits still need confirming.

The "Everything for the bot" block at the bottom of `index.html` is the source of truth for the build.
