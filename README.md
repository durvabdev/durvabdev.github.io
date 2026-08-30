# durvabdev.github.io

## Projects

### TutorTrace
- Tech: React, TypeScript, Dexie.js, IndexedDB, OAuth2, Supabase
- Built an offline-first Canvas LMS study app with AI flashcard generation from course content, a gamification engine with XP and streaks, Canvas OAuth2, and non-blocking full-text search via a Web Worker.

### LedgerLink: Personal Finance App
- Tech: React, FastAPI, PostgreSQL, Plaid, Docker, MCP
- Developed an AI-powered financial assistant utilizing an agent interacting with an MCP-enabled data store to automate expense tracking, enabling users to analyze synced Plaid banking data through natural language queries, and generate proactive insights.

### Locksmith
- Tech: Go, PostgreSQL, GCP, Terraform, Kubernetes, GoitHub Actions
- Built a fault-tolerant job queue in Go and PostgreSQL using `FOR UPDATE SKIP LOCKED` for concurrent worker claiming; implemented exponential backoff with jitter, dead-letter queues, priority aging, and lease recovery.

### Linearizable KV store
- Tech: Go, RPC
- Built a fault-tolerant key-value store in Go using Raft consensus; achieved 65K reads/sec (p99 1.0ms) and 5.8K writes/sec (p99 11.5ms) with sub-20ms failover and crash-safe durability via append-only WAL and periodic snapshots.

### MapReduce Framework
- Tech: C++, gRPC, Protobuf, AWS, HDFS
- Engineered a MapReduce framework in C++ with gRPC inter-node communication; processed 100MB+ datasets under 3s across EC2 instances with 64 concurrent threads; implemented thread-safe nodes with HDFS partitioning and tracing to eliminate data races.

