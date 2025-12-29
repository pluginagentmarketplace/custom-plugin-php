---
name: database-technologies
description: Master SQL and NoSQL databases. Covers PostgreSQL, MySQL, MongoDB, Redis, Cassandra, Neo4j, Vector databases, and advanced database concepts.
sasmp_version: "1.3.0"
bonded_agent: 01-web-frontend
bond_type: PRIMARY_BOND
---

# Database Technologies Skill

Master relational and non-relational database systems.

## Relational Databases (SQL)

### PostgreSQL (Recommended)
- Advanced SQL features
- JSON and JSONB support
- Window functions
- Full-text search
- PostGIS for geospatial
- Best overall choice

### MySQL / MariaDB
- Wide adoption
- LAMP/MEAN stack standard
- Performance for read-heavy workloads

### Microsoft SQL Server
- Enterprise features
- T-SQL language
- Azure SQL integration

### SQLite
- Embedded database
- Mobile and desktop applications

## NoSQL Databases

### Document Store
- **MongoDB** - Most popular document DB
- Collections and documents
- Flexible schema
- Horizontal scaling with sharding

### Key-Value Store
- **Redis** - In-memory data structure store
- Caching layer
- Session storage
- Real-time analytics
- Pub/Sub messaging

### Wide-Column
- **Cassandra** - Distributed, high-write throughput
- Time-series data
- Horizontal scaling

### Graph Database
- **Neo4j** - Graph database leader
- Relationship queries
- Social networks, recommendations

## Emerging

### Vector Databases
- **Pinecone** - Managed vector DB
- **Chroma** - Embeddings storage
- **Milvus** - Open-source vector DB
- AI/ML embeddings and similarity search

## Core SQL Concepts

1. **Schema Design**
   - Normalization (1NF, 2NF, 3NF)
   - Entity-relationship (ER) modeling
   - Indexing strategies

2. **Querying**
   - SELECT, JOIN, GROUP BY
   - Window functions
   - CTEs (Common Table Expressions)
   - Subqueries and optimization

3. **Performance**
   - Query optimization
   - EXPLAIN plans
   - Index types (B-tree, Hash, BRIN)
   - Partitioning

4. **Transactions**
   - ACID properties
   - Transaction isolation levels
   - Locking and deadlock prevention

## Data Modeling

### SQL
- Star schema (data warehouse)
- Snowflake schema
- 3NF (normalized)

### NoSQL
- Document nesting
- Denormalization
- Sharding strategy

## Caching Strategies

- Cache-aside (lazy loading)
- Write-through
- Write-behind
- Refresh-ahead

## Scaling Strategies

- **Vertical** - More powerful hardware
- **Horizontal** - Sharding and partitioning
- **Read Replicas** - Load distribution
- **Caching Layer** - Redis/Memcached

## Recommended Learning Path

1. Master PostgreSQL (SQL fundamentals)
2. Learn Redis for caching
3. Explore MongoDB for flexible schema
4. Advanced: Elasticsearch, Vector DBs
5. Specialization: Based on use case

---

[Explore databases on Roadmap.sh](https://roadmap.sh/)