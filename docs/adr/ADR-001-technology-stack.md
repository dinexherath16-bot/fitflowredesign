# ADR-001: Technology Stack for FitFlow

## Status

Accepted

## Context

FitFlow requires a scalable, secure and cross-platform architecture
supporting Android, iOS and web platforms together with AI/ML and
real-time features.

## Decision

The selected technology stack is:

- Flutter for frontend
- NestJS for backend
- PostgreSQL for database
- Supabase Auth for authentication
- Python/FastAPI for AI/ML
- Redis for caching
- WebSockets for real-time communication

## Rationale

This technology combination provides cross-platform support,
code reusability, scalability, structured data management,
AI/ML integration and maintainability.

## Consequences

The architecture contains multiple services that need to be
maintained. However, separating the services allows individual
components to be developed and scaled independently.
