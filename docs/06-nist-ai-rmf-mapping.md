# NIST AI RMF Mapping – HR AI Screening System

This section maps the project artifacts to the NIST AI Risk Management Framework (AI RMF) core functions: GOVERN, MAP, MEASURE, and MANAGE.

The objective is to assess how well the project aligns with the framework and identify gaps and opportunities for improvement.

---

## GOVERN

### Current Implementation
Basic governance elements are present in the project through defined human oversight practices (see docs/04-human-oversight-checklist.md) and control measures (see docs/03-control-measures.md). 
These elements establish initial expectations for how AI outputs should be used by HR teams.

### Gaps
However, formal governance structures are not fully established. There are no clearly defined roles, accountability mechanisms, or documented AI governance policies.

This limits the organization's ability to assign responsibility, ensure traceability of decisions, and enforce consistent governance practices.

### Recommended Improvements
To improve alignment with the NIST GOVERN function, the project should:
- Define clear roles and responsibilities (e.g., AI system owner, HR decision-maker, compliance reviewer)
- Establish formal AI usage and governance policies
- Introduce audit and logging mechanisms to support accountability and traceability of AI-assisted decisions

---

## MAP

### Current Implementation
Basic elements of the MAP function are present through the definition of the use case (see docs/01-use-case-summary.md) and the identification of key risks (see docs/02-risk-identification.md).

These provide a foundational understanding of the system context and potential risk areas.

### Gaps
However, risks are not prioritized, and stakeholder analysis is not fully developed.

This limits the ability to distinguish high-risk issues from lower-priority ones and reduces awareness of broader societal and legal impacts.

### Recommended Improvements
To improve alignment with the NIST MAP function, the project should:
- Introduce a structured risk prioritization approach (e.g., based on impact and likelihood)
- Expand stakeholder identification to include external actors such as affected individuals, legal stakeholders, and relevant communities

---

## MEASURE

### Current Implementation
Elements of the MEASURE function are partially addressed through the identification of key risks (see docs/02-risk-identification.md).

### Gaps
However, a formal measurement framework is not established. There are no defined metrics or structured methodologies to assess and monitor these risks.

This limits the ability to objectively evaluate system behavior, compare outcomes across groups, and support data-driven decision-making.

### Recommended Improvements
To improve alignment with the NIST MEASURE function, the project should:
- Introduce quantitative and qualitative metrics, including:
  - Performance metrics (e.g., consistency, drift, accuracy proxies)
  - Fairness metrics (e.g., outcome comparison across groups)
  - Explainability measures (e.g., availability of contributing factors)
- Establish monitoring mechanisms to track system behavior over time

---

## MANAGE

### Current Implementation
Elements of the MANAGE function are partially addressed through the use of control measures (see docs/03-control-measures.md) and defined human oversight practices (see docs/04-human-oversight-checklist.md).

### Gaps
However, a formal risk management framework is not fully established. There are no defined processes for incident response, risk prioritization, or residual risk documentation.

This increases the likelihood of inconsistent handling of AI-related issues and reduces preparedness for system failures or unintended impacts.

### Recommended Improvements
To improve alignment with the NIST MANAGE function, the project should:
- Define a structured incident response process, including reporting, investigation, and remediation procedures
- Implement risk prioritization based on impact and likelihood
- Document residual risks that remain after mitigation efforts

---

## Summary

This mapping demonstrates that the project establishes a solid foundation for AI risk management through:

- Definition of system context and use case  
- Identification of key risks  
- Initial control measures and human oversight practices  

However, several important gaps remain in achieving full alignment with the NIST AI RMF:

- Lack of formal governance structures and accountability mechanisms  
- Absence of risk prioritization and comprehensive stakeholder analysis  
- Missing measurement metrics and monitoring processes  
- Lack of structured incident response and residual risk management  

Addressing these gaps would significantly strengthen the project’s alignment with industry best practices and improve its readiness for real-world AI governance applications.
