# Vault Leadership Path  
### SecureTheCloud Academy — Secrets, Identity & Encryption

**Version:** 2025  
**Author:** SecureTheCloud (Ola)

---

## Overview

This repository represents the **Security and Secrets domain** of the SecureTheCloud Academy.

It focuses on **HashiCorp Vault** as the central system for:

- Secrets management
- Encryption services
- Identity-based access
- Token lifecycle management
- Zero-trust security workflows

Infrastructure provisioning is **assumed** to be handled externally via Terraform.

👉 Infrastructure reference repository:  
https://github.com/S3curethecloud/terraform-leadership-path

---

## Architectural Philosophy

> Terraform creates infrastructure.  
> Vault secures infrastructure.

Vault is treated as:

- The system of record for secrets
- The authority for encryption and signing
- The enforcement point for identity and policy
- A security boundary, not a convenience tool

Terraform is used **inside Vault workflows**, not the other way around.

---

## Repository Structure
volume-1-vault-foundations/ → Core Vault concepts
volume-2-vault-associate-exam/ → Certification alignment
volume-3-enterprise-vault-design/ → HA, seal, replication
volume-4-terraform-vault-integration/
anki/

text

---

## Terraform’s Role in This Repository

Terraform is used to:

- Configure Vault auth methods
- Manage Vault policies
- Enable secrets engines
- Automate Vault configuration safely

Terraform is **not taught here from scratch**.

Foundational Terraform knowledge is assumed and sourced from:

👉 https://github.com/S3curethecloud/terraform-leadership-path

---

## Who This Repository Is For

- Security engineers
- Platform engineers
- Cloud architects
- DevSecOps professionals
- Anyone pursuing Vault Associate certification

---

## Outcome

Completing this repository prepares you to:

- Operate Vault securely
- Design secret lifecycles
- Implement encryption-as-a-service
- Integrate Vault into Terraform-driven environments

---
---

# SecureTheCloud Academy Standard (STC-AS) — v1.0

This repository complies with SecureTheCloud Academy Standard (STC-AS) v1.0.

STC-AS enforces:
- ✅ Clear separation of concerns
- ✅ Architect-first design
- ✅ Lab-driven learning
- ✅ Certification-aligned structure
- ✅ Enterprise realism
- ✅ Security-by-design principles

This repository is part of a multi-repository SecureTheCloud Academy ecosystem.

Changes to structure must preserve STC-AS compliance.
