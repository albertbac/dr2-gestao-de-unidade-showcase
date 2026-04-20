# Architecture

## High-level architecture
- Classification: CORE HEALTHCARE / CLINICAL AI
- Category: clinical-ai
- Confidence: HIGH
- Exposure risk: MEDIUM

```mermaid
    flowchart LR
        A[Web dashboard]
    B[Indicator service]
    C[Action-plan orchestration]
    D[Review and audit layer]
    E[Reporting surface]
        A --> B
    B --> C
    C --> D
    D --> E
```

## Public-safe component view
- Web dashboard
- Indicator service
- Action-plan orchestration
- Review and audit layer
- Reporting surface

## Boundary notes
- This diagram is intentionally high level.
- No internal routes, private services, live storage names, or deployment details are published.
- The public-safe view is limited to product layers that can be discussed without weakening security.
