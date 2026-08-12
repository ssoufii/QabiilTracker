# Backlog

Qabiil Tracker is a single-page, vanilla HTML/CSS/JS family tree app: no
framework, no build step, no backend. Data lives in the browser's
localStorage. The whole tree renders as a pedigree diagram — the focus
person at the bottom, ancestors stacking upward, fathers left of mothers in
each pair.

## How we work

- One story at a time, in order. Each issue is a vertical slice: after it
  merges, you can open `index.html` in a browser and see or do something you
  couldn't before.
- Pick up the lowest-numbered open issue whose "Depends on" issues are all
  closed. Don't start a story out of order — later stories assume earlier
  ones are done.
- Every issue has acceptance criteria you can check by hand in a browser.
  Don't close an issue until every box is checked against the real app, not
  just against the code.
- Sizes (S / M / L) are relative effort, not a time estimate — use them to
  judge how much to bite off in one sitting.
- If a story turns out to need more than its stated acceptance criteria to
  actually satisfy the "Story" line, stop and split it into a follow-up issue
  rather than scope-creeping the original.

## Stories

### Milestone 1 — [A tree you can grow](https://github.com/ssoufii/QabiilTracker/milestone/1)
Open the file, record yourself, add parents, and grow the pedigree to any depth.

| # | Story | Size | Depends on |
|---|-------|------|------------|
| [#1](https://github.com/ssoufii/QabiilTracker/issues/1) | Scaffold and shell | S | — |
| [#2](https://github.com/ssoufii/QabiilTracker/issues/2) | Record yourself | M | #1 |
| [#3](https://github.com/ssoufii/QabiilTracker/issues/3) | Add parents | M | #2 |
| [#4](https://github.com/ssoufii/QabiilTracker/issues/4) | Arbitrary depth | L | #3 |

### Milestone 2 — [A tree you can read](https://github.com/ssoufii/QabiilTracker/milestone/2)
Every card shows its computed kinship label, generation tiers are labelled, and you can pan/zoom a large tree.

| # | Story | Size | Depends on |
|---|-------|------|------------|
| [#5](https://github.com/ssoufii/QabiilTracker/issues/5) | Make it legible | M | #4 |
| [#6](https://github.com/ssoufii/QabiilTracker/issues/6) | Navigate the canvas | M | #4 |

### Milestone 3 — [A tree with full records](https://github.com/ssoufii/QabiilTracker/milestone/3)
Every field is captured including photos, records are searchable, and data can be exported, imported, deleted, and reattached.

| # | Story | Size | Depends on |
|---|-------|------|------------|
| [#7](https://github.com/ssoufii/QabiilTracker/issues/7) | Full person record | L | #2 |
| [#8](https://github.com/ssoufii/QabiilTracker/issues/8) | Find people | M | #4 |
| [#9](https://github.com/ssoufii/QabiilTracker/issues/9) | Keep and move the data | M | #8 |

### Milestone 4 — [A finished tree](https://github.com/ssoufii/QabiilTracker/milestone/4)
Siblings appear, any ancestor can become the new focus, and the app prints cleanly and works with a keyboard on any screen.

| # | Story | Size | Depends on |
|---|-------|------|------------|
| [#10](https://github.com/ssoufii/QabiilTracker/issues/10) | Siblings and re-centering | M | #5 |
| [#11](https://github.com/ssoufii/QabiilTracker/issues/11) | Print and accessibility pass | M | #10 |

## Start here

[#1 Scaffold and shell](https://github.com/ssoufii/QabiilTracker/issues/1) has no dependencies and is the first thing to build.
