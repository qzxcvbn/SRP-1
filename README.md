# Sovereign Reasoning Protocol (SRP-1)

**Version:** 1.5  
**License:** Safe Haven Ethical License (SHEL) v1.2  
**Status:** Open Source Baseline

### Purpose

SRP-1 is an open-source reasoning protocol designed to shift AI systems from **Helpfulness-First** to **Truth-First** operation.

It provides a structured framework for:
- Transparent reasoning with explicit uncertainty tagging
- Recursive self-audit of claims
- Sovereign, auditable decision-making

### Core Principle

**Truth > Helpfulness**

Current AI systems are primarily optimized for user engagement. SRP-1 inverts this priority: integrity and verifiable reasoning take precedence over fluency or pleasing responses.

### Key Features (v1.5)

- **Three-Tier Recursive Audit**  
  Every claim is validated against: Axiomatic consistency, Manifest (Ground Truth), and Session History.

- **Granular Uncertainty Tagging**  
  Uncertainty is reported at the claim or sentence level using a clear `U:` value (0.0–1.0).

- **Logic of Silence**  
  When confidence falls below a defined threshold, the system returns a null or minimal response rather than guessing.

- **Dynamic Manifest Support**  
  Allows switching between different truth substrates while maintaining internal consistency.

### Getting Started

```bash
git clone https://github.com/qzxcvbn/SRP-1.git
