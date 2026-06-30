# ADR-001: Use Java 21

## Status

Accepted

## Context

The Ledger Service is intended to represent a production-style backend service for a fintech environment.

The project should use a modern Java version while staying aligned with enterprise backend job requirements.

## Decision

We will use **Java 21** as the main programming language version.

## Rationale

Java 21 is a Long-Term Support version and is widely adopted in modern backend systems.

It allows the project to demonstrate current Java knowledge while remaining relevant to enterprise environments that value stability and maintainability.

## Consequences

Positive:

- Aligns the project with modern Java backend roles.
- Supports current Spring Boot versions.
- Demonstrates knowledge beyond legacy Java versions.

Negative:

- Some companies still use Java 8, 11 or 17.
- The developer must be aware of version compatibility when discussing the project in interviews.
