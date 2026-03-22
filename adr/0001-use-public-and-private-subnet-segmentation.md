# ADR-0001: Use Public and Private Subnet Segmentation

## Status
Accepted

## Context
Platform workloads require different levels of exposure and security.

## Decision
Use public subnets for ingress components and private subnets for runtime and data workloads.

## Alternatives Considered
- flat subnet design
- public placement of runtime services

## Consequences
This improves isolation, reduces exposure, and supports stronger blast-radius control.