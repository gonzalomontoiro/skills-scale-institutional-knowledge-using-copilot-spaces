# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner (assign to appropriate role: PM, DevOps Engineer, UX/UI Designer, etc.)
- Mitigation plan
- Status

### Common Risk Owners by Category
- **Technical/Infrastructure Risks**: DevOps Engineer
- **Design/UX Risks**: UX/UI Designer
- **Process/Team Risks**: Scrum Master
- **Documentation Risks**: Technical Writer
- **Scope/Timeline Risks**: Project Manager
- **Product/Market Risks**: Product Manager

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, customers)
- Provide regular updates (weekly or milestone-based)
  - PM coordinates overall project communication
  - Technical Writer drafts customer-facing communications
  - UX/UI Designer shares design previews with relevant stakeholders
  - DevOps Engineer provides infrastructure and deployment updates
- Use a single source of truth (project README or release doc) for status
- Create stakeholder-specific views (use stakeholder checklist template)

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths

### General Issues
1. **Team-level** (Scrum Master facilitates)
   - Daily standup identification
   - Immediate team resolution attempts
   - Role-specific escalation (e.g., DevOps for infrastructure, UX Designer for design issues)

2. **Project Manager** 
   - Cross-team dependencies
   - Resource constraints
   - Timeline impacts
   - Coordinates with relevant specialists (DevOps Engineer, UX/UI Designer, Technical Writer)

3. **Product Lead**
   - Scope changes
   - Priority conflicts
   - Strategic decisions

4. **Sponsor**
   - Business-impacting issues
   - Budget/resource escalations
   - Go/no-go decisions

### Specialized Escalations
- **Infrastructure/Deployment Issues**: Developer → DevOps Engineer → Platform Team → Infrastructure Lead
- **Design/UX Concerns**: Developer/PM → UX/UI Designer → Design Lead → Product Lead
- **Documentation Gaps**: Any team member → Technical Writer → Documentation Lead
- **Process/Team Issues**: Team member → Scrum Master → PM → HR/Leadership
- **Security Incidents**: Follow security incident runbook, notify Security on-call immediately (DevOps Engineer coordinates technical response)
