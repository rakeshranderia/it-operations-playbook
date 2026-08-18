# Business Continuity & Operational Resilience

## Overview

Technology resilience is the ability of an organisation to continue delivering critical services during disruption and recover effectively when normal operations are affected.

Business continuity should focus on the outcomes the organisation needs to maintain rather than technology alone.

---

## Resilience Principles

A resilient organisation should:

- Understand critical services
- Identify dependencies
- Define acceptable disruption
- Prepare response plans
- Test recovery capabilities
- Learn from incidents
- Continuously improve

---

## Critical Business Services

The starting point should be understanding which services are most important to the organisation.

For each critical service, identify:

- Business owner
- Technology owner
- Customers affected
- Supporting applications
- Infrastructure dependencies
- People dependencies
- Supplier dependencies
- Data dependencies
- Recovery requirements

---

## Business Impact Analysis

A Business Impact Analysis (BIA) helps determine the consequences of disruption.

Consider:

- Financial impact
- Customer impact
- Regulatory impact
- Operational impact
- Reputational impact
- Safety considerations

The BIA should help establish appropriate recovery requirements.

---

## Recovery Objectives

### Recovery Time Objective — RTO

The maximum acceptable time within which a service should be restored following disruption.

### Recovery Point Objective — RPO

The maximum acceptable amount of data loss measured in time.

For example:

**RTO = 4 hours**

**RPO = 1 hour**

This means the organisation aims to restore the service within four hours while limiting data loss to approximately one hour.

---

## Dependency Mapping

Critical services should be mapped to their dependencies.

```text
Business Service
       ↓
Business Process
       ↓
Application
       ↓
Data
       ↓
Infrastructure
       ↓
Network / Cloud
       ↓
Third-Party Providers