# Ingress and Load Balancing

Ingress into the platform is controlled through public-facing load balancers.

## Entry Path

Traffic typically flows through:

- Route 53
- Application Load Balancer
- Kubernetes Ingress
- Kubernetes Service
- Application Pods

## Design Goal

The goal is to allow controlled public entry without directly exposing runtime workloads.

## Why This Matters

Ingress design is a critical part of both platform availability and platform security.