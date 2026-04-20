# NIST AI RMF Mapping

This document shows how the governance assessment for the AI-assisted resume screening use case aligns with the core functions of the NIST AI Risk Management Framework (AI RMF): Govern, Map, Measure, and Manage.

The purpose of this mapping is not to claim full formal compliance, but to demonstrate that the assessment follows a structured risk-based governance approach consistent with the logic of the framework.

## Govern

The project supports the Govern function by defining basic governance expectations for the use of the system. The system is explicitly positioned as a decision-support tool rather than an autonomous decision-maker. Human oversight requirements, documentation expectations, and review responsibilities are defined to ensure that AI-supported screening remains subject to human accountability.

This function is reflected in the project through:
- documented control measures
- a human oversight checklist
- documentation requirements for review outcomes
- clear limits on the use of AI outputs in final decisions
- recognition of governance relevance in the system inventory

## Map

The project supports the Map function by clearly defining the use case, its intended purpose, its deployment context, and the stakeholders affected by it. The assessment identifies the system’s inputs, outputs, business function, and the context in which the system may influence employment-related decisions.

This function is reflected in the project through:
- the use case summary
- the model/system inventory
- identification of intended users
- description of inputs and outputs
- identification of affected stakeholders and governance-sensitive outcomes

## Measure

The project supports the Measure function by identifying and evaluating the main categories of governance risk associated with the use case. The assessment considers whether the system may generate unfair, unreliable, insufficiently explainable, or privacy-intrusive outputs. It also defines conditions under which those risks should trigger further review.

This function is reflected in the project through:
- the risk inventory
- identification of fairness, reliability, transparency, and privacy risks
- reviewer checklist items used to assess questionable outputs
- recognition of edge cases such as incomplete information, keyword stuffing, and weak explanation
- documentation of residual concerns that remain even after controls are applied

## Manage

The project supports the Manage function by proposing practical actions to reduce risk and guide the use of the system in operation. These actions include mandatory human review for sensitive or questionable outputs, restrictions on automated rejection, escalation paths, override options, and ongoing monitoring requirements.

This function is reflected in the project through:
- proposed control measures
- mandatory human review before negative screening outcomes
- override and escalation options for reviewers
- privacy-related limits on data use and retention
- monitoring and review requirements documented in the system inventory

## Conclusion

Overall, the assessment reflects the logic of the NIST AI RMF by combining governance structure, contextual understanding, risk identification, and operational risk treatment. While this project is a practical portfolio exercise rather than a full enterprise implementation, it demonstrates how a structured AI governance review can be organized around the Govern, Map, Measure, and Manage functions.
