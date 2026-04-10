# OctoAcme Project Management Docs

This README serves as the central index and quick-start for all process documentation related to OctoAcme project management.

## Project Management Process Summary

OctoAcme follows a structured five-phase project lifecycle — Initiation, Planning, Execution, Release, and Retrospective — applied consistently across all cross-functional product and feature work. Projects begin with a lightweight one-pager that captures the problem statement, SMART goals, success metrics, and a stakeholder list. A go/no-go decision gate requires confirmed stakeholder alignment, clear success metrics, and team availability before a project advances to planning. During planning, the team holds a kickoff meeting, creates a prioritized backlog with explicit acceptance criteria, defines a shared Definition of Done, maps milestones, and documents a release plan with identified dependencies and risks.

The key roles are the **Project Manager (PM)**, who owns coordination, schedules, risk, and communications; the **Product Manager (PdM)**, who defines outcomes, prioritizes the backlog, and measures impact; **Developers**, who implement features and participate in design and code reviews; and **QA/Testing**, who validate quality and acceptance criteria. Each project also names a Product Lead and Sponsor as escalation points. This clear ownership model — reinforced by documented responsibilities and goals per persona — is central to how OctoAcme maintains accountability and reduces ambiguity across cross-functional teams.

Communication follows a defined cadence: twice-weekly standups for the delivery team, a weekly PM/PdM alignment sync, monthly stakeholder updates, and ad-hoc escalations following a three-level path (team → PM/Product Lead → Sponsor). Risks are tracked in a shared Risk Register (ID, impact, likelihood, owner, mitigation, status) and reviewed at weekly syncs. Standard weekly status updates use a consistent template covering progress, next steps, risks/blockers, and decisions needed. Incidents follow a separate playbook with a triage summary, actions, timeline, and a scheduled blameless post-mortem.

Quality assurance is built into the execution workflow rather than treated as a gate. The PR process requires small, well-described pull requests (ideally ≤400 lines) with issue links and acceptance criteria, automated tests and linting in CI, and at least one approval before merging. Releases require all acceptance criteria met, passing CI and security scans, smoke tests on staging, and a documented rollback plan before promoting to production. After each sprint, release, or significant incident, the team runs a timeboxed retrospective to capture what went well, what to improve, and 2–3 prioritized action items with clear owners and due dates — feeding back into the backlog and weekly PM sync to drive continuous improvement.

## Process Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning Guide](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

Each link provides detailed guidance and checklists for different parts of the project lifecycle.
