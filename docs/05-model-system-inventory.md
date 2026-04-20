# Model / System Inventory

This inventory record summarizes the key system-level information required to register and govern the AI-assisted resume screening use case in a structured way.

## System Name

Internal HR Resume-Screening AI Assistant

## System Purpose

The system is intended to support early-stage resume screening by summarizing resumes, extracting relevant skills and qualifications, and generating an initial relevance score based on job requirements.

## Intended Users

- HR recruiters
- Talent acquisition specialists
- Hiring managers at the review stage

## Business Function / Deployment Context

The system is used in the early stages of the hiring workflow as a decision-support tool for internal resume review and candidate triage.

## Inputs

- Candidate resumes
- Job descriptions
- Role-specific screening criteria

## Outputs

- Resume summaries
- Extracted skills and qualifications
- Initial relevance scores or rankings
- Suggested strengths and gaps relative to the role

## Decision Role

The system is intended for decision-support only. It must not be used as the sole basis for final hiring, rejection, or shortlist decisions.

## Human Involvement

Human review is required before any rejection, exclusion, or shortlist decision is finalized. Additional review is required when outputs are weakly explained, unusually high or low, or based on incomplete or ambiguous resume information.

## Data Sensitivity

The system processes personal data contained in resumes, including direct identifiers, employment history, education history, and other candidate-provided information that may be sensitive or non-essential for early-stage screening.

## Governance Relevance

This use case has meaningful governance relevance because it influences employment-related decision processes and involves the processing of personal data. It therefore requires documented controls, human oversight, and periodic review.

## Key Limitations

- Resume content may be incomplete, ambiguous, or inconsistently formatted.
- Scoring may be affected by keyword repetition rather than actual qualification.
- Some outputs may not be sufficiently explainable.
- Indirect proxy effects may be difficult to detect fully.
- Personal data beyond what is strictly necessary may appear in free-text resume content.

## Monitoring / Review Requirements

- Periodic review of scoring patterns and edge cases
- Human oversight logs for overrides, escalations, and rejected outputs
- Review of false positives and false negatives
- Review of privacy practices, especially if third-party tools are involved
- Ongoing assessment of whether the system remains aligned with its intended use
