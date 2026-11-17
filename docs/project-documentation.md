# The Regeneration Task-Force: project documentation and Cycle 1 work plan

*INCOSE Sustainability Working Group · GfSE Sustainability Working Group · SustainableTogether*

**Can a solar business be redesigned so that it has a net-positive impact on the ecological and social dimensions it touches, and still be economically viable?** This document explains the project that is testing that question, and the work planned to answer it.

| Field | Value |
|---|---|
| Document | Project documentation and work plan, version 0.3, draft for discussion |
| Date | 8 November 2026 |
| Owner | Hamza Bassam, Regeneration Task-Force |
| Status | Proposal. Task owners and milestone dates are deliberately left open for the Task-Force to fill in. |
| Working form | Each task in Part Three is a GitHub issue in this repository (`WP1-T5` = task 1.5), on the [Regeneration Cycle 1 board](../README.md#board). |

# About this document
This document has one purpose: to let anyone — a new contributor, a working-group member, an interested outsider — read it once and understand what the Regeneration Task-Force is doing, why, and who is doing which part.

It is written in plain words. Abbreviations have been avoided almost entirely, even where the project's own working files use them, because the working files are for people already inside the project and this document is not.

### How it is organised
-   **Part One — The project.** What is being tested, why it matters, the vocabulary you need, and how far along the work actually is.

-   **Part Two — How the work is organised.** Nine work packages, six milestones, and the decisions everything else waits on.

-   **Part Three — The work packages.** One chapter each: what the package is for, its tasks, what it needs from others, and what must not slip.

-   **Part Four — Running the cycle.** The risks in the plan, the smaller version of it, how to contribute, and what still has to be decided.

-   **Appendices.** The terms used here, and the shorthand identifiers that connect this document to the project repository.

### If you only read three pages
Read “The claim being tested”, “What counts as an answer”, and “Where the project stands today”. Between them they contain the argument, the standard of proof, and the honest starting position. Everything else is detail hanging off those three.

> **A note on tone**
>
> This document says several unflattering things about the project's own state:
> - that most of the evidence does not exist yet (must be confirmed by a thorough literature review),
> - that seven of the eight outcomes have no agreed number (work in progress),
> - that a key comparison baseline has never been defined (work in progress), and
> - that a negative result is a live possibility.
>
> That is deliberate. The project's entire value rests on being believable, and a plan that hides its gaps cannot be checked by anyone, which is the opposite of what a research task-force is for.

# Part One — The project
## What this project is
The Regeneration Task-Force is a research group inside the Sustainability Working Group of the International Council on Systems Engineering. It sits within a wider effort called SustainableTogether.

The group has one job: to demonstrate, in a real engineering model with a working business model and a proper environmental assessment behind it, that designing an engineered system for regenerative outcomes can be commercially viable.

The demonstration uses one pilot case. A conventional solar-power company — modelled as it exists today, under the name SolarX — is carried forward into a regenerative future version of itself, called SustainaSun. Both are modelled: the business, the physical system, the behaviour over thirty years, the environmental footprint, and the way outcomes would be measured in the field. SolarX is a fictional but representative reference case, not a real company. Where real data is missing, the work runs on explicitly stated assumptions — and how the answer depends on the country, the region and the type of business is itself part of what the second research question sets out to find.

Behind the headline question sits the practical one that a small or medium-sized solar business faces when it wants to become regenerative: how should it evaluate new business propositions, and where can systems thinking, systems engineering and the flourishing business canvas help it do so? That question is not answered in one place. It is broken down across the work packages — the business model (package one), product design (package two), system dynamics (package four) and the enabling systems (package six) — and brought back together at the top level.

Nothing physical is built. This is a modelling and evidence exercise, and the honesty of the evidence is the whole point.

## Why it exists
Sustainability as practiced in engineering is mostly about doing less harm: fewer emissions, less waste, less water. Regeneration asks a different question — can the system leave the place better than it found it, repeatedly, as a by-product of operating normally?

That question is usually answered with value judgements and qualitative arguments rather than numbers. Someone argues that regeneration is the right thing to do; someone else asks what it costs; the conversation ends. The Task-Force exists because the argument only becomes useful when it is settled commercially:

> *To what extent can a business that internalises ecological and social value — soil, biodiversity, water, material circularity, and social value such as community wealth, fair local employment, energy access and a say in decisions — still earn an acceptable return on its own economics? And under which conditions does regeneration only work on subsidy?*
>
> *Answering this needs two views at once: the micro-economic view of the business's own economics, and the macro-economic view of the conditions — prices, regulation, markets — under which a business can internalise its environmental and social costs and benefits.*
>
> *Where the answer is "not yet", the follow-on question is: how can a business imagine and evolve towards a business model and a production system whose primary purpose is to enable social and environmental regeneration while remaining economically viable? This is aligned with the environmental, social and governance (ESG) requirements now placed on companies, and ESG-type indicators will be used to measure and evaluate. But it deliberately looks beyond them: ESG asks a company to disclose and reduce harm; this project asks how a company can create net-positive outcomes.*

If the answer is that it only works on subsidy, that is worth knowing and worth publishing. If it works unsubsidised under identifiable conditions, that is a result other engineers can act on. Either way the project produces something real, which is more than the values argument does.

## The claim being tested
> **The claim, in full**
>
> A solar business designed for regenerative outcomes — one that measurably increases soil carbon, on-site biodiversity, community wealth and material circularity through normal commercial operation — can reach a positive present value and a return of at least eight per cent over a thirty-year lifetime, and can match or beat a conventional solar business on risk-adjusted returns under identifiable market and regulatory conditions.

Two pieces of that sentence carry all the weight, and both are ordinary financial ideas:

-   **Positive present value** means the money the project brings in, once future money is discounted to what it is worth today, exceeds what it costs. In this project the discount rate used is seven per cent.

-   **A return of at least eight per cent** means the project's own rate of return clears the bar that utility-scale solar investors typically expect. Both figures are measured over thirty years.

The comparison half of the claim is a “better when” statement, never an “always better” one. Regeneration will not outperform extraction in every market under every regulation, and claiming so would be easy to disprove and would discredit the rest.

## The vocabulary that makes the rest readable
Six terms unlock everything else. They come from a 2024 paper in Nature Sustainability by Fischer and colleagues, which is the conceptual backbone of the whole project. The sixth comes from a 2025 follow-up by Fischer and colleagues.

|                                     |                                                                                                                                                                                                                                                                                                                            |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Term**                            | **What it means here**                                                                                                                                                                                                                                                                                                     |
| **Desired outcome**                 | Something the system makes improve, repeatedly, over its life — soil carbon, biodiversity, community wealth. This is the unit of design: the project designs for outcomes, not for features. There are eight of them, listed below.                                                                                        |
| **Regenerative dynamics**           | An outcome that rises again and again and partly sustains itself, but still needs ongoing energy, labour and materials, and eventually stops rising at natural limits. Because it is a behaviour over time, it cannot be proved with a static calculation.                                                                 |
| **Restoration is not regeneration** | Repairing damage once is a prerequisite, not the goal. Regeneration means the system then keeps renewing the outcome through ordinary operation.                                                                                                                                                                           |
| **Triple top line**                 | Economy, ecology and equity, all positive at once. If any outcome is bought by sacrificing another, the design is not regenerative — however good the numbers look.                                                                                                                                                        |
| **The five capitals**               | **Natural, human, social, manufactured and financial**. A regenerative design moves value across all five rather than accumulating it in one.                                                                                                                                                                              |
| **Sustainability and regeneration** | **Used together, not as rivals. Sustainability describes the condition; regeneration describes the processes that keep making that condition possible. Source: Fischer, Farny, Pacheco-Romero and Folke (2025), Resilience and regeneration for a world in crisis, Royal Swedish Academy of Sciences, no. 55, pp. 24–34.** |

### The eight desired outcomes
These eight are the spine of the project. Each one is defined once and then used four separate ways — as a behaviour in the time-based model, as a formal requirement in the system model, as a line in the financial model, and as something with a measurement method. Keeping those four uses consistent for all eight is what the third research question is really about.

|           |                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|-----------|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.**   | **Outcome**                       | **Where its value comes from**                                                                                                                                                                                                                                                                                                                                                                                                           |
| **One**   | Soil organic carbon               | Sellable in principle: voluntary carbon-market methods for soil carbon exist (for example Verra VM0042), but prices, permanence and verification are contested, so it is treated as upside, not in the gate case. Directly, it de-risks permitting and strengthens the land-lease position.                                                                                                                                              |
| **Two**   | On-site biodiversity              | Potentially sellable later, if biodiversity credit markets mature. Treated as upside only. Beyond credits — a market that is still flawed and uncertain — biodiversity builds relational value: buy-in from customers, landowners, communities and institutional partners. This mutualistic capital is itself a design principle of regeneration; how it can be measured, and what effect it has on the business, is to be investigated. |
| **Three** | Water retention                   | Not directly sellable today, but increasingly valued — indirectly, and possibly directly — as droughts and water emergencies intensify. Shows up as civil-engineering design cost and as resilience.                                                                                                                                                                                                                                     |
| **Four**  | Material circularity              | A long-dated, modest recovery value when the plant is decommissioned.                                                                                                                                                                                                                                                                                                                                                                    |
| **Five**  | Lifetime greenhouse-gas intensity | Sellable today as a low-carbon price premium — and the only one of the eight with an agreed target.                                                                                                                                                                                                                                                                                                                                      |
| **Six**   | Community wealth retention        | Sellable today, structurally: community ownership lowers the cost of capital.                                                                                                                                                                                                                                                                                                                                                            |
| **Seven** | Energy access                     | Grant-dependent. A small effect on the overall value.                                                                                                                                                                                                                                                                                                                                                                                    |
| **Eight** | Supplier decarbonisation          | Appears as a procurement cost line, and as a slow self-reinforcing effect over decades.                                                                                                                                                                                                                                                                                                                                                  |

*Note the pattern: only three of the eight outcomes* *can be turned into bankable money today. The project's working thesis is that those three — the energy service itself, the low-carbon premium, and the cheaper capital that community ownership brings — are enough to carry the business, and that everything else strengthens the case without being load-bearing. Testing that is the first research question.* *A second line of work runs alongside: finding how the other outcomes — soil carbon, biodiversity, water — can be financed or made profitable, through emerging credit markets, relational value with customers and partners, or avoided risk. Those routes are explored openly, but stay out of the gate case until they are transactable.*

## The three research questions
Three questions, locked at the start of the project so that the answers cannot drift toward whatever turns out to be convenient. Each is broken into sub-questions with exactly one owning group, one named deliverable and one acceptance test.

### Question one — viability. This is a gate.
Can a regenerative solar business reach a positive present value and a return of at least eight per cent over thirty years?

If the answer is no, the other two questions are moot: nobody needs a method for designing businesses that cannot exist. So this one is answered first, and it is answered strictly.

### Question two — conditions
Under which structural, regulatory and market conditions does a regenerative solar business outperform a conventional one, once risk is accounted for?

The answer takes the form: “it outperforms when the following conditions hold”. It also has a second half — the conditions that were claimed but could not be verified — because a reader deciding whether to build one of these needs both lists.

### Question three — method
Can ecological, social and economic outcomes be optimised together in an engineered system, using one method that links the business model, the product architecture and the behaviour of the system over time?

This is the contribution that outlives the pilot. If the method works, it can be applied to a different industry.

## What counts as an answer
This is the most important section in the document, and the one most easily skipped.

Six groups cannot answer a research question by each writing a report and stapling them together. So each question has a rule that states exactly how the parts compose into an answer — and, just as importantly, when they do not.

### The rule for question one
The business case answers yes only if it clears both financial bars over thirty years, and it must do so:

-   using the cost figures accepted from the product design group, traced to system components;

-   using the verified emissions figure from the lifecycle assessment group wherever the low-carbon premium is priced;

-   using only revenue lines that the enabling-systems group has classified as transactable in the market today — anything that needs a market or a regulation that does not yet exist may appear in an optimistic scenario, never in the gate case;

-   under assumptions the behaviour-over-time group has not shown to be unstable;

-   and with the digital-engineering group confirming that all four models describe the same system.

> **The distinction the whole project rests on**
>
> If any of those inputs is missing or fails its own acceptance test, question one is UNANSWERED — which is a completely different thing from ANSWERED NO.
>
> Unanswered means more work is needed. Answered no means the claim has been falsified, which is a legitimate and publishable research result. Reporting one as the other would be the single most damaging thing this project could do, so the rule is written down and the roll-up is somebody's explicit job.

### Three ways to pass the gate dishonestly
Named here so that they can be checked for deliberately rather than avoided by good intentions:

-   **Passing on speculative revenue.** A positive value built on biodiversity credits that cannot yet be sold is not a pass. The bankability filter exists to prevent exactly this.

-   **Passing by trading one capital against another.** Profit funded by ecological or social harm fails the triple top line, and the claim fails on regeneration grounds even if the arithmetic works.

-   **Passing on a static snapshot.** If the behaviour model shows the assumptions erode over thirty years, the result is conditional, not an answer.

### The rule for question two
A condition enters the final answer only if three groups independently confirm it: the enabling-systems group names it and assesses its real-world state; the business-model group shows the financial outcome actually moves when it changes; and the system dynamics group shows the advantage it creates persists over thirty years rather than being eroded by feedback. Conditions that fail any one of the three are published in the second list.

### The rule for question three
The method is demonstrated when every one of the eight outcomes travels through all four of its uses with a machine-checked link at each step — thirty-two links in total. This is deliberately mechanical. “The method integrates the disciplines” is an opinion; “all eight outcomes traverse all four uses and every link passes an automated check” is a fact somebody else can verify.

*One honest limit applies here. Proper validation of a method requires applying it in at least two different industries. This cycle covers one — solar. The answer must therefore be stated as demonstrated in one context, with replication designed for but not performed. Claiming otherwise on a single pilot would be overclaiming, and one of the integration tasks exists purely to write that sentence down before anyone is tempted.*

## How success is judged
Eight criteria were fixed at the start of the project. They are what the three questions are ultimately measured against.

|           |                          |                                                                                                                                                                                                                                |
|-----------|--------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.**   | **Criterion**            | **How it is measured**                                                                                                                                                                                                         |
| **One**   | Financial viability      | Positive present value at a seven per cent discount rate over thirty years.                                                                                                                                                    |
| **Two**   | Acceptable return        | A rate of return of at least eight per cent.                                                                                                                                                                                   |
| **Three** | Risk-adjusted comparison | Risk-adjusted return against a clearly defined conventional solar baseline, producing the set of conditions under which regeneration wins. The risks themselves are identified and managed in package eight (risk management). |
| **Four**  | Ecological improvement   | A reduction in lifetime greenhouse-gas intensity, and measurable gains in soil, biodiversity and water.                                                                                                                        |
| **Five**  | Social value             | Community wealth retained locally, and improved energy access.                                                                                                                                                                 |
| **Six**   | Method validity          | The ten-step design approach applied and machine-checked — in one industry this cycle, as noted above. The method itself is still work in progress and will be refined during the cycle.                                       |
| **Seven** | Proof of compounding     | At least one self-reinforcing loop shown to compound over thirty years in the behaviour model.                                                                                                                                 |
| **Eight** | Measurement feasibility  | A measurement protocol that a named person could actually execute at a named site.                                                                                                                                             |

> **An open flaw in this list**
>
> Criterion five — social value — has no owning research sub-question of its own. It currently rides along inside two other groups' work.
>
> As things stand, community wealth and energy access will be evidenced more weakly than the financial outcomes, in a project whose central principle is that no capital may be traded against another. The Task-Force needs either to give social value its own owner, or to state plainly that this cycle evidences it less rigorously. Both are defensible; leaving it unnoticed is not.
>
> **Proposed resolution:** the lifecycle assessment group extends its work to a social lifecycle assessment (task 3.13). That gives social value a measurement path and a natural owner.

## What is in scope, and what is not
The scope boundary is as much a part of the credibility as the work itself. What follows is what this cycle deliberately does not do.

|                                                  |                                                                                                          |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| **Not doing this cycle**                         | **Because**                                                                                              |
| Building physical hardware or a real plant       | This is a modelling and evidence demonstration, not a deployment.                                        |
| Multi-year field measurement                     | The measurement work delivers a protocol and a field-test plan, not years of soil and biodiversity data. |
| Validating the method beyond solar               | It is written to be general, but it is only tested on the solar pilot. Other industries are future work. |
| Investment-grade financial due diligence         | The financial model is a research demonstrator, not an investor prospectus.                              |
| Issuing or certifying environmental credits      | Their effect on the business case is modelled; nothing is transacted or certified.                       |
| Policy advocacy                                  | The project identifies the conditions that would need to exist; it does not campaign for them.           |
| New ecological science                           | Existing science is applied and critiqued; no ecological experiments are run.                            |
| Rebuilding the existing conventional solar model | It is complete. The product group extends it rather than redoing it.                                     |

## Where the project stands today
*This section is a snapshot taken when this version was written. The current state is kept up to date continuously in the project repository, through the live evidence ledger (task 0.7); where the two differ, the repository is authoritative.*

The project is rich in two areas and thin in a third. What exists is strong: a theoretical foundation, a catalogue of one hundred and forty-four candidate regenerative solutions with sources and maturity ratings, a fifteen-domain survey of definitions, an interactive ontology, a fourteen-section strategic framework, a first business-model document, a built financial model with seven sheets and three scenarios, a working automated consistency pipeline, and a complete physical architecture model of the conventional solar company.

What is missing is the connective engineering — the parts that turn all of that into an answer. Stated as numbers:

|                         |                                                                                                                     |
|-------------------------|---------------------------------------------------------------------------------------------------------------------|
| **The honest position** | **What it means**                                                                                                   |
| **One of six**          | Only one of the six inputs the viability gate needs is even partly in place.                                        |
| **Zero of thirty-two**  | Every one of the thirty-two links in the traceability matrix is drafted. None is validated.                         |
| **Seven of eight**      | Seven of the eight desired outcomes still have no agreed target number. Only the greenhouse-gas target is anchored. |
| **Not started**         | The behaviour-over-time model — the single highest-priority missing piece — does not exist in any form yet.         |

This is why the plan in Part Two leads with decisions rather than with work. Roughly half of what the six groups need to do is currently waiting on numbers that only the Task-Force as a whole can set.

# Part Two — How the work is organised
## Nine work packages
The work is divided into nine packages. Six of them belong to the six working groups. Package zero belongs to the Task-Force as a whole and owns the top-level goal. Two further packages run across the whole cycle: package seven covers the human side of the change — communication, training and the theory of change — and package eight covers risk management.

Three expectations apply to every package. **Stakeholders first:** the cycle starts with a business or mission analysis in the sense of the INCOSE Systems Engineering Handbook (fifth edition), and every package brings in the perspectives of the stakeholders in each lifecycle stage. Because SolarX is a fictional case, this runs on stated assumptions until real stakeholders can be engaged (task 0.15). **Explicit decisions and trade-offs:** design and business decisions are taken through a documented process, with the trade-offs across economy, ecology and equity written down (task 0.16 — still to be detailed). **Verification and validation throughout:** each package plans how its outputs are checked, rather than leaving it to the end (task 0.18).

|           |                                              |                 |                                                                                                                                                                                                                                                                                                    |
|-----------|----------------------------------------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.**   | **Work package**                             | **Who**         | **What it owns**                                                                                                                                                                                                                                                                                   |
| **Zero**  | Integration and roll-up                      | Task-Force lead | The top-level claim, the three composition rules, the shared decisions, governance, and the honesty of what gets published, system purpose, principles that need to be followed to achieve that purpose, the definition of the system of interest and how it fits into the wider system of systems |
| **One**   | Business model                               | Group 1         | The service business model and the financial case, including the comparison against a conventional baseline                                                                                                                                                                                        |
| **Two**   | Product regeneration                         | Group 2         | Regeneration expressed as formal, verifiable engineering: requirements, architecture, and the flows the conventional model ignores                                                                                                                                                                 |
| **Three** | Lifecycle and financial assessment           | Group 3         | The verified environmental numbers, and how every claimed outcome would be measured and verified                                                                                                                                                                                                   |
| **Four**  | System dynamics                              | Group 4         | How the business behaves over thirty years, and whether the regenerative effects compound                                                                                                                                                                                                          |
| **Five**  | Digital engineering                          | Group 5         | Proving by machine that all the models describe one and the same system                                                                                                                                                                                                                            |
| **Six**   | Enabling systems / Enabled systems           | Group 6         | Whether the real world — policy, markets, supply chains, grid, standards, governance — can support any of it, including implementation along the supply chain                                                                                                                                      |
| **Seven** | Communication, training and theory of change | Task-Force      | The human side of the change: communication with stakeholders, training, the theory of change, and dissemination of the results                                                                                                                                                                    |
| **Eight** | Risk management                              | Task-Force      | Identifying, assessing and managing the risks to the regenerative business and to the project — the risk basis for the risk-adjusted comparison                                                                                                                                                    |

### Why package zero is real work, not administration
Six groups can each pass their own acceptance test and the central claim can still be unproven, because the claim lives in the links between their work rather than in the work itself. Somebody has to run the three composition rules, decide when an input has failed its test, and say “unanswered” out loud when that is the honest result. That is what package zero is.

It also holds the decisions that six groups are waiting on, and the uncomfortable items: the unowned success criterion, the risk of overclaiming the method, the absence of a governance document, and the question of whether traditional ecological knowledge — which the project's own principles call first-class engineering knowledge — is going to be engaged properly or honestly deferred.

## How a task is written
There are seventy-seven tasks. Every one carries the same five fields, so that a task can be picked up by someone who was not in the meeting where it was created. (This count predates the tasks added in version 0.3 and will be updated once they are agreed.)

|                         |                                                                                                                                                                |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Field**               | **Purpose**                                                                                                                                                    |
| **Deliverable**         | The things that can exist when the task is done — a document, a model, a dataset, a figure. Not an activity.                                                   |
| **Depends on / blocks** | Both directions, so the effect of a delay is visible immediately rather than discovered later.                                                                 |
| **Size**                | Small is up to about three focused days; medium is one to two weeks; large is three to six weeks of part-time volunteer work. For sequencing, not for billing. |
| **Milestone**           | Which of the six milestones the task belongs to.                                                                                                               |
| **Done when**           | The single condition that makes the task closable. A task with no closable condition is a discussion, not a task.                                              |

*Owners and target dates are left blank throughout, on purpose. The plan is built on dependency order, which does not change when the calendar does.*

## The six milestones
Each milestone has a gate condition — the thing that must be true to pass it — and an empty date for the Task-Force to set.

|           |                                  |                                                                                                                                                                                                            |                          |
|-----------|----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| **No.**   | **Milestone**                    | **Gate condition**                                                                                                                                                                                         | **Target date**          |
| **Zero**  | Decisions taken                  | Target numbers set; leads and dates assigned; governance document adopted; the two scope-honesty statements written down                                                                                   | \_\_\_\_\_\_\_\_\_\_\_\_ |
| **One**   | Foundations unblocked            | Revenue architecture confirmed; the regenerative system functions named; bankability filter delivered; three behaviour diagrams drafted; lifecycle assessment scope defined; measurement protocol complete | \_\_\_\_\_\_\_\_\_\_\_\_ |
| **Two**   | Gate inputs complete             | Costed component list; verified emissions figure; stability assessment; consistency verdict; the unsubsidised gate case built                                                                              | \_\_\_\_\_\_\_\_\_\_\_\_ |
| **Three** | Viability gate assessed          | The verdict published as yes, no, or unanswered — never one reported as another                                                                                                                            | \_\_\_\_\_\_\_\_\_\_\_\_ |
| **Four**  | Questions two and three answered | Condition set confirmed by all three groups, plus the published list of what could not be verified; traceability matrix complete and machine-checked                                                       | \_\_\_\_\_\_\_\_\_\_\_\_ |
| **Five**  | Cycle published                  | Synthesis report, honest scope statement, dissemination material                                                                                                                                           | \_\_\_\_\_\_\_\_\_\_\_\_ |

> **Milestone three is a gate, not a review**
>
> A review asks how the work is going. A gate asks whether a specific condition is met. If an input is missing or has failed its acceptance test at milestone three, the correct response is more work — not a softened rule.
>
> Weakening a composition rule to make an answer reachable is the one thing this plan forbids outright. If a rule cannot be satisfied, the honest output is “unanswered”, and that is a legitimate research result.

## The five decisions that unblock everything else
If this cycle stalls, it will stall on one of these five. They are the first agenda items, in this order — not parallel tasks.

|         |                                        |                                                                                                                                                                                                     |
|---------|----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.** | **What**                               | **Why it gates so much**                                                                                                                                                                            |
| **1**   | Set the eight target numbers           | Gates the business-model pricing, the product requirements, the measurement thresholds and the behaviour-model parameters — all at the same time. Seven of the eight outcomes have no number today. |
| **2**   | Confirm the revenue architecture       | Front of the pipeline. The behaviour diagrams and the bankability filter both wait on it.                                                                                                           |
| **3**   | Deliver the bankability filter         | The gate case cannot be assembled honestly without it. A positive value built on revenue nobody can transact is not an answer.                                                                      |
| **4**   | Name the regenerative system functions | Four groups are waiting for a concrete answer to what this system actually does that a conventional one does not. It is the cheapest task in the plan.                                              |
| **5**   | Draw the three behaviour diagrams      | The behaviour model is the biggest missing piece in the project, and its structural work is blocked by nothing at all.                                                                              |

## What can start immediately
Nineteen of the seventy-seven tasks have no upstream dependency whatsoever. Nobody needs to leave the first meeting with nothing to do.

-   **Package zero:** all six decision-and-governance tasks, plus opening the missing repository issues.

-   **Package one:** defining the conventional comparison baseline.

-   **Package two:** naming the regenerative system functions.

-   **Package three:** verifying what the existing financial model really contains, and completing the measurement protocol.

-   **Package four:** the economic and social behaviour diagrams.

-   **Package five:** developing the integrated ontology past its scope stage.

-   **Package six:** all six current-state assessments — these can run in parallel across several contributors, which makes this the easiest package to bring new people into.

## How the packages depend on each other
Four streams run roughly in parallel and converge at the viability gate.

|                   |                                                                               |                                                                     |
|-------------------|-------------------------------------------------------------------------------|---------------------------------------------------------------------|
| **Stream**        | **Runs from**                                                                 | **Into the gate as**                                                |
| **Commercial**    | Target numbers → revenue architecture → bankability filter → gate case        | The financial verdict itself                                        |
| **Physical**      | System functions → architecture and lifecycle states → costed components      | The cost inputs, traceable to real components                       |
| **Environmental** | Materials and lifecycle stages → assessment scope → dataset → verified figure | The emissions figure that validates or kills the low-carbon premium |
| **Behavioural**   | Three diagrams → integrated diagram → parameterised model → thirty-year runs  | The verdict on whether the assumptions survive time                 |

Running alongside all four, continuously rather than in phases, is the digital-engineering package: whenever any group lands a material change, the automated checks re-run and the consistency report updates. Its one time-boxed piece of work is the bridge into the product model.

Three properties of this structure are worth naming. The business-model package sits both at the front and at the back — it supplies what everyone reacts to, then assembles the gate case from four groups' outputs, so its work splits across two milestones rather than running as one block. The enabling-systems package inverts its own priorities, delivering the smaller bankability question before its headline landscape research, because the gate needs the former. And the behaviour package, though it is the biggest gap, is also the least blocked.

# Part Three — The work packages
Each chapter follows the same shape: what the package is for, why it exists, its tasks, what it needs from other groups, what it gives back, and the one thing that must not slip. Task numbers are written as “Task 1.5”, meaning task five of package one.

## Work package Zero — Integration and roll-up
**Task-Force lead**

### Purpose
Hold the top-level goal. Make the decisions six groups are waiting on, run the three composition rules that turn seventeen sub-answers into three answers, and keep the project honest about what it has not shown.

### Why this package exists
This package exists because the central claim lives in the links between the groups' work rather than in the work itself. Nobody inside a single group can see whether the whole thing composes.

It also carries the items nobody else will raise: a success criterion with no owner, the temptation to overclaim a method validated in one industry, the absence of a governance structure, and a stated principle about traditional ecological knowledge that has no protocol behind it.

### The tasks
|          |                                                                                                            |                                    |                      |                                                                                                                                                                                                                                                               |
|----------|------------------------------------------------------------------------------------------------------------|------------------------------------|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.**  | **Task**                                                                                                   | **Depends on**                     | **Size**             | **Done when**                                                                                                                                                                                                                                                 |
| **0.1**  | Set the numeric targets and baselines for all eight desired outcomes, system purpose and design principles | —                                  | Medium               | All eight carry a number and a named source, or are explicitly recorded as deliberately unquantified with the consequence for dependent work stated. system purpose and design principles are defined and communicated integrated within the different groups |
| **0.2**  | Fix the cycle calendar, the package leads and the repository labels                                        | —                                  | Small                | Every milestone has a date, every package has a named lead, and the stale group labels are replaced                                                                                                                                                           |
| **0.3**  | Give social value an owning sub-question, or accept weaker evidence for it                                 | —                                  | Small                | No success criterion is left unowned                                                                                                                                                                                                                          |
| **0.4**  | Write the scope statement that prevents overclaiming the method                                            | —                                  | Small                | The wording exists, is agreed, and is the wording used in every external output this cycle                                                                                                                                                                    |
| **0.5**  | Write the governance document                                                                              | —                                  | Medium               | A new contributor can read one page and know who decides what, and how their work becomes a Task-Force output                                                                                                                                                 |
| **0.6**  | Engagement and consent protocol for traditional ecological knowledge, or an explicit deferral              | —                                  | Small                | The project's stated principle is either operationalised or honestly deferred in writing                                                                                                                                                                      |
| **0.7**  | Stand up the live evidence ledger and traceability matrix                                                  | 0.2                                | Small, then standing | Anyone can see, per cell, whether it is not started, drafted or validated — and therefore how far each question is from answerable                                                                                                                            |
| **0.8**  | Agree the interface contracts between groups                                                               | 1.2, 2.1                           | Medium               | Each of the fourteen handovers has an agreed format and an acceptance condition the receiving group signed up to                                                                                                                                              |
| **0.9**  | Run the viability gate roll-up                                                                             | 1.5, 1.6, 2.8, 3.7, 4.11, 5.8, 6.1 | Medium               | The verdict is published as yes, no or unanswered, with each of the six inputs shown as accepted or failed, and the three dishonest-pass modes checked explicitly                                                                                             |
| **0.10** | Run the condition roll-up                                                                                  | 0.9, 1.8, 4.6, 6.11                | Medium               | Two lists exist: conditions confirmed by all three groups, and conditions claimed but unverified                                                                                                                                                              |
| **0.11** | Run the traceability roll-up                                                                               | 1.9, 2.7, 3.10, 4.12, 5.5          | Medium               | All thirty-two links are machine-validated, or recorded as not achieved with a reason                                                                                                                                                                         |
| **0.12** | Write the cycle synthesis and dissemination package                                                        | 0.9, 0.10, 0.11                    | Large                | The report states what was shown, what was not shown, and what the next cycle needs — with any “unanswered” in the summary, not an appendix                                                                                                                   |
| **0.13** | Standing triple-top-line and devil's-advocate audit                                                        | 0.7                                | Medium               | Each of the eight outcomes is checked for whether its gain is funded by a loss elsewhere, and the finding is written down                                                                                                                                     |
| **0.14** | Open the missing repository issues                                                                         | this plan being agreed             | Small                | Every task in this plan is an issue on the board, with labels, sizes and blocking links set                                                                                                                                                                   |
| **0.15** | Run the business or mission analysis and identify the stakeholders and their needs                         | —                                  | Medium               | Stakeholders and their needs are listed for each lifecycle stage, following the INCOSE Systems Engineering Handbook (fifth edition). Every need that rests on an assumption is marked as one, since SolarX is fictional                                       |
| **0.16** | Define the decision-making and trade-off process                                                           | 0.5                                | Small                | Major design and business decisions are taken against stated criteria across economy, ecology and equity, and recorded with their trade-offs and rationale. To be detailed                                                                                    |
| **0.17** | Define the system of interest and how it fits into the wider system of systems                             | —                                  | Small                | All groups agree what is inside the system of interest, what is an enabling system, and which neighbouring systems — grid, land, community, supply chain — it interacts with                                                                                  |
| **0.18** | Plan verification and validation across all packages                                                       | 0.7, 0.17                          | Medium               | Each package states how its outputs are verified (built right) and validated (the right thing built), and the plan is linked to the traceability matrix                                                                                                       |

### What this package needs from others
-   Nothing from the groups to start. Tasks 0.9 to 0.11 need every group's gate inputs.

### What it gives back
-   The decisions that unblock all six groups; the shared status view; the three verdicts; the published output.

> **The thing that must not slip**
>
> Tasks 0.9 to 0.11 cannot be delegated — they are the point of the package. Tasks 0.5 and 0.7 can and should be, early, because this package otherwise sits entirely on one person while owning the top-level answer.

## Work package One — Business model
**Group 1**

*Support: Jelena, Kai*

### Purpose
Design the solar-as-a-service business model and prove with a financial model that it stands without subsidy — then identify the conditions under which it beats a conventional solar business.

### Why this package exists
Conventional solar is sold as a product: a linear material flow, a single revenue stream, and most of the lifetime value leaving the community that hosts it. The open question is commercial rather than moral — whether a service business that internalizes ecological and social value can still earn an acceptable return on its own economics.

One decision is already locked: the business is a service, not a sale. The company keeps the physical assets and sells the outcome — clean energy, and the ecological and social value that comes with it — as an ongoing service. This settles an old contradiction in the project's material, where the financial model assumed ownership while the behaviour diagram assumed leasing.

**Future first, then present.** The business model is designed in four steps: initiate; understand the present (SolarX as it is today); imagine the far future — as far ahead as we can go without getting laughed at; then name the gap between the two and design the next steps that close it. What is the gap, what do we need to get there, and what is the next step? The "Future first, then present" marking on tasks 1.2 to 1.4 refers to this sequence.

### The tasks
|          |                                                                                              |                    |          |                                                                                                                                                                    |
|----------|----------------------------------------------------------------------------------------------|--------------------|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.**  | **Task**                                                                                     | **Depends on**     | **Size** | **Done when**                                                                                                                                                      |
| **1.1**  | Define the conventional solar **baseline** the comparison is made against                    | —                  | Medium   | A reader can reproduce the baseline from the definition alone: scale, market and regulatory context, cost and revenue assumptions, horizon, metric                 |
| **1.2**  | Confirm the revenue architecture, line by line (Future first, then present)                  | 0.1                | Medium   | Every value line is confirmed, corrected or removed, with a figure, a source, the outcome it monetises, and the scenario it belongs in                             |
| **1.3**  | Formalise the business model on the flourishing business canvas (Future first, then present) | 1.2                | Medium   | It is a service model throughout, with no ownership contradiction left, and its concepts resolve to entries in the shared vocabulary                               |
| **1.4**  | Recast the financial model for a service business (Future first, then present)               | 1.2                | Large    | The model runs end to end on the service structure and reproduces the earlier ownership case as a sanity check                                                     |
| **1.5**  | Build the unsubsidised gate case                                                             | 1.4, 6.1, 2.8, 3.7 | Medium   | The unsubsidised case is run explicitly rather than derived by adjustment, and every input is either a delivered figure or a flagged placeholder                   |
| **1.6**  | Build the scenario set and compute the headline results                                      | 1.5                | Medium   | At least three scenarios — gate, optimistic, stress — each producing present value, return and payback, with speculative revenue visibly absent from the gate case |
| **1.7**  | Run the sensitivity analysis on the enabling-system conditions                               | 1.6, 6.11          | Medium   | Each condition shows direction and magnitude, and it is visible which flip the outcome rather than merely moving it                                                |
| **1.8**  | Produce the risk-adjusted comparison against the baseline                                    | 1.1, 1.7           | Medium   | The risk-adjustment method is stated, and the output is a set of conditions under which regeneration wins, matches or loses                                        |
| **1.9**  | Fill the feasibility column of the traceability matrix                                       | 1.3, 1.6, 4.5      | Medium   | Every outcome reaches a canvas block and a financial line, or is explicitly recorded as non-bankable with a reason                                                 |
| **1.10** | Build the assumption register                                                                | 1.4                | Medium   | Every material assumption is listed individually with its value, source and confidence — this is also the behaviour group's input list                             |

### What this package needs from others
-   The eight target numbers, to price the ecological and social lines at all.

-   The costed component list from the product group, for capital and operating costs.

-   The verified emissions figure from the lifecycle group, to justify the low-carbon premium.

-   The bankability classification from the enabling-systems group. Without it the gate case cannot be assembled honestly.

-   Flags from the behaviour group on assumptions that do not survive thirty years.

### What it gives back
-   The confirmed business model and revenue architecture, which unblocks the behaviour diagrams and tells the enabling-systems group which conditions are worth studying.

-   A priority signal to the product group: which outcomes are load-bearing, and therefore which requirements matter most.

> **The thing that must not slip**
>
> The comparison baseline. It is undefined anywhere in the project today, and the headline claim is a comparison — without a defined baseline the claim can be neither proved nor disproved.
>
> This package is loaded twice, at the front and at the back of the pipeline. If the group has one contributor, tasks 1.1 to 1.4 and tasks 1.5 to 1.10 should really be different people.

## Work package Two — Product regeneration
**Group 2**

*Support: Axel; Kirk (traceability from requirements to mission, concept of operations and sustainability architecture)*

### Purpose
Define what it means for a product to be regenerative in engineering terms, and formalise it in the system model — from requirements, through architecture, to the ecological and social flows the conventional model does not represent at all.

### Why this package exists
Regeneration is currently argued in prose and priced in spreadsheets. Neither is engineering. If an outcome such as “soil organic carbon stable or increasing” cannot be written as a requirement, allocated to a system element and traced to a flow the system actually produces, then it is an aspiration rather than a design.

The existing model of the conventional solar company describes how sunlight becomes electricity. It says nothing about how the system regenerates soil, supports biodiversity or builds community wealth, and it has connection points for energy and data only — no water, no biological capital, no material cycles. That absence is the gap this package closes.

### The tasks
|          |                                                                                                                                                                                                 |                |          |                                                                                                                                                                |
|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.**  | **Task**                                                                                                                                                                                        | **Depends on** | **Size** | **Done when**                                                                                                                                                  |
| **2.0**  | Model the Baseline System                                                                                                                                                                       |                |          |                                                                                                                                                                |
| **2.1**  | Name the roughly five regenerative system functions                                                                                                                                             | —              | Small    | Five functions, give or take one, each stated as something the system does, with a candidate mechanism and its technology-maturity rating                      |
| **2.2**  | Write a formal requirement for each of the eight outcomes                                                                                                                                       | 2.1            | Medium   | The model validates in the modelling tool; no outcome is without a requirement; no target value is invented — each is sourced or marked as still to be decided |
| **2.3**  | Insert the agreed target values as requirement constraints                                                                                                                                      | 0.1, 2.2       | Small    | Every placeholder is replaced with a sourced value or documented as remaining open, with the reason                                                            |
| **2.4**  | Extend the architecture with the new physical and organisational elements                                                                                                                       | 2.1            | Large    | Each new element traces to at least one regenerative function; earlier modelling steps are extended in order, never overwritten                                |
| **2.5**  | Define the connection points and flows for water, biological capital, material recovery and social flows                                                                                        | 2.4            | Medium   | The model represents flows the conventional model has no connection points for                                                                                 |
| **2.6**  | Model the lifecycle states: installation, operation, end of life. Decide first which lifecycles, and how many, are modelled — for example the plant, the modules, the land use and the business | 2.4            | Medium   | Each state names the flows and functions active in it — this is what makes the end-of-life costs traceable rather than assumed                                 |
| **2.7**  | Produce the traceability report for the product column                                                                                                                                          | 2.3, 2.5, 2.6  | Medium   | Every requirement has at least one satisfying architecture element — no orphans — and the whole chain validates                                                |
| **2.8**  | Derive the costed component list                                                                                                                                                                | 2.4, 2.6       | Medium   | The business-model group can audit any figure back to a named element. A cost that traces to a spreadsheet assumption fails                                    |
| **2.9**  | Hand the material definitions and lifecycle stages to the lifecycle group                                                                                                                       | 2.4, 2.6       | Small    | The lifecycle group confirms it can start its assessment from this handover alone                                                                              |
| **2.10** | Run variant and trade-off analyses of the design choices — including designs inspired by natural systems — and identify which choices are contingent, and on what                               | 2.7, 6.8       | Medium   | Every contingent element names the external condition it depends on, cross-referenced to the enabling-systems classification                                   |
| **2.11** | Trace the requirements to the mission, the concept of operations and the sustainability architecture                                                                                            | 2.2, 0.15      | Medium   | Every requirement traces upward to a mission objective and an operational scenario, and the sustainability architecture is consistent with both                |

### What this package needs from others
-   The eight target numbers — these block the requirement constraints, though not the requirement structure.

-   The business-model group's signal on which outcomes are load-bearing.

-   The enabling-systems group's findings on which supply-chain options actually exist.

### What it gives back
-   The costed component list the financial model consumes.

-   Material definitions and lifecycle stages, without which the environmental assessment cannot start.

-   The system functions that become variables in the environmental behaviour diagram.

-   The product side of the semantic bridge, so cross-model consistency can be checked.

> **The thing that must not slip**
>
> Task 2.1 — naming the functions — is the cheapest task in the whole plan and four groups are waiting on it. It is one page. Do it first.
>
> Task 2.9 is small and holds up something large: the environmental assessment is blocked until the materials handover lands.

## Work package Three — Lifecycle and financial assessment
**Group 3**

*Support: Kirk (tracing measures to requirements and the concept of operations); Reza Sorour (verification and validation through the digital thread, from next year). To consult: Gary, on the other quality attributes*

### Purpose
Quantify the environmental performance of the regenerative system, feed the verified result back into the financial model, and define the measurement protocol that stops every other claimed outcome from being an assertion.

### Why this package exists
The business case prices a low-carbon premium. That premium only exists if the lifetime emissions figure is real, verified and low enough to qualify — which requires an assessment that does not yet exist. The current baseline uses published figures for conventional modules at a European average. A regenerative version changes module sourcing, construction, operation and end-of-life recovery, and nobody has quantified the difference.

Worse: seven of the eight outcomes have no independent measurement path at all. Soil carbon, biodiversity and community wealth are claimed in the model and priced in the spreadsheet, and nothing verifies them. If that stays true, the whole claim rests on self-reported outcomes — which is precisely the failure mode the project's own critiques of regenerative finance warn about.

### The tasks
|          |                                                                                                                                                                                                                       |                |          |                                                                                                                                                                                                       |
|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.**  | **Task**                                                                                                                                                                                                              | **Depends on** | **Size** | **Done when**                                                                                                                                                                                         |
| **3.1**  | Verify what the existing financial model actually contains, as the baseline                                                                                                                                           | —              | Small    | Built versus specified is documented per sheet, with the checked formulas named. Not blocked — start now                                                                                              |
| **3.2**  | Complete the measurement protocol                                                                                                                                                                                     | —              | Medium   | Each outcome has a measurement method, a baseline requirement, an attribution method and a named external verification standard. Self-reported outcomes are labelled as such. Not blocked — start now |
| **3.3**  | Set the measurement thresholds and instruments                                                                                                                                                                        | 0.1, 3.2       | Medium   | Every threshold traces to a target number, and the social-outcome instruments exist as usable drafts                                                                                                  |
| **3.4**  | Write the field-test plan and run its feasibility check                                                                                                                                                               | 3.3            | Medium   | A named person could execute it at a named site, with cost and effort per outcome stated. Execution needs a real system at a real site; this cycle delivers the plan                                  |
| **3.5**  | Define the lifecycle assessment scope                                                                                                                                                                                 | 2.1, 2.9       | Medium   | Boundary, functional unit, impact categories and exclusions are all decided explicitly rather than left implicit                                                                                      |
| **3.6**  | Assemble the lifecycle dataset                                                                                                                                                                                        | 3.5, 2.9, 6.4  | Large    | Every entry has a provenance — a published declaration, a database record, or a documented proxy clearly marked as a proxy                                                                            |
| **3.7**  | Run the regenerative-scenario assessment                                                                                                                                                                              | 3.6            | Large    | The figure is backed by published environmental declarations and conforms to the recognised methodology across the full system. The greenhouse-gas threshold is explicitly met or explicitly missed   |
| **3.8**  | Produce the stage-by-stage difference against the baseline                                                                                                                                                            | 3.7, 1.1       | Medium   | Each lifecycle stage carries its own difference; no single aggregate stands in for the analysis                                                                                                       |
| **3.9**  | Quantify how that difference changes under different conditions                                                                                                                                                       | 3.7, 6.4       | Medium   | Module sourcing and end-of-life recovery are quantified as separate conditions, not bundled                                                                                                           |
| **3.10** | Close the loop back into the financial model                                                                                                                                                                          | 3.7, 5.4, 2.7  | Large    | A change in the system model produces a changed environmental result that produces a changed return — without manual re-entry, at least once                                                          |
| **3.11** | State plainly which outcomes cannot be measured                                                                                                                                                                       | 3.4            | Small    | The list exists and appears in the synthesis report rather than being quietly dropped                                                                                                                 |
| **3.12** | Identify the other quality attributes (the "-ilities") — such as resilience, reliability, maintainability, repairability and recyclability — and trace each measure to the requirements and the concept of operations | 3.2, 2.2       | Medium   | Each relevant attribute has a measure, a source and a trace to a requirement; attributes judged out of scope are listed with a reason                                                                 |
| **3.13** | Extend the assessment to a social lifecycle assessment                                                                                                                                                                | 3.5            | Large    | Community wealth and energy access are evidenced through a social lifecycle assessment following a recognised guideline, giving success criterion five its own measurement path                       |

### What this package needs from others
-   Material definitions and lifecycle stages from the product group. The assessment cannot start without a defined system.

-   The revenue lines whose environmental claims need validating.

-   The data bridge from the digital-engineering group, to carry results between models.

### What it gives back
-   The verified emissions figure that validates or kills the low-carbon premium. This is a gate input: the business model cannot price that outcome without it.

-   Environmental parameters for the behaviour model.

-   The measurement protocol, which is the evidence standard behind every outcome claim in the project.

> **The thing that must not slip**
>
> If a missed greenhouse-gas threshold is discovered, the business-model group must hear about it immediately — it invalidates a revenue line in the gate case.
>
> This is the highest data-availability risk in the plan. Verified low-carbon module data may simply not be obtainable. If so, escalate at milestone one. The fallback is a documented proxy clearly marked as a proxy — never a modelled estimate presented as verified, which would fail the acceptance test and quietly break the gate.

## Work package Four — System dynamics
**Group 4**

*Support: Ivan, Sannelie, Ali*

### Purpose
Model how the service business behaves over time — as a living system where economic, social and environmental factors reinforce or undermine each other — and prove or disprove that the regenerative effects actually compound over thirty years.

### Why this package exists
Regeneration is defined in this project as an outcome that rises repeatedly and partly sustains itself. That is a claim about behaviour over time. A financial model is an accounting snapshot projected forward; it cannot test the claim, because it assumes its own parameters stay put.

Two failure modes hide in that gap. A business case can look strong in year one and be eroded by feedback the spreadsheet never represents. And rebound effects — where an efficiency gain increases consumption, or a revenue success attracts competition that erases the margin — will never surface in a static model.

### The tasks
|          |                                                                                                                             |                          |          |                                                                                                                                                                               |
|----------|-----------------------------------------------------------------------------------------------------------------------------|--------------------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.**  | **Task**                                                                                                                    | **Depends on**           | **Size** | **Done when**                                                                                                                                                                 |
| **4.1**  | Build the economic behaviour diagram (priority one)                                                                         | —                        | Medium   | Revenues, costs, investment, returns and market dynamics, with every variable resolving to an entry in the shared vocabulary                                                  |
| **4.2**  | Build the social behaviour diagram (priority three)                                                                         | —                        | Medium   | Community wealth, trust, employment, energy access and governance, including the trust-to-permitting-speed loop                                                               |
| **4.3**  | Build the environmental behaviour diagram (priority two)                                                                    | 2.1                      | Medium   | Soil carbon, biodiversity, water, lifetime emissions and material flows, using the product group's system functions as variables                                              |
| **4.4**  | Reconcile the existing diagram with the confirmed business model                                                            | 1.2, 1.3                 | Medium   | The reconciliation is verified through the automated pipeline, not by eye                                                                                                     |
| **4.5**  | Integrate the three diagrams into one                                                                                       | 4.1, 4.2, 4.3, 4.4       | Medium   | Cross-perspective links are drawn explicitly; each of the eight outcomes appears as a stock or a driver of one, or is recorded as not dynamically modelled with a reason      |
| **4.6**  | Catalogue and classify every feedback loop                                                                                  | 4.5                      | Medium   | Each loop is classified as self-reinforcing with positive effect, self-reinforcing with negative effect, or balancing — and traces to variables present in the business model |
| **4.7**  | Search explicitly for rebound effects                                                                                       | 4.6                      | Medium   | The report names where rebound was looked for and what was found, including “none identified in this structure”. Absence must be demonstrated, not assumed                    |
| **4.8**  | Analyse the leverage points                                                                                                 | 4.6                      | Medium   | Leverage points are ranked and each names the loop it acts on                                                                                                                 |
| **4.9**  | Parameterise the model                                                                                                      | 0.1, 4.4, 4.5, 1.10, 3.7 | Large    | The model runs over thirty years and its parameters trace to the target numbers, the assumption register and the environmental figures                                        |
| **4.10** | Run the long-term (horizon to be decided; thirty years as the working assumption) scenarios and settle the compounding test | 4.9                      | Medium   | The compounding criterion is answered either way. If nothing compounds, that is reported plainly                                                                              |
| **4.11** | Assess the dynamic stability of every load-bearing financial assumption                                                     | 1.10, 4.9, 4.10          | Medium   | Every assumption in the register is addressed, and each flag names the specific loop that undermines it                                                                       |
| **4.12** | Register every variable in the shared vocabulary defined by the digital-engineering package                                 | 4.5, 5.1                 | Small    | No parallel vocabulary exists; the existing concept register is extended rather than duplicated                                                                               |

### What this package needs from others
-   The confirmed business model, revenue architecture and cost structure. This is the primary blocker: a diagram cannot be reconciled with a business model that has not been confirmed.

-   Environmental parameters from the lifecycle group.

-   The shared vocabulary and generated diagram from the digital-engineering group.

-   The enabling-systems group's view on which external conditions to treat as fixed inputs rather than modelled variables.

### What it gives back
-   The verdict on which financial assumptions are dynamically unstable, and which loops tip the risk-adjusted comparison.

-   Which system-level feedbacks need designing into the architecture.

-   Which enabling systems sit on self-reinforcing loops and therefore compound.

> **The thing that must not slip**
>
> A negative result here is still a result. If no loop compounds over thirty years, the self-sustaining claim is unsupported regardless of what the financial model says — and that is a finding about the design, not a failure to deliver.
>
> The choice of modelling tool is a small decision that becomes expensive to revisit once a model exists. Make it before parameterisation starts and record it.

## Work package Five — Digital engineering
**Group 5**

*Support: Ali, Sannelie, the DEIX working group*

### Purpose
Provide and validate the formal bridge between the project's modelling domains — the business canvas, the behaviour diagram, the system model and the environmental assessment — so that consistency between them is a machine-checkable fact rather than an assurance.

### Why this package exists
Five groups are modelling the same system in four incompatible notations. “Community equity” appears as a block on the business canvas, a variable in the behaviour diagram, a line in the capital structure, and a requirement in the system model. Nothing currently guarantees these are the same thing, and nothing detects it when they drift apart.

That is not a documentation problem — it is the methodological claim itself. The third research question asks whether ecological, social and economic outcomes can be optimised together through an integrated method. Integration that cannot be verified is not integration; it is a diagram of one.

### The tasks
|         |                                                                                  |                              |                       |                                                                                                                                                                       |
|---------|----------------------------------------------------------------------------------|------------------------------|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.** | **Task**                                                                         | **Depends on**               | **Size**              | **Done when**                                                                                                                                                         |
| **5.1** | Define the shared vocabulary to all six groups' concepts                         | 1.3, 4.1 to 4.3 as they land | Medium                | Every concept any group uses resolves to an entry, and concepts that do not are reported as gaps with the owning group named                                          |
| **5.2** | Build the bridge into the product model                                          | 2.2                          | Large                 | The bridge validates, and the chain from outcome to requirement to architecture is checked by machine                                                                 |
| **5.3** | Extend the automated checks and the defect tests                                 | 5.1, 5.2                     | Medium                | Injected defects — a broken chain, a dangling link, a wrong loop polarity — fail the build. A pipeline that never fails proves nothing                                |
| **5.4** | Wire the data path that carries environmental results                            | 5.2                          | Medium                | The lifecycle group can close its loop through this path without manual re-entry                                                                                      |
| **5.5** | Maintain a standing consistency report                                           | 5.1, 5.3                     | Medium, then standing | The check suite runs end to end and the output is a report rather than a judgement call, naming discrepancies plainly — including ones inconvenient for another group |
| **5.6** | Develop the integrated ontology past its scope stage                             | —                            | Large                 | Each of its competency questions can be answered by a query against the graph rather than by reading a document                                                       |
| **5.7** | Generalise the integration method so another project could apply it              | 5.2, 5.6                     | Medium                | The method is readable and applicable without knowledge of solar or of this project's particular canvas                                                               |
| **5.8** | Deliver the consistency verdict the gate needs                                   | 5.2, 5.3, 5.5                | Small                 | The invariants pass and every concept used in the financial model resolves to an entry. Delivered before the gate meeting, not at it                                  |
| **5.9** | What can we do with the Digital engineering System? Generate Insights, DPP, etc. |                              |                       |                                                                                                                                                                       |

### What this package needs from others
-   Concept definitions from every group. This package cannot invent domain content; it formalises what the others decide.

### What it gives back
-   To the business-model group: assurance that the model and the behaviour diagram describe one system.

-   To the product group: the mapping between the system model and the behaviour diagram, reusable elsewhere.

-   To the lifecycle group: the data pipeline carrying results between models.

-   To the behaviour group: the generated diagram and the variable vocabulary.

-   To the Task-Force: the consistency verdict, which is an input to the viability gate.

> **The thing that must not slip**
>
> The boundary that matters: this package owns whether the models agree, never whether they are right about the world. A vocabulary that validates cleanly can still describe a bad business model — and when it does, say so. A green check must never be mistaken for a sound design.
>
> The bridge into the product model is what turns the method claim from “demonstrated between two domains” into “demonstrated across the method”. Start it as soon as the product group produces its first requirements.

## Work package Six — Enabling systems
**Group 6**

### Purpose
Study the external conditions — policy, market, infrastructure, standards, governance — that must exist for the regenerative system and its business model to work in practice. This is the reality check.

### Why this package exists
A business model can have a positive present value, self-reinforcing ecological loops and genuine community wealth creation — and still be a non-starter. If there is no legal route to combining energy generation with agriculture on the same land, if biodiversity credits cannot be verified, if no low-carbon module manufacturer exists, if the grid operator will not accommodate the operating model, or if no governance structure exists for sharing benefits locally, then the model has a blocker rather than a gap.

This package maps every such dependency and answers one question: which of these are blockers, which are accelerators, and which can be skipped while still having a viable regenerative business?

**A note on the term.** In ISO/IEC/IEEE 15288 and the INCOSE Systems Engineering Handbook (fifth edition), an enabling system supports the system of interest during its lifecycle stages without necessarily contributing directly to its function in operation — production, supply, maintenance and recycling systems, for example. This package uses the term more broadly, to include the policy, market and governance conditions around the business. The definition still has to be checked against the Handbook and set alongside the enabling conditions described in the IPBES business and biodiversity assessment (2026), and adjusted where they differ.

### The tasks
|          |                                                                    |                |          |                                                                                                                                                                                                                                              |
|----------|--------------------------------------------------------------------|----------------|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **No.**  | **Task**                                                           | **Depends on** | **Size** | **Done when**                                                                                                                                                                                                                                |
| **6.0**  | Baseline                                                           |                |          |                                                                                                                                                                                                                                              |
| **6.1**  | Build the revenue-line bankability filter                          | 1.2            | Medium   | Every revenue line is classified as transactable now, needing an enabling system, or speculative — each with a named market precedent or a named missing enabler                                                                             |
| **6.2**  | Assess the policy and regulatory landscape                         | —              | Medium   | Dual-use land permits, biodiversity credit schemes, soil-carbon frameworks, community energy regulation and environmental impact assessment — each assessed against a named source                                                           |
| **6.3**  | Assess the market and financial infrastructure                     | —              | Medium   | The low-carbon premium mechanism, biodiversity credit markets, community finance vehicles, green lending and regenerative-risk insurance. The premium and the community-capital effect get the most rigorous treatment, being load-bearing   |
| **6.4**  | Assess the supply chain and materials (Regeneration / Circularity) | —              | Medium   | Verified low-carbon module manufacturers, recycling capacity at the project location and its cost, regional manufacturing, and reversible low-impact mounting. Deliver the manufacturer findings first — the lifecycle dataset waits on them |
| **6.5**  | Assess the grid and infrastructure conditions                      | —              | Medium   | Connection rules for dual-use installations, storage policy, demand-response participation and local energy trading                                                                                                                          |
| **6.6**  | Assess the standards and certification landscape                   | —              | Medium   | Regenerative land-management standards, social-outcome coverage in the reporting regimes, and a mapping of the eight outcomes onto existing reporting frameworks                                                                             |
| **6.7**  | Assess the governance and social infrastructure                    | —              | Medium   | Community energy governance proven at scale, multi-party governance, benefit-sharing mechanisms, and local measurement capacity                                                                                                              |
| **6.8**  | Build the classification matrix                                    | 6.2 to 6.7     | Medium   | No system is unclassified as hard blocker, soft enabler or optional amplifier, and each classification cites its source                                                                                                                      |
| **6.9**  | Map the dependencies and the enabling-system feedback loops        | 6.8            | Medium   | The map exists, and the loops identified are handed to the behaviour group rather than treated as static context                                                                                                                             |
| **6.10** | Determine the critical path                                        | 6.8, 6.9, 4.8  | Medium   | The minimum set of enabling systems needed for the claim to hold is stated as a list, not a narrative                                                                                                                                        |
| **6.11** | Produce the candidate condition set                                | 6.10           | Medium   | Every condition is named, classified and state-assessed against a named source, then handed to the business-model group for the decisiveness test and the behaviour group for the persistence test                                           |
| **6.12** | Add an enabling-systems step to the ten-step design approach       | 6.8            | Medium   | The step would have caught a missing enabling system in this pilot — tested retrospectively against a real finding, not asserted                                                                                                             |

### What this package needs from others
-   The confirmed business model and cost structure. Which enabling systems matter depends on which revenue lines are load-bearing.

-   The eight target numbers, to judge whether a given enabling system is sufficient.

-   The architecture and supply-chain choices from the product group.

### What it gives back
-   The bankability classification per revenue line — a gate input.

-   The conditions the sensitivity analysis must test.

-   The supply-chain constraints that shape the system design.

-   Which enabling systems sit on self-reinforcing loops.

> **The thing that must not slip**
>
> The priority inversion is deliberate: the landscape research is this group's headline question, but the bankability filter is what the gate needs. If the two compete for time, the filter wins.
>
> Six categories and roughly twenty-eight systems is broad for a small group. Suggested triage: full depth on market, supply chain and standards; a lighter pass elsewhere — and say in the output which were done lightly rather than presenting an even survey.

## Work package Seven — Communication, training and theory of change
**Task-Force, cross-cutting (draft — to be detailed)**

### Purpose
Look after the human side of the change. A regenerative design only matters if people understand it, trust it and can act on it. This package owns communication with stakeholders, training for contributors and for businesses that want to apply the method, the theory of change that links the project's outputs to real-world change, and the dissemination of results.

### Proposed tasks
-   Write the theory of change: from the project's outputs to the changes in practice they are meant to cause, with the assumptions at each step.

-   Build a communication plan for each stakeholder group, including the lifecycle-stage stakeholders identified in task 0.15.

-   Develop training material on the method, for contributors and for businesses that want to apply it.

-   Prepare the dissemination material for the cycle publication, together with task 0.12.

## Work package Eight — Risk management
**Task-Force, cross-cutting (draft — to be detailed)**

### Purpose
Identify, assess and manage risk systematically — both the risks to the regenerative business itself (market, regulatory, ecological, social, technical) and the risks to the project. This package supplies the risk basis for the risk-adjusted comparison in task 1.8 and for success criterion three.

### Proposed tasks
-   Set up the risk register and the assessment method: likelihood, impact, owner and response.

-   Assess the risks of the regenerative business against the conventional baseline, as input to task 1.8.

-   Assess the ecological and social risks, including the risk of trading one capital against another.

-   Review the plan-level risks in Part Four at every milestone.

# Part Four — Running the cycle
## Risks in the plan itself
The project's own risks are catalogued separately, in a devil's-advocate document that is deliberately kept as written. What follows are risks in this plan — the ways the work as organised here could fail even if every group does its job well.

|                                                        |                                                                                                            |                                                                                                                              |
|--------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| **Risk**                                               | **Why it is real**                                                                                         | **What to do about it**                                                                                                      |
| **The business-model package is loaded twice**         | It supplies the architecture everyone reacts to and then assembles the gate case from four groups' outputs | Split its work across two milestones explicitly; if possible, two people                                                     |
| **The lifecycle data may not exist**                   | Verified low-carbon module data may not be obtainable at all                                               | Escalate at milestone one, not milestone two. Fall back to a clearly labelled proxy, never a dressed-up estimate             |
| **The enabling-systems package is broad for its size** | Six categories, around twenty-eight systems, each needing a sourced assessment                             | Full depth on three categories, a lighter pass elsewhere — and say which were done lightly                                   |
| **A hidden tooling decision**                          | Behaviour-modelling tools are not interchangeable once a model has been built in one                       | Decide before parameterisation starts; record the decision in the group's own notes                                          |
| **Package zero sits on one person**                    | It owns the top-level answer and every shared decision                                                     | Delegate the governance document and the status ledger early; protect time for the three roll-ups, which cannot be delegated |

## If the contributors do not materialise
This is written plainly because it is the likeliest way the cycle goes wrong. With one or two active people the full plan does not shrink gracefully — it stalls at milestone two with five half-finished packages, which is a worse outcome than a smaller finished cycle.

A defensible minimum path, of roughly twenty-five tasks:

|             |                                                             |
|-------------|-------------------------------------------------------------|
| **Package** | **Tasks**                                                   |
| **Zero**    | 0.1 to 0.4, 0.7, 0.9                                        |
| **One**     | 1.1, 1.2, 1.4, 1.5, 1.6, 1.10                               |
| **Two**     | 2.1, 2.2, 2.8                                               |
| **Three**   | 3.1, 3.2, 3.7 — proxy-tolerant and clearly labelled as such |
| **Four**    | 4.1 to 4.5, 4.9, 4.10                                       |
| **Five**    | 5.2, 5.5, 5.8                                               |
| **Six**     | 6.1, 6.3, 6.4                                               |

That subset answers the viability question honestly against a defined baseline, settles the compounding criterion either way, and leaves the conditions question and the method question explicitly partial. Stated up front, that is a respectable result for a first cycle. Deciding it deliberately at the start is a completely different thing from discovering it at the end.

## How to contribute
-   **Read three things first:** this document, the composition rules in the research-decomposition file, and your group's own task brief.

-   **Pick an unassigned task** from the project board and comment to claim it. Nineteen tasks have no upstream dependency at all.

-   **Work on a branch and open a change request** following the repository's own contribution conventions.

-   **Expand every abbreviation on first use** in whatever you write, and add any new one to the project glossary in the same change.

-   **Cite real, verifiable sources.** Never invent a reference. Keep direct quotations to fifteen words or fewer, one per source per document.

-   **Flag overclaiming wherever you find it —** including in the project's own material. That is a contribution, not an obstruction.

-   **If an input you needed did not arrive,** say so in the deliverable. Work built on placeholder inputs, presented as finished, is the one thing that can discredit the whole cycle.

## What still has to be decided
Eight open questions for the Task-Force. Every one of them changes what somebody does next.

|         |                                          |                                                                                                                                            |
|---------|------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| **No.** | **Question**                             | **What hangs on it**                                                                                                                       |
| **1**   | Is the sequencing right?                 | Whether the five unblocking decisions are taken in the order proposed, or reordered                                                        |
| **2**   | Can all eight target numbers be set now? | If some cannot, they need deliberately-unquantified status and the downstream consequence has to be accepted openly                        |
| **3**   | Who owns social value?                   | Either it gets its own research sub-question and an owner, or the cycle evidences it more weakly than the financial outcomes — and says so |
| **4**   | Full plan or minimum path?               | An ambition decision. Far better made now than discovered at the end                                                                       |
| **5**   | What are the six milestone dates?        | Whether this cycle is calendar-driven or delivery-driven. The plan works either way                                                        |
| **6**   | Who leads each package?                  | One named lead per package, accountable for the handovers to other groups                                                                  |
| **7**   | Which behaviour-modelling tool?          | Who decides, and by when — before parameterisation starts                                                                                  |
| **8**   | Who audits the triple top line?          | Ideally someone in the working group who did not build the model. A self-audit catches less                                                |

# Appendix A — Terms used in this document
This document avoids abbreviations. A few proper names and technical terms are unavoidable, and are collected here.

|                                       |                                                                                                                                                                                                                                                                                |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Term**                              | **Meaning**                                                                                                                                                                                                                                                                    |
| **Balance of system**                 | Everything in a solar installation other than the panels themselves: mounting, wiring, inverters, transformers, civil works.                                                                                                                                                   |
| **Behaviour diagram**                 | Called a causal loop diagram in the field. A map of variables and the causal links between them, used to find feedback loops. It shows structure, not numbers.                                                                                                                 |
| **Dual-use land / agrivoltaics**      | Generating electricity and farming the same piece of land at the same time.                                                                                                                                                                                                    |
| **Environmental product declaration** | A verified, third-party-checked document stating a product's environmental impacts, produced to a recognised standard.                                                                                                                                                         |
| **Flourishing business canvas**       | A business-model canvas with seventeen question areas that holds a model to environmental and social account as well as financial — as opposed to canvases that only ask about profit.                                                                                         |
| **Lifecycle assessment**              | A structured accounting of a product's environmental impacts across its whole life, from raw material to disposal.                                                                                                                                                             |
| **Measurement protocol**              | The project's rules for monitoring, reporting and verifying an outcome: what is measured, against what baseline, by whom, and to which external standard.                                                                                                                      |
| **Present value and rate of return**  | Present value discounts all future money to what it is worth today; a positive figure means the project creates value. The rate of return is the project's own annualised return.                                                                                              |
| **Rebound effect**                    | When an improvement causes behaviour that cancels it out — efficiency that increases consumption, or a profitable niche that attracts competitors who erase the margin.                                                                                                        |
| **Solar-as-a-service**                | Selling the outcome — electricity and the value that comes with it — as an ongoing service, while keeping ownership of the physical equipment, rather than selling the equipment.                                                                                              |
| **System model**                      | The formal engineering model of the product, written in the second version of the Systems Modeling Language, which describes requirements, parts, connection points and flows.                                                                                                 |
| **Traceability matrix**               | The eight desired outcomes by their four uses — thirty-two cells. Completing it, with every link machine-checked, is what answers the third research question.                                                                                                                 |
| **Traditional ecological knowledge**  | Long-standing, place-based environmental knowledge held by Indigenous and local communities. The project treats it as first-class engineering knowledge rather than appendix material — which is why an engagement and consent protocol is a task rather than an afterthought. |

# Appendix B — Repository identifiers
Inside the project repository the same packages and tasks are written in a shorter form. This appendix connects the two so that nothing is lost in translation.

### Tasks
“Task 1.5” in this document is written “WP1-T5” in the repository: work package one, task five. “Task 0.9” is “WP0-T9”. The numbering is identical; only the notation differs.

### Where the full working plan lives
The work-packages file in the project folder holds the same seventy-seven tasks in working form, each with its dependencies in both directions, its size, its milestone, blank owner and date fields, and its closing condition — plus a ready-to-paste template for creating repository issues.

### Existing issues to reuse rather than duplicate
|           |                                                                                                         |
|-----------|---------------------------------------------------------------------------------------------------------|
| **Issue** | **Task in this document**                                                                               |
| **26**    | Task 0.1 — set the eight target numbers                                                                 |
| **27**    | Task 1.2 — confirm the revenue architecture                                                             |
| **28**    | Task 4.4 — reconcile the behaviour diagram with the business model                                      |
| **29**    | Task 4.9 — parameterise the behaviour model                                                             |
| **30**    | Task 1.8 — the risk-adjusted comparison                                                                 |
| **31**    | Task 2.1 — name the regenerative system functions                                                       |
| **32**    | Tasks 2.2 and following — the regenerative requirements and flows. Worth splitting into separate issues |
| **34**    | Tasks 3.5 to 3.7 — the lifecycle assessment. Worth splitting into separate issues                       |
| **35**    | Task 3.2 — the measurement protocol                                                                     |
| **37**    | Task 0.5 — the governance document                                                                      |

Two of these issues currently carry more than one task each. Splitting them is worth the churn: as written, neither can be closed until a large body of work is finished, so neither shows progress in the meantime.

> **Suggested labels for new issues**
>
> The package number, the group number, the size, and the sub-question the task serves. Mark anything that needs a Task-Force decision before work can start, so nobody claims a blocked task by accident.

*Version* *0.3 — proposal for group discussion. Task owners and milestone dates are deliberately blank. Nothing in this document overrides a composition rule in the research-decomposition file; where the two disagree, that file wins.*
