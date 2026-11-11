# Q-CORE
## Master Core Architectural Controller

Q-CORE is the master architecture and integration layer for the **QSDG / QS / Quantum Indotech ecosystem**.

It defines system boundaries, shared architectural principles, interfaces, governance constraints, and evidence requirements across multiple independent projects. Q-CORE is not a token, coin, wallet, blockchain, exchange, or a substitute for the consensus and authorization mechanisms of the systems it coordinates.

## Mission

Build coherent, auditable, interoperable sovereign digital infrastructure—without collapsing distinct projects into one product or making unsupported security, ownership, or maturity claims.

## Architectural boundaries

- **Q-CORE** — architecture, integration rules, standards, change control, and cross-project coordination.
- **UQY** — proposed network and ledger layer; consensus and execution remain governed by UQY's own protocol.
- **UNY** — wallet and user-access layer; authorization, custody, and recovery rules remain enforced by the wallet system.
- **UTY** — proposed native utility coin for network gas and settlement. A native coin is not an ERC-20-style token.
- **QMC** — separate master-coin and Layer #0 network research line; not QTM.
- **Trisula** — a distinct tokenization project family comprising QSDT, QSDC, QSDG, and QTM. QTM is its master token, not Q-CORE's controller and not a master coin.

These descriptions record architectural intent. They do not imply that every component is implemented, deployed, audited, or production-ready.

## Ecosystem projects

The following repositories are related projects with their own scope and lifecycle. Their inclusion does not imply that Q-CORE owns, controls, endorses, or has audited them.

| Project | Repository |
|---|---|
| Quantum Registry (Q-Reg) | [quantumindotech/Quantum-Registry](https://github.com/quantumindotech/Quantum-Registry) |
| Quantum Forge | [quantumindotech/Quantum](https://github.com/quantumindotech/Quantum) |
| Quantum Tokenization | [quantumindotech/QuantumTokenization](https://github.com/quantumindotech/QuantumTokenization) |
| Metaportation | [Sovereign-Titan-Genesis/METAPORTATION](https://github.com/Sovereign-Titan-Genesis/METAPORTATION) |
| Quorum State | [Sovereign-Titan-Genesis/Quorum-State](https://github.com/Sovereign-Titan-Genesis/Quorum-State) |
| STG Chain | [Sovereign-Titan-Genesis/STG-Chain](https://github.com/Sovereign-Titan-Genesis/STG-Chain) |

Additional integrations, including any trade engine or bridge, will be listed only after their canonical repositories and interfaces are verified.

## Non-negotiable constraints

1. Q-CORE must not bypass UQY consensus, UNY authorization, treasury quorum, time-locks, or recovery controls.
2. Cross-project changes require an Architecture Decision Record (ADR), a test plan, an evidence record, and the applicable governance quorum.
3. No security claim without implementation evidence, reproducible tests, and appropriate independent review.
4. Unknown code provenance is a release blocker for redistribution or relicensing.
5. Each project retains its own identity, ownership record, threat model, and release authority.

## Quantum-readiness statement

Post-quantum cryptography (PQC) and quantum readiness are design and research objectives. **This repository does not claim demonstrated quantum resistance or quantum security.** Such claims require specified algorithms, implementation, interoperability testing, cryptographic review, and documented evidence.

## Development status

Q-CORE is in its foundation and architecture-definition phase. The repository currently documents scope and governance foundations; implementation status must be established through committed code, tests, and evidence—not by roadmap language.

## Repository map

- [Contributing](CONTRIBUTING.md)
- [Security policy](SECURITY.md)
- [Code provenance register](docs/CODE_PROVENANCE.md)
- [Intellectual property and licensing policy](docs/IP_POLICY.md)
- [Quantum-readiness policy](docs/QUANTUM_READINESS.md)
- [Ecosystem map](docs/ECOSYSTEM_MAP.md)

## Working principle

**Proof by Work:** architecture, implementation, tests, evidence, review, and accountable operation. This phrase describes a work-and-evidence principle; it is not a claim that Q-CORE uses Proof-of-Work consensus.

---
