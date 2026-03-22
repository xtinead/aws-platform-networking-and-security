# Terraform Module — Security Groups

This module defines security group boundaries for the platform.

## Responsibilities

- restrict ingress to public entry points
- limit east-west and north-south traffic
- enforce least privilege network access
- separate public, application, and data layer traffic

## Why It Matters

Security groups are one of the primary mechanisms for reducing blast radius and controlling access between platform layers.