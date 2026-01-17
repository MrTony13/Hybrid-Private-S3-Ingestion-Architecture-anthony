## VPC Endpoints Configuration

### S3 Gateway Endpoint
Steps:
1. Created a Gateway Endpoint for Amazon S3
2. Associated it with the private route table

Purpose:
Allows private access to Amazon S3 without using the internet or NAT gateway.

### Interface Endpoint (PrivateLink)
Steps:
1. Created an Interface Endpoint for AWS services (e.g., Lambda / API Gateway)
2. Enabled private DNS
3. Placed endpoint ENIs in private subnet

Purpose:
Provides private access to AWS services from on-premises through the VPN.
