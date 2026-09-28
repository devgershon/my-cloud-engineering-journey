# Skills: GitHub Actions

**Order in the tooling block:** 3rd  
**Period:** Within the late 2025 – early 2026 tooling block (~3–4 weeks)  
**Sources:** YouTube GitHub Actions / CI/CD series, official GitHub Actions docs

---

## What I covered

- Workflows, jobs, and steps
- Triggers (push, pull request, manual)
- Runners and environment setup
- Secrets and environment variables
- Multi-job pipelines (test then deploy)
- Deploying to AWS (S3 sync, Lambda update-function-code, etc.)
- Using Actions to gate deploys on test success

---

## How I use it

Both live portfolio projects use GitHub Actions:

- Project 001 — sync static files to S3 and invalidate CloudFront on push to main
- Project 002 — run pytest (with moto), then update the Lambda function code only if tests pass
