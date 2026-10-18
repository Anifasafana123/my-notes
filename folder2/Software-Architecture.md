# Software Architecture Notes

## What is it?
The high-level structure of a system: components, how they connect, and the rules behind those decisions.

## Common Architecture Styles
- **Monolith**: one deployable unit. Simple, but hard to scale parts independently.
- **Microservices**: small independent services. Flexible, but complex to manage.
- **Layered**: presentation, business logic, data layers.
- **Event-driven**: services communicate through events/queues.
- **Serverless**: run functions without managing servers.

## Design Principles
- **SOLID**: Single responsibility, Open/closed, Liskov, Interface segregation, Dependency inversion
- **DRY**: Don't Repeat Yourself
- **KISS**: Keep It Simple
- **Separation of concerns**

## Quality Attributes
Scalability, Availability, Performance, Security, Maintainability

## Common Patterns
MVC, Repository, Factory, Singleton, Observer, API Gateway, CQRS

## Tip
Every architecture choice is a **trade-off**. Document decisions (ADR - Architecture Decision Records).
