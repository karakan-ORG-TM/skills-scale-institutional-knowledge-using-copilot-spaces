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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Recommended Personas

The following personas are recommended additions to clarify ownership of cross-cutting activities (releases, security, UX, analytics, documentation, and customer communication). Each entry describes the role summary, responsibilities, and how they typically interact with existing roles.

### Engineering Manager
Role Summary:
Engineering Managers provide people and technical leadership for delivery teams and own technical capacity planning and risk remediation.

Responsibilities:
- People management and career growth for engineers
- Capacity planning and team staffing recommendations
- Technical risk ownership and mitigation coordination
- Ensure engineering practices (code quality, CI, observability) are followed

Interaction with existing roles:
- Works with Project Managers on capacity and scheduling
- Partners with Product Managers and Tech Leads on technical feasibility and architecture
- Supports Developers during implementation and blockers; escalates persistent impediments to Product Lead or Sponsor when needed

---

### UX Designer
Role Summary:
UX Designers lead user research, interaction and visual design, and ensure accessibility and usability of product features.

Responsibilities:
- Conduct user research and usability testing
- Create wireframes, prototypes, and design assets
- Define interaction patterns and accessibility checks
- Handoff designs and assets to engineering with acceptance criteria

Interaction with existing roles:
- Collaborates closely with Product Managers on user needs and acceptance criteria
- Provides designs and guidance to Developers and QA
- Joins demos and reviews to validate the delivered UX against intent

---

### Product Analyst / Data Analyst
Role Summary:
Product/Data Analysts define and measure success metrics, build dashboards, and run analysis to inform product decisions.

Responsibilities:
- Define measurement plans and success metrics
- Build and maintain dashboards and reports
- Run experiments and post-release analysis
- Provide insights and recommendations based on data

Interaction with existing roles:
- Works with Product Managers to define metrics and experiment design
- Shares metrics and findings with Developers, QA, and stakeholders during weekly syncs
- Helps verify telemetry and analytics instrumentation prior to release

---

### Release Engineer
Role Summary:
Release Engineers own deployment pipelines, runbooks, rollback plans, and post-deploy validation to ensure smooth, low-risk releases.

Responsibilities:
- Maintain CI/CD pipelines and release automation
- Prepare deployment runbooks and rollback procedures
- Coordinate staging and production deployments and verifications
- Monitor deployment health and lead post-deploy validation

Interaction with existing roles:
- Coordinates deployment windows with Project Managers and Developers
- Ensures Release checklist is completed prior to production push
- Escalates production issues to on-call/engineering and Product Lead as needed

---

### Security / Compliance Owner
Role Summary:
Security/Compliance Owners drive security reviews, threat modeling, and ensure compliance controls are met.

Responsibilities:
- Conduct security reviews and coordinate remediation
- Run or ensure security scans in CI and gating policies
- Maintain compliance checklists and evidence for audits
- Define security acceptance criteria for features

Interaction with existing roles:
- Partners with Developers to resolve security findings
- Works with Release Engineer to ensure security checks are enforced in CI/CD
- Escalates critical findings to Product Lead, PM, or Security on-call

---

### Business Stakeholder / Domain Owner
Role Summary:
Business Stakeholders or Domain Owners provide domain expertise, prioritize business needs, and sign off on releases affecting their area.

Responsibilities:
- Provide domain context and business-level requirements
- Review and approve scope decisions and release readiness for their domain
- Coordinate communications with their functional area

Interaction with existing roles:
- Works with Product Managers and Project Managers on prioritization and go/no-go decisions
- Available for major trade-offs and acceptance on business-impacting changes

---

### Technical Writer / Documentation Owner
Role Summary:
Technical Writers produce and maintain user-facing and internal documentation, release notes, and runbooks.

Responsibilities:
- Create and maintain documentation (user guides, internal runbooks)
- Draft release notes and migration guides
- Ensure documentation is updated as part of Definition of Done

Interaction with existing roles:
- Works with Developers, Product Managers, and Release Engineers to gather accurate information
- Publishes docs before release and coordinates with Customer Success for customer-facing changes

---

### Customer Success Representative
Role Summary:
Customer Success Representatives surface customer feedback, help shape support flows, and coordinate customer communications for changes and incidents.

Responsibilities:
- Gather and prioritize customer feedback and pain points
- Define support and communication plans for releases and incidents
- Provide customer context during prioritization

Interaction with existing roles:
- Feeds prioritized customer issues to Product Managers
- Works with Project Managers and Product Managers on customer communications during and after releases
- Supports post-release follow-up and adoption efforts

---

## How these additions improve outcomes
- Clearer ownership reduces delays and finger-pointing during handoffs.
- Defined responsibilities for release, security, and measurement reduce operational and compliance risk.
- Better onboarding and role clarity for cross-functional teams.
- Faster stakeholder alignment and decision-making, with explicit sign-off owners.
