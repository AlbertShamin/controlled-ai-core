# A2 – Autonomy Level Mapping

**Part of:** Controlled AI Core™ (CAIC Standart™)  
**Version:** 2.2  
**Status:** Normative  
**Year:** 2026  
**Author:** Albert Shamin  
**Trademark:** Controlled AI Core™

**PUBLIC SUMMARY** – This document is an abbreviated overview of the Controlled AI Core™ Standard. The full implementation specification is not publicly available.

---

## 1. Purpose

Defines the mandatory classification of AI system autonomy into five discrete levels. Used by the control plane to determine which outputs are permitted based on the system’s assigned autonomy cap.

## 2. Autonomy Levels (L0–L4)

| Level | Name | Brief Description |
|-------|------|-------------------|
| L0 | No Autonomous Output | Pre‑approved content only. |
| L1 | Informational | Factual answers, no actions. |
| L2 | Advisory | Recommendations, human confirmation required. |
| L3 | Conditional Action | Actions under real‑time supervision. |
| L4 | Autonomous Decision | Full actions without intervention (rare). |

## 3. Effective Autonomy

Every AI response is evaluated to determine its **effective autonomy** – a measure derived from content, context, and potential impact. The control plane computes this value (using proprietary heuristics) and compares it to the **maximum allowed level**. If exceeded, the response is blocked or escalated.

## 4. Relationship to Other Standards

This document complements A1 and is referenced by A3 and the test suite (not public).
