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

## Product Owners

### Role Summary
Product Owners translate product direction into an ordered, actionable backlog and make day-to-day scope and acceptance decisions. On some projects, the Product Manager also serves as Product Owner; when the roles are separate, the Product Manager owns product strategy and outcomes while the Product Owner guides delivery-level priorities.

### Responsibilities
- Maintain and prioritize the product backlog
- Clarify requirements and acceptance criteria with stakeholders and the team
- Make timely scope and trade-off decisions within agreed product goals
- Review completed work and confirm whether it meets acceptance criteria

### Goals
- Keep the team focused on the highest-value work
- Provide clear, actionable requirements and timely decisions
- Ensure delivered work supports product goals and user needs

### Typical Communication
- Backlog refinement and sprint planning
- Acceptance criteria, product decisions, and feedback in project tools
- Regular alignment with the Product Manager and stakeholders

### Interactions with Existing Roles
- Align with the Product Manager on strategy, outcomes, and priority changes; clarify who makes backlog and product-scope decisions if one person does not hold both roles.
- Coordinate with the Project Manager on scope, milestones, dependencies, and decision timing.
- Answer questions from Developers and the QA / Test Lead, and review work against agreed acceptance criteria.

---

## Technical Leads / Solution Architects

### Role Summary
Technical Leads and Solution Architects guide technical design and ensure the solution fits architectural, operational, and engineering constraints. The role may be shared or combined with a senior developer on smaller projects.

### Responsibilities
- Define and communicate technical designs, standards, and key implementation decisions
- Identify technical dependencies, estimates, and constraints
- Guide Developers through implementation and review complex technical changes
- Surface technical risks and recommend mitigations

### Goals
- Deliver a coherent, maintainable solution that meets functional and operational needs
- Make technical trade-offs visible early
- Reduce avoidable rework and integration risk

### Typical Communication
- Technical design documents and architecture decision records
- Design reviews and engineering discussions
- Dependency, estimate, and risk updates to the Project Manager

### Interactions with Existing Roles
- Work with the Project Manager to sequence technical dependencies and communicate estimates, risks, and impacts to the plan.
- Partner with the Product Manager and Product Owner to assess technical options and explain their product and scope implications.
- Guide Developers and coordinate with the QA / Test Lead and Security and Privacy Lead on design, quality, and controls.

---

## QA / Test Leads

### Role Summary
QA / Test Leads coordinate quality planning and provide evidence about whether the product meets its requirements and is ready for release.

### Responsibilities
- Define the test approach, coverage, and quality criteria with the team
- Coordinate functional, integration, and regression testing as appropriate
- Track defects, risks, and test results, and communicate their impact
- Advise on release readiness based on agreed criteria and evidence

### Goals
- Find and resolve defects early
- Make product quality and remaining risks visible
- Ensure validation covers agreed requirements and acceptance criteria

### Typical Communication
- Test plans, defect reports, and release-readiness summaries
- Ongoing collaboration with Developers during implementation
- Quality and risk updates during project tracking and release reviews

### Interactions with Existing Roles
- Collaborate with Developers to plan and execute tests and verify fixes.
- Work with the Product Owner to confirm coverage of acceptance criteria and clarify expected behavior.
- Share quality evidence and unresolved risks with the Project Manager, Product Manager, and release decision-makers.

---

## Security and Privacy Leads

### Role Summary
Security and Privacy Leads identify applicable security, privacy, and compliance needs and coordinate reviews and mitigations throughout delivery.

### Responsibilities
- Identify security and privacy requirements, risks, and applicable reviews
- Advise on controls and secure handling of data
- Coordinate assessments and track findings through mitigation or documented acceptance
- Communicate security and privacy risks that affect scope, schedule, or release

### Goals
- Address security and privacy risks early in design and delivery
- Make control requirements and residual risks explicit
- Support informed release decisions and compliance obligations

### Typical Communication
- Security and privacy requirements, assessments, and findings
- Design reviews with technical and delivery roles
- Escalations and risk updates through project governance

### Interactions with Existing Roles
- Partner with the Technical Lead and Developers to incorporate controls into the design and implementation.
- Work with the Project Manager to plan reviews, track mitigations, and escalate schedule or release risks.
- Coordinate with the Product Manager and Product Owner when requirements or mitigations affect product scope or user experience.

---

## Business Owners / Executive Sponsors

### Role Summary
Business Owners and Executive Sponsors are accountable for the business outcomes of a project, provide strategic direction and resources, and make or escalate decisions beyond the delivery team's authority.

### Responsibilities
- Confirm desired business outcomes and measures of success
- Provide sponsorship, resources, and organizational alignment
- Resolve escalations and approve significant trade-offs within their authority
- Review progress and ensure the project remains aligned with business priorities

### Goals
- Realize measurable business value
- Keep the project aligned with organizational strategy
- Enable timely decisions when delivery teams cannot resolve an issue

### Typical Communication
- Steering or sponsor reviews and outcome updates
- Escalation briefs with options and recommendations
- Decisions recorded in project decision logs

### Interactions with Existing Roles
- Align with the Product Manager on business value, product outcomes, and priority changes.
- Work with the Project Manager on status, resource needs, risks, and escalations; the Project Manager coordinates delivery but does not replace sponsor-level decisions.
- Support the Product Owner and team by resolving organizational blockers and confirming the authority for major trade-offs.

---

## Change Management / Training Leads

### Role Summary
Change Management and Training Leads prepare affected users and operational teams to adopt project outcomes and support a successful transition into use.

### Responsibilities
- Assess organizational and user impacts of the change
- Plan stakeholder communications, training, and adoption support
- Coordinate readiness activities and identify adoption risks
- Gather feedback after rollout and recommend follow-up actions

### Goals
- Help affected users understand and adopt the change
- Reduce disruption during rollout
- Ensure adoption needs are addressed alongside technical delivery

### Typical Communication
- Change impact and readiness assessments
- Training materials, communications, and rollout plans
- Adoption feedback and readiness updates

### Interactions with Existing Roles
- Partner with the Product Manager and Product Owner to understand user needs and communicate product changes accurately.
- Coordinate with the Project Manager on readiness milestones, rollout timing, dependencies, and adoption risks.
- Work with the Technical Lead, Developers, QA / Test Lead, and operational stakeholders to prepare support and validate that the change is usable in practice.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

