# Terraform Module — Application Load Balancer

This module defines ingress-related load balancing patterns.

## Responsibilities

- place ALBs in public subnets
- support controlled internet-facing entry points
- route traffic to private runtime workloads
- maintain clear separation between public ingress and private services

## Why It Matters

The ALB acts as the public entry point into the platform and should be intentionally placed and secured.