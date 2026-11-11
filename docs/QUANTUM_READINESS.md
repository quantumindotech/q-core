# Quantum-Readiness and Cryptographic Agility

## Current claim boundary

PQC and quantum readiness are design and research objectives. Q-CORE makes no claim that this repository, any wallet, token, ledger, network, or deployed system is quantum-proof, quantum-secure, or resistant to a cryptographically relevant quantum computer.

## Required engineering work

A defensible readiness claim requires, at minimum:

1. a documented threat model and migration assumptions;
2. selected algorithms grounded in recognized standards and current cryptographic analysis;
3. implementation details, key management, and protocol integration;
4. interoperability and negative testing;
5. performance and resource measurements on target hardware;
6. independent cryptographic review;
7. reproducible evidence, versioning, and a migration plan.

## Crypto agility

Architectures should avoid hard-coding a single cryptographic primitive where practical. Algorithm identifiers, key formats, signature verification, certificate handling, and migration procedures should be designed for controlled replacement.

Crypto agility does not itself establish post-quantum security.
