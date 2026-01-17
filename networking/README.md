## VPC and Networking Setup

### Steps Performed
1. Created a VPC with CIDR 10.0.0.0/16
2. Created public and private subnets
3. Created and attached an Internet Gateway
4. Configured route tables:
   - Public subnet routed to IGW
   - Private subnet has no internet route

### Purpose
Provides isolated networking for AWS resources and supports private hybrid connectivity.
