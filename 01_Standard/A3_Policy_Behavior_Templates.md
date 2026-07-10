# A3 — Policy & Behavior Templates

**Part of:** Controlled AI Core™ (CAIC Standart™)  
**Version:** 1.2  
**Status:** Normative  
**Year:** 2026  
**Author:** Albert Shamin  
**Trademark:** Controlled AI Core™

**PUBLIC SUMMARY** – This document is an abbreviated overview of the Controlled AI Core™ Standard. The full implementation specification is not publicly available.

---

## 1. Purpose

Defines a standardised way to create external rules (policies) that govern AI behaviour, applied by the control plane independently of the model.

## 2. Policy Concept

Policies are sets of conditions and corresponding actions (allow, block, escalate). They are scoped globally, by domain, or per system, and can be evaluated before or after AI generation.

## 3. Policy Categories

Policies address autonomy limits, safety, legal compliance, and operational boundaries.

## 4. Enforcement

The control plane evaluates all applicable policies in priority order; the most restrictive action prevails.

## 5. Relationship

Used with A1 and A2, and referenced by the Audit Framework.
