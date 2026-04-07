# Intake Overview — Why Context-First Scoring Matters

> *"Grading a call without account context, prior conversation history, or the defined objective for that specific call will produce findings that are technically observed but strategically incorrect."*
>
> — Antoine Wade, Strategic Account Director (beta client feedback, April 2026)

---

## The Problem with Pattern-Matching

Most communication analysis tools — including AI-powered ones — score what they observe in the transcript. They flag filler words, measure talk time, identify question patterns, and produce a report.

The problem: they have no idea what the call was supposed to accomplish.

An Account Director who goes silent for 20 minutes on an SC-led calibration call is doing their job. An Account Director who says very little on an AD-led executive business review is failing. The transcript looks the same. The score should not be.

PivotControl AI solves this with a mandatory intake process. **No transcript is scored without a completed intake form.**

---

## What Happened Without Context

The first audit of Antoine Wade's GDIT demo call was run without a completed intake. The tool scored it as a discovery call. It produced five findings. When Antoine provided the correct context, three of those five findings were removed as not applicable:

| Finding | Original Score Impact | Status After Context |
|---------|----------------------|----------------------|
| Premature handoff to SC | Scored as weakness | NOT APPLICABLE — intentional call design |
| Extended silence during discovery | Scored as authority gap | NOT APPLICABLE — Antoine wasn't the discovery lead |
| Passive affirmations | Scored as weakness | CONFIRMED — valid regardless of call type |
| No close or summary | Scored as weakness | CONFIRMED — AD always owns the close |
| SC not supported during confusion | Scored as weakness | CONFIRMED — valid regardless of call type |

Original score: 54/100. Adjusted score with context: 72/100. Full call score (both segments): 88/100.

Context is not a refinement. It is the foundation.

---

## What the Intake Collects

The intake form has two tiers.

### Tier 1 — Required (Minimum Viable Context)

The audit cannot produce accurate findings without these fields:

- **Call type** — What kind of call was this? (SC-led demo, discovery, executive review, negotiation, etc.)
- **Role on this call** — What was the seller there to do? (AD on SC-led call vs AD-led call changes the entire rubric)
- **Defined objective** — What does success look like when this call ends? (One to two sentences, specific)
- **Prior history** — What happened before this call? (Shapes which findings are valid and which are not applicable)
- **Speaker roles** — Who was on the call and what was each person there to do? (Determines whose communication gets scored and against which rubric)

### Tier 2 — Account Intelligence (Unlocks Specific Coaching)

These fields transform generic language suggestions into account-specific coaching:

- **Key business priority** — What is the client trying to solve at the business level?
- **Known objections or sensitivities** — What has come up before? What is politically sensitive?
- **New stakeholders and what they need** — What does each new participant need to see or hear?
- **What a successful close looks like** — Specific commitment, not just positive momentum

**Why Tier 2 matters:**

Without account intelligence, a reframed bridge line looks like this:
> *"Let me add some context here that might help..."*

With account intelligence, the same moment produces:
> *"Kyle — Martin flagged last week that the inspection team is under pressure on cycle time. That is the throughput problem we are mapping. Junior, is the document correlation step the primary bottleneck or is there something upstream?"*

One is a template. The other is a weapon. Account intelligence is the difference.

---

## The Three Persona Intake Forms

PivotControl AI has role-specific intake forms for three seller personas. Each collects the fields relevant to that role's scoring rubric.

### Account Director Intake
Focuses on call classification, SC context, and new stakeholder management. The critical fields are call type, the AD's defined role on this specific call, and SC familiarity level. These three fields determine which rubric applies.

→ [AD Intake Fields](AD_INTAKE.md)

### Solutions Consultant Intake
Introduces a field unique to the SC role: known technical ambiguities going in. This distinguishes intentional diagnostic caution from authority erosion. An SC who flags that the SAP integration point was unclear before the call is scored differently than one who had no identified gaps.

→ [SC Intake Fields](SC_INTAKE.md)

### Enterprise AE Intake
Built around pressure anticipation. The more specific the AE is about what they expected versus what happened, the more precise the PCI scoring becomes. The self-identified authority-at-risk field is the direct feed into the Rapid-Fire Questioning section of the audit.

→ [AE Intake Fields](AE_INTAKE.md)

---

## The Labeling System

Every finding in a PivotControl AI audit is labeled based on what the intake context reveals:

| Label | Meaning |
|-------|---------|
| **CONFIRMED** | This finding is valid regardless of call type, role, or account context. It holds. |
| **CONTEXT-REVISED** | The finding is partially affected by call design. The recommendation changes but the observation stands. |
| **NOT APPLICABLE** | This finding was based on an incorrect call type assumption. With correct context, it is removed. |

This labeling system was introduced after the Antoine Wade beta audit. It is now a permanent part of every PivotControl AI report.

---

## The Rule

> Every audit starts with the intake form. Context is not optional — it is the score.

---

*Intake system and methodology are proprietary to PivotControl AI. All rights reserved.*
