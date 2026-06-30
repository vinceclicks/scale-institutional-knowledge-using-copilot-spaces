# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This repository contains the processes, checklists, and guidance used to manage cross-functional projects from initiation through close.

## 📚 Core Principles

OctoAcme's project management approach is built on five core principles that guide all projects:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments rather than large, monolithic releases
- **Clear ownership**: Each project has named Project and Product Managers with explicit role clarity
- **Data-informed decisions**: Measure impact and iterate based on evidence and metrics
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## 🎯 OctoAcme Project Management Overview

OctoAcme follows a disciplined, five-phase project lifecycle designed to ensure alignment, reduce risk, and deliver reliable outcomes:

### Project Lifecycle at a Glance

1. **Initiation**: Validate business need, define success metrics, align stakeholders, and make a go/no-go decision
2. **Planning**: Break work into shippable increments, define acceptance criteria, identify dependencies and risks
3. **Execution**: Build, test, and review work in regular sprints; track progress and manage blockers daily
4. **Release**: Deploy to production following a standardized checklist with smoke tests and rollback plans
5. **Retrospective & Close**: Capture learnings and convert them into actionable improvements

### Governance & Communication

Every project is governed by a **Project Charter** (one-pager) that documents the problem, goal, success metrics, and stakeholders. Communication flows through a regular cadence:
- **Daily standups** (15 min) for progress, blockers, and dependencies
- **Weekly PM-PdM sync** for alignment and prioritization
- **Twice-weekly delivery standups** for execution teams
- **Monthly stakeholder updates** for high-level visibility

Teams maintain a **Risk Register** reviewed weekly, use **GitHub Projects boards** for workflow tracking, and enforce **quality standards** through automated CI, testing, code reviews, and security scanning. All work is tracked in prioritized backlogs with clear acceptance criteria, and progress is measured against success metrics identified in the Project Charter.

### Key Success Factors

- **Small, focused PRs** (≤400 lines) with clear issue links and acceptance criteria
- **Passing CI/CD checks** before code review and merging
- **Clear escalation paths** from team-level triage → PM → Product Lead → Sponsor
- **Weekly retrospectives** to capture learnings and drive continuous improvement
- **Transparent risk and dependency tracking** to prevent surprises

---

## 📖 Process Documentation

### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to roles, artifacts, and lifecycle
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed definitions of Project Managers, Product Managers, Developers, and QA roles

### Project Phases

Follow this sequence based on where your project is in its lifecycle:

1. **Initiation** → [Project Initiation Guide](./octoacme-project-initiation.md)
   - When: Whenever a new project idea or feature proposal is ready to be explored
   - Deliverables: One-pager, stakeholder list, timeline, risk list, resource needs

2. **Planning** → [Project Planning](./octoacme-project-planning.md)
   - When: After approval to move forward
   - Deliverables: Prioritized backlog, release plan, Definition of Done, test strategy

3. **Execution** → [Execution & Tracking](./octoacme-execution-and-tracking.md)
   - When: During sprints and ongoing development
   - Deliverables: Working software, test results, burndown metrics, risk updates

4. **Release** → [Release & Deployment Guide](./octoacme-release-and-deployment.md)
   - When: Ready to move to production
   - Deliverables: Release notes, deployment verification, stakeholder announcements

5. **Close & Learn** → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
   - When: After sprint, release, or milestone
   - Deliverables: Learnings captured, action items prioritized and assigned

### Cross-Cutting Concerns

- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Managing risks, dependencies, and stakeholder communication throughout all project phases

---

## 👥 Who Should Read What?

### New Team Members
Start here to understand OctoAcme's philosophy and how projects are run:
1. [Project Management Overview](./octoacme-project-management-overview.md)
2. [Roles & Personas](./octoacme-roles-and-personas.md)

### Project Managers
Reference docs throughout the project lifecycle:
- Initiation, Planning, Execution, Release, and Retrospective phases
- [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation and status reporting

### Product Managers
Focus on:
- [Project Initiation Guide](./octoacme-project-initiation.md) — Define problem, success metrics, and stakeholder alignment
- [Project Planning](./octoacme-project-planning.md) — Prioritize backlog and define acceptance criteria
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Measure impact and iterate

### Developers
Review:
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — PR workflow, testing standards, quality gates
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Deployment checklist and rollback procedures
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings

### QA/Testing Teams
Reference:
- [Project Planning](./octoacme-project-planning.md) — Definition of Done and test plan requirements
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Quality and testing standards
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Smoke test procedures

---

## 📋 Quick Reference: Checklists & Templates

Each process document includes practical checklists and templates you can use immediately:

| Phase | Key Checklist |
|-------|---|
| Initiation | Initiation Checklist (approve, align, decide) |
| Planning | Planning Checklist (kickoff, backlog, DoD, risks) |
| Execution | Execution Checklist (branching, CI, demos, risk register) |
| Release | Deployment Checklist (tests, backups, verification, announcement) |
| Retrospective | Retrospective Structure (went well, improve, actions) |

**Key Templates:**
- Project One-pager (Initiation)
- Backlog Item Template (Planning)
- Release Notes Template (Release)
- Action Item Template (Retrospective)

---

## 🔗 Related Resources

- **GitHub Issue Templates**: `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` — Use this template to propose updates to process documentation
- **Project Board**: Use GitHub Projects to track initiatives and backlog items
- **Risk Register**: Maintain in project README or issues; review weekly in syncs

---

## 📝 How to Keep These Docs Fresh

OctoAcme's processes evolve as the team learns. To propose updates:

1. Open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Describe what's missing, unclear, or outdated
3. Tag it with `process improvement` and `documentation`
4. Discuss with the team and iterate

---

## 🎓 Learning Path

**If you're new to OctoAcme:**
- [ ] Read Project Management Overview
- [ ] Read Roles & Personas (find your role)
- [ ] Read Project Initiation Guide (understand how projects start)
- [ ] Read your phase-specific docs as you work on projects

**If you're leading a new project:**
- [ ] Create a Project One-pager (use Initiation template)
- [ ] Run Project Planning and build your backlog
- [ ] Set up GitHub Projects board with your workflow
- [ ] Schedule weekly syncs and daily standups
- [ ] Maintain your Risk Register and track metrics

**If you're improving OctoAcme:**
- [ ] Propose changes via the process doc update template
- [ ] Discuss with PM and Product Lead
- [ ] Update docs and share in next team retrospective

---

**Questions?** Reach out to your Project Manager or Product Lead. We're here to help you succeed! 🚀
