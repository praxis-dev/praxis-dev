# Igor Chesnokov

Financial markets, software engineering, and AI agents.

I combine more than 10 years in brokerage, financial advisory, and asset management with hands-on software development. I build tools for trading workflows, business operations, and automation.

Based in El Salvador.

## What I build

- **AI applications:** tool-using agents, document retrieval, structured extraction, human approval workflows, evaluations, and cost tracking.
- **Financial integrations:** broker event pipelines, order-status monitoring, and accounting workflows with validation and controlled synchronization.
- **Operational systems:** CRMs, communications archives, admin portals, audit trails, background workers, and incident tooling.

## Selected work

### Interactive Brokers integration
[IBDataSync](https://github.com/praxis-dev/IBDataSync)

A read-only event pipeline built with Python and Go. Captures order-status and execution events through the Interactive Brokers TWS API, filters duplicate updates, forwards data to an external API, and stores order-status history in MongoDB.

### Agentic CRM
A CRM with a custom tool-use loop, human confirmation for changes, hybrid document retrieval, tenant isolation, durable background jobs, and automated model evaluations.

### AI bookkeeping integration
Receipt and invoice extraction with server-side amount validation, explicit approval, and queued synchronization with QuickBooks Online. Includes retries, idempotency controls, and recoverable error states. Verified in the Intuit sandbox.

### Business operations software
Production CRM and quoting workflows, communications archiving, access-controlled administration, monitoring, backups, and recovery procedures.

### Earlier RAG work
[questmind](https://github.com/praxis-dev/questmind)

A document-retrieval chatbot built with LangChain, NestJS, MongoDB, and React.

## Technical stack

**Languages:** Python, Go, TypeScript, JavaScript, SQL

**Backend:** FastAPI, Echo, Node.js, Express, NestJS, REST, WebSocket

**Frontend:** React, Next.js, Vite

**Data:** PostgreSQL, pgvector, MongoDB, SQLite

**AI:** Anthropic API, tool-use orchestration, RAG, structured extraction, model evaluations

**Operations:** Docker, Linux, GitHub Actions, structured logging, health checks, backups, runbooks

## How I work

I use Claude Code, Cursor, and OpenAI Codex throughout development, guided by written specifications, documented decisions, code review, and testing.

In applications that change business records or send information externally, I build explicit approval controls, validation, traceability, and failure recovery.