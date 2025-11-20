# OctoAcme — Role Responsibilities Quick Reference

## Purpose
Provide a quick lookup guide for role responsibilities across project phases to reduce confusion and improve accountability.

## How to Use
- Reference when assigning tasks
- Use during project planning to ensure all responsibilities are covered
- Review during retrospectives to identify gaps or overlaps
- Include in onboarding materials for new team members

---

## Responsibilities by Project Phase

### Phase 1: Project Initiation

| Role | Key Responsibilities |
|------|---------------------|
| **Product Manager** | • Define problem statement<br>• Draft success metrics<br>• Identify key stakeholders<br>• Create product vision |
| **Project Manager** | • Facilitate kickoff meeting<br>• Create project charter<br>• Establish communication plan<br>• Set up project tracking |
| **Scrum Master** | • Define team ceremonies<br>• Establish working agreements<br>• Set up retrospective cadence |
| **UX/UI Designer** | • Identify user research needs<br>• Plan design discovery<br>• Review existing design system |
| **DevOps Engineer** | • Assess infrastructure needs<br>• Identify deployment requirements<br>• Review security and compliance needs |
| **Technical Writer** | • Plan documentation deliverables<br>• Identify documentation gaps<br>• Establish doc review process |
| **Developers** | • Provide technical feasibility input<br>• Review technical requirements<br>• Identify dependencies |

### Phase 2: Planning

| Role | Key Responsibilities |
|------|---------------------|
| **Product Manager** | • Prioritize backlog<br>• Define acceptance criteria<br>• Validate user stories |
| **Project Manager** | • Create project plan and timeline<br>• Identify risks and dependencies<br>• Coordinate resource allocation |
| **Scrum Master** | • Facilitate sprint planning<br>• Help with estimation<br>• Identify potential impediments |
| **UX/UI Designer** | • Create wireframes and prototypes<br>• Conduct user research<br>• Plan usability testing |
| **DevOps Engineer** | • Plan infrastructure setup<br>• Define CI/CD pipeline requirements<br>• Plan monitoring strategy |
| **Technical Writer** | • Create documentation plan<br>• Draft initial templates<br>• Plan release note structure |
| **Developers** | • Estimate work items<br>• Review technical design<br>• Identify technical risks |
| **QA/Testing** | • Create test strategy<br>• Define test environments<br>• Plan test data needs |

### Phase 3: Execution & Tracking

| Role | Key Responsibilities |
|------|---------------------|
| **Product Manager** | • Answer product questions<br>• Review feature demos<br>• Adjust priorities as needed |
| **Project Manager** | • Track progress vs. plan<br>• Manage risks and issues<br>• Coordinate stakeholder updates |
| **Scrum Master** | • Facilitate daily standups<br>• Remove impediments<br>• Track velocity and metrics<br>• Shield team from distractions |
| **UX/UI Designer** | • Create final designs<br>• Conduct usability testing<br>• Review implementation<br>• Maintain design system |
| **DevOps Engineer** | • Build CI/CD pipelines<br>• Manage infrastructure<br>• Set up monitoring and alerting<br>• Support developers with tooling |
| **Technical Writer** | • Write user documentation<br>• Draft API documentation<br>• Create internal runbooks<br>• Review code comments |
| **Developers** | • Implement features<br>• Write tests<br>• Conduct code reviews<br>• Fix bugs |
| **QA/Testing** | • Execute test plans<br>• Report defects<br>• Verify fixes<br>• Validate acceptance criteria |

### Phase 4: Release & Deployment

| Role | Key Responsibilities |
|------|---------------------|
| **Product Manager** | • Approve release readiness<br>• Review release notes<br>• Plan feature announcements |
| **Project Manager** | • Coordinate release activities<br>• Communicate with stakeholders<br>• Manage release schedule |
| **Scrum Master** | • Facilitate release planning<br>• Track release readiness<br>• Support team through deployment |
| **UX/UI Designer** | • Final design QA in staging<br>• Verify UI implementation<br>• Document design decisions |
| **DevOps Engineer** | • Execute deployment<br>• Monitor system health<br>• Manage rollback if needed<br>• Verify post-deployment checks |
| **Technical Writer** | • Finalize release notes<br>• Publish documentation<br>• Update changelog<br>• Create migration guides |
| **Developers** | • Support deployment<br>• Monitor for issues<br>• Fix critical bugs<br>• Verify functionality |
| **QA/Testing** | • Run smoke tests<br>• Verify production deployment<br>• Validate critical paths<br>• Monitor quality metrics |

### Phase 5: Retrospective & Continuous Improvement

| Role | Key Responsibilities |
|------|---------------------|
| **Product Manager** | • Review success metrics<br>• Gather user feedback<br>• Plan next iterations |
| **Project Manager** | • Facilitate project closure<br>• Archive project artifacts<br>• Document lessons learned |
| **Scrum Master** | • Facilitate retrospective<br>• Track action items<br>• Measure improvement<br>• Share best practices |
| **UX/UI Designer** | • Analyze user feedback<br>• Review design effectiveness<br>• Identify UX improvements |
| **DevOps Engineer** | • Review deployment process<br>• Optimize pipelines<br>• Improve automation<br>• Update runbooks |
| **Technical Writer** | • Collect doc feedback<br>• Update documentation<br>• Improve doc processes<br>• Archive old versions |
| **Developers** | • Share technical learnings<br>• Propose improvements<br>• Update best practices |
| **QA/Testing** | • Review test coverage<br>• Improve test automation<br>• Document test learnings |

---

## Cross-Role Collaboration Points

### Code Review
- **Primary**: Developers
- **Optional**: DevOps Engineer (for infrastructure code), Technical Writer (for documentation)
- **Artifacts**: PR description, code comments, review comments

### Design Review
- **Primary**: UX/UI Designer, Product Manager
- **Secondary**: Developers (feasibility), Technical Writer (help text consistency)
- **Artifacts**: Design mockups, prototype links, feedback notes

### Release Planning
- **Primary**: Product Manager, Project Manager, DevOps Engineer
- **Secondary**: Scrum Master, Technical Writer, QA
- **Artifacts**: Release checklist, deployment plan, rollback procedures

### Sprint Planning
- **Primary**: Product Manager, Scrum Master, Developers
- **Secondary**: UX/UI Designer, DevOps Engineer, Technical Writer
- **Artifacts**: Sprint backlog, capacity planning, acceptance criteria

### Retrospective
- **Primary**: Scrum Master, entire delivery team
- **Artifacts**: Action items, improvement experiments, team health metrics

### Incident Response
- **Primary**: DevOps Engineer, Developers
- **Secondary**: Project Manager (communication), Product Manager (priority decisions)
- **Artifacts**: Incident report, post-mortem, action items

---

## Decision Authority by Topic

| Topic | Primary Decision Maker | Consulted | Informed |
|-------|----------------------|-----------|----------|
| Product priorities | Product Manager | Project Manager, Scrum Master | Stakeholders |
| Technical architecture | Developers (Tech Lead) | DevOps Engineer | PM, PdM |
| UI/UX design | UX/UI Designer | Product Manager, Developers | Stakeholders |
| Infrastructure changes | DevOps Engineer | Developers, Project Manager | Team |
| Documentation content | Technical Writer | Product Manager, Developers | Support, Customers |
| Deployment timing | Project Manager | DevOps Engineer, Product Manager | Stakeholders |
| Process changes | Scrum Master | Team | Project Manager |
| Scope changes | Product Manager | Project Manager, Stakeholders | Team |
| Sprint commitment | Developers (with Scrum Master) | Product Manager | Project Manager |

---

## Accountability Areas (RACI Model)

### Feature Development

| Activity | PM | PdM | SM | Dev | UX | DevOps | TW | QA |
|----------|----|----|----|----|----|----|----|----|
| Define requirements | I | R | C | C | C | I | C | I |
| Design UI/UX | I | C | I | C | R | I | C | I |
| Implement code | I | I | I | R | I | C | I | I |
| Write tests | I | I | I | R | I | I | I | C |
| Code review | I | I | I | R | I | C | I | I |
| QA testing | I | C | I | C | I | I | I | R |
| Write docs | I | C | I | C | I | I | R | I |
| Deploy to prod | C | C | I | C | I | R | I | I |

**Legend**: R = Responsible (does the work), A = Accountable (final approver), C = Consulted, I = Informed

*Note: PM = Project Manager, PdM = Product Manager, SM = Scrum Master, Dev = Developer, UX = UX/UI Designer, TW = Technical Writer, QA = QA/Testing*

---

## Common Questions & Clarifications

### "Who approves feature specifications?"
**Answer**: Product Manager owns and approves feature specifications. Developers and UX/UI Designer should be consulted before approval.

### "Who decides when we're ready to release?"
**Answer**: Product Manager makes go/no-go decision based on input from QA (quality), DevOps Engineer (technical readiness), and Project Manager (dependencies/risks).

### "Who handles production incidents?"
**Answer**: DevOps Engineer leads technical response. Project Manager coordinates stakeholder communication. Product Manager makes priority decisions for fixes.

### "Who prioritizes bug fixes vs. new features?"
**Answer**: Product Manager prioritizes with input from Developers (technical debt impact), UX/UI Designer (user impact), and Project Manager (resource availability).

### "Who owns the sprint backlog?"
**Answer**: The development team owns the sprint backlog. Product Manager owns product backlog prioritization. Scrum Master facilitates but doesn't dictate.

### "Who decides on design changes during implementation?"
**Answer**: Minor changes: UX/UI Designer with Developer. Major changes: UX/UI Designer with Product Manager approval.

### "Who manages the risk register?"
**Answer**: Project Manager maintains the register. Risk owners (varies by risk type) are responsible for mitigation. All roles contribute to risk identification.

---

## Role Boundaries & Common Overlaps

### Project Manager vs. Scrum Master
- **PM**: External coordination, stakeholder management, budget/timeline, overall project success
- **SM**: Internal team facilitation, impediment removal, agile practices, team health and velocity
- **Overlap**: Both care about delivery and team effectiveness; PM focuses outward, SM focuses inward

### Product Manager vs. UX/UI Designer
- **PdM**: What to build and why (business value, user problems)
- **UX**: How users will interact with it (user experience, interface design)
- **Overlap**: Both advocate for users; PdM defines success metrics, UX validates through research

### DevOps Engineer vs. Developers
- **DevOps**: Infrastructure, pipelines, deployment automation, production operations
- **Dev**: Application code, business logic, features
- **Overlap**: Both write code; DevOps focuses on platform/tooling, Devs focus on product features

### Technical Writer vs. Developers
- **TW**: User-facing documentation, communication clarity
- **Dev**: Code implementation, technical accuracy
- **Overlap**: Both contribute to documentation; TW owns content quality, Devs provide technical accuracy

---

## When to Involve Each Role

| Situation | Primary Roles to Involve | Timing |
|-----------|-------------------------|--------|
| New feature request | Product Manager, Project Manager | Immediately |
| Technical architecture decision | Developers, DevOps Engineer | During design phase |
| User experience issue | UX/UI Designer, Product Manager | Immediately |
| Production incident | DevOps Engineer, Developers | Immediately |
| Scope change request | Product Manager, Project Manager | Before commitment |
| Timeline concern | Project Manager, Scrum Master | As soon as identified |
| Documentation gap | Technical Writer, Developers | During or before release |
| Process inefficiency | Scrum Master, Team | During retrospective |
| Deployment issue | DevOps Engineer, Project Manager | Immediately |
| Quality concern | QA, Developers | As soon as identified |
