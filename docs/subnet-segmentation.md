# Subnet Segmentation

Subnet segmentation is used to separate workloads by exposure and function.

## Layers

### Public Subnets
Used for internet-facing infrastructure such as ALBs and NAT gateways.

### Private Application Subnets
Used for runtime workloads such as EKS nodes and application services.

### Private Data Subnets
Used for data-tier resources such as RDS and EFS.

## Why This Matters

Separating public, application, and data tiers reduces blast radius and improves security posture.