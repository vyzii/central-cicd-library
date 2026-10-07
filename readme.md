# central-cicd-library

This is a library containing reusable GitHub Actions Workflows.

## Reusable workflows

| Workflow | Source | Description |
| --- | --- | --- |
| [Python Lint](./docs/python-lint.md) | [Source](./.github/workflows/python-lint.yaml) | Checks code quality and formatting with Ruff. |
| [Python Test](./docs/python-test.md) | [Source](./.github/workflows/python-test.yaml) | Runs tests with pytest. Uses uv to manage dependencies. |
| [Python Bandit](./docs/python-bandit.md) | [Source](./.github/workflows/python-bandit.yaml) | Performs SAST scanning for common security issues via Bandit. |
| [Python Trivy](./docs/python-trivy.md) | [Source](./.github/workflows/python-trivy.yaml) | Performs SCA scanning for vulnerabilities in dependencies via Trivy. |

### todo:

- Create docs for all current workflows
- Create release for current actions
- Add Terraform workflows