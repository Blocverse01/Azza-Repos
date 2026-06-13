# Azza Codebase Directory

This repository serves as a high-level directory of Azza's major codebases, with links, descriptions, and access guidance.

Azza's engineering stack spans customer-facing payments infrastructure, internal operations tooling, treasury and FX automation, metrics, provider orchestration, and earlier product experiments. Some repositories are public and open for reference. Others remain private because they contain sensitive business logic, operational workflows, partner integrations, security-sensitive implementation details, and core technical IP.

If you need access to a private repository for legitimate collaboration, auditing, partnership, or engineering work, email **tc@blocverse.com** with your request and context.

---

## 1. Azza WhatsApp Bot
**Repository:** <https://github.com/Blocverse01/Azza-whatsapp-bot>

**Description:**
This is the main Azza WhatsApp Bot codebase and one of the most important repositories in the Azza stack. It contains the core backend and application logic behind Azza's WhatsApp-based product experience, including the workflows, orchestration, and technical patterns that power the bot in production.

**Access:** Private

**Why it is private:**
This repository contains core technical IP, product logic, infrastructure patterns, operational workflows, and implementation details that are central to how Azza works. Restricting access helps protect the platform's architecture, partner-facing integrations, internal flows, and security-sensitive logic.

**Access requests:** Email **tc@blocverse.com** to request access.

---

## 2. Azza FX Management Service
**Repository:** <https://github.com/Blocverse01/azza-fx-management-service>

**Description:**
This service manages and automates Azza's FX, treasury, and reconciliation flows. It is part of the internal financial operations layer that helps coordinate exchange-rate handling, reconciliations, and supporting financial workflows required to keep the system operational and accurate.

**Access:** Public

---

## 3. Pay with Azza
**Repository:** <https://github.com/Blocverse01/pay-with-azza>

**Description:**
This codebase represents Azza's newer payment gateway product, designed to extend Azza's infrastructure into broader payment acceptance and gateway flows. It reflects an important next step in Azza's platform evolution and is currently in private beta.

**Access:** Private beta

**Why it is private:**
This repository is still under active controlled rollout and contains product logic, integration patterns, and implementation details that are not yet ready for open distribution. Keeping it private helps protect unreleased functionality, maintain operational control during beta, and reduce security and integration risk while the product matures.

**Access requests:** Email **tc@blocverse.com** to request access.

---

## 4. Azza Operations
**Repository:** <https://github.com/Blocverse01/azza-operations>

**Description:**
This is Azza's operations codebase. It powers the internal systems used to support company operations, transaction monitoring, operational workflows, internal tooling, and day-to-day visibility into the platform's activity.

**Access:** Public

---

## 5. Azza Metrics
**Repository:** <https://github.com/Blocverse01/azza-metrics>

**Description:**
This codebase powers Azza's metrics and reporting infrastructure. It is used for tracking platform performance, growth, transaction activity, and internal business visibility through dashboards and reporting workflows.

**Access:** Public

---

## 6. Azza Rate Monitor
**Repository:** <https://github.com/Blocverse01/rates-monitor>

**Description:**
Azza's open-source rate monitor. This repository is focused on observing and tracking rate data, helping provide visibility into pricing conditions and rate movements relevant to Azza's broader payments and FX flows.

**Access:** Public

---

## 7. Fiat Ramps gRPC Service
**Repository:** <https://github.com/Blocverse01/fiat-ramps-gRPC-service>

**Description:**
This Go-based service was built to handle fiat ramp flows across multiple providers. It represents part of Azza's infrastructure layer for orchestrating ramps and abstracting provider-level complexity into a more unified internal service architecture.

**Access:** Public

---

## 8. Azza Business WhatsApp Bot
**Repository:** <https://github.com/Blocverse01/azza-business-whatsapp-bot>

**Description:**
This repository contains the V1 implementation of Azza's business-focused WhatsApp infrastructure. It reflects an earlier phase of Azza's business product architecture and has since been open-sourced as part of Azza's broader technical journey.

**Access:** Public

---

## Notes on Private Repositories
Azza keeps some repositories private not to reduce transparency, but to protect the security, integrity, and long-term defensibility of the platform. These private codebases may include:

- core product and infrastructure IP
- internal operational logic and workflows
- sensitive partner and provider integration details
- security-relevant implementation patterns
- unreleased or beta product functionality

Where access is needed for legitimate work, collaboration, diligence, or review, requests can be made via **tc@blocverse.com**.

---

## About Azza
**Azza** is building stablecoin-native financial infrastructure around a chat-first user experience. At its core, Azza turns familiar messaging interfaces, especially WhatsApp, into an access layer for digital dollar banking, crypto-fiat conversion, treasury movement, and broader payment workflows.

Azza's product direction is rooted in making stablecoin usage feel simple, accessible, and practical for real users. Instead of forcing people to navigate complex crypto interfaces, Azza brings onchain and offchain financial actions into a lightweight conversational flow.

### What Azza is solving
- **Complex blockchain UX:** Traditional crypto products are often too technical for everyday users.
- **Trust and security barriers:** Users want intuitive products without compromising the safety of their funds.
- **Access gaps:** Many users do not have easy access to conventional exchanges or the technical knowledge to use them comfortably.

### Azza's approach
- **Chat-first financial access:** Users can interact with stablecoin infrastructure through familiar messaging flows.
- **Simplified ramps:** Buying, selling, moving, and cashing out stablecoins becomes much easier than navigating fragmented crypto tools.
- **Operationally grounded infrastructure:** Azza combines product UX with internal tooling, rate monitoring, treasury automation, metrics, and provider orchestration.
- **Security-conscious architecture:** Parts of the stack rely on sensitive infrastructure and implementation details, which is one reason several repos remain private.

### Product visuals
![Azza WhatsApp Bot](https://github.com/user-attachments/assets/ea83b999-f938-43c7-8460-db6ee1d7f0d8)

### Links
- **Azza Insights / Documentation:** <https://medium.com/azza-insights>
- **Demo Video:** <https://www.loom.com/share/d74a937909c44bf69d0545ad939a1d9f?sid=c89f4f8a-7c00-4485-b7f2-c6426df875ff>
