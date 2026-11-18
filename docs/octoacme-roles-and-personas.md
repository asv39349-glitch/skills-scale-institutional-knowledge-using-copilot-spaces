# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Teams should assign the personas that are relevant to a project rather than requiring every role for every initiative. Handoffs and escalation responsibilities should be recorded in the project plan or responsibility matrix.

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

## Release Manager

### Role Summary
Release Managers own release readiness and coordinate the people and activities needed to move approved changes into production safely.

### Responsibilities
- Maintain release plans, schedules, checklists, and rollback/mitigation plans
- Coordinate staging validation and production deployment windows
- Confirm that acceptance criteria, CI checks, security scans, and smoke tests are complete
- Communicate release status, expected impact, and operational readiness
- Escalate unresolved release risks to the Project Manager and Sponsor as needed

### Goals
- Deliver releases predictably with minimal operational disruption
- Make go/no-go decisions based on documented evidence
- Improve release observability and rollback readiness

### Interactions and handoffs
- Works with the **Project Manager** on timing, dependencies, status, and escalation
- Works with the **Product Manager** on scope, release notes, and stakeholder messaging
- Works with **Developers** and **QA/Testing** to confirm implementation and validation readiness
- Coordinates operational readiness with **Support/Operations**, **Security**, and **DevOps/Platform** roles

---

## Security Lead

### Role Summary
Security Leads define security requirements, assess project risk, and guide secure implementation and release decisions.

### Responsibilities
- Define applicable security controls and review threat or risk concerns
- Review security findings and validate remediation plans
- Provide guidance on incident response and security escalation paths
- Define security-related release gates and evidence requirements
- Partner with teams to address findings without delaying delivery unnecessarily

### Goals
- Reduce security risk while supporting effective delivery
- Ensure security requirements are understood early
- Improve the consistency of remediation and incident handling

### Interactions and handoffs
- Advises **Developers** on secure design and remediation
- Collaborates with **QA/Testing** on security test coverage and findings
- Reviews release readiness with the **Release Manager**
- Escalates material risks and incidents through the **Project Manager** and Sponsor
- Coordinates with **DevOps/Platform** on secure pipelines and environments

---

## DevOps/Platform Engineer

### Role Summary
DevOps/Platform Engineers build and operate the CI/CD systems, environments, observability, and delivery tooling that enable reliable project delivery.

### Responsibilities
- Maintain build, test, deployment, and rollback tooling
- Provide test and staging environments
- Implement monitoring, logging, and alerting
- Improve deployment automation and developer workflows
- Support incident investigation and operational readiness

### Goals
- Increase delivery reliability and deployment frequency
- Reduce manual effort and environment-related failures
- Improve observability and recovery time

### Interactions and handoffs
- Partners with **Developers** on CI/CD, deployment design, instrumentation, and troubleshooting
- Provides environments and pipelines for **QA/Testing**
- Supports the **Release Manager** with deployment, verification, and rollback mechanisms
- Works with **Security** on secure configuration, scanning, and access controls
- Helps the **Data/Analytics Lead** make operational and product metrics observable

---

## UX/Design Lead

### Role Summary
UX/Design Leads represent user needs and define the interaction design, usability standards, and review activities for customer-facing work.

### Responsibilities
- Conduct or synthesize user research and usability findings
- Create interaction designs, prototypes, or experience standards
- Clarify usability acceptance criteria and trade-offs
- Review implementation for experience fidelity and accessibility
- Gather feedback from stakeholders and users

### Goals
- Improve usability, accessibility, and customer value
- Reduce rework caused by unclear experience decisions
- Align delivered experiences with the product vision

### Interactions and handoffs
- Works with the **Product Manager** to turn outcomes and user needs into priorities
- Consults **Developers** on feasibility and implementation details
- Collaborates with **QA/Testing** on acceptance criteria and usability validation
- Presents designs and findings to **Stakeholders** for informed decisions
- Raises unresolved scope or schedule trade-offs to the **Project Manager**

---

## Support/Operations Lead

### Role Summary
Support/Operations Leads represent customer support and operational readiness before, during, and after delivery.

### Responsibilities
- Define support and operational readiness requirements
- Validate support documentation, training, runbooks, and escalation paths
- Monitor customer-impact trends and supportability risks
- Coordinate incident triage and operational handoffs
- Provide feedback from customers and support teams

### Goals
- Improve operational readiness and support effectiveness
- Reduce customer disruption and time to resolution
- Ensure issues discovered after launch have clear ownership

### Interactions and handoffs
- Provides launch and support requirements to **Developers** and the **Project Manager**
- Coordinates defect triage and escalation with **QA/Testing**
- Confirms support readiness with the **Release Manager** before go-live
- Works with **Security** and **DevOps/Platform** on incidents and operational controls
- Communicates customer impact and risks to the **Product Manager** and Stakeholders

---

## Data/Analytics Lead

### Role Summary
Data/Analytics Leads define the measurement approach, validate data quality, and translate project evidence into actionable insights.

### Responsibilities
- Define success metrics and measurement plans
- Establish dashboards and reporting needs
- Validate event instrumentation and data quality
- Analyze outcomes and recommend follow-up actions
- Identify measurement gaps and data dependencies

### Goals
- Enable evidence-based prioritization and delivery decisions
- Ensure success metrics can be measured reliably
- Surface expected and unexpected outcomes quickly

### Interactions and handoffs
- Partners with the **Product Manager** to define and interpret success metrics
- Works with **Developers** to implement instrumentation and data pipelines
- Collaborates with **QA/Testing** to validate data collection and quality
- Supplies evidence and findings to the **Project Manager** and Stakeholders
- Coordinates observability needs with **DevOps/Platform** and **Support/Operations**

---

## Stakeholder/Domain Expert

### Role Summary
Stakeholder/Domain Experts provide business context, specialized knowledge, approvals, and validation for project decisions and outcomes.

### Responsibilities
- Clarify domain requirements, constraints, and policies
- Provide feedback and validate proposed outcomes
- Participate in prioritization and decision-making as assigned
- Identify impacted groups and communicate needs
- Escalate unresolved business risks or decisions

### Goals
- Improve relevance and correctness of delivered outcomes
- Surface business and policy constraints early
- Build shared understanding and approval across affected groups

### Interactions and handoffs
- Provides context and validates priorities with the **Product Manager**
- Partners with the **Project Manager** on decisions, dependencies, communications, and approvals
- Reviews designs and feedback with the **UX/Design Lead**
- Clarifies requirements for **Developers** and **QA/Testing**
- Receives status and outcome updates from the delivery team

---

## Responsibility and handoff guidance

Use a lightweight responsibility matrix in the project plan to make ownership explicit. Assign each relevant role to the work it owns or contributes to, and document decisions that require approval. This reduces gaps in delivery, release, security, quality, support, measurement, and stakeholder alignment.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Add roles only when they add clear accountability or address a project dependency.
