# Methodology

## Purpose

The BMG AI Readiness Diagnostic is a rapid, evidence-oriented conversation tool for organizations considering or already experimenting with AI. It evaluates the organizational conditions needed to turn a promising use case into sustained, responsible value.

It does **not** certify an organization, select a vendor, or replace a technical, legal, security, or impact assessment.

## Model

The prototype evaluates six mutually reinforcing capabilities:

1. **Strategy & Value** — clear problems, strategic alignment, measurable outcomes, and boundaries.
2. **Leadership & Governance** — accountable ownership, decision rights, controls, and responsible-use policies.
3. **Data & Technology** — usable data, compatible systems, infrastructure, privacy, security, and vendor constraints.
4. **Processes & Workflows** — documented work, appropriate division of human and machine activity, and redesigned handoffs.
5. **People & Adoption** — trust, skills, participation, training, support, and change capacity.
6. **Measurement & Learning** — baselines, monitoring, pilot learning, and scale/pause/stop decisions.

## Scoring

Each statement is rated from 1 to 4:

| Rating | Meaning |
|---|---|
| 1 | Not in place |
| 2 | Early or informal |
| 3 | Defined and partly consistent |
| 4 | Established and evidenced |

For each dimension, three responses are summed. The raw range of 3–12 is normalized to 0–100:

`dimension score = (raw score - 3) / 9 × 100`

The overall score is the unweighted mean of the six dimension scores. Equal weighting is intentional in this prototype: readiness is treated as a system, and a severe constraint in any one dimension can undermine an otherwise promising initiative.

| Overall score | Maturity stage | Interpretation |
|---|---|---|
| 0–24 | Exploring | Establish the problem, ownership, and basic safeguards before piloting. |
| 25–49 | Emerging | Foundations exist unevenly; choose a bounded use case and close critical gaps. |
| 50–74 | Developing | Run controlled pilots while strengthening weak capabilities and evidence. |
| 75–100 | Scaling-ready | Conditions support wider adoption, subject to use-case-specific assurance. |

The lowest-scoring dimension generates the first recommended action. This reflects a constraint-based approach: the best next move is usually to address the bottleneck, not maximize an already strong capability.

## How a consulting assessment would go further

A full assessment would triangulate self-reported answers with:

- Leadership and frontline interviews
- Workflow observation and process maps
- Data quality, access, and ownership review
- Architecture, integration, security, and vendor review
- Policy and regulatory analysis
- Employee readiness and adoption evidence
- Use-case value/risk prioritization
- Pilot scorecards and an implementation roadmap

## Design choices and limitations

- The model assesses organizational readiness, not model performance.
- The prototype stores and transmits no answers; scoring occurs in the browser.
- Results are directional and vulnerable to optimism, uneven knowledge, and respondent bias.
- Different use cases have different risk and capability requirements.
- The current instrument has not been psychometrically validated.
- Future development should include expert review, pilot testing, inter-rater comparison, dimension weighting research, and validation against implementation outcomes.

## Responsible use

Organizations should not use the score alone to approve high-impact or sensitive AI systems. Human accountability, affected-stakeholder participation, domain expertise, legal review, privacy and security controls, and continuous monitoring remain necessary.