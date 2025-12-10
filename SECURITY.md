# Security Policy

## Overview

The TetraKlein Unified Architecture is an early-stage, research-oriented framework
that integrates post-quantum cryptography, zero-knowledge verification, XR physics
models, digital-twin convergence mathematics, and hypercube-ledger synchronization.

Although this repository contains cryptographic and verification-related material,
**it is not a production security system** and **must not be used for real-world
security, financial, or safety-critical applications** without independent review.

Security research, responsible disclosure, and constructive analysis are welcomed.

---

## Supported Versions

Since this repository is in active research and pre-release development, only the
latest commit on the `main` branch is considered supported for security review.

| Version | Status |
|--------|--------|
| `main` | Accepting security reports |
| Tags   | Historical snapshots; not supported |

No backporting or patch maintenance is provided for older versions or tags.

---

## Reporting a Vulnerability

If you discover a vulnerability or suspect a security issue in:

- any cryptographic construction (PQC, RTH, hashing, AIR constraints),
- TK-VM execution rules or opcode semantics,
- XR–TSU or Digital Twin Convergence lineage mathematics,
- hypercube ledger logic or spectral-consistency rules,
- recursion, verification, or commitment structures,

**please report it privately using the contact below:**

**michael@baramaystationresearchinc.ca**

Please include:

1. **Detailed description** of the issue  
2. **Steps to reproduce / proof-of-concept**, if applicable  
3. **Scope and potential impact**, as best as can be estimated  
4. Whether you prefer **public acknowledgement** or **anonymous reporting**

You will receive an acknowledgment within **72 hours**.

---

## Responsible Disclosure Expectations

We ask that researchers:

- Provide **reasonable time** for analysis and mitigation before public disclosure  
- Avoid exploiting vulnerabilities beyond what is necessary for demonstration  
- Refrain from testing on systems, networks, or environments not owned by you  
- Avoid publishing exploit code that creates unnecessary real-world risk  

Baramay Station Research Inc. will:

- Treat all security reports as confidential until resolution  
- Communicate timelines and findings clearly  
- Credit researchers who wish to be acknowledged  
- Publish fixes, clarifications, or revisions as appropriate  
- Update the monograph or AIR/VM specifications if the issue affects correctness  

---

## Scope of Security Review

### In Scope

- PQC key handling (Kyber-1024, Dilithium-V, Module-LWE/SIS)  
- RTH (Recursive Tesseract Hashing) lineage structure and commitments  
- AIR constraint definitions (TK–U through TK–Z)  
- TK-VM opcode semantics and algebraic safety rules  
- XR–TSU physics constraints as they relate to mathematical correctness  
- DTC lineage equations and timestamp coherence  
- Hypercube ledger adjacency rules, spectral-ladder operators, and finality logic  
- IVC recursion, folding rules, and degree-propagation math  

### Out of Scope

The following are *not* considered part of the security perimeter:

- Third-party libraries or dependencies  
- Unreal Engine or external XR visualization layers  
- Hardware acceleration systems (GPUs, NPUs, TSU hardware, etc.)  
- Personal forks or downstream modifications  
- Incorrect or unsafe deployments of early-stage research code  

---

## Cryptographic Disclaimer

The cryptographic systems described in this repository—including PQC,
zero-knowledge systems, and RTH—are **experimental**. They require:

- formal security proofs,  
- peer review by cryptographic experts,  
- multi-institutional verification, and  
- extensive validation under adversarial models.

No component in this repository should yet be considered secure for:

- production identity systems,  
- financial transactions,  
- safety-critical XR/robotics,  
- medical or industrial control environments.

---

## Coordinated Disclosure Timeline

Baramay Station Research Inc. follows a modified coordinated disclosure approach:

1. **0–3 days:** Acknowledgement of report  
2. **3–14 days:** Analysis, reproduction, and classification  
3. **14–60 days:** Drafting of mitigation or specification updates  
4. **Publication:**  
   - Revised AIR, VM semantics, or monograph sections  
   - Release notes documenting the fix  
   - Research acknowledgement (optional)

For severe issues in cryptographic or verification components, the timeline may
be extended to **90 days** to coordinate with external reviewers.

---

## Thank You

We are deeply appreciative of researchers, mathematicians, engineers, and
cryptographers who contribute to the security and correctness of TetraKlein.

Your feedback directly strengthens the long-term integrity of the framework.
