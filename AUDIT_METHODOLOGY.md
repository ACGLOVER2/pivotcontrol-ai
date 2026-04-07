# PivotControl AI

**Authority Under Pressure for Enterprise Sellers**

---

PivotControl AI is a sales communication coaching and analysis business that helps enterprise Account Executives, Account Directors, and Solutions Consultants maintain authority, structure, and narrative control during high-stakes executive conversations.

The core problem it solves: enterprise sellers don't lose deals because of bad strategy. They lose momentum during unstructured pivots — especially under rapid-fire executive questioning, multi-stakeholder pressure, and cognitive overload.

PivotControl AI measures that gap and closes it.

---

## What's in This Repo

This repository documents the methodology, framework, audit system, and intake process developed during PivotControl AI's beta launch phase (March–April 2026).

```
pivotcontrol-ai/
├── README.md                        ← You are here
├── framework/
│   ├── PCI_FRAMEWORK.md             ← Pivot Control Index™ scoring system
│   ├── ROLE_RUBRICS.md              ← AD, SC, and AE role-specific scoring criteria
│   └── CALL_TYPES.md                ← How call type changes what gets scored
├── intake/
│   ├── INTAKE_OVERVIEW.md           ← Why context-first scoring matters
│   ├── AD_INTAKE.md                 ← Account Director intake fields
│   ├── SC_INTAKE.md                 ← Solutions Consultant intake fields
│   └── AE_INTAKE.md                 ← Enterprise AE intake fields
├── audits/
│   ├── AUDIT_METHODOLOGY.md         ← How audits are structured and scored
│   ├── antoine_wade_gdit/           ← Full audit case study — AD on SC-led demo
│   ├── kam_miller_forgeai/          ← Full audit case study — Founder/AE executive intro
│   └── kyle_walsh_gdit/             ← Full audit case study — SC on technical discovery
└── docs/
    ├── PRODUCT_ROADMAP.md           ← Beta → productized → SaaS trajectory
    └── BETA_LEARNINGS.md            ← Key findings from beta audit cycle
```

---

## The Core Framework

### Pivot Control Index™ (PCI)

The PCI is a five-metric scoring system that measures communication authority across the full arc of a high-stakes enterprise call.

| Metric | What It Measures | Max Score |
|--------|-----------------|-----------|
| Interruption Recovery | How cleanly authority is reclaimed after being interrupted or corrected | 20 |
| Structural Clarity | Whether responses are organized and compressed under pressure | 20 |
| Strategic Framing | Whether answers stay at the executive/outcome level vs drifting tactical | 20 |
| Authority Signal Stability | Whether tone, pacing, and language confidence hold under pressure | 20 |
| Narrative Reclaim | Whether the speaker redirects the conversation or follows the questioner's frame | 20 |

**Score Interpretation**

| Range | Level |
|-------|-------|
| 80–100 | Executive |
| 60–79 | Capable |
| 40–59 | Developing |
| 0–39 | At Risk |

---

## Context-First Scoring

> *Grading a call without account context, prior conversation history, or the defined objective for that specific call will produce findings that are technically observed but strategically incorrect.*
>
> — Antoine Wade, Strategic Account Director (beta client feedback)

The most important product insight from beta: **context determines which rubric applies.**

The first audit of Antoine Wade's GDIT demo call produced a PCI of 54/100 scored against a discovery call rubric. When he provided the correct call context — SC calibration session, not discovery — three of five findings were removed as not applicable. The adjusted score was 72/100. The full call (both transcript segments) produced a final score of 88/100 once the close was confirmed.

Every PivotControl AI audit begins with a structured intake form completed by the seller before any transcript is submitted. Without it, the output is pattern-matching against the wrong test.

---

## Beta Audit Case Studies

### Antoine Wade — Strategic Account Director, Tungsten Automation
**Account:** GDIT (General Dynamics IT) — AP Automation Executive Demo  
**Call type:** SC-Led Executive Demo  
**Final PCI:** 88/100 — Executive  

12-month strategic account culminating in a 85-minute executive demo with 9 stakeholders including a VP Sales interjection, three new AP stakeholders, and a live FedRAMP authorization upgrade. Covers the full AD role on an SC-led call — opening, discovery recap, VP interjection handling, SC protection windows, and close ownership.

→ [View audit](audits/antoine_wade_gdit/)

---

### Kamau Miller — Founder, ForgeAI Solutions LLC
**Account:** Business Tactical (prospect)  
**Call type:** Informal Executive Meeting / Founder Peer Intro  
**Final PCI:** 84/100 — Executive  

Live product demonstration of a deployed SAM.gov contract monitoring dashboard to a group of established entrepreneurs including a seven-figure operator, a body armor company founder, and a former JPMorgan professional. Covers founder-level positioning, rapid-fire differentiation questioning, and authority under an age and experience gap.

→ [View audit](audits/kam_miller_forgeai/)

---

### Kyle Walsh — Solutions Consultant, Tungsten Automation
**Account:** GDIT (General Dynamics IT) — Technical Calibration Session  
**Call type:** SC Calibration / Technical Discovery  
**Final PCI:** 47/100 — Developing  

SC-led technical discovery with a defense contractor client. Covers the most common SC failure mode: verbalized confusion in front of the client during an ambiguous fit moment. Key finding: when Kyle knew the answer, he communicated with authority. When the path was unclear, his structure collapsed outward. That gap is the entire development opportunity.

→ [View audit](audits/kyle_walsh_gdit/)

---

## Key Beta Findings

**1. Context is not optional — it is the score.**  
The rubric applied determines the findings. Call type, prior history, defined objective, and speaker roles must be collected before scoring begins.

**2. Role determines what gets scored.**  
An Account Director on an SC-led call is not scored on discovery quality. Deliberate silence during the SC's technical presentation is correct AD behavior, not an authority gap. Rubrics are role-specific.

**3. Findings must be labeled.**  
Every observation is labeled CONFIRMED or NOT APPLICABLE based on call context. The first version of the Antoine Wade audit had five findings. With context applied, two were confirmed and three were removed.

**4. Language coaching becomes specific with account intelligence.**  
Generic bridge line suggestions are templates. When the intake includes stakeholder names, prior objections, and account-specific constraints, the reframed language is a usable weapon — not a framework exercise.

**5. The close is always the AD's responsibility.**  
Regardless of call type, call structure, or who drove the conversation — the Account Director owns the summary, commitment, timeline, and next step. This finding held across every audit in the beta cycle.

---

## Business Model

**Current phase:** Beta — free audits in exchange for feedback and testimonials  
**Next phase:** Paid audits at $497 per engagement  
**Long-term:** Productized coaching program → SaaS scoring platform

**Target market:** Enterprise AEs and Account Directors in tech and logistics companies managing $500K–$5M+ deal cycles where communication authority directly affects deal velocity and promotion trajectory.

---

## Built With

- PivotControl AI — methodology, framework, and scoring system
- Claude (Anthropic) — audit generation, document production, intake form design
- Microsoft Word (.docx) — client-facing audit reports and intake forms

---

## Contact

**Alaquondria Glover**  
Founder, PivotControl AI  
*Authority Under Pressure for Enterprise Sellers*

---

*This repository documents beta phase work product. Framework, scoring, and methodology are proprietary to PivotControl AI.*
