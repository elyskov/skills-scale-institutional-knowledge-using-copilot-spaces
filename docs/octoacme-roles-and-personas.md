# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Test Engineers

### Role Summary
QA / Test Engineers define and execute test strategies to validate that features meet acceptance criteria and quality standards before release.

### Responsibilities
- Draft and maintain the test plan and test cases for each release
- Execute manual and automated tests across unit, integration, and end-to-end layers
- Validate acceptance criteria in collaboration with the Product Manager
- File, triage, and verify bug fixes
- Maintain the Definition of Done quality gates
- Support smoke testing during deployments

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and reduce regression risk
- Ensure releases are safe and verifiable

### Typical Communication
- Sprint planning and backlog grooming with Product Managers and Developers
- Bug triage sessions and test result reports
- Pre-release sign-off shared with Project Manager and Tech Lead

### Interaction with Existing Roles
- Works with **Developers** on coverage and testability during design
- Reports test status to **Project Managers** for risk and status updates
- Validates acceptance criteria defined by **Product Managers**

---

## Tech Lead / Engineering Lead

### Role Summary
The Tech Lead provides technical direction for the delivery team. They own architectural decisions, code quality standards, and cross-team technical dependencies.

### Responsibilities
- Define and enforce coding standards and architectural patterns
- Lead technical design reviews and spike investigations
- Break down complex work into estimable tasks with Developers
- Identify and own technical risks and mitigation plans
- Serve as the escalation point for technical blockers
- Coordinate technical dependencies with other teams

### Goals
- Ensure technical integrity and scalability of delivered solutions
- Reduce technical debt and unplanned rework
- Mentor Developers and maintain team velocity

### Typical Communication
- Technical design docs and architecture decision records (ADRs)
- Code review feedback and pair programming sessions
- Weekly sync with Project Manager and Product Manager on technical risks

### Interaction with Existing Roles
- Partners with **Product Managers** to assess feasibility and trade-offs
- Guides **Developers** on technical direction and standards
- Reports technical risks to **Project Managers** for the risk register

---

## UX Designers

### Role Summary
UX Designers ensure that features are usable, accessible, and aligned with customer needs. They translate requirements into wireframes, prototypes, and design specifications.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define interaction patterns and accessibility standards
- Collaborate with Product Managers on problem framing and user stories
- Participate in design reviews and provide sign-off on UI implementations

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework caused by usability issues discovered late in development
- Ensure design consistency across the product

### Typical Communication
- Design reviews with Developers and Product Managers
- Usability test findings and design documentation
- Feedback loops through prototypes and acceptance testing

### Interaction with Existing Roles
- Works closely with **Product Managers** on problem definition and user stories
- Provides design specs and assets to **Developers** for implementation
- Validates UI implementations in coordination with **QA / Test Engineers**

---

## DevOps / Release Engineers

### Role Summary
DevOps / Release Engineers own the CI/CD pipeline, deployment infrastructure, and operational reliability. They enable safe, repeatable releases and respond to production incidents.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Define and enforce pre-release gates (build, test, security scans)
- Coordinate and execute production deployments
- Maintain rollback and incident response playbooks
- Monitor system health post-deployment
- Serve as on-call for production incidents

### Goals
- Enable frequent, low-risk deployments
- Minimize mean time to restore (MTTR) during incidents
- Ensure the deployment process is auditable and repeatable

### Typical Communication
- Deployment window coordination with Project Managers
- Post-deploy verification reports and incident retrospectives
- Pipeline status updates in release planning meetings

### Interaction with Existing Roles
- Coordinates deployment scheduling with **Project Managers**
- Supports **QA / Test Engineers** with environment provisioning and test pipelines
- Notifies **Stakeholders / Executive Sponsors** during major incidents via escalation paths

---

## Stakeholders / Executive Sponsors

### Role Summary
Stakeholders and Executive Sponsors provide strategic direction, funding, and approval authority for projects. They are the ultimate escalation point and serve as organizational champions for the project.

### Responsibilities
- Approve project charter, scope, and funding
- Receive and review regular status updates and milestone reports
- Make decisions on scope changes, trade-offs, and escalated risks
- Champion the project within the organization
- Participate in project kickoff and major milestone reviews

### Goals
- Ensure the project delivers business value and meets strategic objectives
- Provide timely decisions to unblock the team
- Maintain organizational alignment and executive visibility

### Typical Communication
- Monthly or milestone-based status briefings from Project Manager
- Escalation communications for high-impact risks and blockers
- Project kickoff and retrospective summaries

### Interaction with Existing Roles
- Aligned to by **Project Managers** for escalation and decision authority
- Receives roadmap and outcome updates from **Product Managers**
- Final approver for scope decisions raised by the **Tech Lead**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

