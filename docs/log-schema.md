# Log schema (vendor-neutral)

## Required fields
- `timestamp`
- `correlation_id`
- `workflow`
- `step`
- `status` — success|retry|failed
- `attempt`
- `duration_ms`
- `error_class` (when failed)

## Optional fields
- `idempotency_key`
- `external_system`
- `http_status`
- `payload_bytes`

## Why this matters
If you can grep `correlation_id` across services, your integrations become debuggable.
