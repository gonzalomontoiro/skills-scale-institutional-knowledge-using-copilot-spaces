# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
  - Include UX/UI Designer for design review and feedback
  - DevOps Engineer provides infrastructure and deployment updates
  - Technical Writer shares documentation progress
- Demo/Review at the end of each sprint or milestone
  - Scrum Master facilitates demo and retrospective
  - UX/UI Designer demonstrates new UI/UX features
  - Technical Writer presents updated documentation

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Design Review, Ready, In Progress, In Review, QA, Done
  - UX/UI Designer moves items through Design Review column
  - DevOps Engineer monitors CI/CD pipeline health
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Include design mockup links when relevant (from UX/UI Designer)
  - Run automated tests and linting in CI before requesting review (DevOps Engineer maintains pipelines)
  - Require at least one approval before merging (or team-defined policy)
  - Technical Writer reviews PRs affecting user-facing features for documentation needs

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates)
  - Scrum Master attempts to remove impediments
  - DevOps Engineer addresses infrastructure/pipeline blockers
  - UX/UI Designer resolves design ambiguities
- Level 2: PM escalates to Product Lead and dependent teams
  - Scrum Master coordinates with PM on cross-team dependencies
  - DevOps Engineer escalates infrastructure issues to platform teams
- Level 3: Sponsor-level escalation for business-impacting issues
  - PM coordinates with Scrum Master on impact assessment

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (DevOps Engineer)
- [ ] Design system and components documented (UX/UI Designer)
- [ ] Regular demos scheduled (Scrum Master facilitates)
- [ ] Risk register updated weekly (PM with input from all roles)
- [ ] Documentation updated with each release (Technical Writer)
- [ ] Monitoring and alerting configured (DevOps Engineer)
