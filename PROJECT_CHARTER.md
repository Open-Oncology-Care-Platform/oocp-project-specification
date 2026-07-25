# Project Charter

**Project Name:** Open Oncology Care Platform (OOCP)

**Project Code:** OOCP-001

**Version:** 1.0.0

**Status:** Active

**Repository:** oocp-project-specification

**Project Type:** Open Source Digital Health Platform

**Author:** Stephen Maina Macharia

**License:** Apache License 2.0

**Document Classification:** Public

**Last Updated:** 25 July 2026

---

# Table of Contents

1. Executive Summary
2. Background
3. Problem Statement
4. Vision
5. Mission
6. Project Objectives
7. Scope
8. Out of Scope
9. Stakeholders
10. Success Criteria
11. Guiding Principles
12. Technical Strategy
13. Expected Deliverables
14. Risks
15. Assumptions
16. Constraints
17. Governance
18. Milestones
19. Long-Term Vision

---

# 1. Executive Summary

The Open Oncology Care Platform (OOCP) is an open-source digital health platform designed to support the complete continuum of oncology care through standards-based interoperability.

The project integrates multiple mature open-source technologies—including OpenSRP, OpenEMR, HAPI FHIR, SMART on FHIR, HL7 FHIR R4, Keycloak, Docker, and modern DevOps practices—to create a modular, scalable, secure, and interoperable oncology ecosystem.

Rather than building another electronic medical record system, OOCP focuses on integrating existing best-of-breed technologies into a unified platform capable of supporting community health, clinical oncology services, laboratory workflows, referrals, follow-up care, analytics, and research.

---

# 2. Background

Cancer continues to place a significant burden on healthcare systems, particularly in low- and middle-income countries where fragmented information systems limit continuity of care.

Healthcare providers frequently use disconnected applications that cannot exchange clinical information effectively.

The emergence of HL7 FHIR, SMART on FHIR, and modern open-source healthcare platforms presents an opportunity to build interoperable digital ecosystems capable of supporting patient-centred oncology care.

OOCP seeks to demonstrate how open standards and open-source technologies can be combined to build such a platform.

---

# 3. Problem Statement

Current healthcare information systems often suffer from:

- Fragmented patient records
- Poor interoperability
- Duplicate data collection
- Limited integration between community and hospital care
- Lack of standards-based APIs
- Limited support for oncology-specific workflows
- Difficult deployments
- Vendor lock-in

These limitations reduce care coordination and impede evidence-based clinical decision making.

---

# 4. Vision

To build a world-class open-source oncology platform that demonstrates how interoperable healthcare systems can deliver coordinated, patient-centred cancer care using international standards and modern software engineering practices.

---

# 5. Mission

To design, implement, document, and openly share a production-quality oncology platform built upon internationally recognised healthcare interoperability standards.

---

# 6. Project Objectives

The project aims to:

- Build an interoperable oncology platform.
- Demonstrate practical HL7 FHIR R4 implementation.
- Implement SMART on FHIR applications.
- Integrate OpenSRP and OpenEMR.
- Develop oncology-specific clinical workflows.
- Publish an oncology FHIR Implementation Guide.
- Implement secure authentication using OAuth2 and OpenID Connect.
- Demonstrate Docker-based deployment.
- Apply Clean Architecture and SOLID principles.
- Produce comprehensive engineering documentation.
- Create an educational reference implementation for healthcare interoperability.

---

# 7. Scope

The project includes:

## Community Health

- OpenSRP
- Community registration
- Screening
- Referrals
- Follow-up

## Clinical Care

- OpenEMR
- Oncology consultations
- Treatment records
- Laboratory integration

## Interoperability

- HL7 FHIR R4
- SMART on FHIR
- REST APIs
- Terminology services

## Security

- Keycloak
- OAuth2
- OpenID Connect
- Role-based access control

## Infrastructure

- Docker
- Docker Compose
- CI/CD
- GitHub Actions

## Documentation

- Engineering specifications
- Architecture documentation
- Deployment guides
- API documentation

---

# 8. Out of Scope

The project does not currently include:

- Commercial deployment
- Billing systems
- Insurance processing
- National health information exchange implementation
- Medical device integration
- PACS deployment
- AI-assisted diagnosis
- Production cloud hosting

These may be considered in future releases.

---

# 9. Stakeholders

Primary stakeholders include:

- Software engineers
- Healthcare interoperability engineers
- Oncology clinicians
- Community health programmes
- Researchers
- Students
- Open-source contributors
- Health informatics professionals

---

# 10. Success Criteria

The project will be considered successful if it:

- Demonstrates end-to-end oncology workflows.
- Successfully integrates OpenSRP and OpenEMR.
- Implements HL7 FHIR R4 consistently.
- Supports SMART on FHIR applications.
- Publishes a complete oncology Implementation Guide.
- Is fully deployable using Docker.
- Includes comprehensive engineering documentation.
- Can be reproduced by independent developers.

---

# 11. Guiding Principles

The project will be guided by the following principles:

## Engineering Excellence

- Clean Code
- SOLID Principles
- Clean Architecture
- Test-Driven Development
- Domain-Driven Design where appropriate
- Continuous Refactoring

## Healthcare Standards

- HL7 FHIR R4
- SMART on FHIR
- OAuth2
- OpenID Connect
- RESTful APIs

## Open Source

- Transparency
- Community collaboration
- Reproducibility
- Standards compliance

---

# 12. Technical Strategy

OOCP adopts a modular architecture.

Core components include:

- OpenSRP
- OpenEMR
- HAPI FHIR
- SMART Applications
- Keycloak
- PostgreSQL
- Docker
- GitHub
- CI/CD pipelines

Each component remains independently deployable while participating in a larger interoperable ecosystem.

---

# 13. Expected Deliverables

The project will produce:

- Complete GitHub organisation
- Engineering documentation
- Architecture diagrams
- Docker deployments
- SMART applications
- Oncology workflows
- FHIR profiles
- Implementation Guide
- API documentation
- Technical blog series

---

# 14. Risks

Potential risks include:

- Technology changes
- Learning curve
- Integration complexity
- Security vulnerabilities
- Resource limitations
- Documentation drift

Mitigation strategies will be documented throughout the project.

---

# 15. Assumptions

The project assumes:

- Continued availability of open-source components
- Stable HL7 FHIR R4 ecosystem
- Docker support
- Community collaboration
- Long-term maintainability

---

# 16. Constraints

Project constraints include:

- Approximately two hours of development per day
- Single primary developer
- Local-first development environment
- Open-source technology stack
- Public documentation

---

# 17. Governance

Project governance follows the policies defined in the OOCP Governance repository.

Development standards include:

- Mandatory code reviews
- Architecture Decision Records (ADRs)
- Coding standards
- Security reviews
- Documentation-first development

---

# 18. Milestones

Phase 1
Foundation

Phase 2
Infrastructure

Phase 3
Community Health

Phase 4
Clinical Care

Phase 5
Interoperability

Phase 6
Oncology Workflows

Phase 7
Security

Phase 8
Deployment

Phase 9
Public Demonstration

---

# 19. Long-Term Vision

OOCP aims to become a comprehensive educational and reference implementation demonstrating how open-source healthcare technologies can be integrated into a standards-based oncology platform.

Beyond software, the project seeks to provide reusable engineering knowledge, architecture documentation, deployment guidance, interoperability examples, and implementation best practices that can support healthcare organisations, researchers, and developers building the next generation of interoperable digital health systems.

---

# Approval

| Role | Name | Status |
|------|------|--------|
| Project Sponsor | Stephen Maina Macharia | Approved |
| Lead Architect | Stephen Maina Macharia | Approved |
| Lead Developer | Stephen Maina Macharia | Approved |

---

**End of Project Charter**
