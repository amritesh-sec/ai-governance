---
layout: post
title: "The EU AI Act: A Practical Compliance Guide for 2026"
date: 2026-05-12
author: Amritesh
category: ai-governance
tags: [EU-AI-Act, compliance, risk-tiers, governance, NIST-AI-RMF]
description: "A practical guide to EU AI Act compliance — risk tiers, obligations by tier, timeline, and how it compares to NIST AI RMF for organisations operating across the US, UK, and EU."
---

The EU AI Act is the world's first comprehensive AI regulation — and it does not only apply to companies headquartered in Europe. Any organisation whose AI system output is used by people in the EU falls within scope, regardless of where the company is based. For US and UK organisations with European customers, this is not optional reading.

This guide translates the regulation into what actually matters for compliance teams, boards, and AI governance functions.

---

## Who This Affects

The extraterritorial reach of the EU AI Act mirrors GDPR's approach. You are in scope if:

- You provide an AI system that is placed on the EU market
- Your AI system's output is used within the EU, even if you have no EU presence
- You are a US or UK company with EU customers using your AI-powered product

> If your SaaS product has a single EU customer using an AI feature, you are likely in scope. This catches far more US and UK companies than most realise.

---

## The Risk-Tier Structure

The EU AI Act's core mechanism is risk classification. Obligations scale with risk:

### Unacceptable Risk — Prohibited

Certain AI practices are banned outright, including:

- Social scoring by public authorities
- Real-time biometric identification in public spaces (with narrow exceptions)
- Manipulative AI exploiting vulnerabilities (age, disability)
- Emotion inference in workplaces and educational institutions (with limited exceptions)

### High Risk — Heavily Regulated

This is where most enterprise compliance effort concentrates. High-risk categories include:

- AI used in recruitment, employee evaluation, and HR decisions
- AI used in credit scoring and financial services eligibility
- AI used in critical infrastructure
- AI used in education (assessment, admission)
- AI used in law enforcement and migration

**High-risk obligations include:**

1. Risk management system throughout the AI lifecycle
2. Data governance — training data quality, bias testing
3. Technical documentation and record-keeping
4. Transparency to users
5. Human oversight mechanisms
6. Accuracy, robustness, and cybersecurity requirements
7. Conformity assessment before market placement

### Limited Risk — Transparency Obligations

Chatbots, deepfakes, and emotion recognition systems require disclosure that users are interacting with AI or AI-generated content.

### Minimal Risk — No Specific Obligations

The majority of AI applications (spam filters, AI in video games) fall here with no specific obligations beyond general product safety law.

### General-Purpose AI (GPAI) — Special Category

Foundation models and general-purpose AI systems have their own obligations, scaling further for models deemed to carry "systemic risk" based on compute thresholds.

---

## Compliance Timeline

| Date | Obligation |
|------|-----------|
| February 2025 | Prohibited practices ban took effect |
| August 2025 | GPAI obligations took effect |
| August 2026 | High-risk system obligations take effect |
| August 2027 | Extended deadline for certain embedded high-risk systems |

If you are reading this and have not yet begun a high-risk classification exercise, the August 2026 deadline is closer than it appears once you account for documentation and conformity assessment lead time.

---

## EU AI Act vs NIST AI RMF — Key Differences

US organisations often ask how their NIST AI RMF work translates to EU AI Act compliance. The honest answer: it helps, but does not replace it.

| Aspect | EU AI Act | NIST AI RMF |
|--------|-----------|--------------|
| Nature | Mandatory law | Voluntary framework |
| Enforcement | Fines up to €35M or 7% global turnover | None (reputational/contractual only) |
| Structure | Risk-tiered prohibitions and obligations | Four functions: Govern, Map, Measure, Manage |
| Scope | EU market impact, extraterritorial | Primarily US-focused, increasingly cited internationally |
| Certification | Conformity assessment required for high-risk | No formal certification |

**Practical implication:** Organisations using NIST AI RMF as their governance foundation have strong process maturity that maps well onto EU AI Act risk management requirements — but legal compliance still requires EU AI Act-specific documentation, conformity assessment, and CE marking for high-risk systems.

---

## What Boards Should Be Asking Now

For board members and executives overseeing AI governance, the right questions are:

1. **Do we know our AI system inventory?** Most organisations cannot answer this completely.
2. **Have we classified each system by risk tier?** This drives everything downstream.
3. **Who owns AI governance internally?** Without clear ownership, compliance gaps emerge silently.
4. **What is our August 2026 readiness for high-risk systems?**
5. **Do our vendor contracts address AI Act compliance obligations?**

---

## A Practical First Step — AI System Inventory

Before any compliance programme can function, organisations need a complete inventory:

```
For each AI system, document:
- Business purpose and deployment context
- Risk tier classification (and rationale)
- Data sources used for training/operation
- Human oversight mechanisms in place
- Vendor/third-party AI components
- Current documentation status
```

This inventory becomes the foundation for risk registers, board reporting, and conformity assessment preparation.

---

## Official Resources

- [EU AI Act — Official Text](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689)
- [European Commission — AI Act Implementation](https://digital-strategy.ec.europa.eu/en/policies/ai-act-implementation)
- [NIST AI Risk Management Framework 1.0](https://www.nist.gov/itl/ai-risk-management-framework)
- [ISO/IEC 42001:2023](https://www.iso.org/standard/81230.html)

---

## Conclusion

The EU AI Act represents a fundamental shift — AI governance is no longer a voluntary best practice for organisations with EU exposure; it is enforceable law with significant penalties. Organisations that begin systematic risk classification now will face August 2026 with confidence. Those that wait face a documentation and conformity assessment timeline that does not compress easily.

The next article in this series covers **building an AI governance committee structure** — who should sit on it, what authority it needs, and how it reports to the board.

---

*Questions or corrections on this analysis? [Get in touch](https://amritesh-sec.github.io/contact/).*
