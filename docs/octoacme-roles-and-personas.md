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

## Engineering Managers

### Role Summary
Engineering Managers lead engineering teams and create the conditions for sustainable delivery. They focus on people, capacity, and team health rather than owning product priorities or project plans.

### Responsibilities
- Coach and support Developers and technical leads
- Plan engineering capacity and address staffing constraints
- Surface delivery risks and help resolve team-level blockers
- Promote sustainable engineering practices and team health

### Goals
- Build a capable, supported, and effective engineering team
- Make delivery commitments realistic and sustainable
- Resolve staffing and organizational impediments early

### Typical Communication
- Capacity and staffing discussions with Project Managers
- Feasibility and trade-off discussions with Product Managers
- Regular coaching, feedback, and escalation conversations with Developers

### Interaction Notes
- Partners with Project Managers on capacity, delivery risks, and schedule trade-offs; the Project Manager remains responsible for the project plan and status.
- Advises Product Managers on engineering feasibility; Product Managers retain ownership of product priorities and outcomes.
- Supports Developers through coaching and blocker escalation without replacing their ownership of implementation.

---

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects guide technical design and integration so that solutions are coherent, maintainable, and aligned with engineering standards.

### Responsibilities
- Define or facilitate architecture and significant technical decisions
- Establish implementation patterns and integration approaches
- Identify technical dependencies, risks, and quality concerns
- Review designs and support Developers with technical decisions

### Goals
- Deliver secure, reliable, and maintainable technical solutions
- Keep architecture and integrations aligned across the project
- Enable Developers to make timely, well-informed decisions

### Typical Communication
- Design reviews and technical decision records
- Implementation discussions and code reviews with Developers
- Scope, dependency, and sequencing discussions with Product and Project Managers

### Interaction Notes
- Guides Developers on technical approach while Developers own implementation details and code changes.
- Works with Product Managers to explain technical options and scope trade-offs; the Product Manager decides product priority and value.
- Coordinates with Project Managers on technical dependencies and sequencing risks; the Project Manager owns schedule tracking.
- Consults Security Engineers, DevOps / SRE, and QA/testing partners where architecture affects security, operability, or test strategy.

---

## UX Designers / Researchers

### Role Summary
UX Designers and Researchers understand user needs and shape accessible, usable experiences through research, interaction design, and validation.

### Responsibilities
- Plan and conduct user research and usability validation
- Create user flows, prototypes, and design specifications
- Identify accessibility and usability requirements
- Share research findings and design rationale with the team

### Goals
- Help users complete their tasks effectively and confidently
- Ensure product decisions are informed by user evidence
- Reduce usability and accessibility gaps before release

### Typical Communication
- Research findings and design reviews with Product Managers
- Design handoffs and implementation discussions with Developers
- Usability findings and test scenarios with QA/testing

### Interaction Notes
- Partners with Product Managers on problem framing and desired user outcomes; Product Managers retain ownership of product scope and prioritization.
- Collaborates with Developers on feasible implementation and clarifies design intent; Developers own the implementation.
- Provides QA/testing with usability and accessibility considerations to inform validation; QA/testing owns its test execution and reporting.
- Shares relevant research findings with stakeholders while respecting user privacy and research constraints.

---

## Security Engineers

### Role Summary
Security Engineers help teams identify and reduce security risk throughout design, development, testing, and operations.

### Responsibilities
- Facilitate threat modeling and identify security requirements
- Advise on secure design, implementation, and testing practices
- Review security-sensitive changes and recommend mitigations
- Support security issue triage and escalation

### Goals
- Reduce the likelihood and impact of security vulnerabilities
- Integrate security into delivery without avoidable late-stage surprises
- Ensure security risks and mitigations are visible to decision-makers

### Typical Communication
- Threat models and security reviews with Technical Leads and Developers
- Security risks and mitigations in project risk tracking
- Findings and remediation guidance with QA/testing and operations

### Interaction Notes
- Advises Technical Leads and Developers on secure design and implementation; engineering owners remain responsible for making and maintaining code changes.
- Works with Project Managers to record security risks and coordinate remediation; Project Managers track delivery but do not determine whether a security risk is acceptable.
- Partners with QA/testing on security test coverage and communicates material risks through established stakeholder escalation channels.
- Escalates unresolved or urgent security concerns to the appropriate security and engineering decision-makers.

---

## DevOps / SRE

### Role Summary
DevOps and Site Reliability Engineering (SRE) partners improve delivery automation and production reliability, helping teams operate software safely.

### Responsibilities
- Maintain and improve CI/CD pipelines and deployment practices
- Define observability, reliability, and operational readiness expectations
- Support rollback planning, production monitoring, and incident response
- Identify operational risks and reliability improvements

### Goals
- Make releases repeatable, observable, and safe
- Meet agreed reliability expectations and reduce avoidable incidents
- Help teams diagnose and recover from production issues effectively

### Typical Communication
- Release readiness and operational reviews with Developers and Technical Leads
- Deployment windows and operational risks with Project Managers
- Reliability metrics, incidents, and service health updates with stakeholders

### Interaction Notes
- Works with Developers and Technical Leads on pipeline, deployment, and observability needs; feature teams remain responsible for the quality and behavior of their services.
- Coordinates operational dependencies and deployment timing with Project Managers; Project Managers manage project communications and schedules.
- Collaborates with QA/testing on environment and release validation needs.
- During incidents, coordinates operational response with engineering owners and provides factual service-health updates through agreed stakeholder channels.

---

## Customer Support / Success Representatives

### Role Summary
Customer Support and Success Representatives bring customer feedback and support readiness needs into project planning and carry release information back to customers.

### Responsibilities
- Share recurring customer questions, pain points, and product feedback
- Identify support, documentation, and training needs for upcoming changes
- Prepare support teams with release notes, known issues, and escalation paths
- Capture post-release feedback and incident trends

### Goals
- Help customers adopt changes and resolve issues effectively
- Ensure support teams are prepared for releases
- Close the feedback loop between customers and product teams

### Typical Communication
- Customer-impact and feedback discussions with Product Managers
- Release readiness and stakeholder updates with Project Managers
- Known-issue and incident trend reviews with Developers, QA/testing, and support teams

### Interaction Notes
- Shares customer evidence with Product Managers, who own product prioritization and roadmap decisions.
- Coordinates release readiness information with Project Managers, who own project status and stakeholder coordination.
- Reports reproducible issues and customer impact to Developers and QA/testing; engineering and QA/testing own technical investigation, fixes, and verification.
- Communicates approved release and known-issue information to customers without making commitments on scope, delivery dates, or technical fixes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
