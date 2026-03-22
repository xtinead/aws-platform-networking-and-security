# ADR-0004: Use Least Privilege Security Groups and IAM

## Status
Accepted

## Context
Excessive permissions increase operational and security risk.

## Decision
Use least privilege IAM policies and security group boundaries to limit access between platform layers.

## Alternatives Considered
- broad access roles
- permissive security group rules

## Consequences
This reduces blast radius and aligns with production-grade security design.