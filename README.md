## Goals:

# Create python bootstrap script
Should create storage account for state file and access policies for said account

# Create ci/cd github actions to deploy pulumi configs
Ideally, ci shoul trigger on push. creating an output that is stored as an artifact.
This artifact can be deployed via pipeline, which are either triggered manually to
a as part of merge to dev

# Create keyvault to store all creds

# Create VNET

# Create postgres db with hello world table

# Configure sql role managment somehow

# Create azure function that talks with database

## Extra credit
Attempt to use re-base instead of merge
Attempt to keep a clean git history in the master branch (no squash)

## Git strategy
Feature branches
Single occupancy branches
After testing and before opening PRs, rebase and force push to remote feature branch