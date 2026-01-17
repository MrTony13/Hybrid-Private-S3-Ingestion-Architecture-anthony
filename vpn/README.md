 Site-to-Site VPN Configuration

### Components
- Customer Gateway (simulated on-premises)
- Virtual Private Gateway (AWS side)
- Site-to-Site VPN connection

### Steps Performed
1. Created a Customer Gateway using EC2 public IP
2. Created a Virtual Private Gateway and attached it to the VPC
3. Created a Site-to-Site VPN connection
4. Enabled route propagation to the VPC route table

### Purpose
Provides encrypted connectivity between on-premises and AWS VPC.
