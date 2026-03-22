# ADR-0002: Place Load Balancers in Public Subnets

## Status
Accepted

## Context
Internet-facing traffic requires a controlled public entry point.

## Decision
Place ALBs in public subnets while keeping runtime workloads private.

## Alternatives Considered
- directly exposing workloads
- mixed public runtime placement

## Consequences
This enables controlled ingress while preserving private runtime isolation.