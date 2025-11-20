# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by DevOps Engineer)
- Release notes drafted (Technical Writer with input from Product Manager)
- User documentation updated (Technical Writer)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared and passed (QA with DevOps Engineer)
- Design QA completed for UI changes (UX/UI Designer)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — coordinated by PM and DevOps Engineer
- [ ] Backup or snapshot (if applicable) — DevOps Engineer
- [ ] Deploy to staging and run smoke tests — DevOps Engineer with QA
- [ ] Design review in staging environment — UX/UI Designer
- [ ] Deploy to production (automated pipeline preferred) — DevOps Engineer
- [ ] Run post-deploy verifications — DevOps Engineer and QA
- [ ] Verify documentation is live and accurate — Technical Writer
- [ ] Announce release to stakeholders and support — PM with Technical Writer
- [ ] Monitor metrics and error rates — DevOps Engineer

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - DevOps Engineer triggers incident response and notifies on-call
  - DevOps Engineer executes rollback to last known-good release if necessary
  - PM coordinates communication with stakeholders
  - DevOps Engineer leads root cause triage with development team
  - Technical Writer updates incident communication and post-mortem
  - Scrum Master facilitates blameless post-mortem and captures action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
