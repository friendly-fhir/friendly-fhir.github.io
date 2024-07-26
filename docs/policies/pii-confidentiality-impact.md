# PII Confidentiality Impact

This section outlines the guidelines for how the **Friendly FHIR** organization
categorizes the potential impact of a loss of confidentiality of
Personally Identifiable Information ([PII]). This information can be found
as [custom properties] on GitHub repositories within the organization that _may_
process or otherwise handle FHIR data when deployed to a production environment.

This follows the [NIST] definition for [Confidentiality Impact Assessment]

[PII]: https://en.wikipedia.org/wiki/Personally_identifiable_information
[NIST]: https://csrc.nist.gov
[Confidentiality Impact Assessment]: https://csrc.nist.gov/glossary/term/pii_confidentiality_impact_level
[custom properties]: https://docs.github.com/en/github/administering-a-repository/customizing-your-repository/about-repository-metadata-on-github

## Impact Levels

Impact is categorized as low, moderate, or high based on the potential adverse
effects on individuals or organizations resulting from a loss of confidentiality
of PII.

### Low Impact

A loss of confidentiality is considered low impact if it would cause limited
adverse effects on individuals or organizations.

Examples of such adverse effects include:

* Minor inconvenience or harm to individuals, such as needing to change a
  telephone number.
* Minor damage to organizational assets.
* Minor financial loss.

### Moderate Impact

A loss of confidentiality is considered moderate impact if it would cause
serious adverse effects on individuals or organizations.

Examples of such adverse effects include:

* Significant degradation in the organization’s ability to perform its primary
  functions.
* Significant damage to organizational assets.
* Significant financial loss.
* Significant harm to individuals, such as identity theft, public humiliation,
  discrimination, and blackmail.

### High Impact

A loss of confidentiality is considered high impact if it would cause severe or
catastrophic adverse effects on individuals or organizations.

Examples of such adverse effects include:

* Severe degradation in or loss of mission capability.
* Major damage to organizational assets.
* Major financial loss.
* Severe or catastrophic harm to individuals, including loss of life, serious
  life-threatening injuries, or inappropriate physical detention.

## Additional Factors

Additional factors to be considered when determining the PII confidentiality
impact level include:

1. **Identifiability**: How easily PII can be used to identify specific
   individuals.
2. **Quantity of PII**: The number of individuals identified in the information.
3. **Data Field Sensitivity**: Sensitivity of individual PII data fields and the
   sensitivity of combined data fields.
4. **Context of Use**: The purpose for which the PII is collected, stored, used,
   processed, disclosed, or disseminated.
