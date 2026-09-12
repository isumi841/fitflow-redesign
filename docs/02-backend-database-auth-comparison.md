# Activity 2 – Backend, Database and Authentication Comparison

## Backend Options

| Criteria | Node.js / Express | Python / FastAPI | Go (Gin/Fiber) |
|---|---|---|---|
| Performance | Good; strong for I/O-heavy real-time workloads | Good; async ASGI support | Excellent; compiled and low latency |
| AI/ML Integration | Moderate; typically calls Python/cloud ML services | Excellent; native Python AI/ML ecosystem | Limited native ML ecosystem |
| Real-Time Capability | Excellent; WebSocket and Socket.io ecosystem | Good; WebSockets supported | Good; strong concurrency |
| Developer Availability | Very large talent pool | Large and growing | Smaller talent pool |
| Ecosystem | Huge npm ecosystem | Rich AI/scientific ecosystem | Smaller ecosystem |
| Cost / Scaling | Low to moderate | Low to moderate | Very efficient resource usage |

**Recommended backend:** Node.js / NestJS

## Database Options

| Criteria | PostgreSQL | MongoDB | Firebase / Firestore | DynamoDB |
|---|---|---|---|---|
| Data Model | Relational; suitable for structured records | Document-based | Document-based | Key-value/document |
| Scalability | Strong; replicas/sharding possible | Strong horizontal scaling | Managed automatic scaling | Managed automatic scaling |
| Query Performance | Excellent for joins, analytics, reporting | Strong for simple document queries | Strong for simple real-time reads/writes | Very fast key-based access |
| Health Data Handling | Strong ACID consistency | Requires extra consistency care | Convenient but less suited to strict relational integrity | Strong consistency options |
| Real-Time Support | Usually needs additional mechanisms/services | Change streams available | Built-in listeners | Streams available |
| Cost / Maintainability | Predictable managed/self-managed options | Managed Atlas available | Pay-as-you-go | Pay-per-request |

**Recommended database:** PostgreSQL

## Authentication Options

| Criteria | Firebase Auth | AWS Cognito | Auth0 | Supabase Auth |
|---|---|---|---|---|
| Authentication | Email/password, phone, Google, Apple | Password/social/enterprise | Social, passwordless, MFA | Email/password, magic links, social |
| Security | Secure tokens, rules, encryption support | Strong IAM and encryption | MFA and threat-detection features | JWT + Row-Level Security |
| Authorization | Firebase Security Rules | IAM-based access control | Strong RBAC | Role/database security |
| Scalability | Automatic scaling | Enterprise scale | Highly scalable | Good cloud scalability |
| Real-Time Support | Strong with Firebase ecosystem | Usually needs extra AWS services | External service usually needed | Supabase Realtime |
| Cost / Maintenance | Low cost and easy maintenance | More complex | Can become expensive | Cost-effective |

**Recommended authentication:** Firebase Authentication
