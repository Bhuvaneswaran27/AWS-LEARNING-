# Amazon VPC Notes

## What is Amazon VPC?
Amazon Virtual Private Cloud (VPC) is a service that lets you create an isolated virtual network within AWS where you can launch and manage AWS resources securely.

## Key Components
- VPC
- Subnets (Public and Private)
- Route Tables
- Internet Gateway (IGW)
- NAT Gateway
- Security Groups
- Network ACLs (NACLs)
- Elastic IP
- VPC Peering
- VPN Gateway

## Public Subnet
- Has a route to the Internet Gateway.
- Used for web servers, bastion hosts, and load balancers.

## Private Subnet
- No direct route to the Internet Gateway.
- Used for databases and application servers.
- Can access the internet through a NAT Gateway if needed.

## Benefits
- Network isolation
- Improved security
- Flexible IP addressing
- High availability
- Full control over networking
