# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
  - Include UX/UI review for interface changes
  - Pass to QA column after merge for acceptance testing
- QA Workflow:
  - QA Specialist validates against acceptance criteria
  - Execute test cases (manual and automated as needed)
  - Report defects and retest after fixes
  - Sign off on feature completion before marking as Done

## Quality & Testing
- Unit tests for new logic (Developer responsibility)
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed (QA Specialist)
- Usability testing for significant UI changes (UX/UI Designer + QA Specialist)
- Documentation validation (Technical Writer ensures accuracy)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor/Executive Stakeholder escalation for business-impacting issues or resource needs

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] QA test cases created and maintained
- [ ] UX/UI design review process established (if applicable)
- [ ] Documentation updated alongside features (if Technical Writer assigned)
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
