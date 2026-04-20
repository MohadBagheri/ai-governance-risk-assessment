# Control Measures

This section defines the initial control measures proposed to reduce the governance risks identified in the use case. The focus is on practical controls that support fairness, reliability and safety, transparency, and privacy in AI-assisted resume screening.

## Control Design Approach

The controls below are intended to reduce the likelihood or impact of unfair, unreliable, insufficiently explainable, or privacy-intrusive outcomes. They do not eliminate risk entirely, and ongoing human oversight and periodic review remain necessary.

## Risk 1: Unfair candidate scoring due to proxy attributes

**Control objective:** Reduce the risk of unfair candidate scoring caused by non-job-related proxy attributes.

### Proposed controls

- Before scoring, non-job-related attributes should be removed or excluded where feasible.
- Low-scoring and high-scoring candidates should be subject to human review to identify potential false negatives or false positives.
- The system should not rely on non-job-related proxy attributes in its scoring logic.

### Implementation notes

- Human review should occur before any rejection or negative screening outcome is finalized.
- HR reviewers should be instructed to assess whether the score appears justified by job-relevant qualifications.
- Review decisions should be documented for traceability.

### Residual concern

- Some proxy effects may remain indirect and difficult to detect.
- Human reviewers may still rely too heavily on AI-generated decisions.

## Risk 2: Improper exclusion due to incomplete resume information

**Control objective:** Prevent unjustified rejection or downranking based on incomplete or ambiguous resume information.

### Proposed controls

- No resume should be automatically rejected solely because some expected information is missing.
- The system should flag the case for human review when information is incomplete or unclear.
- The screening output should distinguish between “insufficient information” and “low relevance.”

### Implementation notes

- Cases with incomplete or ambiguous information should be routed to manual review before a negative screening outcome is finalized.
- HR reviewers should verify whether key qualifications may be present but not explicitly stated in the resume.
- The system should use a separate flag such as “needs additional review” when confidence is low.

### Residual concern

- Some qualified candidates may still be undervalued if important information is implicit, poorly formatted, or difficult for the system to interpret.
- Human reviewers may not review all borderline cases with the same level of care or consistency.

## Risk 3: Score inflation due to keyword stuffing

**Control objective:** Prevent unjustified high ranking based on excessive repetition of job-related keywords when the candidate’s actual experience or competency is not well supported.

### Proposed controls

- The system should not rely solely on keyword frequency when generating candidate scores.
- High-scoring resumes should be flagged for human review when the score appears to be driven primarily by repeated job-related terms.
- Scoring should take into account contextual evidence of experience, not only lexical overlap with the job description.

### Implementation notes

- HR reviewers should verify whether highly ranked candidates provide concrete evidence of relevant skills and experience beyond repeated keywords.
- Cases with unusually high scores should be subject to manual review before shortlist decisions are finalized.

### Residual concern

- Some keyword-driven inflation may remain difficult to detect, especially when resumes appear superficially aligned with the job description.
- Human reviewers may not consistently identify weak evidence behind high scores.

## Risk 4: Limited explainability of candidate scoring

**Control objective:** Reduce the risk of candidate scoring without clear, understandable, and sufficiently documented reasons.

### Proposed controls

- Each score should include the main contributing factors that influenced the output.
- When the system’s explanation is insufficient, the case should be flagged for mandatory human review.
- Outputs that cannot be meaningfully explained should not be used as the sole basis for screening decisions.

### Implementation notes

- The system’s explanation should be displayed alongside each score.
- When the system’s explanation is weak or insufficient, HR should manually review the case.
- Review outcomes should be documented for traceability.

### Residual concern

- Some explanations may appear convincing without being sufficiently informative.
- HR reviewers may still accept weak explanations without sufficient challenge.
- Complete explainability may not always be achievable.

## Risk 5: Excessive processing or retention of personal data

**Control objective:** Reduce the processing, storage, or transfer of unnecessary personal information.

### Proposed controls
- Only information necessary for early-stage screening should be processed by the system.
- Access to candidate resume data should be limited to authorized personnel only.
- Unnecessary personal identifiers should be masked, excluded, or not retained where feasible.
- Personal data should not be shared with third-party tools unless there is a documented and justified need.
- A defined retention period should be established for candidate data used by the system.

### Implementation notes

- HR and system owners should define what information is necessary for screening before deployment.
- Access permissions should be role-based and limited to those directly involved in the process.
- Data retention and deletion rules should be documented and applied consistently.
- Any use of third-party services should be reviewed before deployment to assess privacy implications.

### Residual concern

- Some personal information may still appear in free-text resumes even when it is not needed for screening.
- Complete removal of sensitive or non-essential signals may be difficult in practice.
- Third-party processing may still introduce additional privacy and data protection risk.
