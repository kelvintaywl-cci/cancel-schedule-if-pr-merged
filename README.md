# cancel-schedule-if-pr-merged

Sample project to showcase how to cancel a (scheduled) pipeline if pull-requests (PRs) are merged within last 24 hour.

## Requirements

You would need to add the following project environment variables to your CircleCI project:

- `GITHUB_TOKEN` : GitHub API token (required to list PRs)
- `CIRCLE_TOKEN` : CircleCI user API token (required to cancel workflow)
