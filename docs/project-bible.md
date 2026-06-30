# Project Bible

## International Backend Engineer Journey

### Project

**NorthBridge Ledger Service**

### Company Context

NorthBridge Financial is a fictional fintech company based in the United States.

The company provides payment infrastructure for businesses that need reliable account movement tracking, balance calculation and financial auditability.

### Role

You are acting as a **Backend Software Engineer** in the **Payments Platform** team.

### Product Mission

Build a ledger service capable of recording financial movements safely, consistently and with strong auditability.

### Engineering Principles

- Prefer clarity over cleverness.
- Business rules must be explicit.
- Financial values must never use floating point types.
- Data consistency matters more than convenience.
- Every relevant decision should be documented.
- Tests are part of the feature, not optional work.
- Operational concerns matter: logs, metrics and errors must be designed intentionally.

### Initial Scope

The first version of the service will support:

- Account registration
- Credit and debit entries
- Balance calculation
- Transaction statement
- Idempotent transaction creation
- Standardized error responses
- Integration tests
- Documentation and architecture records

### Out of Scope for the First Phase

- Android or mobile development
- Real payment provider integration
- Real customer data
- Cloud deployment
- Kubernetes

### Learning Strategy

The project will introduce tools gradually:

- GitHub workflow first
- Java and Spring Boot foundation
- PostgreSQL and Flyway when persistence is needed
- Docker when local infrastructure is needed
- RabbitMQ when asynchronous processing is needed
- Observability when the service has behavior worth monitoring

### Sprint 0 Goal

Prepare the repository, workflow and documentation before implementing business features.
