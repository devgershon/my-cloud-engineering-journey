# Skills: Terraform

**Order in the tooling block:** 2nd  
**Period:** More than a month of focused study before using it on real projects (within the late 2025 – early 2026 block)  
**Sources:** YouTube Terraform series, HashiCorp tutorials and docs

---

## What I covered

- Providers, resources, and data sources
- Variables, outputs, and locals
- State and remote state concepts
- Modules and reusable patterns
- Multiple providers / aliases (e.g. us-east-1 for ACM with CloudFront)
- IAM roles, policies, and least privilege in Terraform
- Packaging and deploying Lambda with archive_file
- API Gateway, DynamoDB, S3, CloudFront, and related resources
- Planning, applying, and reading plans carefully

---

## How I use it

Terraform is the main Infrastructure as Code tool across the portfolio:

- Project 001 — full static site stack (S3, CloudFront, OAC, ACM)
- Project 002 — DynamoDB, IAM, Lambda, API Gateway, log groups

I spent the extra time on Terraform first so that when I started building real projects, the infrastructure was defined as code from day one instead of clicked together in the console.
