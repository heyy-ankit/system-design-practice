# System Design Document

## 1. Problem Overview
- **System Name:**
- **One-line Description:**
- **Primary Use Cases:**

---

## 2. Requirements

### 2.1 Functional Requirements
- List of functional requirements

### 2.2 Non-Functional Requirements
- Latency:
- Availability:
- Consistency:
- Durability:
- Scalability:
- Security:

### 2.3 Out of Scope
- List of out of scope requirements

---

## 3. Assumptions
- Daily Active Users:
- Read/Write Ratio:
- QPS (Queries per Second):
- Payload size:
- Storage growth per day:

---

## 4. API Design

### 4.1 Endpoints
- POST /resource 
- GET /resource/{id} 
- DELETE /resource/{id}


### 4.2 Request/Response Examples
- **Request:**
- **Response:**
- **Status Codes:**

---

## 5. Data Model

### 5.1 Database Choice (SQL/NoSQL):

### 5.2 Schema / Collections
- Table:
- Columns:
- Indexes:


### 5.3 Partitioning / Sharding Strategy

---

## 6. High-Level Architecture (HLD)

### 6.1 Components
- Load Balancer
- API Gateway
- Application Layer
- Cache
- Database
- Message Queue
- CDN
- Object Storage

### 6.2 Architecture Diagram
*(Draw in tools like diagrams.net or Mermaid)*

---

## 7. Detailed Design / Sequence Flows

### 7.1 Primary Flow
1.
2.
3.
4.

### 7.2 Sequence Diagram
*(Optional diagram)*

---

## 8. Capacity & Scaling

### 8.1 Back-of-the-envelope Calculations
- RPS:
- Data size/day:
- Cache hit ratio:
- DB storage estimate:

### 8.2 Scaling Strategy
- Horizontal scaling
- Caching
- Read replicas
- Sharding
- Queue for async tasks
- CDN

---

## 9. Reliability & Fault Tolerance
- Replication strategy
- Failover
- Circuit breaker
- Retry logic
- Idempotency keys
- Graceful degradation

---

## 10. Consistency & Availability Trade-offs
- Strong/Eventual consistency
- CAP theorem discussion
- Read path consistency
- Write path consistency

---

## 11. Security
- Authentication
- Authorization
- TLS encryption
- Input sanitization
- Secrets management
- Rate limiting

---

## 12. Monitoring & Observability
- Metrics
- Logs
- Traces
- Dashboards
- Alerts

---

## 13. Future Improvements