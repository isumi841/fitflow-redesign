# ADR-001 – FitFlow Technology Stack

## Status
Accepted

## Context
FitFlow requires Android, iOS, and web support, high performance, real-time community features, secure authentication, structured health/fitness data handling, and AI-powered recommendations and nutrition analysis.

## Decision
The selected stack is:

- React Native + React Native Web
- Node.js / NestJS
- PostgreSQL
- Firebase Authentication
- Python / FastAPI

## Rationale
This combination provides a strong balance of performance, scalability, development speed, security, cost, AI/ML support, real-time functionality, and maintainability.

## Consequences

### Positive
- High frontend code reuse
- Strong real-time backend support
- Reliable relational data handling
- Simplified authentication management
- Strong Python AI/ML ecosystem

### Trade-offs
- Multiple technology ecosystems must be maintained
- Some React Native features may still require native modules
- Firebase introduces external-service dependency
- AI services and the main backend need clear API boundaries
