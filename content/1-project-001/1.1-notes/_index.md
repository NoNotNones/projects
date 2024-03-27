---
title : "Notes"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1.1 </b> "
---

## Subnets

A **subnet** is a segment of the IP address range that you use when provisioning your Amazon VPC. It directly provides the active network range to the AWS resources that may run within it, such as Amazon EC2 and Amazon RDS (Amazon Relational Database Service). Subnets are identified through CIDR blocks (e.g., 10.0.1.0/24 and 192.168.0.0/24), and the subnet's CIDRs must be within the VPC's CIDR. The smallest subnet that can be created is /28 (16 IP addresses). AWS reserves the first 4 IP addresses and the last 1 IP address of each subnet for intranet networking purposes. For example, a /28 subnet has 16 available IP addresses, but 5 reserved IPs are used for AWS, leaving 11 usable IP addresses for resources operating within this subnet.
addresses within this range from outside the Internet.

![Subnets](/images/1-Introduce/subnet.png?featherlight=false&width=50pc)
