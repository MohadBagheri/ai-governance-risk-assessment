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
