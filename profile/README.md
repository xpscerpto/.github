<div align="center">

# XPScerpto

### Governed Sovereign Cryptographic Infrastructure for Sensitive Systems

**Explicit authority · Controlled access · Provable custody · Replayable evidence · Evidence-gated claims**

<br>

![Status](https://img.shields.io/badge/status-sovereign%20validation-informational)
![Production Ready](https://img.shields.io/badge/production--ready-not%20asserted-critical)
![Bootstrap Complete](https://img.shields.io/badge/bootstrap--complete-not%20asserted-critical)
![Sanitizer Clean](https://img.shields.io/badge/full%20sanitizer%20clean-not%20asserted-critical)
![Claim Discipline](https://img.shields.io/badge/claims-evidence%20gated-blue)

</div>

---

## 🧭 Definition

**XPScerpto** is a governed sovereign cryptographic infrastructure platform for sensitive systems.

It subjects authority, access, custody, evidence, and operational behavior to replayable proof. The platform connects governance, access control, supply-chain control, verification, audit, and advanced cryptographic layers, including classical cryptography, post-quantum cryptographic domains, and encrypted-computing domains, under one disciplined model.

XPScerpto is not organized as a loose collection of cryptographic utilities. It is structured as a governed platform where execution authority, validation evidence, module boundaries, failure behavior, and public claims must remain aligned with proven truth.

---

## 🏛️ Authority Chain

```text
Platform Providers
        ↓
Platform API
        ↓
Hardware Authority
        ↓
Routing Envelope
        ↓
Decision Capsule
        ↓
Domain Bridges
        ↓
SIMD / FHE / PQC Execution
        ↓
Forensic Evidence / Runtime Custody
```

A capability may exist on a machine, but that does not make it admitted execution authority.

Execution authority must be explicit, governed, and aligned with the platform’s validation and evidence model.

---

## 🔒 Claim Discipline

XPScerpto does not treat documentation, UI status, packaged logs, build success, target success, sanitizer configuration, or self-attestation as proof.

Claims must be:

| Requirement           | Meaning                                                    |
| --------------------- | ---------------------------------------------------------- |
| Scope-bound           | The claim must identify exactly what it covers             |
| Evidence-bound        | The claim must be backed by validation evidence            |
| Runtime-bound         | Runtime claims require actual runtime execution            |
| Reproducibility-bound | The result must be tied to replayable or inspectable proof |
| Fail-closed           | Incomplete proof must not become a positive claim          |

A precise partial result is acceptable.
A broad claim without matching evidence is not.

---

## 📊 Current Public Status

| Area                          |        Public status |
| ----------------------------- | -------------------: |
| Organization foundation       |        `in progress` |
| Documentation baseline        |             `staged` |
| Public website                |             `staged` |
| Forensic Command Center       | `staged publication` |
| Production-ready claim        |     **not asserted** |
| Full bootstrap-complete claim |     **not asserted** |
| Full sanitizer-clean claim    |     **not asserted** |
| Full graph acceptance claim   |     **not asserted** |

These are not marketing labels. They are public claim boundaries.

They protect the project from accidental overclaim, stale evidence, partial validation, and misleading release status.

---

## 🧩 Platform Domains

| Domain                 | Role                                                            |
| ---------------------- | --------------------------------------------------------------- |
| Governance             | Authority, ownership, review, and claim discipline              |
| Platform API           | Admitted platform-facing execution surface                      |
| Access Control         | Controlled admission, ownership, and boundary enforcement       |
| Supply Chain           | Source identity, dependency control, and evidence alignment     |
| Hardware Authority     | Hardware evidence, routing discipline, and capability admission |
| Decision Capsule       | Governed routing and execution decision boundary                |
| Domain Bridges         | Controlled transition into cryptographic execution domains      |
| SIMD                   | Authority-routed acceleration and data movement                 |
| Classical Cryptography | Conventional cryptographic domains and primitives               |
| PQC                    | Post-quantum cryptographic domains                              |
| FHE / BFV / CKKS       | Encrypted-computing and bootstrap validation discipline         |
| Evidence / Audit       | Runtime custody, forensic evidence, and replay support          |
| Verification           | Evidence-backed validation, claim gates, and fail-closed review |

---

## 🌐 Public Surfaces

| Surface                 | Location / Status                                           |
| ----------------------- | ----------------------------------------------------------- |
| Documentation           | https://github.com/xpscerpto/docs                           |
| Architecture            | https://github.com/xpscerpto/docs/blob/main/ARCHITECTURE.md |
| Governance              | https://github.com/xpscerpto/docs/blob/main/GOVERNANCE.md   |
| Security                | https://github.com/xpscerpto/docs/blob/main/SECURITY.md     |
| Forensic Command Center | staged publication                                          |
| Website                 | staged publication                                          |

Public surfaces must not imply a stronger validation status than the evidence supports.

---

## 🧪 Validation Boundaries

XPScerpto keeps validation levels separate:

```text
configure success ≠ build success
build success ≠ test success
test success ≠ sanitizer truth
target success ≠ full graph truth
subsystem success ≠ platform-wide readiness
documentation status ≠ implementation proof
UI status ≠ court-accepted evidence
packaged logs ≠ live validation
```

No status is elevated unless the relevant gate proves it.

---

## 🧱 Core Principle

XPScerpto’s engineering model is based on one central rule:

> **Correctness, authority, custody, evidence, and claims must describe the same truth.**

This means a claim is not accepted because it sounds reasonable, appears in documentation, passes a local target, or is displayed by a UI. A claim is accepted only when the required evidence gate proves it within its exact scope.

---

<details>
<summary><strong>What XPScerpto is</strong></summary>

<br>

XPScerpto is a governed sovereign cryptographic infrastructure platform for sensitive systems.

It focuses on:

* explicit execution authority;
* controlled access;
* provable custody;
* platform-controlled admission;
* source identity and supply-chain control;
* hardware-governed routing;
* cryptographic domain separation;
* classical cryptographic domains;
* post-quantum cryptographic domains;
* encrypted-computing domains;
* FHE, BFV, CKKS, and bootstrap validation discipline;
* forensic evidence and replayable proof;
* strict module and authority boundaries;
* fail-closed validation behavior;
* conservative public claim discipline.

</details>

---

<details>
<summary><strong>What XPScerpto is not</strong></summary>

<br>

XPScerpto is not:

* a normal utility library;
* a collection of unrelated cryptographic snippets;
* a production-ready claim by default;
* a project where build success implies acceptance;
* a project where documentation implies implementation proof;
* a project where sanitizer configuration implies sanitizer cleanliness;
* a project where target-only success implies full graph truth;
* a project where one subsystem’s progress implies platform-wide readiness;
* a project where public status can outrun validation evidence;
* a project where cryptographic presence implies deployment readiness.

</details>

---

<details>
<summary><strong>Security-sensitive topics</strong></summary>

<br>

Security-sensitive topics include:

* secret key or private key exposure;
* seed, token, credential, or secret material leakage;
* cryptographic correctness failures with security impact;
* authority bypasses;
* platform or provider bypasses;
* unauthorized hardware routing or SIMD dispatch;
* memory safety findings in protected paths;
* CI, evidence, or release manipulation;
* documentation claims that could mislead users about security or readiness.

Security-sensitive reports should follow the project security policy.

</details>

---

<details>
<summary><strong>Why claim boundaries matter</strong></summary>

<br>

XPScerpto separates partial progress from broad acceptance.

A subsystem may advance without implying that the full platform is production-ready. A test may pass without implying sanitizer cleanliness. A build may complete without implying full runtime validation. A UI may render a status without becoming the authority that grants that status.

This discipline prevents:

* stale evidence from becoming current truth;
* local success from becoming platform-wide acceptance;
* documentation from outrunning implementation;
* packaged logs from replacing live validation;
* partial subsystem progress from becoming a production claim.

</details>

---

## 🧾 Final Principle

<div align="center">

**XPScerpto advances only when implementation, authority, access, custody, evidence, documentation, and claims describe the same truth.**

</div>
