# OctoAcme Cross-Functional Collaboration Guide

## Purpose
Provide clear guidance on how different roles collaborate within OctoAcme projects, communication patterns, and decision-making responsibilities.

## Overview
Cross-functional collaboration is essential for successful project delivery. This guide clarifies:
- Which roles work together on specific activities
- Who owns what decisions
- Communication frequencies and formats
- Escalation paths and approval workflows

---

## Project Lifecycle Collaboration

### Initiation Phase
**Primary Roles**: Stakeholder/Sponsor, Product Manager, Project Manager

**Key Activities**:
- Define business case and success metrics (Sponsor + PdM)
- Identify team composition and resource needs (PM)
- Establish stakeholder communication plan (PM + Sponsor)
- Create project charter (PM + PdM)

**Communication**:
- Kickoff meeting with all stakeholders
- Decision log maintained by PM

---

### Planning Phase
**Primary Roles**: Product Manager, Project Manager, Tech Lead, Developers, QA/Testing Specialist, Scrum Master

**Key Activities**:
- Break down work into stories and tasks (PdM + Dev + Tech Lead)
- Estimate scope and effort (Developers with Tech Lead guidance)
- Define acceptance criteria (PdM + QA)
- Identify technical risks and dependencies (Tech Lead + Developers)
- Create release plan and milestones (PM + Tech Lead + PdM)

**Communication**:
- Planning ceremonies (sprint planning, backlog refinement)
- Design reviews for significant technical decisions
- Daily standup facilitated by Scrum Master

---

### Execution Phase
**Primary Roles**: Developers, QA/Testing Specialist, Tech Lead, Project Manager, Scrum Master

**Key Activities**:
- Implement features (Developers with Tech Lead guidance)
- Write and review code (Developers + Tech Lead)
- Test and validate (QA with Developers)
- Track progress and manage risks (PM + Scrum Master)
- Remove impediments (Scrum Master)

**Communication**:
- Daily standups (15 min)
- Code reviews on PR descriptions
- Defect reports and test status updates
- Risk escalation as needed

---

### Release Phase
**Primary Roles**: Project Manager, Tech Lead, Developers, QA/Testing Specialist, Support/Operations, Stakeholder/Sponsor

**Key Activities**:
- Validate release readiness (QA + PM)
- Prepare release notes (PdM + Tech Lead)
- Coordinate deployment (PM + Support/Ops)
- Execute smoke tests (QA + Support/Ops + Developers)
- Announce release (PM + Stakeholder)

**Communication**:
- Release readiness checklist
- Pre-deployment and post-deployment coordination
- Incident escalation procedures

---

### Retrospective Phase
**Primary Roles**: Scrum Master, All Team Members, Project Manager

**Key Activities**:
- Facilitate retrospective (Scrum Master)
- Identify action items (Team)
- Track improvements (PM)
- Share learnings with stakeholders (PM)

**Communication**:
- Retrospective meeting (45–75 min)
- Action item tracking with owners and due dates

---

## Decision-Making Matrix

| Decision Type | Owner | Consulted | Informed |
|---|---|---|---|
| **Product Prioritization** | Product Manager | Stakeholder, PM | Tech Lead, Developers |
| **Technical Architecture** | Tech Lead | Developers, PM | QA, Product Manager |
| **Timeline/Release Date** | Project Manager | Product Manager, Tech Lead | All roles |
| **Quality Standards** | QA Specialist | Tech Lead, Developers | Product Manager |
| **Resource Allocation** | Sponsor | Project Manager | All roles |
| **Risk Escalation** | Project Manager | Stakeholder, Tech Lead | All roles |
| **Acceptance Criteria** | Product Manager | QA, Developers | Tech Lead |
| **Incident Response** | Support/Operations | Tech Lead, Developers | Project Manager, Stakeholder |

---

## Communication Patterns

### Daily Communication
- **Standup** (15 min, daily): Led by Scrum Master. All roles report progress, blockers, and next steps.
- **Slack/Chat channels**: Developers, QA, and Tech Lead for quick problem-solving.

### Weekly Communication
- **PM + PdM sync** (30 min): Discuss roadmap, priorities, and risks.
- **Leadership/Stakeholder updates**: Weekly status from PM to Sponsor.
- **Team retro or health check**: Scrum Master facilitates discussion on process improvements.

### Bi-Weekly/Sprint-Based
- **Sprint Planning** (2–4 hours): All roles. Define sprint goals and pull items for execution.
- **Sprint Review** (1–2 hours): Demo work and gather feedback from Stakeholder and Product Manager.
- **Backlog Refinement** (1–2 hours): Product Manager, Tech Lead, and Developers prepare upcoming stories.

### Monthly/Milestone
- **Stakeholder Review**: Project Manager shares progress, metrics, and risks.
- **Retrospective** (45–75 min): Team reflects on what went well, what could improve, and action items.

---

## Escalation Paths

### Level 1: Team Triage
- **When**: Blocker identified in daily standup or sprint execution
- **How**: Scrum Master brings up in standup; team problem-solves immediately
- **Owner**: Scrum Master or relevant role lead

### Level 2: PM / Tech Lead Escalation
- **When**: Cross-team dependency, technical risk, or timeline impact
- **How**: Project Manager or Tech Lead escalates to Product Manager and relevant stakeholders
- **Owner**: Project Manager

### Level 3: Sponsor Escalation
- **When**: Business impact, resource constraints, or strategic decision needed
- **How**: Project Manager escalates to Sponsor with context and options
- **Owner**: Project Manager

### Level 4: Incident Response
- **When**: Production issue or critical customer impact
- **How**: Support/Operations initiates incident response; escalates to On-Call Engineer and PM
- **Owner**: Support/Operations or On-Call

---

## Role Responsibilities in Common Scenarios

### Scenario: Feature Acceptance Criteria Not Clear
- **Product Manager**: Clarifies intent and acceptance criteria
- **QA Specialist**: Proposes testability improvements; works with PdM on criteria
- **Tech Lead**: Identifies technical unknowns or complexity
- **Developer**: Asks clarifying questions; flags feasibility concerns

**Resolution**: PdM + QA document refined criteria; add to backlog item

---

### Scenario: Technical Blocker During Sprint
- **Developer**: Identifies blocker in standup
- **Tech Lead**: Proposes solutions or escalates architectural decision
- **Scrum Master**: Tracks blocker and ensures it gets unblocked
- **Project Manager**: Escalates if impact to timeline

**Resolution**: Tech Lead makes decision or escalates; Dev proceeds once unblocked

---

### Scenario: Production Incident
- **Support/Operations**: Detects issue; escalates to On-Call Engineer
- **Developer/Tech Lead**: Responds to incident; implements fix
- **Project Manager**: Communicates impact to Sponsor; manages customer comms
- **QA**: Validates fix; plans regression testing
- **Scrum Master**: Captures learnings for retrospective

**Resolution**: Incident resolved; post-incident retrospective scheduled within 24–48 hours

---

## Tips for Effective Collaboration

1. **Clarify Ownership**: Always know who owns each decision or activity.
2. **Communicate Early**: Surface risks, dependencies, and blockers ASAP.
3. **Document Decisions**: Use decision logs, ADRs (Architecture Decision Records), or issue comments.
4. **Respect Input**: Seek input from all relevant roles before finalizing decisions.
5. **Escalate Appropriately**: Don't skip levels; escalate through the chain when needed.
6. **Celebrate Wins**: Share success across the team; acknowledge contributions.
7. **Learn from Retrospectives**: Use retrospectives to improve collaboration patterns over time.

---

## Related Documents
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Project Management Overview](octoacme-project-management-overview.md)
