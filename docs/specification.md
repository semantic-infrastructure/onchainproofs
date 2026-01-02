# Technical Specification: Onchain Proofs
**Version:** 1.0.0 (Agentic Era Standard)  
**Status:** Draft for Semantic Infrastructure

## 1. Overview
This document defines the transition logic for migrating off-chain evidence into immutable on-chain attestations.

## 2. Evidence-to-State Pipeline
1. **Source Validation:** Verification of the 'Authority Anchor' providing the raw data.
2. **Cryptographic Commitment:** Hashing the evidence to ensure data integrity.
3. **Attestation Issuance:** Creating the on-chain proof via Ethereum Attestation Service (EAS) or similar protocols.

## 3. Core Modules
* `/verification`: Logic for checking digital signatures.
* `/schemas`: Defining the structure of the proof payload.
