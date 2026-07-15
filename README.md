# IdeaForge

IdeaForge is a portfolio project for turning a product idea into a traceable release.

The service will manage projects, requirements, tasks, architecture decisions, and release history. It will be developed incrementally from a local HTTP API into an observable AWS deployment.

## Status

Repository initialization is in progress. Application code has not been implemented yet.

## Prerequisites

- Node.js 24.18.0 LTS
- npm 11.16.0
- Docker Desktop

## Planned stack

- TypeScript
- Node.js
- React
- PostgreSQL
- Docker Compose
- GitHub Actions
- AWS
- Terraform

## Development principles

- Every change starts from an issue with acceptance criteria.
- Changes are submitted through small pull requests.
- Tests and documentation are part of the deliverable.
- Secrets are never committed.
- Architecture decisions are recorded in ADRs.

## Documentation

Architecture decision records will be stored in `docs/adr/`.
