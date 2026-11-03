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

## Project Sponsor / Executive Sponsor

### Role Summary
The Project Sponsor champions the business need, ensures the initiative remains aligned with organizational strategy, and helps resolve issues that exceed the project team's authority.

### Responsibilities
- Confirm strategic alignment and continued business sponsorship
- Secure or advocate for the resources needed to deliver the initiative
- Make or escalate high-impact business trade-off decisions
- Review progress against intended outcomes and address major impediments

### Goals
- Realize the intended business value
- Ensure the project has clear sponsorship and appropriate support
- Resolve escalated decisions promptly

### Typical Communication
- Milestone and executive status reviews with the Project Manager
- Outcome and priority discussions with the Product Manager
- Time-sensitive escalation decisions as needed

### Collaboration and Decision Boundaries
The Sponsor works with the Project Manager on escalations, resources, and project-level impediments, and with the Product Manager on strategic outcomes and priority trade-offs. The Sponsor provides business direction and escalation decisions; the Product Manager remains responsible for product backlog priorities, while the Project Manager coordinates delivery and communicates impacts.

---

## UX/UI Designer or User Researcher

### Role Summary
The UX/UI Designer or User Researcher helps the team understand user needs and shape usable, accessible experiences that address the product problem.

### Responsibilities
- Plan or conduct user research and synthesize findings
- Create and validate user flows, interaction designs, prototypes, and design specifications
- Identify usability and accessibility considerations
- Share evidence and design rationale with the delivery team

### Goals
- Ensure solutions address user needs and are understandable and usable
- Validate assumptions early and reduce avoidable rework
- Make user experience and accessibility considerations visible in delivery decisions

### Typical Communication
- Discovery and design reviews with the Product Manager and stakeholders
- Design handoffs and ongoing collaboration with Developers
- Usability findings and acceptance discussions with QA and the delivery team

### Collaboration and Decision Boundaries
The designer or researcher partners with the Product Manager to frame user problems and validate concepts, and with Developers to assess feasibility and clarify design intent. They work with QA to make usability and accessibility expectations testable. They provide design and research expertise; product scope and priority remain with the Product Manager, and delivery coordination remains with the Project Manager.

---

## QA Engineer / Test Lead

### Role Summary
The QA Engineer or Test Lead helps the team establish confidence that delivered work meets acceptance criteria and quality expectations.

### Responsibilities
- Define or coordinate test strategy and appropriate test coverage
- Review requirements and acceptance criteria for testability
- Validate features, document defects, and report quality risks
- Coordinate regression and release-readiness testing with the team

### Goals
- Detect important issues early and reduce production risk
- Provide clear evidence of quality and acceptance readiness
- Support a shared understanding of expected behavior

### Typical Communication
- Test planning with Developers and the Product Manager
- Defect triage and progress updates with the delivery team
- Quality and readiness reporting with the Project Manager

### Collaboration and Decision Boundaries
The QA Engineer works with Developers on testability, test automation, and defect resolution; with the Product Manager on expected behavior and acceptance criteria; and with the Project Manager on test status, risks, and schedule impacts. QA provides evidence and raises quality concerns; product acceptance and release decisions follow the team's agreed approval and release policies.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect guides technical design and integration decisions so the solution is maintainable, secure, and compatible with the project's technical context.

### Responsibilities
- Facilitate technical design and document significant decisions
- Identify architecture, integration, scalability, and technical risks
- Support Developers with implementation guidance and technical reviews
- Surface technical dependencies, estimates, and trade-offs

### Goals
- Deliver a coherent, maintainable technical solution
- Reduce technical and integration risk
- Enable Developers to make informed, consistent implementation decisions

### Typical Communication
- Design discussions and code reviews with Developers
- Technical options and dependency updates with the Product Manager and Project Manager
- Coordination with QA and Operations on testability and operational needs

### Collaboration and Decision Boundaries
The Technical Lead partners with Developers on implementation and reviews, and consults QA and Operations on quality and operational requirements. They communicate scope, estimates, and dependency impacts to the Product Manager and Project Manager. The Technical Lead advises on technical choices within agreed architecture and policy; product priorities remain with the Product Manager, and project plans and escalations are coordinated by the Project Manager.

---

## Operations / Site Reliability or Support Representative

### Role Summary
An Operations, Site Reliability, or Support Representative brings operational and customer-support needs into planning, release, and ongoing service ownership.

### Responsibilities
- Advise on reliability, monitoring, alerting, capacity, and operational readiness
- Identify support impacts, runbook needs, and relevant service dependencies
- Help define deployment verification and incident-response expectations
- Share customer or operational feedback that may affect delivery or prioritization

### Goals
- Make services supportable and observable
- Reduce avoidable release and operational risk
- Ensure support teams are prepared for changes that affect customers

### Typical Communication
- Readiness and release planning with the Project Manager and Product Manager
- Operational design and monitoring discussions with Developers and QA
- Support handoffs, incident reviews, and service updates as needed

### Collaboration and Decision Boundaries
This representative works with Developers and QA on operational checks, monitoring, and support readiness, and with the Product Manager and Project Manager on launch readiness, customer impact, and delivery risks. They provide operational expertise and raise readiness concerns; product scope and delivery coordination remain with the Product Manager and Project Manager respectively, following the team's release and incident policies.

---

## Business / Domain Subject-Matter Expert

### Role Summary
The Business or Domain Subject-Matter Expert (SME) contributes specialized knowledge of business rules, workflows, users, and constraints relevant to the project.

### Responsibilities
- Explain domain terminology, rules, exceptions, and process constraints
- Review proposed workflows and clarify business scenarios
- Provide timely answers to questions raised during refinement, implementation, and testing
- Help validate that delivered behavior reflects agreed domain expectations

### Goals
- Ensure the team has accurate domain knowledge
- Reduce misunderstandings and rework caused by unclear business rules
- Support solutions that fit real business workflows and constraints

### Typical Communication
- Requirements and backlog refinement with the Product Manager
- Scenario clarification with Developers and QA
- Reviews and decision follow-up coordinated by the Project Manager

### Collaboration and Decision Boundaries
The SME collaborates with the Product Manager to clarify requirements and domain needs, and with Developers and QA to explain expected behavior and edge cases. They provide subject-matter input and review; the Product Manager owns product decisions and priorities, while the Project Manager coordinates participation, schedule, and follow-up.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- New personas are candidates to validate against team and project needs; not every project requires every role. Teams should make ownership, decision boundaries, and handoffs explicit when a role is involved.
