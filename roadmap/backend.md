# My Customize Roadmap
1. CS50x 2025 - Lecture 0 - Scratch
   - [https://www.youtube.com/watch?v=2WtPyqwTLKM]
2. CS50x 2025 - Lecture 1 - C
   - [https://www.youtube.com/watch?v=89cbCbWrM4U]
3. CS50x 2025 - Lecture 2 - Arrays
   - [https://www.youtube.com/watch?v=Y8qnryVy5sQ]
4. CS50x 2025 - Lecture 3 - Algorithms
   - [https://www.youtube.com/watch?v=iCx3zwK8Ms8]
5. CS50x 2025 - Lecture 4 - Memory
   - [https://www.youtube.com/watch?v=kcRdFGbzR1I]
6. CS50x 2025 - Lecture 5 - Data Structures
   - [https://www.youtube.com/watch?v=aV8LlSmd1E8]
7. CS50x 2025 - Lecture 6 - Python
   - [https://www.youtube.com/watch?v=0eNc5lJfZFM]
8. CS50x 2025 - Artificial Intelligence
   - [https://www.youtube.com/watch?v=1HuD2ryeOLg]
9. Harvard CS50’s Intro to Databases with SQL
   - [https://www.youtube.com/watch?v=WXk7yDqsKxs]
10. CS50x 2025 - Lecture 7 - SQL
   - [https://www.youtube.com/watch?v=ZA25WHO62ZA]
11. CS50x 2025 - Lecture 8 - HTML, CSS, JavaScript
   - [https://www.youtube.com/watch?v=xiWUL3M9D8c]
12. Frontend Web Development Course (JavaScript, HTML, CSS)
   - [https://www.youtube.com/watch?v=zJSY8tbf_ys]
13. Full HTTP Networking Course – Fetch and REST APIs in JavaScript
   - [https://www.youtube.com/watch?v=2JYT5f2isg4]
14. CS50x 2025 - Lecture 9 - Flask
   - [https://www.youtube.com/watch?v=1r-dFbPQ7Z8]
15. CS50x 2025 - The End
   - [https://www.youtube.com/watch?v=WGEy-Bu5Hos]
16. PHP For Beginners - Complete Laracasts Course
   - [https://www.youtube.com/watch?v=fw5ObX8P6as]

# Original Roadmap from roadmap.sh
1. Internet
   - How does the internet work?
   - What is HTTP?
   - What is Domain Name?
   - What is hosting?
   - DNS and how it works?
   - Browsers and how they work?
2. Frontend Basics
   - HTML
   - CSS
   - JavaScript
3. Pick Backend Languange
   - JavaScript
   - Go
   - Java
   - Python
   - C#
   - Ruby
   - PHP
   - Rust
4. Version Control System
   - Git
5. Repo Hosting Services
   - Github
   - Gitlab
6. Relational Database
   - MySQL
   - PostgreSQL
   - SQLite
   - MariaDB
   - Oracle
   - MS SQL
   1. Migrations
   2. N+1 Problem
7. Learn about API
   1. API Styles
      - REST
      - JSON APIs
      - SOAP
      - gRPC
      - GraphQL
   2. Open API Specs
   3. Authentication
      - JWT
      - OAuth
      - Basic Authentication
      - Token Authentication
      - Cookie Based Auth
      - OpenID
      - SAML
   4. Web Security
      - Hashing Algorithm (MD5, SHA, scrypt, bcrypt)
      - HTTPS
      - OWASP Risks
      - CORS
      - SSL/TLS
      - CSP
      - Server Security
   5. API Security Best Practices
      1. Authentication
         - Avoid ‘Basic Authentication’, use standard (e.g. JWT)
         - Do not reinvent the wheel in authentication mechanisms
         - Use `Max Retry’ and jail features in Login
         - Use encryption on all sensitive data
      2. JWT
         - Use good 'JWT Secret' to make brute force attacks difficult
         - Do not extract the algorithm from the header, use backend
         - Make token expiration (TTL, RTTL) as short as possible
         - Avoid storing sensitive data in JWT payload
         - Keep the payload small to reduce the size of the JWT
      3. Access Control
         - Limit requests (throttling) to avoid DDoS/Brute Force
         - Use HTTPS on server side and secure ciphers
         - Use HSTS header with SSL to avoid SSL Strip attacks
         - Turn off directory listings
         - Private APIs to be only accessible from safe listed IPs
      4. OAuth
         - Always validate `redirect_uri’ on server-side
         - Avoid `response_type=token’ and try to exchange for code
         - Use `state’ parameter to prevent CSRF attacks
         - Have default scope, and validate scope for each application
      5. Input
         - Use proper HTTP methods for the operation
         - Validate `content-type` on request header
         - Validate user input to avoid common vulnerabilities
         - Use standard Authorization header for sensitive data
         - Use only server-side encryption
         - Use an API Gateway for caching, Rate Limit policies etc
      6. Processing
         - Check if all the endpoints are protected behind authentication to avoid broken authentication process
         - Avoid user’s personal ID in the resource URLs e.g. users/242/orders
         - Prefer using UUID over auto-increment IDs
         - Disable entity parsing if you are parsing XML to avoid XXE attacks
         - Disable entity expansion if using XML, YML or any other language
         - Use CDN for file uploads
         - Avoid HTTP blocking if you are using huge amount of data
         - Make sure to turn the debug mode off in production
         - Use non-executable stacks when available
      7. Output
         - Send `X-Content-Type-Options: nosniff` header
         - Send `X-Frame-Options: deny` header
         - Send `Content-Security-Policy: default-src 'none'` header
         - Remove fingerprinting headers (i.e. x-powered-by etc)
         - Force `content-type` for your response
         - Avoid returning sensitive data (credentials, sec. tokens etc)
         - Return proper response codes as per the operation
      8. CI/CD
         - Audit your design and implementation with unit/integration tests
         - Use a code review process and disregard self-approval
         - Continuously run security analysis on your code
         - Check your dependencies for known vulnerabilities
         - Design a rollback solution for deployments
      9. Monitoring
         - Use centralized logins for all services and components
         - Use agents to monitor all requests, responses and errors
         - Use alerts for SMS, Slack, Email, Kibana, Cloudwatch, etc
         - Ensure that you aren't logging any sensitive data
         - Use an IDS and/or IPS system to monitor everything
8. Caching (Server Side)
   - Redis
   - Memcached
   - HTTP Caching
9. Learn about Web Servers
   - Nginx
   - Caddy
   - Apache
   - MS IIS
10. More about Databases
    - Transactions
    - ORMs
    - ACID
    - Normalization
    - Failure Modes
    - Profiling Performance
11. Testing
    1. Containerization
       - Docker
       - Linux Containers
    2. Container Orchestration
       - Kubernetes
13. Message Brokers
    - RabbitMQ
    - Kafka
    - elasticsearch
    - Solr
14. CI/CD
15. Search Engines
16. Architectural Patterns
    1. System Design
       1. Introduction
          - What is System Design?
          - How to approach System Design?
       2. Performance vs Scalability
       3. Latency vs Throughput
       4. Availability vs Consistency
          - CAP Theorem
       5. Consistency Patterns
          - Weak Consistency
          - Eventual Consistency
          - Strong Consistency
       6. Availability Patterns
          - Fail-Over
          - Replication
          - Availability in Numbers
       7. Background Jobs
          - Event-Driven
          - Schedule Driven
          - Returning Results
       8. Domain Name System
       9. Content Delivery Networks
          - Pull CDNs
          - Push CDNs
       10. Load Balancers
           - LB vs Reverse Proxy
           - Load Balancing Algorithms
           - Layer 7 Load Balancing
           - Layer 4 Load Balancing
           - Horizontal Scaling
       11. Application Layer
           - Microservices
           - Service Discovery
       12. Databases (SQL vs NoSQL)
           1. RDBMS
              - Replication
              - Sharding
              - Federation
              - Denormalization
              - SQL Tuning
           2. NoSQL
              - Key-Value Store
              - Document Store
              - Wide Column Store
              - Graph Databases
       14. Caching
           1. Strategies
              - Refresh Ahead
              - Write-behind
              - Write-through
              - Cache Aside
           2. Types of Caching
              - Client Caching
              - CDN Caching
              - Web Server Caching
              - Database Caching
              - Application Caching
       15. Asynchronism
           - Back Pressure
           - Task Queues
           - Message Queues
       16. Idempotent Operations
       17. Communication
           - HTTP
           - TCP
           - UDP
           - RPC
           - REST
           - gRPC
           - GraphQL
       18. Performance Antipatterns
           - Improper Instantiation
           - Busy Database
           - Monolithic Persistence
           - Busy Frontend
           - Noisy Neighbor
           - Chatty I/O
           - Synchronous I/O
           - Retry Storm
           - No Caching
           - Extraneous Fetching
       19. Monitoring
           - Health Monitoring
           - Availability Monitoring
           - Performance Monitoring
           - Security Monitoring
           - Usage Monitoring
           - Instrumentation
           - Visualization & Alerts
       20. Cloud Design Patterns
           1. Design & Implementation
              - Strangler Fig
              - Sidecar
              - Static Content Hosting
              - Leader Election
              - CQRS
              - Pipes & Filters
              - Ambassador
              - Gateway Routing
              - Gateway Offloading
              - Gateway Aggregation
              - External Config Store
              - Compute Resource Consolidation
              - Backends for Frontend
              - Anti-Corruption Layer
           2. Data Management
              - Valet Key
              - Static Content Hosting
              - Sharding
              - Materialized View
              - Index Table
              - Event Sourcing
              - CQRS
              - Cache-Aside
           3. Messaging
              - Sequential Convoy
              - Scheduling Agent Supervisor
              - Queue-Based Load Leveling
              - Publisher/Subscriber
              - Priority Queue
              - Pipes and Filters
              - Competing Consumers
              - Choreography
              - Claim Check
              - Async Request Reply
       21. Relaibility Patterns
           1. Availability
              - Deployment Stamps
              - Geodes
              - Throttling
              - Health Endpoint Monitoring
              - Queue-Based Load Leveling
           2. High Availability
              - Deployment Stamps
              - Geodes
              - Health Endpoint Monitoring
              - Bulkhead
              - Circuit Breaker
           3. Resiliency
              - Bulkhead
              - Circuit Breaker
              - Compensating Transaction
              - Health Endpoint Monitoring
              - Leader Election
              - Queue-Based Load Leveling
              - Retry
              - Scheduler Agent Supervisor
           4. Security
              - Federated Identity
              - Gatekeeper
              - Valet Key
    3. Design & Architecture
       1. Clean Code Principles
          - Be consistent
          - Meaningful names over comments
          - Indentation and Code Style
          - Keep methods / classes / files small
          - Pure functions
          - Minimize cyclomatic complexity
          - Avoid passing nulls, booleans
          - Keep framework code distant
          - Use correct constructs
          - Tests should be fast and independent
          - Organize code by actor it belongs to
          - Command query separation
          - Keep it simple and refactor often
       2. Programming Paradigms
          - Structured Programming Programming Paradigms
          - Functional Programming
          - Object Oriented Programming
       3. Object Oriented Programming
          1. Primary Principles
             - Inheritance
             - Polymorphism
             - Abstraction Encapsulation
          2. Paradigm Features
             - Abstract Classes
             - Concrete Classes
             - Scope / Visibility
             - Interfaces
          3. Model-Driven Design
             - Domain Models
             - Anemic Models
             - Domain Language
             - Class Variants
             - Layered Architectures
       4. Design Principle
          - SOLID
          - DRY
          - YAGNI
          - Law of Demeter
          - Tell, don't ask
          - Hollywood Principle
          - Composition over Inheritance
          - Encapsulate what varies
          - Program against abstractions
       5. Design Patterns
          - GoF Design Patterns
          - PoSA Patterns
       6. Architectural Principles
          - Component Principles
          - Policy vs Detail
          - Coupling and Cohesion
          - Boundaries
       7. Architectural Styles
          1. Messaging
             - Event-Driven
             - Publish-Subscribe
          2. Distributed
             - Client-Server
             - Peer-to-Peer
          3. Structural
             - Component-Based
             - Monolithic
             - Layered
       8. Architectural Patterns
          - Domain-Driven Design
          - Model-View Controller
          - Microservices
          - Blackboard Pattern
          - Microkernel
          - Serverless Architecture
          - Message Queues/Streams
          - Event Sourcing
          - SOA
          - CQRS
       9. Enterprise Patterns
          - DTOs
          - Identity Maps
          - Usecases
          - Repositories
          - Mappers
          - Transaction Script
          - Commands / Queries
          - Value Objects
          - Domain Models
          - Entities
          - ORMs
    - Monolith
    - Microservices
    - SOA
    - Serverless
    - Service Mesh
    - Twelve Factor Apps
18. Real Time Data
    - Server Sent Events
    - WebSockets
    - Long/Short Polling
19. Scaling Databases
    - Database Indexes
    - Sharding Strategies
    - Data Replication
    - CAP Theorem
20. s
    - 
