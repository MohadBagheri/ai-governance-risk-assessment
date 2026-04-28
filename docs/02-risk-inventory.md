# Risk Inventory

This inventory is intended to identify the initial governance risks associated with the use case, with a focus on fairness, reliability and safety, transparency, and privacy.
The objective of this section is risk identification rather than mitigation.

## Risk Identification Approach

The risks listed below were identified by considering how the system could produce unfair, unreliable, insufficiently explainable, or privacy-intrusive outcomes within the defined HR screening use case.

## Risk 1: Unfair candidate scoring due to proxy attributes
**Related principle:** Fairness

The system may produce unfairly lower relevance scores for candidates due to proxies associated with names, nationality, linguistic background, or other non-job-related attributes.

## Risk 2: Improper exclusion due to incomplete resume information
**Related principle:** Reliability & Safety

The system may treat incomplete or ambiguously formatted resumes as low-quality or irrelevant, which could result in unjustified downranking or exclusion of otherwise qualified candidates.

## Risk 3: Score inflation due to keyword stuffing
**Related principle:** Reliability & Safety / Fairness

The system may overvalue resumes that contain frequent repetition of job-related keywords, even when the underlying experience, context, or level of competency is weak or not well supported.

## Risk 4: Limited explainability of candidate scoring
**Related principle:** Transparency / Explainability

The system may generate rankings or relevance scores without clear, interpretable, or sufficiently documented reasons for why a candidate was scored higher or lower.

## Risk 5: Excessive processing or retention of personal data
**Related principle:** Privacy & Data Protection

The system may process, store, or transmit personal information contained in resumes beyond what is necessary for the defined screening purpose. This may include direct identifiers, non-essential personal details, or inferred attributes that are not required for early-stage candidate evaluation.

## Risk Summary Table

| Risk ID | Risk Title | Likelihood | Impact | Risk Level | Regulatory Reference |
|---|---|---|---|---|---|
| R1 | Unfair scoring due to proxy attributes | High | High | Critical | Canadian Human Rights Act; Quebec Law 25 |
| R2 | Improper exclusion due to incomplete resume | Medium | Medium | Moderate | PIPEDA Principle 4.4 |
| R3 | Score inflation due to keyword stuffing | Medium | Low | Low | — |
| R4 | Limited explainability of scoring | High | High | Critical | Quebec Law 25, Art. 12; Directive on Automated Decision-Making |
| R5 | Excessive processing or retention of personal data | Medium | High | High | PIPEDA; Quebec Law 25; Canada Bill C-27 |

## Risk Scoring Methodology

Each risk is assessed using a two-dimensional model based on 
**likelihood** (probability of occurrence) and **impact**(severity of harm if it occurs). Risk level is derived from 
the combination of these two dimensions:

| | Low Impact | Medium Impact | High Impact |
|---|---|---|---|
| **High Likelihood** | Moderate | High | Critical |
| **Medium Likelihood** | Low | Moderate | High |
| **Low Likelihood** | Low | Low | Moderate |

