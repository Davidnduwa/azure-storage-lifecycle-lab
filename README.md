# Azure Storage: Hot vs Cool vs Archive + Lifecycle Rules

This repo contains my AZ-900-friendly lab:
- Storage Account with secure defaults
- Containers: `logs/` and `images/`
- Lifecycle rules:
  - `logs/` → Cool after 30 days, delete after 365
  - `images/` → Archive after 90 days of no access

## Why it matters
Cost control, real-world data lifecycle, and AZ-900 fundamentals.

## Deliverables
- Polished LinkedIn post (with emojis): [/posts/Azure_Storage_Lifecycle_LinkedIn_Post_Emojis.pdf](./posts/Azure_Storage_Lifecycle_LinkedIn_Post_Emojis.pdf)
- Pro one-pager with workflow figure: [/posts/Azure_Storage_Lifecycle_Post_Pro_Workflow.pdf](./posts/Azure_Storage_Lifecycle_Post_Pro_Workflow.pdf)

## Screenshots
