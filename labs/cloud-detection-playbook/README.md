# Cloud Detection Engineering Playbook

## Goal
Outline the purpose of this lab: developing, testing, and validating detections for suspicious behavior across cloud services (e.g., AWS, Azure, GCP).

## Data Sources
- CloudTrail, GuardDuty, VPC Flow Logs, CloudWatch Metrics
- IAM access analyzer or CSPM findings

## Detection Use Cases
Describe each detection with the following template:

| Use Case | MITRE ATT&CK | Detection Logic | Response |
| --- | --- | --- | --- |
| Example: Unauthorized access key creation | T1098 | CloudWatch Insights query or Sigma rule | Notify security channel, auto-disable key |

## Automation & Response
Detail any playbooks or Lambda/Logic App functions used to triage or remediate alerts.

## Testing & Validation
- Red-team simulations or Atomic Red Team tests executed
- Results and tuning iterations

## Supporting Assets
- `/queries`: Saved queries and dashboards
- `/automation`: Infrastructure-as-code or scripts that deploy detections
- `/reports`: Executive summaries or stakeholder communications

## Key Outcomes
Summarize the measurable improvements (reduced mean time to detect, new coverage, automation wins).
