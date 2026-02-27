# AWS Well-Architected & Cloud Adoption Framework Assessment

## Project Overview
This repository documents the evaluation and redesign of a two-tier web application migrated from on-premises infrastructure to AWS.  
The goal was to analyze the system using structured cloud architecture frameworks and propose an improved design aligned with AWS best practices.

---

## Approach

### 1. Architecture Review
The existing workload was analyzed to understand its components and limitations.  
The system consisted of:
- Web frontend
- Backend database
- Single deployment environment

Key risks were identified, including single point of failure, limited scalability, weak security controls, and lack of automation.

---

### 2. Well-Architected Framework Evaluation
The workload was evaluated across the five AWS Well-Architected pillars:

- Operational Excellence  
- Security  
- Reliability  
- Performance Efficiency  
- Cost Optimization  

For each pillar, the process followed three steps:
1. Identify a strength in the current design
2. Identify a weakness or risk
3. Recommend an AWS service or architectural improvement

Findings were documented in a structured assessment table to maintain consistency and traceability.

---

### 3. Cloud Adoption Framework Analysis
Organizational readiness for cloud migration was evaluated using six CAF perspectives:

- Business
- People
- Governance
- Platform
- Security
- Operations

Each perspective was assessed by:
- Identifying current capabilities
- Highlighting readiness gaps
- Recommending enabling actions for successful adoption

This ensured the evaluation considered organizational and operational factors, not just technical architecture.

---

### 4. Improved Architecture Design
Based on insights from WAF and CAF evaluations, a redesigned AWS architecture was proposed.  
The design emphasizes:

- High availability using multi-AZ deployment
- Scalability through load balancing and auto scaling
- Security using IAM controls and network isolation
- Observability through monitoring and logging
- Cost efficiency via elastic resource usage

The architecture addresses weaknesses identified in the original system and aligns with cloud-native best practices.
