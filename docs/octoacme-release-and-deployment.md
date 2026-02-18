# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- QA Specialist sign-off on acceptance testing
- Passing CI and security scans
- Technical documentation completed and reviewed (if Technical Writer assigned)
- Release notes drafted
- UX/UI validation completed for interface changes (if applicable)
- Rollback / mitigation plan documented
- Smoke tests prepared
- Sponsor/Executive Stakeholder informed of release timeline

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] QA sign-off obtained
- [ ] Documentation published or updated (user guides, API docs, help content)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support (including Sponsor/Executive Stakeholder)
- [ ] Update release tracking in project management tools

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
