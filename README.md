# Azure Storage: Hot vs Cool vs Archive + Lifecycle Rules

![Workflow](./assets/azure_storage_lifecycle_workflow.png)

This repo contains my AZ-900-friendly lab for optimizing Blob Storage with lifecycle policies.

## What’s inside
- Storage Account with secure defaults (private containers, soft delete, optional versioning)
- Containers: `logs/` and `images/`
- Lifecycle rules:
  - `logs/` → Cool after 30 days, delete after 365
  - `images/` → Archive after 90 days of no access

## Why it matters
- 💸 Cost control via automatic tiering and cleanup  
- 🧭 Real-world data lifecycle (hot → cool → archive)  
- 📘 Reinforces AZ-900 fundamentals: governance, cost management, monitoring

## Deliverables
- Pro one-pager: [posts/Azure_Storage_Lifecycle_Post_Pro_Workflow.pdf](./posts/Azure_Storage_Lifecycle_Post_Pro_Workflow.pdf)  
- Emoji LinkedIn post: [posts/Azure_Storage_Lifecycle_LinkedIn_Post_Emojis.pdf](./posts/Azure_Storage_Lifecycle_LinkedIn_Post_Emojis.pdf)  
- LinkedIn caption (Markdown): [linkedin/azure-storage-lifecycle-post.md](./linkedin/azure-storage-lifecycle-post.md)

## Screenshots
See [/assets](./assets) for the workflow figure and portal screenshots.

## How to use
- Recreate the storage account and lifecycle rules in your own subscription.
- Swap prefixes (e.g., `logs/`, `images/`) for your data layout.
- Update thresholds based on retention/compliance needs.

## License
Choose an appropriate license (MIT for code, CC BY 4.0 for documents), or dual-license if you have both.
