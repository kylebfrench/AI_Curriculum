# Concept Dependency Map

## Purpose

This document defines the major prerequisite relationships across the AI Curriculum.

The curriculum may eventually be presented as a mostly linear sequence, but the underlying learning system should be treated as a dependency graph.

The purpose of this map is to prevent advanced topics from being introduced before the learner has enough foundational understanding for them to make sense.

This document should evolve as the detailed syllabus is built and as actual learning reveals missing prerequisites.

---

## Core Principle

Do not ask:

> What topic sounds exciting next?

Ask:

> What does the learner need to understand before this topic will make sense?

A topic may be introduced conceptually before all prerequisites are complete.

However, meaningful implementation should usually wait until the necessary foundations are in place.

---

## High-Level Dependency Chain

A simplified view of the curriculum is:

```text
Computer Fundamentals
        ↓
Software Fundamentals
        ↓
Files / Command Line
        ↓
Git / GitHub
        ↓
Programming Fundamentals
        ↓
Python
        ↓
Networking Fundamentals
        ↓
HTTP
        ↓
JSON
        ↓
APIs
        ↓
Databases
        ↓
AI / LLM Foundations
        ↓
Model APIs
        ↓
Structured Outputs
        ↓
Embeddings
        ↓
Vector Search
        ↓
RAG
        ↓
Tool Calling
        ↓
Single-Agent Systems
        ↓
Multi-Agent / Orchestration
        ↓
Infrastructure / Containers / Local AI
        ↓
AI Systems Engineering
        ↓
Architecture / Capstone Systems
```

This is intentionally simplified.

Many topics have multiple prerequisites and may develop in parallel.

---

## Dependency Group 1 — Computer Fundamentals

### Concepts

- Computation.
- CPU.
- RAM.
- Storage.
- Operating systems.
- Processes.
- Files.
- Directories.
- Programs.
- Source code.

### Enables

These concepts support later understanding of:

- Command-line tools.
- Programming.
- Local applications.
- Processes and services.
- Containers.
- Local AI models.
- Memory and compute limitations.
- Infrastructure.

---

## Dependency Group 2 — Files and Command Line

### Prerequisites

- Basic operating system understanding.
- Files.
- Directories.
- Programs.

### Concepts

- File paths.
- Directories.
- Current working directory.
- Creating files.
- Moving files.
- Deleting files.
- Executing programs.
- Environment basics.
- Command-line interfaces.

### Enables

- Git.
- Python environments.
- Package managers.
- Repository work.
- Docker.
- Server administration.
- Local AI tooling.
- Reading setup instructions.

---

## Dependency Group 3 — Git and GitHub

### Prerequisites

- Files.
- Directories.
- Basic command-line concepts.
- Basic understanding of source code.

### Concepts

- Version control.
- Repository.
- Working tree.
- Staging.
- Commit.
- Commit history.
- Diff.
- Branch.
- Merge.
- Conflict.
- Remote repository.
- Push.
- Pull.
- Fetch.
- Clone.
- Revert.
- Pull request.

### Enables

- Safe coding practice.
- Project history.
- Experimentation.
- Collaboration.
- AI coding-agent workflows.
- Open-source repository work.
- Controlled infrastructure changes.
- Recovery from mistakes.

### Important Rule

Git fundamentals should be understood before AI coding agents are allowed to make broad repository changes.

Branches, diffs, and rollback should be understood before large AI-generated refactors.

---

## Dependency Group 4 — Programming Fundamentals

### Prerequisites

- Basic computer concepts.
- Source code.
- Programs.

### Concepts

- Variables.
- Values.
- Data types.
- Expressions.
- Operators.
- Conditions.
- Loops.
- Functions.
- Inputs.
- Outputs.
- Errors.
- Debugging.

### Enables

- Python.
- API clients.
- Data processing.
- Automation.
- AI applications.
- Agents.
- Tool functions.

---

## Dependency Group 5 — Python

### Prerequisites

- Programming fundamentals.

### Concepts

- Python syntax.
- Variables.
- Strings.
- Numbers.
- Booleans.
- Lists.
- Dictionaries.
- Conditions.
- Loops.
- Functions.
- Modules.
- Imports.
- Files.
- Exceptions.
- Packages.
- Virtual environments.

### Enables

- API clients.
- Automation scripts.
- Database access.
- AI model API calls.
- RAG systems.
- Agents.
- Data processing.
- Testing.
- Local tooling.

---

## Dependency Group 6 — Networking Fundamentals

### Prerequisites

- Basic understanding of computers.
- Programs.
- Client and server concept.

### Concepts

- Network.
- Client.
- Server.
- IP address.
- Port.
- DNS.
- Request and response.
- Localhost.
- Internet versus local network.

### Enables

- HTTP.
- APIs.
- Cloud services.
- Local inference servers.
- Databases across networks.
- Containers.
- Self-hosted applications.

---

## Dependency Group 7 — HTTP

### Prerequisites

- Networking fundamentals.
- Client/server concepts.

### Concepts

- HTTP request.
- HTTP response.
- Methods.
- URL.
- Headers.
- Body.
- Status codes.
- Authentication headers.
- HTTPS at an appropriate level.

### Enables

- REST APIs.
- Model APIs.
- Web applications.
- Tool integrations.
- Cloud services.
- Debugging API failures.

---

## Dependency Group 8 — JSON

### Prerequisites

- Basic data types.
- Lists.
- Dictionaries or key-value structures.

### Concepts

- Objects.
- Arrays.
- Strings.
- Numbers.
- Booleans.
- Null.
- Keys and values.
- Nested structures.

### Enables

- API payloads.
- API responses.
- Configuration.
- Structured model outputs.
- Tool schemas.
- Agent communication.
- Logs.

---

## Dependency Group 9 — APIs

### Prerequisites

- HTTP.
- JSON.
- Basic programming.
- Python at a functional level.

### Concepts

- API.
- Endpoint.
- Request.
- Response.
- Parameters.
- Authentication.
- API keys.
- Rate limits.
- Error handling.
- SDK.
- REST concepts.

### Enables

- Model APIs.
- External data integrations.
- Automation.
- AI-enabled applications.
- Tool calling.
- Agents.
- Cloud services.

---

## Dependency Group 10 — Databases

### Prerequisites

- Data concepts.
- Basic programming.
- Basic application concepts.

### Concepts

- Database.
- Table.
- Row.
- Column.
- Schema.
- Primary key.
- Relationships.
- Query.
- SQL.
- Insert.
- Update.
- Delete.
- Join.
- Index at an appropriate level.

### Enables

- Persistent application state.
- User data.
- AI application memory.
- Analytics.
- Vector databases.
- Retrieval systems.
- Agent state.

---

## Dependency Group 11 — AI Foundations

### Prerequisites

Formal programming mastery is not required for initial conceptual exposure.

Helpful foundations include:

- Computers.
- Software.
- Data.
- Programs.
- Basic probability intuition.

### Concepts

- Artificial intelligence.
- Machine learning.
- Deep learning.
- Neural networks.
- Models.
- Training.
- Inference.
- Parameters.
- Tokens.
- Context windows.
- Probabilistic outputs.
- Hallucinations.
- Transformers.
- Attention.
- Embeddings.

### Enables

- Meaningful use of LLMs.
- Model comparison.
- Prompt engineering.
- Model APIs.
- Embeddings.
- RAG.
- Agents.
- Local models.

---

## Dependency Group 12 — Prompting and Context Engineering

### Prerequisites

- AI foundations.
- Basic understanding of LLM limitations.

### Concepts

- Objective.
- Instructions.
- Constraints.
- Context.
- Examples.
- Structured output.
- Decomposition.
- Iteration.
- Verification.
- Prompt debugging.
- Context management.
- Instruction hierarchy.

### Enables

- Better AI-assisted development.
- Model API design.
- Agent instructions.
- Tool use.
- Context engineering.
- Handoffs.
- AI workflow design.

---

## Dependency Group 13 — Model APIs

### Prerequisites

- APIs.
- HTTP.
- JSON.
- Python.
- AI foundations.
- Prompting fundamentals.

### Concepts

- Model endpoint.
- API key.
- Model selection.
- Request payload.
- Response payload.
- Token usage.
- Streaming.
- Errors.
- Rate limits.
- Cost.
- SDK usage.

### Enables

- AI-enabled software.
- Structured outputs.
- Tool calling.
- RAG.
- Agents.
- Evaluations.

---

## Dependency Group 14 — Structured Outputs

### Prerequisites

- JSON.
- Model APIs.
- Prompting.

### Concepts

- Schema.
- Structured response.
- Validation.
- Parsing.
- Predictable machine-readable output.

### Enables

- Tool calling.
- Agent actions.
- Reliable application integration.
- Workflow routing.
- Evaluations.

---

## Dependency Group 15 — Embeddings

### Prerequisites

- AI foundations.
- Basic vector intuition.
- Data concepts.
- Model API familiarity.

### Concepts

- Embedding.
- Vector.
- Semantic representation.
- Similarity.
- Distance at an intuitive level.

### Enables

- Semantic search.
- Vector databases.
- Retrieval.
- RAG.
- Recommendation-like systems.

---

## Dependency Group 16 — Vector Search and Vector Databases

### Prerequisites

- Databases.
- Embeddings.

### Concepts

- Vector storage.
- Similarity search.
- Nearest neighbors at an intuitive level.
- Metadata.
- Indexing.
- Retrieval.

### Enables

- Document search.
- Semantic retrieval.
- RAG.
- AI memory patterns.

---

## Dependency Group 17 — RAG

### Prerequisites

- Model APIs.
- Embeddings.
- Vector search.
- Databases.
- Prompt/context engineering.

### Concepts

- Retrieval.
- Chunking.
- Embedding documents.
- Search.
- Context injection.
- Generation.
- Retrieval quality.
- Grounding.
- Common failure modes.

### Enables

- Document assistants.
- Knowledge systems.
- Enterprise search.
- Retrieval-enabled agents.

---

## Dependency Group 18 — Tool and Function Calling

### Prerequisites

- Model APIs.
- JSON.
- Structured outputs.
- APIs.
- Functions.
- Basic application state.

### Concepts

- Tool definition.
- Function schema.
- Arguments.
- Tool selection.
- Tool execution.
- Tool result.
- Return to model.
- Validation.
- Permission boundaries.

### Enables

- Agents.
- External actions.
- Workflow automation.
- Human approval systems.
- AI application integrations.

---

## Dependency Group 19 — State and Memory

### Prerequisites

- Programming.
- Databases.
- Model APIs.
- Basic application architecture.

### Concepts

- Stateless interaction.
- Application state.
- Conversation state.
- Persistent state.
- Memory.
- Context versus memory.
- Storage.
- Retrieval.

### Enables

- Long-running workflows.
- Agents.
- Personalized systems.
- Multi-step applications.
- Orchestration.

---

## Dependency Group 20 — Single-Agent Systems

### Prerequisites

- Model APIs.
- Prompting.
- Tool calling.
- State.
- Basic error handling.

### Concepts

- Goal.
- Instruction.
- Observation.
- Reasoning.
- Action.
- Tool use.
- Result.
- Loop.
- Stop condition.
- Human approval.
- Failure handling.

### Enables

- Tool-using agents.
- Research workflows.
- Task automation.
- Multi-agent systems.

---

## Dependency Group 21 — Multi-Agent Systems and Orchestration

### Prerequisites

- Single-agent systems.
- Tool calling.
- State.
- APIs.
- Workflow design.

### Concepts

- Agent responsibilities.
- Specialization.
- Routing.
- Supervisor patterns.
- Shared state.
- Communication.
- Coordination.
- Failure propagation.
- Cost.
- Latency.
- Observability.

### Important Rule

Do not introduce multi-agent systems simply because multiple agents sound more advanced.

First ask whether a single agent or deterministic workflow solves the problem more clearly.

### Enables

- Complex orchestration.
- Specialized AI workflows.
- Larger agent systems.

---

## Dependency Group 22 — Containers

### Prerequisites

- Operating systems.
- Processes.
- Files.
- Networking.
- Command line.
- Applications and dependencies.

### Concepts

- Container.
- Image.
- Runtime.
- Port mapping.
- Volume.
- Environment variable.
- Service.
- Docker.
- Docker Compose.

### Enables

- Self-hosted AI platforms.
- Reproducible environments.
- Local inference servers.
- Multi-service applications.
- Open-source deployment labs.

---

## Dependency Group 23 — Local AI

### Prerequisites

- AI foundations.
- Model concepts.
- Hardware fundamentals.
- Command line.
- Networking.
- Containers where appropriate.

### Concepts

- GPU.
- VRAM.
- Model size.
- Quantization.
- Local model.
- Model runtime.
- Inference server.
- Hosted versus local inference.
- Hardware limits.

### Enables

- Home AI labs.
- Hybrid architectures.
- Self-hosted AI applications.
- Infrastructure design.

---

## Dependency Group 24 — MCP and Tool Ecosystems

### Prerequisites

- APIs.
- Tool calling.
- Client/server concepts.
- JSON.
- Agents.

### Concepts

- Tool ecosystem.
- MCP server.
- MCP client.
- Resources.
- Tools.
- Permissions.
- External capability integration.

### Enables

- Tool-rich AI applications.
- AI development platforms.
- Agent ecosystems.
- Self-hosted workspaces.

---

## Dependency Group 25 — Self-Hosted AI Platforms

### Prerequisites

- Git and GitHub.
- Command line.
- Networking.
- APIs.
- Model APIs.
- Local/cloud models.
- Containers.
- Tools.
- Agents.
- MCP concepts.
- Memory.
- Configuration.
- Secrets.

### Concepts

- Application layer.
- Frontend.
- Backend.
- Services.
- Model providers.
- Local model services.
- Tools.
- Agents.
- MCP servers.
- Storage.
- Memory.
- Configuration.
- Authentication.
- Security boundaries.
- Logs.

### Example Case Study

Odysseus / Project Odysseus.

### Important Rule

Do not perform a guided installation merely because the software is interesting.

The installation becomes educational only after enough of the underlying components can be recognized and explained.

---

## Dependency Group 26 — AI Systems Engineering

### Prerequisites

- AI applications.
- APIs.
- Databases.
- Agents.
- Infrastructure.
- Basic architecture.

### Concepts

- Reliability.
- Latency.
- Cost.
- Monitoring.
- Logging.
- Observability.
- Evaluations.
- Guardrails.
- Permissions.
- Authentication.
- Security.
- Privacy.
- Human-in-the-loop.
- Recovery.
- Failure modes.

### Enables

- Production-quality systems.
- Architecture decisions.
- Operational ownership.
- Professional AI operations and enablement work.

---

## Dependency Group 27 — Architecture and Systems Thinking

### Prerequisites

Architecture develops throughout the course rather than appearing only at the end.

Advanced architecture requires familiarity with:

- Applications.
- APIs.
- Databases.
- AI models.
- Agents.
- Infrastructure.
- Networking.
- Security.
- Git workflows.

### Concepts

- Components.
- Boundaries.
- Responsibilities.
- Interfaces.
- Data flow.
- Dependencies.
- Failure points.
- Tradeoffs.
- Build versus buy.
- Local versus cloud.
- Human versus automated responsibility.

### Ultimate Outcome

The learner should eventually be able to encounter an unfamiliar technical system and determine:

- What its major components are.
- Why those components exist.
- How they communicate.
- Where data moves.
- Where AI is involved.
- Which dependencies matter.
- Where failures are likely.
- What questions should be asked.
- How the architecture might be improved.

---

## Parallel Learning Tracks

Not every concept needs to wait in a single strict line.

Several learning tracks may progress in parallel once their minimum prerequisites exist.

### Engineering Workflow Track

```text
Files
  ↓
Command Line
  ↓
Git
  ↓
GitHub
  ↓
Branches / Diffs / Recovery
  ↓
AI-Assisted Development Workflow
```

### Software Development Track

```text
Programming Fundamentals
  ↓
Python
  ↓
Debugging
  ↓
Packages / Environments
  ↓
Applications
```

### Application Communication Track

```text
Networking
  ↓
HTTP
  ↓
JSON
  ↓
APIs
  ↓
Model APIs / External APIs
```

### Data Track

```text
Data Concepts
  ↓
Databases
  ↓
SQL
  ↓
Embeddings
  ↓
Vector Search
  ↓
RAG
```

### Agent Track

```text
LLMs
  ↓
Prompting
  ↓
Model APIs
  ↓
Structured Outputs
  ↓
Tool Calling
  ↓
State
  ↓
Single Agent
  ↓
Multi-Agent / Orchestration
```

### Infrastructure Track

```text
Computer Fundamentals
  ↓
Operating Systems
  ↓
Processes
  ↓
Networking
  ↓
Command Line
  ↓
Containers
  ↓
Local Models / Servers
  ↓
Self-Hosted AI

These tracks should periodically reconnect through integration lessons.
```

---

## Stop-and-Connect Checkpoints

Integration checkpoints should appear when several branches of the dependency graph have matured enough to connect.

Examples include:

### Checkpoint 1 — Computer to Program

Connect:

CPU
RAM
Storage
Operating System
Files
Processes
Source Code
Program

### Checkpoint 2 — Software Communication

Connect:

Python Application
Client
Network
HTTP
JSON
API
Server
Database

### Checkpoint 3 — First AI Application

Connect:

Python
HTTP
JSON
API Key
Model API
Prompt
LLM
Response

### Checkpoint 4 — RAG

Connect:

Documents
Database Concepts
Embeddings
Vector Search
Retrieval
Prompt Context
LLM
Response

### Checkpoint 5 — Agent

Connect:

User Goal
Prompt
Model
Tool Schema
Tool Call
API
Tool Result
State
Model Response

### Checkpoint 6 — Self-Hosted AI System

Connect:

Git Repository
Containers
Frontend
Backend
Networking
Database
Model API
Local Model
Tools
Agents
MCP
Memory
Secrets
Logs

---

## Prerequisite Status Rules

For each important concept, future progress tracking may use statuses such as:

- Not introduced.
- Introduced.
- Developing.
- Functional.
- Strong.
- Needs reinforcement.

A dependency does not always need to be at the Strong level before moving forward.

The required level depends on how heavily the next topic depends on it.

For example:

A learner may only need an Introduced understanding of neural-network mathematics before beginning practical LLM usage.

However, Python functions should likely be Functional before building significant tool-calling applications in Python.

---

## Dependency Exception Rule

The instructor may occasionally introduce an advanced concept early to provide orientation.

For example:

An agent may be discussed conceptually before tool calling is formally taught.

However:

Conceptual exposure should not be mistaken for prerequisite completion.

When later implementation begins, return to the required foundations.

---

## Dependency Gap Rule

If a future lesson unexpectedly requires an unfamiliar concept:

1. Stop.
2. Identify the missing prerequisite.
3. Add it to the dependency map if necessary.
4. Teach the missing prerequisite.
5. Verify enough understanding.
6. Resume the original lesson.

Do not silently skip the missing concept.

---

## Current Status

**Version:** 0.1

**Status:** Initial dependency architecture.

This map should be refined while the detailed syllabus is created.

The next curriculum-design step should translate the architecture and dependency map into a detailed syllabus containing:

- Modules.
- Chapters.
- Learning objectives.
- Prerequisites.
- Labs.
- Assessments.
- Integration checkpoints.
- Project milestones.
