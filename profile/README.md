<p align="center">
  <img src="https://avatars.githubusercontent.com/u/298460041?v=4" alt="PoWV Protocol" width="128" />
</p>

<h1 align="center">PoWV Protocol</h1>

<p align="center">
  <strong>Evidence infrastructure for the physical world</strong><br />
  Cyber-physical systems · Operational trust · Industrial traceability · Real-world assets
</p>

<p align="center">
  <a href="https://powvprotocol.com/">Website</a> ·
  <a href="https://www.powvprotocol.org/">Institutional</a> ·
  <a href="https://powv-protocol.gitbook.io/powv-protocol-docs/overview">Documentation</a> ·
  <a href="https://powv-protocol.gitbook.io/powv-protocol-docs/product-proposals/">Product portfolio</a> ·
  <a href="https://www.linkedin.com/company/powv-protocol/">LinkedIn</a>
</p>

---

## At a glance

| Question | Current answer |
| --- | --- |
| **What is PoWV?** | An R&D protocol and proposed product portfolio for producing, evaluating and using evidence about physical events. |
| **What has been demonstrated?** | Selected software tests and a separate controlled laboratory path from a physical weighing instrument to an embedded receiver. |
| **What is proposed?** | A verification foundation, an operational-trust platform, secure capture hardware and a financial-operations security profile. |
| **What is not claimed?** | Production readiness, certification, verified physical truth, commercially available products or a live token-issuance, custody or settlement platform. |
| **Where is the evidence?** | [Dated Lab Status](https://github.com/powvprotocol-org/powv-lab-status) and [Product Maturity](https://powv-protocol.gitbook.io/powv-protocol-docs/product-proposals/maturity). |

**Core principle:** A digital signature can support attribution and integrity; it cannot, by itself, establish the correctness of the original physical measurement.

PoWV investigates the boundary where an observation becomes digital evidence, and where downstream systems must decide whether that evidence is sufficient for a particular action.

## Product architecture

These are **product proposals in research and development**, not generally available offerings. The Protocol Suite, EdgeGuard and Secure Capture Node have distinct roles and can interoperate through defined verification rules. Digital Treasury is a proposed EdgeGuard profile.

| Product | Intended role | Current positioning |
| --- | --- | --- |
| [**PoWV Protocol Suite**](https://powv-protocol.gitbook.io/powv-protocol-docs/product-proposals/protocol-suite) | Foundational evidence and verification architecture for physical-to-digital workflows. | Protocol research and software experimentation |
| [**PoWV EdgeGuard**](https://powv-protocol.gitbook.io/powv-protocol-docs/product-proposals/edgeguard) | Operational-trust and authorization platform: Edge Security Agent, Attestation Engine, Risk Quarantine Engine, Authorization Gateway, Verify Service and Audit Console. | Proposed platform architecture |
| [**PoWV Secure Capture Node**](https://powv-protocol.gitbook.io/powv-protocol-docs/product-proposals/secure-capture-node) | Proposed hardware for attributable acquisition of physical-event evidence. | Hardware concept; earlier laboratory integration is precursor work, not product validation |
| [**PoWV Digital Treasury**](https://powv-protocol.gitbook.io/powv-protocol-docs/product-proposals/edgeguard/digital-treasury) | EdgeGuard security and authorization profile for custody and financial-operation environments. | Proposed financial-security profile; not a custodian, token issuer or settlement operator |

[Explore the Product Portfolio](https://powv-protocol.gitbook.io/powv-protocol-docs/product-proposals/) · [Trust Boundaries](https://powv-protocol.gitbook.io/powv-protocol-docs/product-proposals/trust-boundaries) · [Maturity and Availability](https://powv-protocol.gitbook.io/powv-protocol-docs/product-proposals/maturity)

## From physical evidence to economic applications

The long-term PoWV thesis includes physical asset backing, traceability, institutional recognition of economic value, RWA tokenization and trade finance. Its architecture separates four responsibilities:

1. **Physical evidence:** acquire and evaluate attributable records of observations and measurements.
2. **Operational trust:** assess integrity and admissibility; apply separate authorization controls.
3. **Economic recognition:** let an accountable institution determine whether a legally and economically valid asset or right exists.
4. **Downstream finance:** enable other systems to use suitable evidence for tokenization, financing, custody or settlement.

Evidence about a physical asset does **not** establish title, enforceability, valuation or economic finality. PoWV does not currently operate a production tokenization or financial settlement system.

## Public engineering record

Each record supports only the scope tested at the time. Later experiments do not retrospectively validate earlier results.

| Date | Public record | Demonstrated scope and limitations |
| --- | --- | --- |
| **September 6, 2026** | [Software validation snapshot](https://powv-protocol.gitbook.io/powv-protocol-docs/project-status/validation-evidence) | 25 selected software test cases; no physical-hardware validation. |
| **September 18, 2026** | [Physical-to-edge experimental record](https://github.com/powvprotocol-org/powv-scale-edge-integration/blob/main/docs/integration-module/experimental-record.md) | Physical weighing acquisition, event representation, integrity identification and local transport with embedded acknowledgment; not independent hardware-backed attestation. |
| **November 20, 2026** | [Software engineering update](https://github.com/powvprotocol-org/powv-lab-status/blob/main/status/2026-11-software-engineering-update.md) | Experimental software hardening, conformance and provisional contract governance; 343 automated tests passed on Python 3.12 and 3.13, with no physical-hardware tests in that update and no approved release. |

The [Lab Status repository](https://github.com/powvprotocol-org/powv-lab-status) is the canonical public index of dated engineering status and production-readiness limitations.

## Public repositories

| Repository | Responsibility |
| --- | --- |
| [**powv-governance-and-docs**](https://github.com/powvprotocol-org/powv-governance-and-docs) | Canonical GitBook sources, disclosure boundaries and intellectual-property governance. |
| [**powv-lab-status**](https://github.com/powvprotocol-org/powv-lab-status) | Dated validation evidence, development status and explicit limitations. |
| [**powv-core**](https://github.com/powvprotocol-org/powv-core) | Protocol concepts, reference architecture and public research material. |
| [**powv-scale-edge-integration**](https://github.com/powvprotocol-org/powv-scale-edge-integration) | Historical laboratory record of physical measurement acquisition and edge transport. |
| [**powv-embedded-security**](https://github.com/powvprotocol-org/powv-embedded-security) | Public security-reporting guidance and scope of embedded-security research. |
| [**powvprotocol-org.github.io**](https://github.com/powvprotocol-org/powvprotocol-org.github.io) | Source for the public research and institutional web interface. |
| [**.github**](https://github.com/powvprotocol-org/.github) | Organization profile and documentation entry points. |

**Documentation ownership:** GitBook content is maintained in `powv-governance-and-docs`. Other repositories link to that source rather than maintaining competing normative copies. Public documentation explains capabilities and evidence limits; proprietary implementations and confidential records remain access-controlled.

## Founder and contact

**Gabriel de Almeida Santos Silva** · Founder & Protocol Architect

- **Official contact:** [gabriel@powvprotocol.com](mailto:gabriel@powvprotocol.com)
- **Support:** [powv.protocol@proton.me](mailto:powv.protocol@proton.me)
- [LinkedIn](https://www.linkedin.com/company/powv-protocol/) · [YouTube](https://www.youtube.com/@GabrielProtocolPowv) · [Substack](https://powvprotocol.substack.com/)

---

<p align="center"><sub>PoWV Protocol · Research and development · Evidence before economic interpretation</sub></p>
