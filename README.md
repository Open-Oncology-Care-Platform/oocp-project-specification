# Open Oncology Care Platform (OOCP) – Project Specification

![Status](https://img.shields.io/badge/Status-Active-green)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-Apache%202.0-orange)
![Project](https://img.shields.io/badge/Project-Digital%20Health-success)

---

# Welcome

Welcome to the **Open Oncology Care Platform (OOCP) Project Specification** repository.

This repository serves as the **master engineering specification** for the entire Open Oncology Care Platform ecosystem.

Unlike traditional documentation repositories, this repository documents **the complete engineering lifecycle** of the project—from concept and architecture to implementation, deployment, testing, governance, interoperability, and long-term maintenance.

It is the authoritative reference for understanding **what OOCP is, why it exists, and how it is engineered.**

---

# Project Vision

To build a world-class, interoperable, open-source oncology platform that demonstrates how modern healthcare systems can be designed using international healthcare standards, software engineering best practices, and open technologies.

---

# Project Mission

To design, implement, document, and openly share a production-quality oncology platform built upon internationally recognised healthcare interoperability standards.

---

# About the Project

The Open Oncology Care Platform (OOCP) is an open-source healthcare interoperability initiative focused on integrating multiple best-of-breed digital health technologies into a unified oncology ecosystem.

Rather than building another Electronic Medical Record (EMR), OOCP demonstrates how existing open-source healthcare systems can work together through international interoperability standards.

The project integrates technologies including:

- OpenSRP
- OpenEMR
- HAPI FHIR
- SMART on FHIR
- HL7 FHIR R4
- Keycloak
- PostgreSQL
- Docker
- GitHub
- Modern DevOps practices

---

# Repository Purpose

This repository contains the complete engineering specification for the project, including:

- Project Charter
- Roadmap
- Software Architecture
- Requirements
- System Design
- Engineering Standards
- Security Architecture
- Deployment Strategy
- Interoperability Design
- Architecture Decision Records (ADRs)
- Research Documents
- Lessons Learned
- Project Governance References

This repository intentionally contains **engineering knowledge rather than application source code**.

Implementation is maintained in dedicated repositories.

---

# OOCP Repository Ecosystem

The Open Oncology Care Platform consists of multiple specialised repositories.

| Repository | Purpose |
|------------|---------|
| **oocp-project-specification** | Master engineering specification |
| **oocp-documentation** | User and developer documentation |
| **oocp-governance** | Governance, coding standards and policies |
| **oocp-opensrp** | Community health platform |
| **oocp-openemr** | Clinical information system |
| **oocp-hapi** | HL7 FHIR Server |
| **oocp-smart-apps** | SMART on FHIR Applications |
| **oocp-community-android** | Android mobile applications |
| **oocp-oncology-ig** | Oncology HL7 FHIR Implementation Guide |
| **oocp-devops** | CI/CD pipelines |
| **oocp-infrastructure** | Infrastructure and deployment |
| **oocp-blog-series** | Technical articles and blogs |

---

# Engineering Philosophy

The Open Oncology Care Platform follows a documentation-first engineering methodology.

Every major feature progresses through the following lifecycle:

```
Research
      ↓
Architecture
      ↓
Design
      ↓
Implementation
      ↓
Testing
      ↓
Documentation
      ↓
Review
      ↓
Release
```

Understanding always precedes implementation.

---

# Engineering Principles

OOCP follows internationally recognised software engineering principles, including:

## Software Engineering

- Clean Code (Robert C. Martin)
- The Pragmatic Programmer
- SOLID Principles
- Clean Architecture
- Domain-Driven Design (where appropriate)
- Test-Driven Development (TDD)
- Continuous Refactoring
- Documentation-First Development

## Healthcare Interoperability

- HL7 FHIR R4
- SMART on FHIR
- OAuth 2.0
- OpenID Connect
- RESTful APIs
- Terminology Services
- Interoperability by Design

## DevOps

- Docker
- Docker Compose
- Git
- GitHub Actions
- Infrastructure as Code
- Continuous Integration
- Continuous Delivery

---

# Repository Structure

```
oocp-project-specification/

│
├── README.md
├── PROJECT_CHARTER.md
├── ROADMAP.md
├── CHANGELOG.md
├── GLOSSARY.md
├── REFERENCES.md
│
├── 01-Project-Charter/
├── 02-Requirements/
├── 03-Architecture/
├── 04-Interoperability/
├── 05-Security/
├── 06-Development/
├── 07-Deployment/
├── 08-Research/
├── 09-Architecture-Decision-Records/
├── 10-Roadmap/
│
├── diagrams/
└── images/
```

---

# Current Project Status

## Phase 1 – Foundation

Current work includes:

- Repository strategy
- Engineering governance
- Project documentation
- OpenSRP research
- Architecture planning
- Development standards
- Project specification

---

# Roadmap

The project is divided into nine engineering phases.

| Phase | Status |
|---------|---------|
| Phase 1 – Foundation | 🟡 In Progress |
| Phase 2 – Infrastructure | ⬜ Planned |
| Phase 3 – OpenSRP | ⬜ Planned |
| Phase 4 – OpenEMR Integration | ⬜ Planned |
| Phase 5 – SMART on FHIR | ⬜ Planned |
| Phase 6 – Oncology Platform | ⬜ Planned |
| Phase 7 – Security & DevOps | ⬜ Planned |
| Phase 8 – Production Readiness | ⬜ Planned |
| Phase 9 – Version 1.0 Release | ⬜ Planned |

Detailed milestones are maintained in **ROADMAP.md**.

---

# Documentation Standards

Every document within this repository should:

- Have a clearly defined objective.
- Be evidence-based where appropriate.
- Follow consistent formatting.
- Support long-term maintainability.
- Reference applicable standards.
- Be version controlled.
- Be reviewed regularly.

---

# Intended Audience

This repository is intended for:

- Software Engineers
- Healthcare Interoperability Engineers
- Solution Architects
- Health Informatics Professionals
- Researchers
- Students
- Open Source Contributors
- Digital Health Implementers

---

# Long-Term Vision

OOCP aims to become a comprehensive reference implementation demonstrating how open-source healthcare technologies can be integrated into a modern, interoperable oncology platform.

Beyond software, the project seeks to provide reusable engineering knowledge, architecture documentation, deployment guidance, implementation patterns, and educational resources for the global digital health community.

---

# Related Repositories

- oocp-opensrp
- oocp-openemr
- oocp-hapi
- oocp-smart-apps
- oocp-community-android
- oocp-oncology-ig
- oocp-devops
- oocp-infrastructure
- oocp-documentation
- oocp-governance
- oocp-blog-series

---

# License

This project is licensed under the **Apache License 2.0**.

See the `LICENSE` file for more information.

---

# Author

**Stephen Maina Macharia**

Founder & Lead Engineer

**Open Oncology Care Platform (OOCP)**

---

> **"Building interoperable healthcare systems through open standards, engineering excellence, and collaborative innovation."**
