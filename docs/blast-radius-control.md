# Blast Radius Control

Blast radius control is a core security principle of the platform foundation.

## Mechanisms Used

- subnet segmentation
- security group boundaries
- IAM role isolation
- Kubernetes RBAC
- namespace isolation
- separation of public and private runtime layers

## Design Goal

The goal is to ensure that compromise or misconfiguration in one area does not easily affect the entire platform.

## Why This Matters

Strong blast-radius control improves resilience, security, and operational safety.