<!-- Title: plain language, like a ticket title. -->
## For the PO
<!-- The head: plain language, read in about a minute. Nothing under "Needs you", "Assumptions made" or "Known limitations" goes in Details. -->

## What changes for you
<!-- Two to four plain lines: what users or the PO will notice. -->

## How to see it
<!-- Where to look; a screenshot when something is visible. -->

## Criteria
<!-- "<n> of <n> met". The proof per criterion is in Details under Verification. -->

## Decided for you
<!-- The number of decisions made for the PO, with the link to the decisions comment where they can be overruled. -->

## Assumptions made
<!-- Every choice you made where the ticket was silent, whether the ticket's Assumptions list covered it or not: one plain line each, linked to its entry in the decisions comment. Mark one that is not on the ticket's list as new. "None" when there are none. -->

## Needs you
<!-- Manual steps after merging (a new secret, a rebuild, a data migration), an irreversible migration, a reserved decision, a new dependency outside the standing criteria, a missing verification tool (link the chore ticket you proposed), a bug found outside the scope (propose a bug ticket). "Nothing" when there is none. -->

## Known limitations
<!-- What the PR knowingly does not do or fix. "None" when there are none. -->

## Risk
<!-- One line in plain words. -->

<details>
<summary>Details</summary>

## Context
<!-- Link the ticket: `Fixes #<n>` when this completes it, otherwise `Refs #<n>`. Stacked PR this PR builds on: `Builds on #<pr>`. Also link its parent story. -->

## What changed
<!-- 1-5 bullets on the approach, not a file list. -->

## Deviations from the proposal
<!-- Where the PR deviates from the proposed solution in the task. Write "None" when it doesn't. A deviation with a medium or large cost to undo is also in the decisions comment. -->

## Risk areas
<!-- e.g. touches auth middleware; adds a DB migration (MEDIUM); an irreversible DB migration and what data is lost (HIGH) -->

## Verification
<!-- For each acceptance criterion and each spec: how you know it is met (a command and its result, a test name, or a screenshot). Then the other commands run and results. What was NOT tested and why. -->

## Notes for the reviewer
<!-- Anything else the reviewer should know: added or removed dependencies (library, tool, Docker image, CI action) with the reason and where it was approved. Discard this section if there are no notes. -->

</details>

Author: 🤖 **<session name>**
