# Hybrid-Private-S3-Ingestion-Architecture-anthony
This project demonstrates a secure hybrid architecture where an on-premises environment uploads data to Amazon S3 using a Site-to-Site VPN and VPC Gateway Endpoint, without using the public internet.

### Key AWS Services Used
- Amazon VPC
- Site-to-Site VPN (Customer Gateway & Virtual Private Gateway)
- Amazon S3
- VPC Gateway Endpoint (S3)
- VPC Interface Endpoint (PrivateLink)
- Route 53 Private Hosted Zone
- Amazon EC2 (On-Prem Simulation)

### Architecture Goal
Enable private, secure data ingestion from on-premises into Amazon S3 using AWS
best practices and enterprise networking patterns.


  hybrid-private-s3-ingestion/structure
├── architecture/
│   └── architecture-diagram.png
│
├── networking/
│   └── README.md
│
├── vpn/
│   └── README.md
│
├── route53/
│   └── README.md
│
├── vpc-endpoints/
│   └── README.md
│
├── s3/
│   └── README.md
│
├── compute-onprem/
│   └── README.md
│
├── testing/
│   └── README.md
│
└── README.md   ← main project overview
