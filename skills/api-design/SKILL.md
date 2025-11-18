---
name: api-design
description: Master API design and development. Covers REST, GraphQL, gRPC, API security, versioning, documentation, and best practices.
---

# API Design Skill

Master API design and development practices.

## REST APIs

### Core Principles
- **Resource-Based** - URLs represent resources
- **HTTP Methods** - GET, POST, PUT, PATCH, DELETE
- **Status Codes** - 2xx success, 4xx client error, 5xx server error
- **Stateless** - Each request contains all info
- **Cacheable** - Leverage HTTP caching

### URL Design
- Nouns for resources: `/users`, `/products`
- Hierarchical: `/users/123/orders`
- Avoid verbs: `/getUsers` ❌ → `/users` ✓
- Plural nouns: `/users` not `/user`

### HTTP Methods
- **GET** - Retrieve resource (safe, idempotent)
- **POST** - Create new resource
- **PUT** - Replace entire resource (idempotent)
- **PATCH** - Partial update (not always idempotent)
- **DELETE** - Remove resource (idempotent)

### Status Codes
- **2xx Success**
  - 200 OK
  - 201 Created
  - 204 No Content
- **4xx Client Error**
  - 400 Bad Request
  - 401 Unauthorized
  - 403 Forbidden
  - 404 Not Found
- **5xx Server Error**
  - 500 Internal Server Error
  - 503 Service Unavailable

### Advanced REST
- **Pagination** - offset/limit or cursor-based
- **Filtering** - query parameters
- **Sorting** - order_by query param
- **Content Negotiation** - Accept header
- **HATEOAS** - Hypermedia links (optional)

## GraphQL

### Core Concepts
- **Schema-Driven** - Type system
- **Single Endpoint** - One URL for all data
- **Query Language** - Flexible data fetching
- **Strongly Typed** - Type safety
- **No Over/Under-fetching** - Get exactly what you need

### Schema Basics
- **Types** - Objects with fields
- **Queries** - Read-only operations
- **Mutations** - Write operations
- **Subscriptions** - Real-time updates

### Advantages
- Solve over-fetching (get only needed fields)
- Solve under-fetching (single request for related data)
- Type safety and documentation
- Self-documenting API (introspection)

### Tools
- Apollo Server (Node.js)
- Graphene (Python)
- Sangria (Scala)
- Gqlgen (Go)

## gRPC

### Characteristics
- Binary protocol (Protocol Buffers)
- HTTP/2 multiplexing
- Streaming support
- High performance
- Language-agnostic

### Use Cases
- Microservices communication
- Real-time applications
- Large data transfers
- Performance-critical systems

## API Security

### Authentication
- **API Keys** - Simple, stateless
- **OAuth 2.0** - Standard authorization
- **JWT Tokens** - Stateless auth
- **mTLS** - Mutual TLS certificate

### Authorization
- **RBAC** - Role-Based Access Control
- **ABAC** - Attribute-Based
- **Scopes** - OAuth 2.0 scopes

### Protection Mechanisms
- **Rate Limiting** - Requests per time period
- **CORS** - Cross-Origin Resource Sharing
- **HTTPS/TLS** - Encryption in transit
- **Input Validation** - Prevent injection attacks
- **API Gateway** - Centralized security

## API Versioning

### Strategies
1. **URL Path** - `/v1/users`, `/v2/users`
2. **Query Parameter** - `/users?version=2`
3. **Header** - `Accept: application/vnd.company.v2+json`
4. **Subdomain** - `v2.api.company.com`

### Best Practices
- Semantic versioning
- Support multiple versions during transition
- Clear deprecation policy
- Documentation for version differences

## Documentation

### OpenAPI/Swagger
- Industry standard specification
- Auto-generated documentation
- Interactive API explorer (Swagger UI)
- Code generation support

### Good Documentation
- Clear endpoint descriptions
- Example requests and responses
- Error response examples
- Authentication requirements
- Rate limiting information
- Changelog and deprecations

### Tools
- **Swagger UI** - Visual API explorer
- **Postman** - API client and documentation
- **ReDoc** - Alternative OpenAPI viewer
- **Stoplight Studio** - API design tool

## API Design Patterns

### Pagination
- **Offset/Limit** - Simple but inefficient for large datasets
- **Cursor-Based** - Better for large datasets
- **Keyset** - Efficient for huge datasets

### Filtering
- Query parameters: `?status=active&role=admin`
- Complex filters with operators
- Full-text search

### Error Handling
- Consistent error format
- Error codes and messages
- Detailed error information
- Error documentation

### Bulk Operations
- Batch create/update/delete
- Avoid N+1 requests
- Transactional safety

## Recommended API Style

1. **Most Common**: REST for public APIs, GraphQL for internal
2. **High Performance**: gRPC for microservices
3. **Real-time**: WebSockets or Server-Sent Events

## Learning Path

1. REST fundamentals
2. HTTP methods and status codes
3. API design best practices
4. Authentication and security
5. API documentation (OpenAPI)
6. GraphQL basics (optional)
7. gRPC for performance (optional)

---

[Explore API Design on Roadmap.sh](https://roadmap.sh/)