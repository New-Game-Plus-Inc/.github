# Welcome to New Game Plus, Inc.

This is the central hub for our engineering standards, onboarding, and project guidelines. All internal teams and external partners are expected to follow these protocols.

---

## Quick Links
- [Engineering Standards](../standards/ENGINEERING.md): Coding style, PR protocols, and quality bars.
- [PR Template](../.github/PULL_REQUEST_TEMPLATE.md): Template for all pull requests.
- [Security Policy](../standards/SECURITY.md): How we handle vulnerabilities and secrets.
- [Onboarding for Partners](../onboarding/EXTERNAL_TEAMS.md): How to get set up with our environment.

---

## Global Standards Summary

### Pull Request (PR) Protocol
All repositories require a Pull Request for any code change. 
- A minimum of one approved review from the core team is required.
- CI/CD checks must pass before merging.
- PR titles must include the Jira Ticket ID.
- Branch names must follow the format: `dev-[feature-name]-[Jira ID]`
- Use imperative mood for commit messages: "Add feature" not "Added feature"
[View Detailed PR Guidelines](../standards/ENGINEERING.md)

### Issue & PRs
To maintain parity with our Jira boards, please use the following labels on all GitHub Issues and PRs:
- **bug**: Functional errors or regressions (Maintenance Epic).
- **story**: New feature development - linked to a Jira Child (Development Epic).
- **task**: Individual work items within a feature (Sub-Task).
- **blocked**: External dependencies preventing progress.

### Communication
- Technical discussions should occur within GitHub Issues or Discussions.
- Urgent blockers should be reported via the established Slack/Teams channel.

---

## Collaboration Rules
1. **Always use PR Template**: Every PR must fill out the provided checklist.
2. **Outside Collaborators**: Please refer to the [Partner Guidelines](../onboarding/EXTERNAL_TEAMS.md) before starting your first ticket.
3. **Internal Review**: Internal leads are responsible for final merges to protected branches.
