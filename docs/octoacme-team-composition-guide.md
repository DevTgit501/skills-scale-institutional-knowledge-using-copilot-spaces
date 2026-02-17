# OctoAcme Team Composition Guide

## Overview
This guide helps project managers and team leads assemble effective cross-functional teams based on project scope and complexity. It provides recommended team compositions for different project types and guidelines for role allocation.

---

## Core vs. Extended Team Roles

### Core Team Roles (Always Required)
These roles are essential for every OctoAcme project:

- **Project Manager** - Coordinates delivery and manages timelines
- **Product Manager** - Defines what to build and success metrics
- **Developer(s)** - Implement features and solutions
- **QA/Quality Assurance Engineer** - Validates quality and acceptance criteria

### Extended Team Roles (Based on Project Scope)
These roles should be included based on project characteristics:

- **Technical Lead** - For projects with architectural complexity or technical debt concerns
- **Scrum Master/Agile Coach** - For distributed teams or organizations new to agile
- **DevOps/Release Engineer** - For projects with infrastructure, deployment, or reliability requirements
- **Customer Success Manager** - For customer-facing products or significant feature releases
- **Stakeholder/Executive Sponsor** - For strategic initiatives or high-visibility projects
- **Developers** (additional) - For complex projects requiring multiple specializations

---

## Team Composition by Project Type

### Small Feature Enhancement
**Scope:** Low-risk update to existing functionality; estimated < 2 weeks

**Recommended Team:**
- 1 Project Manager (shared across multiple projects)
- 1 Product Manager
- 1-2 Developers
- 1 QA Engineer (may be shared)

**Communication:** Weekly touchpoints; async updates acceptable

---

### Medium Feature Development
**Scope:** New feature with moderate complexity; estimated 2-6 weeks

**Recommended Team:**
- 1 Project Manager (dedicated)
- 1 Product Manager (dedicated)
- 2-3 Developers
- 1 QA Engineer (dedicated)
- 1 Technical Lead (if new technology or architectural decisions needed)
- 1 Scrum Master (if team is new to agile or distributed)

**Communication:** Twice-weekly standups; weekly planning and review

---

### Large/Complex Initiative
**Scope:** Major feature, platform, or cross-functional project; estimated 6+ weeks

**Recommended Team:**
- 1 Project Manager (dedicated, may have assistant)
- 1 Product Manager (dedicated)
- 3-5 Developers (including specialists as needed)
- 1-2 QA Engineers
- 1 Technical Lead (dedicated)
- 1 Scrum Master (dedicated)
- 1 DevOps/Release Engineer
- 1 Customer Success Manager (for customer-facing features)
- 1 Stakeholder/Executive Sponsor (oversight and decision authority)

**Communication:** Daily standups; thrice-weekly planning/review cycles; weekly stakeholder updates

---

### Infrastructure/Platform Project
**Scope:** DevOps, infrastructure, or deployment automation improvements

**Recommended Team:**
- 1 Project Manager
- 1 Technical Lead (for architectural guidance)
- 1-2 DevOps/Release Engineers
- 2-3 Backend Developers (for integration and automation)
- 1 QA Engineer (for testing infrastructure)
- 1 Scrum Master (for ceremony facilitation)

**Communication:** Twice-weekly standups; infrastructure impact assessment in planning

---

### Customer-Facing Release
**Scope:** External product release with customer communication requirements

**Recommended Team:**
- 1 Project Manager (dedicated)
- 1 Product Manager (dedicated)
- 2-4 Developers
- 1-2 QA Engineers
- 1 Technical Lead
- 1 DevOps/Release Engineer (for deployment safety)
- 1 Customer Success Manager (for onboarding and feedback)
- 1 Scrum Master
- 1 Stakeholder/Executive Sponsor (strategic oversight)

**Communication:** Daily standups; daily customer readiness assessment; post-release check-ins

---

## Role Allocation Principles

### Primary vs. Extended Responsibilities
Team members can take primary and extended roles:

- **Primary Role:** Main responsibility and accountability
- **Extended Role:** Secondary responsibilities shared across team

Example: A Senior Developer might have primary Developer responsibilities and extended Technical Lead responsibilities for architectural guidance.

### Shared Roles
Certain roles can be shared across multiple concurrent projects:

- **Project Manager** - Can manage 2-3 low-complexity projects concurrently
- **Product Manager** - Typically owns 1-2 product areas
- **QA Engineer** - Can support 2-3 concurrent projects with staggered timelines
- **Scrum Master** - Can serve 1-2 teams depending on team size

### Escalation and Decision Authority
Always clarify decision authority:

- **Product Decisions** - Product Manager (in consultation with stakeholders)
- **Technical Decisions** - Technical Lead (in consultation with developers)
- **Project/Schedule Decisions** - Project Manager (in consultation with team)
- **Business/Strategic Decisions** - Stakeholder/Executive Sponsor
- **Quality Gates** - QA Engineer (in consultation with developers)

---

## Team Composition Checklist

Before kickoff, verify your team has:

- [ ] **Product Definition** - Product Manager assigned and empowered
- [ ] **Delivery Leadership** - Project Manager assigned with clear ownership
- [ ] **Technical Direction** - Technical Lead or Senior Developer for architectural guidance
- [ ] **Quality Assurance** - QA Engineer with defined acceptance criteria authority
- [ ] **Development Capacity** - Sufficient developers with right skill sets
- [ ] **Operational Support** - DevOps/Release Engineer if infrastructure/deployment involved
- [ ] **Ceremony Facilitation** - Scrum Master or PM can facilitate agile ceremonies
- [ ] **Stakeholder Alignment** - Sponsor identified with decision-making authority
- [ ] **Customer Input** - Customer Success Manager if customer-facing work
- [ ] **Escalation Path** - Clear escalation procedures and decision authorities

---

## Scaling Team Composition

### Growing from Small to Medium Team
When a project grows from small to medium scope:

1. Add a dedicated Project Manager (move from shared to dedicated)
2. Add a second QA Engineer
3. Consider adding a Scrum Master for ceremony structure
4. Assign a Technical Lead if architectural decisions arise

### Growing from Medium to Large Team
When scaling to large scope:

1. Expand development team incrementally (avoid communication overhead)
2. Add specialized roles (DevOps, Customer Success, etc.)
3. Establish clear sub-team ownership with technical leads per area
4. Add project management support (assistant PM or coordinator)
5. Introduce Scrum of Scrums for multi-team coordination

---

## Avoiding Common Team Composition Problems

| Problem | Signs | Solution |
|---------|-------|----------|
| **No Clear PM** | Unclear priorities, missed deadlines | Assign dedicated PM with clear authority |
| **Too Many Managers** | Conflicting directions, slow decisions | Single PM leads; Product Lead has final say |
| **Missing Technical Lead** | Poor architecture decisions, technical debt | Assign experienced Senior Dev as Technical Lead |
| **Understaffed QA** | Bugs in production, slow progress | Add QA headcount or hire testing specialists |
| **No Release/DevOps Experience** | Deployment failures, operational issues | Include DevOps Engineer for infrastructure projects |
| **Lack of Customer Voice** | Features don't meet user needs | Include Customer Success Manager or user representative |
| **Distributed Team Struggles** | Async communication issues, misalignment | Add Scrum Master for ceremony structure |

---

## Team Communication Across Roles

Ensure clear communication paths for each role:

| Role Pair | Key Interactions | Communication Cadence |
|-----------|------------------|----------------------|
| PM + Developers | Task assignment, progress, blockers | Daily standup, as-needed |
| Product Manager + Developers | Requirements, acceptance criteria | Sprint planning, design reviews |
| Product Manager + Stakeholder | Roadmap, priorities, business impact | Weekly or bi-weekly |
| Technical Lead + Developers | Architecture, design guidance, code review | Continuous, design docs for big changes |
| DevOps + Developers | Deployment, observability, monitoring | On-demand, release readiness meetings |
| QA Engineer + Developers | Test plans, defects, acceptance criteria | Daily, sprint planning |
| Scrum Master + Team | Ceremony facilitation, blocker removal | Daily standups, retrospectives |

---

## Onboarding New Team Roles

When adding a new role or persona to a team:

1. **Define Role Scope** - Clarify primary and extended responsibilities
2. **Establish Authority** - Make decision authority explicit
3. **Map Interactions** - Show how the role connects with existing team members
4. **Set Expectations** - Communicate team needs and success criteria
5. **Introduce Gradually** - Bring in new role with mentorship from similar role or PM
6. **Adjust as Needed** - Retrospect after first sprint and refine role fit
