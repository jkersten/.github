---
name: Task
about: A concrete piece of work with a clear result, often one step of a story
labels: task, draft
---

<!-- The head: what the PO reads, in plain language. It must make sense without reading other tickets, and has no open question when the ticket goes to Ready. -->
### What
<!-- One or two lines in plain words: what this task changes or builds. -->

### Goal
<!-- One or two lines: the problem this solves or the reason it is needed now, what exists today, and what is true once the task is done. -->

### Acceptance criteria
<!-- Checkboxes. Each one says in plain words what the PO can see and a reviewer can verify. Exact values (widths, WCAG level, browser names) go in a spec or the key tests. -->
- [ ]

### Out of scope
<!-- What this task will not do. If another ticket or step covers it, name it. -->

### Specs
<!-- Checkboxes. Small, testable rules about behaviour that came out of the design feedback, each with its id from the note of the mockup (S1, S2, ...). A look is not a spec. Omit this section when there are none. -->
- [ ]

**Decided:** <!-- The PO's decisions made at the Go, one line each, with the link to the decision document. Omit this line when there are none. Replaces the open questions at Ready. -->

**Risk:** <!-- In plain words: straightforward | risky but understood (say why) | unknown (needs a spike first, which blocks this task). -->

**Model:** <!-- Sonnet | Opus, with a few words of reason. Default from the risk: Sonnet for straightforward, Opus for risky or unknown. -->

**Mockup:** <!-- When a user sees the change: the link to the approved mockup, or the mockup of the story or bug with the part this task builds. Omit this line when nothing a user sees changes. Never describe the design in words. -->

<details>
<summary>Details</summary>

### Proposed solution
<!-- The files or modules and the approach, in one or two sentences first. The builder follows it and reports deviations in the PR. -->

### Key tests
<!-- The tests that show the criteria are met, with the exact values the criteria leave out. -->

### Assumptions
<!-- Choices the builder may make without asking and logs in the decisions comment. Omit if none. -->

### Context
<!-- How this relates to other tickets (its parent, the steps before and after it, what blocks it, the siblings it builds on), the current situation, and links to earlier decisions, including the decision document. -->

### Notes
<!-- Approach, links, risks. Omit if not applicable. -->

</details>
