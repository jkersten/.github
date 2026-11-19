---
name: Bug
about: Something works differently from what it should
labels: bug, draft
---

<!-- The head: what the PO reads, in plain language. It must make sense without reading other tickets, and has no open question when the ticket goes to Ready. -->
### Summary
<!-- One line describing the bug, and one line on how often it happens and who it hurts. -->

### Steps to reproduce
<!-- A numbered list in plain words, starting from a clean state. -->
1.

### Expected behavior
<!-- What should happen. -->

### Actual behavior
<!-- What happens instead. -->

### Acceptance criteria
<!-- Checkboxes. Each one says in plain words what the PO can see and a reviewer can verify. Exact values (widths, WCAG level, browser names) go in a spec or the key tests. -->
- [ ]

### Specs
<!-- Checkboxes. Small, testable rules about behaviour that came out of the design feedback, each with its id from the note of the mockup (S1, S2, ...). A look is not a spec. Only for a bug without tasks and with a mockup. Omit it otherwise. -->
- [ ]

**Mockup:** <!-- When the fix changes what a user sees: the link to the approved mockup, as a commit link into `docs/design/mockups/`. Omit this line when nothing a user sees changes. -->

### Out of scope
<!-- What this fix will not do. If another ticket or step covers it, name it. -->

**Decided:** <!-- The PO's decisions made at the Go, one line each, with the link to the decision document. Omit this line when there are none. Replaces the open questions at Ready. -->

<details>
<summary>Details</summary>

### Environment
<!-- App, library or package version; operating system, browser or runtime; relevant config. Full error messages or logs in a code block. Omit what doesn't apply. -->

### Context
<!-- Screenshots, regressions, workarounds, how this relates to other tickets (its parent, the steps before and after it, what blocks it, the siblings it builds on), the current situation, and links to earlier decisions, including the decision document. -->

### Assumptions
<!-- Choices the builder may make without asking and logs in the decisions comment. Omit if none. -->

### Notes
<!-- Links, designs, risks. Omit if not applicable. -->

</details>
