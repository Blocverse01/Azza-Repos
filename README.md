# Azza Codebase Directory

This repository is a curated directory of Azza's major codebases, with links, descriptions, access guidance, and product context.

Azza's engineering stack spans customer-facing payments infrastructure, treasury and FX automation, internal operations tooling, metrics, rate monitoring, provider orchestration, and earlier product implementations. Some repositories are public and open for reference. Others remain private because they contain core technical IP, sensitive business logic, operational workflows, partner integrations, security-relevant implementation details, and unreleased product functionality.

If you need access to a private repository for legitimate collaboration, diligence, partnership, security review, or engineering work, email **tc@blocverse.com** with your request and context.

Additional Azza repositories may be added to this directory over time as they are opened, published, or made suitable for broader access.

---

## Codebase Index

### 1. Azza WhatsApp Bot
**Repository:** <https://github.com/Blocverse01/Azza-whatsapp-bot>

**What it is:**
This is the primary Azza WhatsApp Bot repository and one of the most strategically important codebases in the Azza stack. It contains the core backend systems, product logic, orchestration flows, and implementation patterns behind Azza's WhatsApp-native financial experience.

**Access:** Private

**Why it is private:**
This repository contains core technical IP and sensitive implementation details central to how Azza operates in production. That includes product logic, infrastructure patterns, internal workflows, and partner-facing integrations. Restricting access helps protect security, operational integrity, and the long-term defensibility of the platform.

**Access requests:** Email **tc@blocverse.com** to request access.

---

### 2. Azza FX Management Service
**Repository:** <https://github.com/Blocverse01/azza-fx-management-service>

**What it is:**
This service manages and automates Azza's FX, treasury, and reconciliation flows. It supports the internal financial operations layer that helps coordinate exchange-rate management, reconciliations, and supporting capital movement workflows required to keep the broader system accurate and efficient.

**Access:** Public

---

### 3. Pay with Azza
**Repository:** <https://github.com/Blocverse01/pay-with-azza>

**What it is:**
This codebase represents Azza's newer payment gateway product, extending Azza's infrastructure into broader payment acceptance and gateway workflows. It is a key part of Azza's next-generation platform direction and is currently in private beta.

**Access:** Private beta

**Why it is private:**
This repository remains private because it contains beta-stage product logic, integration patterns, and implementation details that are still under controlled rollout. Keeping it private helps protect unreleased functionality, reduce security risk, and preserve operational control while the gateway matures.

**Access requests:** Email **tc@blocverse.com** to request access.

---

### 4. Azza Operations
**Repository:** <https://github.com/Blocverse01/azza-operations>

**What it is:**
This is Azza's operations codebase. It powers internal systems used for operational workflows, transaction visibility, monitoring, support tooling, and day-to-day company operations across the platform.

**Access:** Public

---

### 5. Azza Metrics
**Repository:** <https://github.com/Blocverse01/azza-metrics>

**What it is:**
This codebase powers Azza's metrics and reporting infrastructure. It supports internal visibility into platform performance, growth, transaction activity, reporting, and business intelligence workflows.

**Access:** Public

---

### 6. Azza Rate Monitor
**Repository:** <https://github.com/Blocverse01/rates-monitor>

**What it is:**
Azza's open-source rate monitor. This repository focuses on observing and tracking rate data, helping provide visibility into pricing conditions and market movements relevant to Azza's broader payments and FX infrastructure.

**Access:** Public

---

### 7. Fiat Ramps gRPC Service
**Repository:** <https://github.com/Blocverse01/fiat-ramps-gRPC-service>

**What it is:**
This Go-based service was built to handle fiat ramp flows across multiple providers. It represents part of Azza's infrastructure layer for orchestrating ramps and abstracting provider complexity into a more unified internal service architecture.

**Access:** Public

---

### 8. Azza Business WhatsApp Bot
**Repository:** <https://github.com/Blocverse01/azza-business-whatsapp-bot>

**What it is:**
This repository contains the V1 implementation of Azza's business-focused WhatsApp infrastructure. It reflects an earlier phase of Azza's business product architecture and has since been open-sourced as part of Azza's broader technical journey.

**Access:** Public

---

## Why Some Repositories Are Private
Azza keeps some repositories private not to reduce transparency, but to protect the security, integrity, and strategic defensibility of the platform. These private codebases may include:

- core product and infrastructure IP
- internal operational logic and workflows
- sensitive partner and provider integration details
- security-relevant implementation patterns
- unreleased or beta product functionality

Where access is needed for legitimate collaboration, diligence, review, or partnership work, requests can be made via **tc@blocverse.com**.

---

## About Azza
**Azza** is building stablecoin-native financial infrastructure around a chat-first user experience. At its core, Azza turns familiar messaging interfaces, especially WhatsApp, into an access layer for digital dollar banking, crypto-fiat conversion, treasury movement, and broader payment workflows.

Azza's product direction is rooted in making stablecoin usage simple, accessible, and practical for real users. Instead of forcing people to navigate complex crypto interfaces, Azza brings onchain and offchain financial actions into a lightweight conversational flow.

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
![Azza WhatsApp Bot](https://res.cloudinary.com/dtfyyzwoz/image/upload/v1781361843/Azzareadmeimg_suhpr4.png)

### Links
- **Azza Insights / Documentation:** <https://medium.com/azza-insights>
- **Demo Video:** <https://www.loom.com/share/d74a937909c44bf69d0545ad939a1d9f?sid=c89f4f8a-7c00-4485-b7f2-c6426df875ff>
