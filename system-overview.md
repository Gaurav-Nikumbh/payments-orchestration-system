# System Overview

The payments orchestration system acts as a control layer for payment execution.

It does not move funds directly but determines:

- whether a payment is allowed
- when it should be executed
- how it should be routed

---

## Core Responsibilities

- validation and entitlement checks
- balance verification
- fraud and compliance enforcement
- retry and failure handling
- transaction lifecycle tracking
