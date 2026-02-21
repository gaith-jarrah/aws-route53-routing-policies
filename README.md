# AWS Route 53 Routing Policies Lab

## About this project
This project demonstrates hands-on implementation of Amazon Route 53 DNS routing policies in AWS.
The goal was to understand how DNS-based traffic routing works in real-world cloud environments.

This lab focuses on DNS behavior, routing strategies, and traffic management concepts rather than compute infrastructure.

---

## Routing policies implemented

### 1. Simple Routing
- Basic A record returning a single IP address
- Demonstrates default DNS resolution behavior

### 2. Geolocation Routing
- Traffic routed based on user geographic location
- Configured records for:
  - Germany
  - United States
  - Default fallback location

### 3. IP-Based Routing
- Routing decisions based on client source IP address
- CIDR collections used to map IP ranges to specific responses

### 4. Multi-Value Answer Routing
- Multiple A records for the same DNS name
- Basic DNS-level load distribution and availability

---

## AWS Services Used
- Amazon Route 53
- Hosted Zones
- DNS Records
- Routing Policies
- CIDR Collections

---

## Key Concepts Learned
- How DNS routing policies affect global traffic behavior
- When to use Geolocation vs IP-based routing
- How Multi-Value routing differs from load balancing
- How DNS design impacts availability and latency

---

## Cost Considerations
- Hosted zones incur small recurring charges
- All resources were removed after testing
- No unnecessary DNS records left active

---

## Cleanup
All Route 53 records and hosted zones were deleted after completing the lab to avoid ongoing charges.
