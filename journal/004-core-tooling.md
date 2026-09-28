# 004 – Core tooling: Docker, Terraform, GitHub Actions, FastAPI

**Period:** Started late 2025, finished early 2026

---

## What I did

I worked through structured courses and the official docs for four tools, in this order:

1. **Docker** — containers, images, Dockerfiles, Compose, volumes, networking
2. **Terraform** — providers, resources, state, IAM, multi-region patterns, packaging Lambda (more than a month before real projects)
3. **GitHub Actions** — workflows, secrets, test-then-deploy pipelines
4. **FastAPI** — Python APIs, Pydantic models, routing, docs

Docker, GitHub Actions, and FastAPI each took roughly three weeks to a month. Terraform took longer on purpose — I wanted to understand it properly before using it to build real infrastructure.

---

## Why it matters

These four sit underneath the live projects:

- Terraform defines the infrastructure for the static site and the serverless API
- GitHub Actions deploys both and runs tests before the API goes out
- Docker is the base for the next project (containers on ECS)
- FastAPI gives a solid Python API foundation alongside the pure Lambda style

Without this block, the projects would have been thinner and harder to extend.

---

## What changed after this

I stopped treating infrastructure as something you click in the AWS console and started treating it as code. Deploys became repeatable. Tests became part of the pipeline instead of an afterthought.

---

*Next: keep using these tools on Projects 003 and 004 and add deeper notes where something new comes up.*
