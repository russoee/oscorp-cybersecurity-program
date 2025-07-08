# **NIST Category: Detect**

## **Sub-Category: Anomalies and Events**

| Control Area                  | Recommendation                                                                                                                        | Priority   | Timeline   | Owner                    | Notes                                            |
|:------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------|:-----------|:-----------|:-------------------------|:-------------------------------------------------|
| Baseline Network Behavior     | Deploy a SIEM platform (e.g., Microsoft Sentinel, Splunk, or Elastic) to establish a baseline of normal system and network behavior.  | High       | 0–3 months | Cybersecurity / IT Ops   | No SIEM or centralized logging in place          |
| Alert Analysis                | Create a structured alert triage and threat analysis process to investigate anomalies and suspected attacks.                          | High       | 3–6 months | SOC Team / Cybersecurity | Alerts are not currently analyzed or correlated  |
| Log Aggregation & Correlation | Integrate existing infrastructure (firewalls, endpoints, O365, Azure logs) into the SIEM for correlation across multiple data points. | High       | 0–6 months | Cybersecurity / IT Ops   | No log sources currently centralized or analyzed |

## **Sub-Category: Security Continuous Monitoring**

| Control Area                   | Recommendation                                                                                                                            | Priority   | Timeline    | Owner                         | Notes                                                                   |
|:-------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------|:-----------|:------------|:------------------------------|:------------------------------------------------------------------------|
| Network Activity Monitoring    | Implement SIEM to monitor network traffic and correlate suspicious behavior. Integrate key sources such as firewalls, VPN, and endpoints. | High       | 0–3 months  | Cybersecurity / IT Operations | No SIEM currently deployed; no visibility into network traffic          |
| Physical Security Monitoring   | No action required                                                                                                                        |            |             | Facilities / Security Team    | Alerts for physical breaches are already monitored                      |
| Personnel Activity Monitoring  | Expand detection to include user behavior analytics (UBA/UEBA) for identifying insider threats and anomalous activity.                    | Medium     | 6–12 months | Cybersecurity / SOC           | Physical alerts only; personnel cybersecurity activity is not monitored |
| Malware Detection              | No action required                                                                                                                        |            |             | IT / Endpoint Security        | Microsoft Defender is deployed and actively used                        |
| Unauthorized Mobile Code       | No action required                                                                                                                        |            |             | IT / Endpoint Security        | Covered by Defender’s endpoint scanning capabilities                    |
| Third-Party Service Monitoring | Implement a TPRM process requiring breach notification and audit trails from service providers.                                           | High       | 6–12 months | Procurement / Vendor Mgmt     | No monitoring of third-party provider security activity                 |

## **Sub-Category: Detection Processes**

| Control Area               | Recommendation                                                                                                              | Priority   | Timeline    | Owner                     | Notes                                                     |
|:---------------------------|:----------------------------------------------------------------------------------------------------------------------------|:-----------|:------------|:--------------------------|:----------------------------------------------------------|
| Roles & Responsibilities   | Define formal roles and responsibilities for threat detection and assign them within the cyber team. Consider MSSP support. | High       | 0–3 months  | CISO / Cybersecurity Lead | No ownership or clarity around detection responsibilities |
| Regulatory Compliance      | Review applicable detection requirements (e.g., NIST, industry-specific) and align tooling and processes with them.         | Medium     | 6–12 months | Compliance / Cyber Team   | No evidence of regulatory or contractual alignment        |
| Detection Use Case Testing | Perform detection testing (e.g., purple teaming, cyber drills) to evaluate and validate detection logic.                    | High       | 3–6 months  | SOC / Cybersecurity Team  | No use case testing or validation                         |

