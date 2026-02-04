# Controlled AI Core™ — Versioning Policy

## Overview

This repository follows a strict and transparent versioning policy to ensure
stability, auditability, and enterprise trust for high-risk and regulated AI systems.

Controlled AI Core™ is treated as a **standard**, not as an experimental framework.

---

## Versioning Scheme

Versions follow the format:

MAJOR.MINOR (e.g. v1.2)

### MAJOR version (v2.0, v3.0, ...)
A MAJOR version change indicates:
- Changes to core requirements or guarantees
- Changes in autonomy definitions or responsibility boundaries
- Breaking changes affecting compliance or audit interpretation
- Structural changes to the standard itself

MAJOR upgrades require explicit migration guidance.

---

### MINOR version (v1.1 → v1.2)
A MINOR version change indicates:
- Clarification of existing requirements
- Enterprise hardening and alignment
- Additional governance, compliance, or documentation layers
- No breaking changes to previously compliant implementations

Backward compatibility is guaranteed within the same MAJOR version.

---

## Frozen Components (Normative)

The following components are considered **normative and frozen** within a MAJOR version:

- Core Specification
- Autonomy Level Mapping Guide
- Policy & Behavior Templates
- Test Scenarios & Provocation Sets
- Compliance & Audit Framework
- Governance & Accountability Specifications

Changes to these components require a MAJOR version increment.

---

## Extensible Components (Informative)

The following components may evolve without changing the MAJOR or MINOR version:

- Technical Implementation Guide
- Reference Architecture
- Adoption & Migration Framework
- Legal & Compliance Examples
- Reference Implementations

These components provide guidance but do not alter compliance requirements.

---

## Change Control

- All changes must be documented
- No silent or undocumented changes are permitted
- All version updates must be reflected in CHANGELOG.md

---

## Stability Commitment

Once a version is marked **STABLE**, its normative requirements will not change
until the next MAJOR release.

---

© Controlled AI Core™  
All rights reserved.
