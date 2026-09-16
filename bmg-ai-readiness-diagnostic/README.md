# BMG AI Readiness Diagnostic

A strategy case study and working browser prototype for assessing whether an organization has the capabilities to adopt AI responsibly and create measurable value.

[Open the prototype files](./index.html) · [Review the methodology](./methodology.md) · [See a sample assessment](./sample-assessment.md)

## The problem

Organizations are often encouraged to “adopt AI” before answering more fundamental questions:

- Which operational or strategic problem is worth solving?
- Is the required data usable and responsibly governed?
- Does the current workflow make sense before it is automated?
- Who owns the decision and its consequences?
- Can employees adopt the new way of working?
- How will the organization know whether the intervention worked?

This creates a tool-first pattern: software is purchased or piloted, while the organizational conditions required for sustained value remain underdeveloped.

## Strategic question

**How can an organization—especially one operating with limited capacity—identify its most important AI-readiness constraint and choose a responsible next step?**

## What I built

I designed a minimum viable diagnostic that combines:

- A six-dimension organizational capability model
- 18 behaviorally anchored assessment questions
- Transparent maturity scoring
- A constraint-based recommendation engine
- A privacy-conscious browser prototype that stores and transmits no answers
- A fictional composite case showing how results become a practical pilot roadmap

The prototype deliberately avoids recommending tools. It first helps an organization understand the system into which AI would be introduced.

## Readiness model

| Dimension | What it evaluates |
|---|---|
| Strategy & Value | Problem clarity, strategic alignment, outcomes, and boundaries |
| Leadership & Governance | Accountability, decision rights, controls, and responsible-use policies |
| Data & Technology | Data fitness, integration, infrastructure, privacy, security, and vendor constraints |
| Processes & Workflows | Process visibility, human judgment, exceptions, handoffs, and redesign readiness |
| People & Adoption | Trust, participation, skills, training, support, and change capacity |
| Measurement & Learning | Baselines, monitoring, pilot evidence, and scale/pause/stop decisions |

## Product logic

Each of the 18 statements is rated from 1 (“not in place”) to 4 (“established and evidenced”). Scores are normalized to 0–100 for each dimension and averaged for an overall maturity stage.

The prototype identifies the lowest-scoring dimension as the priority constraint and recommends a corresponding first move. This is intentional: AI readiness is systemic. Improving an already strong capability may matter less than addressing the bottleneck most likely to prevent adoption or create risk.

The scoring is fully documented in [methodology.md](./methodology.md), including assumptions and limitations.

## From diagnosis to action

A score is not the deliverable. The useful output is a sequenced decision.

In the [sample assessment](./sample-assessment.md), a fictional community education nonprofit scores 43/100 (“Emerging”). Although leadership has promising AI ideas, process readiness is the principal constraint. The recommendation is therefore not to buy a tool. It is to map one bounded learner-support workflow, establish safeguards and measures, and run a four-week human-in-the-loop pilot with a defined scale/pause/stop gate.

## Responsible AI choices

- No response data is stored or transmitted.
- The diagnostic does not approve technologies or certify readiness.
- High-impact use cases require deeper legal, privacy, security, domain, and affected-stakeholder review.
- Self-reported scores must be validated against operational evidence.
- The methodology openly states that the instrument has not been psychometrically validated.
- Human accountability and continuous monitoring remain necessary at every maturity level.

## Research connection

This project operationalizes the research question I am developing toward doctoral study:

> How do resource-constrained organizations build the capabilities required to adopt AI effectively and responsibly?

It treats adoption as an organizational-capability problem rather than a software-acquisition event. The current artifact is designed to support future inquiry into readiness constructs, bottleneck patterns, adoption behavior, and the relationship between diagnostic results and implementation outcomes.

## Next research and product iterations

1. Conduct expert review with AI governance, organizational change, and domain practitioners.
2. Pilot with multiple respondents inside the same organization and compare perspectives.
3. Test question clarity, reliability, and dimension structure.
4. Study whether dimension weights should vary by use-case risk and organizational context.
5. Compare readiness scores with pilot outcomes over time.
6. Add an evidence log and facilitated assessment version without compromising sensitive data.

## Run locally

No installation or dependencies are required.

1. Download or clone this repository.
2. Open `bmg-ai-readiness-diagnostic/index.html` in a modern browser.
3. Complete all 18 questions to generate a result.

## My role

I developed the problem framing, capability model, assessment statements, scoring logic, responsible-use boundaries, sample application, interface, and implementation roadmap.

**Tools:** HTML, CSS, JavaScript, organizational capability analysis, workflow design, responsible AI, product strategy.

---

*Butterfly Mandate Group (BMG): Legacy. Innovation. Purpose-Driven Impact.*