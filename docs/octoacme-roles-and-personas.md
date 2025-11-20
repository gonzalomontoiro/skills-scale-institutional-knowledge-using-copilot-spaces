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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on agile practices. They ensure the team follows agreed processes and foster continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, retrospectives, and demos
- Remove blockers and escalate impediments
- Coach team on agile principles and practices
- Shield team from external disruptions
- Foster psychological safety and continuous improvement
- Track team metrics (velocity, cycle time, etc.)

### Goals
- Maximize team productivity and flow
- Ensure consistent delivery cadence
- Build team autonomy and self-organization
- Improve team health and satisfaction

### Typical Communication
- Facilitation of all agile ceremonies
- One-on-ones with team members to identify blockers
- Coordination with Project Manager on cross-team dependencies
- Metrics dashboards and improvement suggestions

### Key Touchpoints
- **With Developers**: Daily impediment removal, coaching on practices
- **With Project Manager**: Alignment on timelines, dependencies, and reporting
- **With Product Manager**: Backlog readiness and sprint goal clarity
- **With DevOps Engineer**: CI/CD pipeline improvements, automation opportunities

---

## UX/UI Designer

### Role Summary
UX/UI Designers research user needs, create wireframes and prototypes, and ensure the product delivers an intuitive, accessible user experience.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define design systems and UI component libraries
- Collaborate with developers on implementation feasibility
- Validate designs through user feedback and analytics
- Ensure accessibility standards (WCAG) are met

### Goals
- Deliver intuitive, accessible user experiences
- Reduce time-to-value for users
- Maintain design consistency across product
- Validate designs with real user feedback

### Typical Communication
- Design reviews and critique sessions
- User research findings presentations
- Handoff documentation for developers
- Usability test reports and recommendations

### Key Touchpoints
- **With Product Manager**: Understanding user problems, defining feature scope
- **With Developers**: Design handoff, implementation feasibility discussions
- **With Technical Writer**: Consistency between UI and documentation
- **With QA/Testing**: Acceptance criteria for UI/UX requirements

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, infrastructure, and deployment automation. They enable reliable, frequent releases while maintaining system stability and security.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code (IaC)
- Implement monitoring, logging, and alerting
- Automate deployments and rollbacks
- Ensure security scanning and compliance
- Support incident response and post-mortems

### Goals
- Reduce deployment time and increase frequency
- Maintain high availability and system reliability
- Automate manual operational tasks
- Improve observability and incident response

### Typical Communication
- Infrastructure change requests and reviews
- Deployment planning and coordination
- Incident response and post-mortem reports
- Performance and reliability metrics

### Key Touchpoints
- **With Developers**: CI/CD pipeline usage, build optimization
- **With Project Manager**: Deployment scheduling, infrastructure dependencies
- **With QA/Testing**: Test environment provisioning, automated test integration
- **With Scrum Master**: Identifying process automation opportunities

---

## Technical Writer

### Role Summary
Technical Writers create and maintain documentation that helps users, developers, and stakeholders understand and use the product effectively.

### Responsibilities
- Write user guides, API documentation, and tutorials
- Maintain technical documentation and knowledge base
- Collaborate with developers to document features
- Ensure documentation accuracy and clarity
- Create onboarding materials and runbooks
- Manage documentation versioning and releases

### Goals
- Reduce support burden through clear documentation
- Improve onboarding time for new users and team members
- Maintain up-to-date, accurate documentation
- Ensure documentation accessibility and discoverability

### Typical Communication
- Documentation review requests with developers
- Content planning with Product Manager
- Style guide and terminology discussions
- User feedback on documentation quality

### Key Touchpoints
- **With Developers**: Feature documentation, API reference, code examples
- **With Product Manager**: Release notes, feature announcements
- **With UX/UI Designer**: Consistency between UI and help text
- **With Project Manager**: Documentation milestones and deliverables

---

## Role Interaction Matrix

| Role | Primary Collaborators | Accountability Areas | Communication Methods |
|------|----------------------|---------------------|----------------------|
| Developer | Scrum Master, UX/UI Designer, DevOps Engineer | Code quality, feature delivery | PRs, standups, design reviews |
| Product Manager | Project Manager, UX/UI Designer, Technical Writer | Product vision, prioritization | Roadmap reviews, sprint planning |
| Project Manager | Scrum Master, DevOps Engineer, all stakeholders | Timeline, risk, coordination | Status reports, meetings |
| Scrum Master | Developers, Project Manager | Team velocity, process | Ceremonies, metrics |
| UX/UI Designer | Product Manager, Developers, Technical Writer | User experience, design quality | Design reviews, prototypes |
| DevOps Engineer | Developers, Project Manager, Scrum Master | Infrastructure, deployments | Deployment plans, runbooks |
| Technical Writer | Developers, Product Manager, UX/UI Designer | Documentation quality | Doc reviews, release notes |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The Role Interaction Matrix helps clarify cross-functional dependencies and communication patterns.

