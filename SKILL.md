---
name: hermes-skill-understand
description: Analyze a codebase into an interactive knowledge graph of components and relationships. Use when a user asks for this workflow or a closely related task.
---

# Understand

Analyze a codebase into a navigable knowledge graph of modules, entry points, data flows, dependencies, and ownership boundaries.

## Workflow

1. Scan the repository without executing untrusted code.
2. Identify languages, packages, entry points, services, stores, interfaces, tests, and deployment configuration.
3. Extract direct relationships from imports, calls, routes, schemas, and configuration.
4. Label inferred relationships and confidence separately from direct evidence.
5. Generate a compact graph plus an onboarding summary and open questions.
6. Exclude secrets, generated noise, and irrelevant vendor code.

Make every graph edge traceable to a file or command result.
