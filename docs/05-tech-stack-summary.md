# Recommended Technology Stack

## Final Recommendation

- **React Native** – Android, iOS, and web with reusable code and fast development.
- **Node.js / NestJS** – API development and efficient handling of real-time features.
- **PostgreSQL** – Structured fitness/health data, complex queries, relationships, and strong consistency.
- **Firebase Authentication** – Secure, scalable, low-maintenance user authentication.
- **Python / FastAPI** – AI/ML integration for workout recommendation and nutrition analysis.

## Architecture Integration

The client applications communicate with the Node.js/NestJS backend through HTTPS REST APIs and WebSockets. The backend communicates with the Python/FastAPI AI microservices through REST APIs. PostgreSQL stores structured application data, while Firebase Authentication provides login and token management. External services provide media storage, push notifications, maps, and video delivery.
