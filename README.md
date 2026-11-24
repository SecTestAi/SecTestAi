# SecTestAi

**Authorized Web & API security assessment, run by an AI agent.**

SecTestAi plans and runs security assessments against **Web and API** targets you own or are expressly authorized to test. Each run begins with an authorization declaration in your account and ends with reproducible, evidence-backed findings your team or your client can act on.

> **This repository is documentation only.** SecTestAi is **not open source**. We do **not** publish source code or installers on GitHub. Download Windows / macOS / Linux builds and obtain API keys only at **[https://sectestai.com](https://sectestai.com)**.

<p align="center">
  <a href="https://sectestai.com"><img src="https://img.shields.io/badge/Website-sectestai.com-0A66C2?style=for-the-badge" alt="Website" /></a>
  <a href="https://sectestai.com"><img src="https://img.shields.io/badge/Sign%20up%20%26%20Get%20API%20key-16A34A?style=for-the-badge" alt="Sign up" /></a>
  <a href="https://sectestai.com"><img src="https://img.shields.io/badge/Download-Win%20%7C%20macOS%20%7C%20Linux-111827?style=for-the-badge" alt="Download" /></a>
</p>

## Why signature-based testing is not enough

Modern applications express behaviour through APIs and multi-step flows. Rule-based scanners match known patterns; they do not reason about who should be able to do what.

| Challenge | What goes wrong |
|-----------|-----------------|
| **Pattern matching has limits** | Logic defects with no known “signature” are where unintended exposure often hides. |
| **Access control is where exposure starts** | Horizontal/vertical privilege errors and insecure object references remain common causes of data exposure. |
| **Multi-step flows need a tester** | Approvals, checkout, and state changes spanning several requests are invisible to single-endpoint scanners. |

## Platform + AI Agent + Browser

One system to schedule an assessment, work through the target the way a tester would, and produce structured deliverables — with authorization controls applied to every run.

1. **Platform** — Task lifecycle, live logs, reports, and the account console where declarations and human confirmation gate each run.
2. **AI Agent** — Plans a route through the application, forms and tests hypotheses about roles and business intent, and records evidence for each finding within the scope you approved.
3. **Browser** — Drives modern front-ends (clicks, forms, sessions) so assessments follow genuine user journeys rather than a static request list.

**Flow:** Approved target → Live assessment log → Evidence-backed report

## Assess, then independently verify

Discovery and confirmation are separated so noisy candidates are filtered before anything reaches a report.

1. **Assess** — The agent works through the approved target and records candidate findings with evidence.
2. **Verify** — A separate pass re-tests each candidate, confirms or discards it, and keeps only issues that reproduce with a complete evidence chain.

## What SecTestAi assesses

SecTestAi performs **security assessment and risk evaluation** within an approved scope — it is not a source-code audit. Running outside that scope is prohibited.

### Access control

- Horizontal and vertical privilege errors
- Insecure direct object references (IDOR)
- Authentication and session weaknesses

### Data exposure

- Predictable and enumerable identifiers
- Fields returned without masking
- Over-broad query and search responses

### Business-flow integrity

- Parameter tampering across multi-step flows
- Verification or approval steps that can be skipped or reordered
- State-changing requests that can be replayed or raced

## Get started (download on the website only)

1. Open **[https://sectestai.com](https://sectestai.com)** and download the client for **Windows**, **macOS**, or **Linux** (latest version is always on the website).
2. **Sign up** for an account and obtain an API key. **New accounts receive $20 in Token credit.**
3. In your account, declare the target and the basis for testing it, then **confirm** authorization in the portal before a run can start.
4. Run the assessment on your machine; review live logs and the structured report.

There are **no GitHub Releases**, installers, or binaries in this repository.

## Not open source

| What this repo is | What this repo is not |
|-------------------|------------------------|
| Product overview and links for discovery | Source code of the agent or desktop app |
| Pointers to documentation and policies on the website | A place to download `.exe` / `.dmg` / `.tar.gz` |
| Proprietary software notice (`LICENSE`) | An open-source license (MIT/Apache/GPL, etc.) |

Software, trademarks, and related materials are proprietary. Use of SecTestAi is governed by the Terms of Service and Acceptable Use Policy on [sectestai.com](https://sectestai.com).

## Built to run inside a scope you can prove

SecTestAi is offered for **authorized security assessment only**:

- A declaration before every assessment (assets you own/operate, or assets entrusted by a client or employer)
- A human confirms in the portal (recorded with declaration version, time, IP, and user-agent)
- Target location checks; declarations or authorizations can be refused or withdrawn
- Append-only, hash-chained audit events for authorization and assessment
- Published abuse-reporting channel; accounts or authorizations can be suspended or withdrawn
- One account, its own operator — runs may not be resold, sublicensed, or shared

Read the **Acceptable Use Policy** and **Terms of Service** on the website before you run anything. An assessment cannot start until they are accepted in your account.

## Support

- Product, downloads, billing, and API keys: **[https://sectestai.com](https://sectestai.com)**
- For product questions on GitHub, open an Issue in this repo — **downloads and billing are handled only on the website**.
