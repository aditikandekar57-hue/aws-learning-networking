# Day 2 – Cloud Networking Basics

## Objective
Understand networking fundamentals required for cloud servers and validate connectivity to an EC2 instance.

## Topics Covered
- Public and private IP addressing
- Port and service validation
- EC2 connectivity checks
- Basic network troubleshooting

## Tasks Performed
- Identified private IP of EC2 instance
- Verified public IP for internet access
- Tested outbound connectivity
- Checked open ports and running services
- Validated web server accessibility using curl
- Verified security group rules

## Commands Used
```bash
ip a
hostname -I
ping google.com
curl ifconfig.me
ss -tuln
curl localhost
systemctl start nginx
systemctl stop nginx
