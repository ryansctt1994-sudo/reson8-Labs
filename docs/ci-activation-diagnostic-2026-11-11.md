# CI activation diagnostic — 2026-11-11

This documentation-only file exists to create an isolated pull-request event for investigating why the repository has GitHub Actions workflow definitions but zero retained workflow runs.

Scope:
- Test whether existing pull_request CI workflows are allowed to execute.
- Do not modify default-branch source, dependencies, workflow definitions, security gates or publishing credentials.
- Preserve any failed or skipped results as observations.
- Do not interpret a green or skipped result as evidence of production readiness.
- Do not merge this probe; close after the diagnostics are documented.

Base observed at creation: f88c5a3536449d9db59b3601d44e2e2210bbbc4b
