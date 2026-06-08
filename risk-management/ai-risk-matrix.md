# AI Risk Matrix

## Risk Evaluation Method

Likelihood:
- 1 = Rare
- 2 = Unlikely
- 3 = Possible
- 4 = Likely
- 5 = Almost Certain

Impact:
- 1 = Negligible
- 2 = Minor
- 3 = Moderate
- 4 = Major
- 5 = Critical

Risk Score = Likelihood × Impact

## Risk Matrix

| Risk ID | Risk Description | Likelihood | Impact | Score | Level |
|----------|-----------------|------------|---------|--------|--------|
| AI-001 | Sensitive data disclosure | 4 | 5 | 20 | Critical |
| AI-002 | Hallucinated business decision | 4 | 4 | 16 | High |
| AI-003 | GDPR violation | 3 | 5 | 15 | High |
| AI-004 | Unauthorized AI usage | 4 | 3 | 12 | Medium |
| AI-005 | Third-party provider breach | 3 | 5 | 15 | High |
| AI-006 | Prompt injection attack | 3 | 4 | 12 | Medium |
| AI-007 | Model bias impacting decisions | 3 | 4 | 12 | Medium |
| AI-008 | Service unavailability | 2 | 4 | 8 | Low |

## Treatment Thresholds

| Score | Classification | Required Action |
|---------|---------------|----------------|
| 1-5 | Low | Monitor |
| 6-10 | Moderate | Mitigate if feasible |
| 11-15 | High | Treatment required |
| 16-25 | Critical | Immediate action required |
