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

## QA Lead

### Role Summary
QA Leads own quality assurance strategy and execution. They coordinate testing efforts, manage defect tracking, and ensure the Definition of Done is met before releases.

### Responsibilities
- Develop and maintain test plans aligned with acceptance criteria
- Coordinate manual and automated testing efforts
- Track, prioritize, and escalate defects with clear severity levels
- Confirm Definition of Done compliance before handoff to deployment
- Collaborate on test coverage and quality metrics
- Design and maintain test infrastructure and automation frameworks

### Goals
- Ensure product quality and reliability before release
- Reduce production defects and customer-facing issues
- Build confidence in feature readiness through comprehensive testing
- Enable fast feedback loops during development

### Typical Communication
- Weekly QA status updates and test coverage reports
- Defect escalation emails and triage meetings
- Collaboration with developers on test design and edge cases
- Go/no-go decisions with Release Manager and PM before deployment

### Interacts With
- **Developers**: coordinate on test coverage, edge cases, and testability
- **Project Managers**: provide timelines for QA phases and test readiness
- **Release Manager**: confirm quality gates before production deployment
- **Product Managers**: validate acceptance criteria and success conditions

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centered interfaces and experiences. They conduct user research, design wireframes and prototypes, and validate usability before development.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Develop and maintain design systems and component libraries
- Collaborate on interaction design and accessibility standards
- Iterate based on user feedback and behavioral data
- Ensure designs align with product vision and brand guidelines

### Goals
- Maximize user satisfaction and adoption
- Reduce friction and confusion in user workflows
- Build accessible, inclusive experiences for all users
- Enable data-driven design decisions

### Typical Communication
- Design review meetings with stakeholders and developers
- User research reports and insights presentations
- Design specifications and component documentation
- Feedback loops during development and post-launch

### Interacts With
- **Product Managers**: understand requirements and validate design solutions against business goals
- **Developers**: collaborate on implementation and component behavior
- **Stakeholders**: present prototypes and gather feedback on usability
- **QA Leads**: ensure design intent is preserved in final product

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and execute releases to production. They ensure all pre-release requirements are met, orchestrate deployment activities, and manage rollback procedures.

### Responsibilities
- Create and maintain release plans and schedules
- Verify all pre-release requirements are met (testing, documentation, approvals)
- Coordinate deployment timing and communication
- Execute or oversee deployment to staging and production
- Run post-deployment verification and smoke tests
- Lead incident response and coordinate rollback if needed
- Maintain deployment runbooks and documentation

### Goals
- Deliver releases on schedule with minimal risk
- Reduce deployment-related incidents and downtime
- Maintain transparent communication with all stakeholders during releases
- Enable rapid rollback capability in case of critical issues

### Typical Communication
- Pre-release checklists and readiness reviews
- Deployment calendars and go/no-go announcements
- Release notes and stakeholder announcements
- Post-deployment verification reports
- Incident communication during critical issues

### Interacts With
- **Developers**: coordinate on code freezes, hotfixes, and deployment considerations
- **QA Leads**: confirm quality gates and test completion
- **Project Managers**: align on release timing and dependencies
- **Product Managers**: coordinate feature announcements and rollout strategy
- **Stakeholders**: provide pre- and post-release communication

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They elicit requirements, map processes, validate business value, and ensure solutions align with organizational goals.

### Responsibilities
- Gather and document business requirements from stakeholders
- Map current and future process flows
- Translate business needs into clear user stories and acceptance criteria
- Validate that proposed solutions address business problems
- Identify and document interdependencies with other systems and teams
- Support scope management and trade-off decisions
- Participate in UAT (User Acceptance Testing) coordination

### Goals
- Ensure technical solutions deliver measurable business value
- Reduce scope creep and misalignment through clear requirements
- Enable faster decision-making by providing business context
- Increase stakeholder confidence in solution outcomes

### Typical Communication
- Requirements workshops and stakeholder interviews
- Business process documentation and flow diagrams
- User story refinement and acceptance criteria review
- Business impact assessments and ROI analyses
- UAT coordination and issue resolution

### Interacts With
- **Product Managers**: collaborate on requirements prioritization and business value
- **Developers**: clarify requirements, discuss feasibility, and address technical questions
- **Project Managers**: support scope and timeline management
- **Stakeholders**: gather requirements and validate solutions
- **QA Leads**: define acceptance criteria and support UAT planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning projects, ensure all critical roles are assigned and responsibilities are clear.
- Reference these personas in project kickoffs to align team members on expectations and interactions.
