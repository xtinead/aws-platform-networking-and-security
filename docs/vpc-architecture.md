# VPC Architecture

The VPC architecture defines the foundational network structure of the platform.

## Core Design

The VPC is segmented into multiple subnet tiers:

- public subnets
- private application subnets
- private data subnets

The design is distributed across multiple availability zones to improve resilience.

## Key Components

- VPC CIDR allocation
- internet gateway
- route tables
- NAT gateways
- public ingress path
- private runtime isolation

## Why This Matters

A well-structured VPC is the basis for secure and resilient platform design.