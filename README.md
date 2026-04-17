# engineerblue-labs/.github

This repository is the organization-wide `.github` repository for EngineerBlue Labs.

It centralizes default community health files, templates, and reusable automation that can be shared across repositories in the organization.

## What this repo demonstrates

- Community health defaults (`CODE_OF_CONDUCT`, `CONTRIBUTING`, `SECURITY`, `SUPPORT`)
- Organization profile README (`profile/README.md`)
- Default issue templates and pull request template
- CODEOWNERS and funding metadata
- Dependabot configuration
- Reusable GitHub Actions workflow
- Workflow template for bootstrapping new repositories
- Composite action for shared setup logic

## How to use

### Community health defaults
GitHub automatically uses these files as defaults for repositories that do not define their own:

- `/CODE_OF_CONDUCT.md`
- `/CONTRIBUTING.md`
- `/SECURITY.md`
- `/SUPPORT.md`

### Profile README
The organization profile content is sourced from:

- `/profile/README.md`

### Templates and defaults
- Issues: `/.github/ISSUE_TEMPLATE/*`
- Pull requests: `/.github/PULL_REQUEST_TEMPLATE.md`
- CODEOWNERS: `/.github/CODEOWNERS`

### Actions sharing
- Reusable workflow: `/.github/workflows/reusable-ci.yml`
- Workflow template: `/.github/workflow-templates/*`
- Composite action: `/.github/actions/setup-node-project/action.yml`
