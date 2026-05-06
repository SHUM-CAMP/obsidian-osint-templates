# Metadata Contract

Use this frontmatter schema for operational notes (`Cases`, `Entities`, `Sources`, `Evidence`, `Reports`).

```yaml
---
case_id:
status: intake
assignee:
priority: medium
language: en
source_reliability:
verification_state:
last_reviewed:
tags: []
---
```

## Naming conventions
- Cases: `case-YYYYMMDD-shortslug`
- Person entities: `ent-person-shortslug`
- Company entities: `ent-org-shortslug`
- Sources: `src-platform-shortslug`
- Evidence: `evidence-YYYYMMDD-shortslug`

## Status values
- `intake`
- `assigned`
- `investigating`
- `review`
- `approved`
- `published`
