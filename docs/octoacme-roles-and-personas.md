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

## Technical Program Manager (TPM)

### Role Summary
TPMs coordinate complex, cross-team programs that span multiple teams or components; they focus on delivery at program scale rather than individual feature implementation.

### Responsibilities
- Coordinate cross-team dependencies and schedules
- Maintain program roadmap, milestones, and risk register
- Track and report program-level progress and blockers
- Facilitate cross-functional planning and decision sessions

### Interactions
- Works with Project Managers (PM) to align timelines and status reporting
- Partners with Product Managers (PdM) on prioritization trade-offs across teams
- Engages Engineering Managers and Tech Leads to unblock technical dependencies
- Coordinates with Release Manager for program release windows and cutovers

---

## Release Manager

### Role Summary
Owns release process and readiness, ensuring deployments are planned, communicated, and reversible when needed.

### Responsibilities
- Define and maintain release cadence and runbooks
- Coordinate staging and production deployments
- Validate release readiness (QA, observability, rollback) and confirm sign-offs
- Maintain rollback/mitigation plans and communicate them to stakeholders

### Interactions
- Works with Developers and QA to confirm PRs and tests meet release criteria
- Coordinates with SRE for deployment tooling, monitoring, and rollback
- Aligns with TPM and PM on release windows and stakeholder communications

---

## Site Reliability Engineer (SRE) / Reliability Lead

### Role Summary
SREs focus on reliability, operational readiness, and production health through SLIs/SLOs, alerting, and incident response.

### Responsibilities
- Define and track SLIs/SLOs and error budgets
- Create and maintain runbooks and on-call procedures
- Lead post-incident reviews and reliability-focused improvements
- Partner on deployment and scaling guidance to reduce production risk

### Interactions
- Partners with Developers to ensure adequate instrumentation and observability
- Works with Release Manager on deployment risk assessments and pre-release checks
- Feeds reliability metrics and incident learnings into PM and TPM prioritization

---

## Product Designer / UX Lead

### Role Summary
Product Designers ensure product usability, accessibility, and coherent user experience across features.

### Responsibilities
- Lead UX design, prototypes, and interaction specifications
- Ensure accessibility and usability standards are met
- Provide design validation and acceptance criteria for features

### Interactions
- Works closely with PdM to translate user needs into design outcomes
- Collaborates with Developers during implementation to clarify edge cases
- Partners with QA to define UX acceptance tests and validate results

---

## Data Analyst / Analytics Owner

### Role Summary
Data Analysts define success metrics and provide the data and analysis to inform product decisions.

### Responsibilities
- Define and validate success metrics and experiment measurement
- Build dashboards and reports for product and project visibility
- Ensure data quality and instrumentation correctness
- Support A/B testing and post-launch analysis

### Interactions
- Works with PdM to set metric definitions and evaluation plans
- Collaborates with Developers to ensure proper instrumentation and event telemetry
- Provides PM/TPM with outcome reporting to influence prioritization and changes

---

## Support / Operations Lead

### Role Summary
The Support/Operations Lead is the primary owner for triage, customer-facing issue handling, and operational runbooks for recurring problems.

### Responsibilities
- Triage and prioritize customer support tickets and operational alerts
- Maintain runbooks for common operational issues and first-response steps
- Surface user-impacting trends and escalate critical issues
- Feed product and engineering teams with actionable user feedback

### Interactions
- Works with PM and PdM to prioritize bug fixes and user-impacting improvements
- Coordinates with SRE during incidents and escalations
- Partners with Developers to implement fixes and long-term mitigations

---

## How these additions improve outcomes
- Clarifies ownership across common handoffs (release, incident, design, data)
- Reduces ambiguity in escalation and decision-making
- Speeds cross-team coordination and reduces meeting overhead
- Helps recruiters and new hires understand role expectations

## Next steps (for the doc update)
- Add short examples or links to runbooks and on-call docs where applicable
- Create anchors/links for each persona to reference from project READMEs or runbooks
- Review with stakeholders and adjust responsibilities to match team realities
