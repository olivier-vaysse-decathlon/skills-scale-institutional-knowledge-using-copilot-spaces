# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Personas describe responsibilities, not mandatory separate positions; one person may cover multiple roles depending on team size and project needs.

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

## Project Sponsors

### Role Summary
Project Sponsors provide organizational backing and are accountable for ensuring an initiative remains aligned with its approved business case.

### Responsibilities
- Champion the initiative and secure agreed resources
- Confirm strategic alignment and make or escalate major scope and priority decisions
- Resolve escalations that exceed the project team's authority
- Review progress against intended business outcomes at key milestones

### Interactions with Existing Roles
- Partner with the Project Manager on escalations, constraints, and milestone updates
- Align with the Product Manager on the business outcomes and priority trade-offs
- Provide Developers and other delivery contributors with timely decisions through the Project Manager and Product Manager
- Consult Stakeholders when decisions affect their commitments or interests

---

## Business Analysts

### Role Summary
Business Analysts connect business needs to clear, actionable requirements and workflows for delivery teams.

### Responsibilities
- Elicit and document stakeholder needs, processes, assumptions, and constraints
- Translate needs into requirements and supportable acceptance criteria
- Identify gaps, dependencies, and impacts across business workflows
- Keep requirements traceable as scope or decisions change

### Interactions with Existing Roles
- Work with the Product Manager to clarify desired outcomes and backlog priorities
- Partner with Stakeholders to validate needs and resolve conflicting requirements
- Collaborate with Developers and QA/Testing to make requirements feasible and testable
- Keep the Project Manager informed of requirement changes that affect scope, risks, or milestones

---

## UX/UI Designers and Researchers

### Role Summary
UX/UI Designers and Researchers understand user needs and shape accessible, usable experiences that support the product's intended outcomes.

### Responsibilities
- Plan and conduct appropriate user research and synthesize findings
- Create and validate user flows, interaction designs, and interface guidance
- Identify usability and accessibility considerations early
- Share evidence and design decisions with the delivery team

### Interactions with Existing Roles
- Collaborate with the Product Manager to connect user needs, product direction, and priorities
- Work with Developers and the Technical Lead to assess feasibility and carry designs into implementation
- Partner with QA/Testing to define and verify usability-related acceptance criteria
- Share research findings with Stakeholders and the Project Manager when they affect scope, risks, or timing

---

## Technical Leads and Architects

### Role Summary
Technical Leads and Architects guide technical design and integration so the solution is maintainable, reliable, and aligned with engineering standards.

### Responsibilities
- Guide architecture, technical decisions, and engineering practices
- Identify technical dependencies, constraints, and risks
- Support Developers with design reviews and complex implementation decisions
- Advise on technical readiness and trade-offs

### Interactions with Existing Roles
- Coordinate implementation approaches and technical risks with Developers
- Inform the Project Manager about dependencies or technical decisions that may affect delivery plans
- Work with the Product Manager to explain technical trade-offs that affect product scope or outcomes
- Partner with QA/Testing on testability and with Security and Privacy Leads on technical controls

---

## Security and Privacy Leads

### Role Summary
Security and Privacy Leads help teams identify and address security, privacy, and applicable compliance needs throughout delivery.

### Responsibilities
- Advise on relevant security, privacy, and compliance requirements
- Help identify risks and recommend proportionate controls and mitigations
- Review security and privacy considerations at appropriate design and release checkpoints
- Coordinate escalation to the organization's security incident process when needed

### Interactions with Existing Roles
- Work with the Technical Lead and Developers to incorporate controls into design and implementation
- Collaborate with QA/Testing on security and privacy validation
- Advise the Project Manager on risk status, mitigations, and release readiness
- Help the Product Manager and Stakeholders understand material risks and decisions; follow the security incident runbook and notify Security on-call for incidents

---

## Data and Analytics Leads

### Role Summary
Data and Analytics Leads define how teams will collect and interpret evidence about product usage and project success.

### Responsibilities
- Translate success metrics into measurement plans and instrumentation needs
- Define data quality, event, and reporting requirements
- Help interpret results and communicate limitations in the evidence
- Recommend improvements to measurement based on observed outcomes

### Interactions with Existing Roles
- Align with the Product Manager on success metrics and how outcomes will be evaluated
- Coordinate with Developers on instrumentation and data access needs
- Work with QA/Testing to verify events, data quality, and reporting behavior
- Share evidence with the Project Manager and Stakeholders for status and decisions

---

## Release and Operations Leads

### Role Summary
Release and Operations Leads coordinate production readiness and the transition from delivery into ongoing operation and support.

### Responsibilities
- Coordinate deployment readiness, monitoring, and operational handoff
- Confirm that release, rollback, and mitigation plans are understood
- Identify operational dependencies and readiness risks
- Support post-release verification and incident coordination with the appropriate on-call teams

### Interactions with Existing Roles
- Work with Developers and QA/Testing on deployment checks, smoke tests, and post-release verification
- Coordinate release timing, dependencies, and communications with the Project Manager
- Align with the Product Manager on release scope and stakeholder impact
- Handoff service context and known issues to support and on-call teams, involving Stakeholders as appropriate

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign or combine responsibilities to fit the project's size and context; use the role interactions to make ownership and handoffs explicit.
