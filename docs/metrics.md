# Metrics (vendor-neutral)

## Core metrics per workflow
- `workflow_success_total`
- `workflow_failure_total`
- `workflow_retry_total`
- `workflow_duration_ms` (histogram)
- `dlq_depth`

## Suggested SLOs
- Success rate ≥ 99% for critical workflows
- P95 duration: define per workflow
