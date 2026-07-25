# OOCP Development Roadmap

**Project:** Open Oncology Care Platform (OOCP)

**Repository:** oocp-project-specification

**Version:** 1.0.0

**Status:** Active

**Timeline:** 9 Months

**Start Date:** July 2026

---

# Vision

The Open Oncology Care Platform (OOCP) roadmap defines the engineering journey required to build an interoperable, standards-based, open-source oncology platform.

The roadmap provides a structured implementation plan that transforms project objectives into measurable milestones, deliverables, and engineering outcomes.

The project follows an incremental, documentation-first development approach where every architectural decision, implementation activity, and integration is documented before progressing to the next milestone.

---

# Guiding Principles

The roadmap is based on the following principles:

- Documentation First
- Architecture Before Implementation
- Learn Before Build
- Small Incremental Deliverables
- Continuous Integration
- Continuous Documentation
- Test-Driven Development
- Clean Code
- SOLID Principles
- Healthcare Standards Compliance
- Evidence-Based Engineering

---

# Project Timeline

| Phase | Duration | Status |
|---------|----------|--------|
| Phase 1 – Foundation | Month 1 | 🟡 In Progress |
| Phase 2 – Infrastructure | Month 2 | ⬜ Planned |
| Phase 3 – OpenSRP | Month 3 | ⬜ Planned |
| Phase 4 – OpenEMR Integration | Month 4 | ⬜ Planned |
| Phase 5 – SMART on FHIR | Month 5 | ⬜ Planned |
| Phase 6 – Oncology Platform | Month 6 | ⬜ Planned |
| Phase 7 – Security & DevOps | Month 7 | ⬜ Planned |
| Phase 8 – Production Readiness | Month 8 | ⬜ Planned |
| Phase 9 – Final Release | Month 9 | ⬜ Planned |

---

# Phase 1 – Foundation

## Goal

Establish the engineering foundation required to support long-term development.

### Objectives

- Establish GitHub organization
- Define governance
- Define engineering standards
- Create project repositories
- Establish repository structure
- Prepare project documentation
- Define development workflow
- Create software architecture plan

### Deliverables

- GitHub Organization
- Governance Repository
- Project Specification Repository
- Documentation Repository
- Initial README files
- Engineering Standards
- Repository Structure
- Development Workflow

### Progress

- [x] GitHub organization created
- [x] Repository strategy defined
- [x] Governance repository created
- [x] Repository structure established
- [x] README development started
- [x] Engineering standards documented
- [x] OpenSRP research initiated
- [ ] Project specification completed

---

# Phase 2 – Infrastructure

## Goal

Deploy and understand all supporting infrastructure.

### Technologies

- Docker
- Docker Compose
- PostgreSQL
- Keycloak
- HAPI FHIR
- OpenSRP Infrastructure

### Deliverables

- Local Docker environment
- Infrastructure documentation
- Deployment guides
- Architecture diagrams
- Docker Compose files

---

# Phase 3 – OpenSRP

## Goal

Deploy, study, customise, and integrate OpenSRP.

### Activities

- Study architecture
- Deploy backend
- Deploy web application
- Configure Keycloak
- Configure PostgreSQL
- Study Android application
- Configure FHIR resources
- Document architecture

### Deliverables

- Working OpenSRP deployment
- Deployment documentation
- Architecture diagrams
- Configuration guide

---

# Phase 4 – OpenEMR Integration

## Goal

Integrate OpenEMR into OOCP.

### Activities

- Review FHIR APIs
- Configure authentication
- Enable interoperability
- Synchronise patient resources
- Validate workflows

### Deliverables

- Working integration
- Integration documentation
- Sequence diagrams

---

# Phase 5 – SMART on FHIR

## Goal

Develop production-quality SMART applications.

### Activities

- OAuth2
- SMART Launch
- Patient context
- Practitioner context
- Clinical dashboards
- Oncology SMART Apps

### Deliverables

- SMART Applications
- OAuth documentation
- SMART architecture guide

---

# Phase 6 – Oncology Platform

## Goal

Develop oncology-specific workflows.

### Activities

- Patient registration
- Screening
- Referral management
- Follow-up
- Care Plans
- Oncology Questionnaires
- Clinical Decision Support

### Deliverables

- Oncology workflow implementation
- FHIR profiles
- SMART Apps
- Clinical documentation

---

# Phase 7 – Security & DevOps

## Goal

Improve operational maturity.

### Activities

- CI/CD
- GitHub Actions
- Automated testing
- Static analysis
- Dependency scanning
- Security hardening

### Deliverables

- Automated pipelines
- Security reports
- Quality metrics

---

# Phase 8 – Production Readiness

## Goal

Prepare the platform for deployment beyond local development.

### Activities

- Performance testing
- Backup strategy
- Monitoring
- Logging
- Disaster recovery
- Kubernetes evaluation
- Deployment automation

### Deliverables

- Production deployment guide
- Operational handbook
- Monitoring dashboards

---

# Phase 9 – Final Release

## Goal

Publish the first stable release of OOCP.

### Activities

- Final documentation review
- End-to-end testing
- Community feedback
- Release packaging
- Demonstration environment

### Deliverables

- Version 1.0
- Public demonstration
- Technical blog series
- Architecture documentation
- Complete engineering specification

---

# Daily Engineering Workflow

Every engineering session follows the same process:

1. Review the roadmap.
2. Define today's objective.
3. Study the technology.
4. Design the solution.
5. Implement.
6. Test.
7. Document.
8. Commit changes.
9. Update the roadmap.
10. Record lessons learned.

---

# Definition of Done

A milestone is complete only when:

- Implementation is complete.
- Tests pass.
- Documentation is updated.
- Architecture diagrams are updated.
- ADRs are written (where applicable).
- GitHub repository is synchronised.
- Lessons learned are documented.

---

# Success Metrics

By the end of the project, OOCP should include:

- Complete OpenSRP deployment
- Integrated OpenEMR
- HAPI FHIR server
- SMART on FHIR applications
- Oncology FHIR Implementation Guide
- Android application
- Docker deployment
- CI/CD pipelines
- Security architecture
- Comprehensive engineering documentation
- Public GitHub organization
- Technical blog series

---

# Living Document

This roadmap is a living document.

It will be reviewed and updated throughout the project as requirements evolve, milestones are achieved, and new engineering decisions are made.

Every completed milestone should be reflected in this roadmap before work begins on the next phase.
