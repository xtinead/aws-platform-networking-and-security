# ADR-0003: Isolate Runtime Workloads in Private Subnets

## Status
Accepted

## Context
Runtime workloads should not be directly accessible from the public internet.

## Decision
Place EKS nodes and application services in private subnets.

## Alternatives Considered
- public subnet runtime placement
- mixed public/private workload placement

## Consequences
This improves security posture and reduces direct exposure.