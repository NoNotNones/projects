---
title : "Project 002"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 2. </b> "
---

### Security Groups

A **Security Group** acts as a virtual firewall for an EC2 Instance, allowing control over network traffic. In a VPC, an Instance can be assigned up to 5 Security Groups. It's important to note that Security Groups operate at the Instance layer and not at the Subnet layer.

> **Note:** Security Groups function at the virtual machine level, rather than the subnet level. However, each virtual machine within a subnet can be assigned to different security groups.

## Contents

- [Notes](2.1-notes/)