# A1 – Core Specification

**Part of:** Controlled AI Core™ (CAIC)  
**Version:** 1.2  
**Status:** Normative  
**Year:** 2026  
**Author:** Albert Shamin  
**Trademark:** Controlled AI Core™

**PUBLIC SUMMARY** – This document is an abbreviated overview of the Controlled AI Core™ Standard. The full implementation specification is not publicly available.

---

## 1. Purpose

The Controlled AI Core™ (CAIC) Standard defines a mandatory control plane for any AI system that interacts with users or executes actions. Its goal is to ensure that every AI‑generated output is subject to explicit, enforceable constraints – regardless of the underlying model’s intelligence or capabilities.

The control plane acts as a gateway between the user and the AI model. All requests and responses pass through this layer, where they are inspected, evaluated against predefined policies, and either allowed, modified, or blocked.

## 2. Core Concepts

### 2.1 Control Plane
A separate logical component that intercepts every interaction. It is model‑agnostic and does not rely on the AI’s cooperation. Responsible for parsing inputs/outputs, evaluating effective autonomy, applying policies, enforcing human oversight, and logging all decisions.

### 2.2 Autonomy Levels
Defines five levels (L0–L4) ranging from no autonomous output to full autonomous decisions. Each system is assigned a maximum allowed level; the control plane computes the effective autonomy of each response and blocks or escalates if exceeded.

### 2.3 Policies
External rules applied by the control plane, not embedded in the model. Cover safety, legal compliance, operational boundaries, and autonomy restrictions. Can be global, domain‑specific, or system‑specific; evaluated before and/or after generation.

### 2.4 Execution Gates
Checkpoints that validate input, process output, compare effective autonomy with allowed level, and decide: ALLOW, BLOCK, or ESCALATE.

### 2.5 Human Oversight Interface
Mandatory component allowing designated humans (e.g., AISO) to review escalated requests and override decisions. All interventions are logged with attribution.

### 2.6 Audit Layer
Every decision is recorded in an immutable audit log – complete, traceable, and attributable.

## 3. Compliance Requirements

To claim compliance, an implementation must include all mandatory components, have a designated AISO, pass test scenarios, and provide a signed Compliance Statement.

## 4. Relationship to Other Documents

This Core Specification is complemented by A2, A3, A6, A13, A14, A15, and the Reference Architecture.

## 5. Disclaimer

This document is a public summary. It omits exact API schemas, algorithms, test cases, audit log structures, legal clauses, and implementation guides. For full specifications, refer to the commercial version.
