# markers

## Notes for projects that use CI/CD

- Keep workflows in version control (for example, under `.github/workflows/`).
- Run linting and tests on every pull request.
- Use protected branches with required status checks.
- Store secrets in the CI/CD provider's secret manager, not in source code.
- Deploy from tagged or reviewed commits only.
