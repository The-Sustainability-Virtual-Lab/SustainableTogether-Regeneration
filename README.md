# SustainableTogether-Regeneration

**Can a solar business be redesigned so that it has a net-positive impact on the
ecological and social dimensions it touches, and still be economically viable?**

The Regeneration Task-Force of the INCOSE and GfSE Sustainability Working Groups
tests this question. This repository holds its work. It is a scenario of the
[Sustainability Virtual Lab](https://github.com/The-Sustainability-Virtual-Lab):
it starts from
[SustainableTogether-Baseline v1.0.0](https://github.com/The-Sustainability-Virtual-Lab/SustainableTogether-Baseline/releases/tag/v1.0.0)
and compares the regenerative design with it.

## The claim being tested

A solar business designed for regenerative outcomes can reach a positive present
value (7 % discount rate) and a return of at least 8 % over thirty years. Under
identifiable market and regulatory conditions, it can also match or beat a
conventional solar business on risk-adjusted returns.

Three research questions test the claim:

1. **Viability (a gate).** Does the regenerative business pass both financial bars?
2. **Conditions.** Under which conditions does it outperform a conventional one?
3. **Method.** Can one method link the business model, the product architecture
   and the behaviour over time, with each link checked by machine?

Each answer is *yes*, *no* or *unanswered*. An unanswered question is never
reported as a no, and a no is never reported as an unanswered question.

## Read first

| Document | Content |
|---|---|
| [Project documentation](docs/project-documentation.md) | The full plan, v0.3: the claim, the outcomes, the rules for an answer, all work packages and tasks |
| [Research question decomposition](docs/research-question-decomposition.md) | The composition rules. Where it and the plan disagree, this file wins |
| [Glossary](docs/glossary.md) | Every abbreviation used in the project |

## Work packages

| WP | Folder | Owner |
|---|---|---|
| 0 | [Integration and roll-up](wp0-integration/) | Task-Force lead |
| 1 | [Business model](wp1-business-model/) | Group 1 |
| 2 | [Product regeneration](wp2-product/) | Group 2 |
| 3 | [Lifecycle and financial assessment](wp3-lca-mrv/) | Group 3 |
| 4 | [System dynamics](wp4-system-dynamics/) | Group 4 |
| 5 | [Digital engineering](wp5-digital-engineering/) | Group 5 |
| 6 | [Enabling systems](wp6-enabling-systems/) | Group 6 |
| 7 | [Communication, training and theory of change](wp7-communication/) | Task-Force (draft) |
| 8 | [Risk management](wp8-risk/) | Task-Force (draft) |

## Board

Each task is an issue. The issue title starts with the task identifier, for
example `WP1-T5` for task 1.5. Every issue carries the five fields of the plan:
deliverable, dependencies, size, milestone, and the condition for "done".

- **Board:** BOARD_URL
- **Milestones:** [M0 to M5](https://github.com/The-Sustainability-Virtual-Lab/SustainableTogether-Regeneration/milestones). Each milestone description holds its gate condition.
- **Labels:** `wp0` to `wp8`, `size:S` / `size:M` / `size:L`, `needs-decision`
  (the task waits on a Task-Force decision), `draft` (the task is not detailed yet),
  `no-dependency` (the task can start now).

## How to contribute

1. Read the project documentation, the composition rules, and your work package's chapter.
2. Pick an open issue without an assignee, and comment to claim it.
3. Work on a branch and open a pull request that links the issue (`Closes #N`).
4. Expand each abbreviation the first time you use it, and add new ones to the glossary.
5. Cite real, verifiable sources. Never invent a reference.
6. If an input that you needed did not arrive, say so in the deliverable.

## License

[MIT](LICENSE)
