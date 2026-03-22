# Terraform Module — IAM

This module defines IAM roles, policies, and access boundaries used by the platform.

## Responsibilities

- define least privilege access patterns
- support AssumeRole usage where required
- separate engineer access from automation access
- protect platform operations through role isolation

## Why It Matters

IAM boundaries are critical to controlling who can provision infrastructure, operate the platform, and access sensitive resources.