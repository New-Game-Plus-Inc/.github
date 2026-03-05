# Engineering Standards

## Coding Standards
- **Language Consistency**: TBD
- **Formatting**: TBD

## Pull Requests
- **Branching**: Format new branches as: [Jira ID]-[feature-name]-dev.  
- **Descriptions**: Provide a clear "why" behind the change in the PR body.
- **PR Commits**: Use imperative mood: "Add user authentication" instead of "Added user authentication."

## Commit Example Of Branch:
- **Branch Commits**: Use imperative mood with jira ID. 
Example: "ODY2-108: Fix- payment stripe issue fix"
Example: "ODY2-108: Update- payment stripe id in db"


- **Template**: All PRs must use the [PR Template](../.github/PULL_REQUEST_TEMPLATE.md).
- **Creating PRs**: `gh pr create --title "Add feature [JIRA-123]" --body-file .github/PULL_REQUEST_TEMPLATE.md`
- **Review Requests**: `gh pr edit <PR-number> --add-reviewer <username>` (Example: `gh pr edit 23 --add-reviewer imranodessy`)


## Jira Format (Epic / Child / Sub-Task)
- Epic: Two categories; maintenance, and Development
- Child: Feature
- Sub-Task: Individual work items within a feature

## Documentation
- All public APIs must be documented.
- READMEs must be kept up to date with setup instructions.
- Project-level wikis are for issue tracking and specific dev-logs only.
