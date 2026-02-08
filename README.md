# Controlled AI Core™ (CAIC Standard™)

**PUBLIC SUMMARY** – This is an abbreviated overview of the CAIC Standard™. The full Implementation Specification is available under a commercial license.

---

**Controlled AI Core™ (CAIC)** is a normative security standard for autonomous AI systems. It provides an architectural control layer that enforces autonomy limits, human accountability, and immutable audit—turning AI safety from policy promises into measurable, enforceable, and legally‑binding requirements.

The CAIC Standard™ defines a practical, auditable, and human‑accountable architecture for deploying AI systems with controlled autonomy, explicit responsibility, and enforceable safety mechanisms.

## Purpose

As AI systems transition from assistive tools to autonomous and agentic systems, organizations face growing risks related to:

- Loss of human control
- Undefined responsibility and accountability
- Regulatory non‑compliance
- Unsafe or irreversible autonomous actions

The CAIC Standard™ addresses these risks by providing a vendor‑neutral governance architecture that makes AI systems controllable, auditable, and legally defensible.

## What CAIC Standard™ Is

The CAIC Standard™ is:

- A governance and control standard, **not a software product**
- Model‑agnostic and vendor‑independent
- Designed for enterprise and high‑risk AI systems
- Focused on **operational control**, not ethics statements or principles
- Built around human responsibility by design

**It is not:** a software product, a regulatory framework, or a certification guarantee.

## Architecture Overview

The CAIC Standard™ is structured in three layers:

1. **Governance Layer** – autonomy scale (L0–L4), risk classification, lifecycle management, and human accountability (AISO).
2. **Technical Control Layer** – runtime enforcement via kernel‑level constraints, including a reference eBPF implementation for Linux.
3. **Operational Security Layer** – continuous behaviour monitoring, fuzzing, adaptive defence, and supply chain integrity.

## Core Concepts

The standard is built around several key mechanisms:

- **Control Plane** – a mandatory interception layer between users and AI models.
- **Autonomy Levels (L0–L4)** – explicit limits on AI decision‑making authority.
- **Policy Engine** – machine‑enforceable rules defining allowed and forbidden actions.
- **Pre‑ and Post‑Inference Gates** – control points evaluating requests and responses before and after model execution.
- **AISO (AI System Owner)** – a formally accountable human role responsible for AI system behavior.
- **Kill‑Switch & Incident Control** – mandatory emergency shutdown and incident response mechanisms.
- **Immutable Audit Logging** – verifiable records of all AI decisions and control actions.

## Standard Composition

The full version of the standard includes **22 normative protocols**, structured as:

- **16 Governance protocols** (A1–A15, A5a) – autonomy, policies, testing, audit, roles, lifecycle.
- **4 Technical Control protocols** (A16–A19) – runtime security, MCP gateway, agent control, RAG security.
- **3 Operational Security protocols** (A20–A22) – observability, continuous monitoring, supply chain integrity.

## Current Status

- **Standard Version:** v2.2 (current)
- **Publication Status:** Public summary available; full specification under commercial license
- **Certification:** Available for licensees upon request
- **Domain‑specific policies:** Not included in this public summary

## Licensing & Trademark

**Controlled AI Core™** and **CAIC Standard™** are original works.

- Use of this public summary is governed by the terms defined in **LICENSE.md**.
- Trademark usage is governed by **TRADEMARK.md**.
- Commercial use, certification, and redistribution of the full specification require explicit written permission from the author.

## Author

**Albert Shamin**  
Independent author and maintainer

## Disclaimer

The CAIC Standard™ is provided as a governance and architectural standard.  
It **does not constitute** legal advice, regulatory approval, or a warranty of compliance.

Organizations remain fully responsible for the lawful and safe operation of their AI systems.

## Contact

For licensing, certification, or access to the full Implementation Specification, please contact the author directly.

---

© 2026 Albert Shamin. All rights reserved.  
CAIC Standard™, Controlled AI Core™ – trademarks pending.
