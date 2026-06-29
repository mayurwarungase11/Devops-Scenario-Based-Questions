# AWS Scenario and Concept-Based Interview Questions


### ❓ Interview Question

**1. What is the difference between a Security Group and a Network ACL (NACL)?**

### ✅ Interview Answer

> **"Security Groups and Network ACLs are both AWS security features used to control network traffic, but they work at different levels. A Security Group is attached to an EC2 instance and acts as a virtual firewall for that specific instance. It is stateful, which means if I allow incoming traffic, the return traffic is automatically allowed. It supports only allow rules. On the other hand, a Network ACL is applied at the subnet level and controls traffic for all resources within that subnet. It is stateless, so I need to define both inbound and outbound rules separately, and it supports both allow and deny rules. In simple terms, I use a Security Group to secure individual EC2 instances, while a Network ACL provides an additional layer of security for the entire subnet."**

### 🎯 Key Points to Remember

* Security Group → **EC2 Instance Level**
* Network ACL → **Subnet Level**
* Security Group → **Stateful**
* Network ACL → **Stateless**
* Security Group → **Allow Rules Only**
* Network ACL → **Allow and Deny Rules**
