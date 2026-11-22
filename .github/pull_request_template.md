<!-- Title: plain language, like a ticket title. -->
<!-- When the PR changes something only the PO may decide (a reserved topic), start with one bold line: **Reserved:** <what, in plain words>. Otherwise leave it out. -->

# For the PO
<!-- Plain language, read in about a minute: no file names or jargon. Bullets in every section. Leave out a section that doesn't apply, except Needs you. Nothing under "Needs you", "Assumptions made" or "Known limitations" goes in Details. -->

## Needs you
<!-- What the PO must do: the merge or acceptance, manual steps after merging (a new secret, a rebuild, a data migration), an irreversible migration, a reserved decision, a new dependency outside the standing criteria, a missing verification tool (link the chore ticket you proposed), a bug found outside the scope (propose a bug ticket). Numbered steps when the order matters, bullets otherwise. "Nothing" when there is none. -->

## What changed
<!-- Changes that affect the PO or an end user, one bullet each, with before and after. -->

## How to see it
<!-- Where to look; a screenshot when something is visible. -->

## Criteria
<!-- "<n> of <n> met". The proof per criterion is in Details under Verification. -->

## Decided for you
<!-- The number of decisions made for the PO, each in a few plain words, with the link to the decisions comment where they can be overruled. -->

## Assumptions made
<!-- Every choice you made where the ticket was silent, whether the ticket's Assumptions list covered it or not: one plain bullet each, linked to its entry in the decisions comment. Mark one that is not on the ticket's list as new. -->

## Known limitations
<!-- What the PR knowingly does not do or fix. -->

## Risk
<!-- One bullet in plain words. -->

<details>
<summary>Details</summary>

## Context
<!-- Link the ticket: `Fixes #<n>` when this completes it, otherwise `Refs #<n>`; "No ticket" when none asked for it. Stacked PR this PR builds on: `Builds on #<pr>`. Also link its parent story. -->

## How it's done
<!-- 1-5 bullets on the approach, not a file list. -->

## What changes for sessions
<!-- For a change to the working agreement: what sessions do differently, one bullet each. Leave it out otherwise. -->

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
