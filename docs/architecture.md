# Koraal Platform – Architecture

## Overview

Koraal is composed of several components:

- Mobile application
- Web application
- Public API
- Backend services
- Infrastructure (cloud)

The API exposes the platform capabilities to client applications, while the backend contains the business logic and integrations.

---

## High-level architecture

Mobile App / Web App
        |
        v
       API
        |
        v
    Backend Services
        |
        v
Database / External services / Queues

---

## Repository structure

apps/
- mobile
- web

services/
- api
- backend

infrastructure/
- cloud infrastructure
- deployment configuration

docs/
- architecture
- specifications

scripts/
- development utilities

---

## Responsibilities

### API
- Authentication
- Request validation
- Routing
- Response formatting

### Backend
- Business logic
- Workflows
- External integrations
- Data processing

---

## Infrastructure

Planned stack:

- Cloud: AWS
- API hosting: containerized services
- Database: TBD
- CI/CD: GitHub Actions