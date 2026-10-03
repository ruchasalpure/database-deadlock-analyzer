---
name: lock-graph-analysis
description: Specialized capability for Monitors relational database lock graphs and transaction logs to detect circular lock waits and recommend index restructuring.
license: MIT
allowed-tools: ""
metadata:
  author: "Rucha Salpure"
  version: "1.0.0"
  category: data-analytics
---

# Database Deadlock Analyzer Agent — Lock Graph Analysis Skill

## Purpose
The `lock-graph-analysis` capability provides high-assurance execution routines for `Database Deadlock Analyzer Agent`.

## Execution Workflow
1. Validate input parameters against typed schemas and invariant constraints.
2. Ingest contextual metrics and establish a deterministic baseline.
3. Formulate candidate recommendations with explicit confidence intervals.
4. Submit draft plans to the independent checker agent for verification.

## Boundary Conditions
- **Input validation:** Reject non-conforming or malformed payloads before evaluation.
- **Fail-safe:** Escalate immediately if telemetry indicators exhibit critical anomalies.
