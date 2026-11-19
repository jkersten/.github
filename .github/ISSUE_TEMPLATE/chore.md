---
name: Chore
about: Maintenance that doesn't change what the app does (dependencies, CI, refactoring, tooling)
labels: task, chore, draft
---

<!-- The head: what the PO reads, in plain language. It must make sense without reading other tickets, and has no open question when the ticket goes to Ready. -->
### What
<!-- One or two lines in plain words: the change itself. -->

### Goal
<!-- What this chore achieves and why now: an outdated dependency, a slow CI run, code that is hard to change. -->

### Acceptance criteria
<!-- Checkboxes, in plain words. If the change turns out to alter behaviour, this is a task, not a chore. -->
- [ ] Behaviour is unchanged; the full test suite passes
- [ ]

### Out of scope
<!-- What this chore will not do. If another ticket or step covers it, name it. -->

**Decided:** <!-- The PO's decisions made at the Go, one line each, with the link to the decision document. Omit this line when there are none. Replaces the open questions at Ready. -->

**Risk:** <!-- In plain words: straightforward | risky but understood (say why) | unknown (needs a spike first, which blocks this task). -->

**Model:** <!-- Sonnet | Opus, with a few words of reason. Default from the risk: Sonnet for straightforward, Opus for risky or unknown. -->

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
