# SmartStock-INZOX
SmartStock is the P02 Smart Inventory Management System.

## Working on a task

1. Start from the latest `develop`.
2. Create a branch named `feature/<task-id>-<short-description>`.
   Example: `feature/P02-FE-01-scaffolding`.
3. Include the task ID in each commit message.
   Example: `chore(client): scaffold React app [P02-FE-01]`.
4. Open a pull request with `develop` as the base branch.
   Describe the change and how you verified it.

Follow the agreed peer-review assignments. DevOps-only changes are
exempt from human review. Once CI checks are enabled, they must pass
before merging, including for DevOps changes.

## Production branch

`main` is protected. Release and hotfix changes enter `main` through
a pull request with mentor approval.

## Environment variables and secrets

Use `.env.example` to document variable names and example values.
Keep real credentials in local `.env` files. Store CI/CD credentials
in GitHub Actions secrets. Never commit passwords, tokens, or database
connection strings containing credentials.
