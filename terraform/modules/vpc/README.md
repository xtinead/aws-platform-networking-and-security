# Terraform Module — VPC

This module represents the core AWS networking foundation.

## Responsibilities

- create the VPC
- define public subnets
- define private application subnets
- define private data subnets
- attach internet gateway
- define route tables
- support NAT gateway routing

## Why It Matters

The VPC module establishes the network isolation boundaries that all platform workloads depend on.