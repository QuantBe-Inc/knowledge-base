# ADR: API Gateway POC Disposition

Date: 2026-03-23
Status: Accepted
Scope: qb-api-gateway-poc

## Context
- Repository `qb-api-gateway-poc` was a proof-of-concept and never entered production.
- Historical README content contained only template placeholders and no architectural implementation detail.

## Decision
- Archive `qb-api-gateway-poc` repository.
- Do not treat POC implementation as production baseline.
- Keep gateway standardization decisions in this knowledge base instead of the archived repo.

## Consequences
- Future gateway work should start from production requirements and current service topology.
- Any new gateway implementation must define:
  - auth strategy (service-to-service + end-user)
  - routing and contract versioning
  - resiliency policy (retry, timeout, circuit-breaker)
  - observability baseline
