# Control Measures

## Control Design Approach

## Risk 1: Unfair candidate scoring due to proxy attributes

**Control objective:** Reduce the risk of unfair candidate scoring caused by non-job-related proxy attributes.

### Proposed controls

- Before scoring, non-job-related attributes should be removed or excluded where feasible.
- Low-scoring and high-scoring candidates should be subject to human review to identify potential false negatives or false positives.
- The system should not rely on non-job-related proxy attributes in its scoring logic.

### Implementation notes

Human review should occur before any rejection or negative screening outcome is finalized.

### Residual concern

Some proxy effects may remain indirect and difficult to detect, and human reviewers may still rely too heavily on AI-generated decisions.

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
