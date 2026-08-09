# AI Curriculum Syllabus

## Purpose

This document defines the current detailed learning sequence for the AI Curriculum.

It translates the curriculum architecture and concept dependency map into a practical sequence of modules, lessons, labs, assessments, integration sessions, and projects.

This syllabus should be treated as a living plan.

The sequence may change when:

- Diagnostic assessments reveal existing knowledge.
- Foundational gaps appear.
- A concept requires more or less depth than expected.
- A better prerequisite order becomes apparent.
- Technology changes.
- A tool becomes outdated or irrelevant.
- Professional or personal learning goals evolve.

The syllabus should adapt without abandoning the core Course Charter or dependency logic.

---

## Course Structure

The curriculum is organized into phases.

Each phase may contain:

- Modules.
- Lessons.
- Labs.
- Mental-model checks.
- Module assessments.
- Stop-and-Connect sessions.
- Projects.

The learner should not advance purely because a lesson was completed.

Progress depends on sufficient understanding of the prerequisites required for the next topic.

---

# Phase 0 — Technical Orientation and Baseline

## Module 0.1 — Mapping the Technical World

### Learning Objectives

Understand at a high level:

- What a computer is.
- What computation means.
- What software is.
- What a program is.
- What data is.
- What a model is.
- What artificial intelligence is.
- How ordinary software differs from machine-learning systems.
- How AI applications fit inside larger software systems.

### Lessons

1. What does a computer actually do?
2. What is computation?
3. Hardware versus software.
4. What is a program?
5. What is data?
6. Traditional software versus AI systems.
7. What is a model?
8. What physically happens when an AI application receives a request?
9. Local computing versus cloud computing.
10. First map of the modern AI technology stack.

### Assessment

Explain in simple terms:

- What a program is.
- What a model is.
- How software and AI differ.
- Where computation occurs.

### Outcome

Establish a shared mental map before deeper technical instruction begins.

---

## Module 0.2 — Baseline Diagnostic

## Purpose

Determine current understanding without assuming either mastery or beginner status.

### Areas to Diagnose

- Computers and operating systems.
- Files and directories.
- Command line.
- Programming concepts.
- Python.
- Git and GitHub.
- Networking.
- HTTP.
- APIs.
- Databases.
- AI fundamentals.
- Prompting.
- Agents.
- Local versus cloud AI.
- Software architecture.

### Assessment Style

Use short conversational questions and small practical tasks.

Do not turn the diagnostic into a large exam.

### Outcome

Identify which future lessons may be accelerated and which require full foundational treatment.

---

# Phase 1 — Computer and Software Foundations

## Module 1.1 — Hardware and Computation

### Lessons

1. CPU.
2. RAM.
3. Storage.
4. Input and output.
5. Instructions and computation.
6. Why different resources matter.

### Learning Objectives

Explain:

- What each major hardware component does.
- Why RAM differs from storage.
- Why software ultimately depends on physical computation.
- Why AI workloads place unusual demands on hardware.

### Mental-Model Check

Trace what happens when a simple program runs.

---

## Module 1.2 — Operating Systems

### Lessons

1. Why operating systems exist.
2. Files and directories.
3. Processes.
4. Applications.
5. Permissions at an introductory level.
6. Environment concepts.
7. Local user versus system responsibilities.

### Lab

Explore the local file system and identify:

- Files.
- Folders.
- Applications.
- Paths.
- Basic process information.

### Outcome

Understand the operating system as the layer coordinating applications and hardware.

---

## Module 1.3 — Command Line Foundations

### Lessons

1. What a shell is.
2. Terminal versus shell.
3. Current directory.
4. Paths.
5. Listing files.
6. Creating directories.
7. Moving through directories.
8. Creating and editing files.
9. Moving and copying files.
10. Deleting files safely.
11. Running commands.
12. Reading command output.

### Lab

Create a small directory structure entirely from the command line.

### Assessment

Navigate an unfamiliar folder tree and explain each command used.

---

# Phase 2 — Git, GitHub, and Engineering Workflow

## Module 2.1 — Why Version Control Exists

### Lessons

1. The problem version control solves.
2. Git versus GitHub.
3. Local repositories.
4. Remote repositories.
5. Working directory.
6. Repository history.

### Outcome

Explain why Git exists independently of GitHub.

---

## Module 2.2 — Core Git Workflow

### Lessons

1. Initialize a repository.
2. Repository status.
3. Tracking files.
4. Staging.
5. Commits.
6. Commit messages.
7. Commit history.
8. Diffs.
9. Why small commits matter.

### Lab

Use the AI Curriculum repository as a practical example where appropriate.

Create controlled edits and inspect how Git represents changes.

---

## Module 2.3 — Branching and Recovery

### Lessons

1. Branches.
2. Why branches exist.
3. Switching branches.
4. Merging.
5. Merge conflicts.
6. Reverting.
7. Restoring files.
8. Recovering from mistakes.

### Core Lab — Break It on Purpose

1. Create a branch.
2. Make a controlled change.
3. Commit it.
4. Introduce a mistake.
5. Inspect the diff.
6. Recover.
7. Merge the correct work.

### Assessment

Explain how Git provides safety when AI-generated code causes problems.

---

## Module 2.4 — GitHub Workflow

### Lessons

1. Clone.
2. Push.
3. Pull.
4. Fetch.
5. Pull requests.
6. Issues.
7. Releases and tags at an introductory level.
8. Repository permissions.
9. Secrets and credentials.
10. Reading unfamiliar repositories.

### Outcome

Use GitHub as both a project platform and technical portfolio surface.

---

# Stop-and-Connect Session 1 — From Computer to Repository

Connect:

- Operating system.
- Files.
- Directories.
- Command line.
- Source code.
- Git.
- GitHub.
- Local versus remote state.

The learner should be able to explain exactly where repository files physically exist and what changes when they are pushed to GitHub.

---

# Phase 3 — Programming Foundations and Python

## Module 3.1 — Programming Mental Models

### Lessons

1. Instructions.
2. Values.
3. Variables.
4. Data types.
5. Expressions.
6. Operators.
7. Input.
8. Output.
9. Control flow.
10. Errors.

### Outcome

Understand programming concepts independently of Python syntax.

---

## Module 3.2 — Python Basics

### Lessons

1. Running Python.
2. Variables.
3. Strings.
4. Integers.
5. Floating-point numbers.
6. Booleans.
7. Printing.
8. Input.
9. Comparisons.
10. Conditions.

### Lab

Build a tiny interactive calculator or decision program.

---

## Module 3.3 — Collections and Loops

### Lessons

1. Lists.
2. Dictionaries.
3. Indexes.
4. Key-value relationships.
5. For loops.
6. While loops.
7. Iteration.
8. Nested structures.

### Lab

Create a small data-tracking program.

---

## Module 3.4 — Functions

### Lessons

1. Why functions exist.
2. Parameters.
3. Arguments.
4. Return values.
5. Scope.
6. Reuse.
7. Decomposition.

### Assessment

Explain the difference between:

- Calling a function.
- Passing an argument.
- Returning a value.

---

## Module 3.5 — Files, Modules, and Packages

### Lessons

1. Reading files.
2. Writing files.
3. Modules.
4. Imports.
5. Libraries.
6. Packages.
7. Package managers.
8. Virtual environments.
9. Dependencies.

### Lab

Build a small utility that reads data from a file, processes it, and writes output.

---

## Module 3.6 — Errors and Debugging

### Lessons

1. Syntax errors.
2. Runtime errors.
3. Logic errors.
4. Exceptions.
5. Stack traces.
6. Debugging strategy.
7. Hypothesis testing.
8. Logging versus printing.

### Lab

Debug intentionally broken Python programs.

### Outcome

Treat debugging as an engineering process rather than random trial and error.

---

# Phase 4 — Networking, HTTP, and APIs

## Module 4.1 — Client and Server

### Lessons

1. What a network is.
2. Client.
3. Server.
4. IP address.
5. Port.
6. DNS.
7. Localhost.
8. Local network versus internet.

### Outcome

Explain how two programs running on different machines can communicate.

---

## Module 4.2 — HTTP

### Lessons

1. Why HTTP exists.
2. URL.
3. Request.
4. Response.
5. Methods.
6. Headers.
7. Body.
8. Status codes.
9. HTTPS.
10. Authentication headers.

### Lab

Inspect real HTTP requests and responses.

---

## Module 4.3 — JSON

### Lessons

1. Objects.
2. Arrays.
3. Keys.
4. Values.
5. Nested structures.
6. JSON versus Python dictionaries.
7. Serialization.

### Lab

Read and modify sample JSON payloads.

---

## Module 4.4 — APIs

### Lessons

1. What an API is.
2. Why APIs exist.
3. Endpoint.
4. Parameters.
5. Requests and responses.
6. API keys.
7. Authentication.
8. Rate limits.
9. SDKs.
10. Error responses.

### Lab — First API Client

Use Python to call a simple external API.

### Project Option

Build a small weather-style application using an API.

---

# Stop-and-Connect Session 2 — How Applications Communicate

Trace:

- Python application.
- Client.
- DNS.
- Server.
- HTTP request.
- JSON.
- API.
- HTTP response.
- Python application.

The learner should verbally trace one complete request from beginning to end.

---

# Phase 5 — Databases and SQL

## Module 5.1 — Why Databases Exist

### Lessons

1. Data persistence.
2. Files versus databases.
3. Tables.
4. Rows.
5. Columns.
6. Schemas.
7. Primary keys.
8. Relationships.

---

## Module 5.2 — SQL Fundamentals

### Lessons

1. SELECT.
2. WHERE.
3. ORDER BY.
4. INSERT.
5. UPDATE.
6. DELETE.
7. JOIN.
8. Aggregation at an appropriate level.

### Lab

Create and query a tiny database.

---

## Module 5.3 — Applications and Databases

### Lessons

1. Application connection.
2. Queries from code.
3. Persistent state.
4. Errors.
5. Transactions at an introductory level.
6. Database security basics.

### Project

Build a small Python application backed by a database.

---

# Phase 6 — Artificial Intelligence Foundations

## Module 6.1 — AI, Machine Learning, and Deep Learning

### Lessons

1. Artificial intelligence.
2. Machine learning.
3. Training from data.
4. Deep learning.
5. Neural networks.
6. Models.
7. Parameters.

### Outcome

Explain the relationship between AI, machine learning, deep learning, neural networks, and models.

---

## Module 6.2 — Large Language Models

### Lessons

1. What an LLM is.
2. Tokens.
3. Tokenization.
4. Training.
5. Inference.
6. Parameters.
7. Context windows.
8. Probabilistic generation.
9. Hallucination.
10. Model families.

---

## Module 6.3 — Transformers and Attention

### Lessons

1. Why sequence processing matters.
2. Transformer intuition.
3. Attention intuition.
4. Context relationships.
5. Why transformers changed language modeling.

The objective is conceptual understanding rather than advanced mathematics.

---

## Module 6.4 — Model Comparison

### Lessons

1. Model capability.
2. Model size.
3. Context window.
4. Latency.
5. Cost.
6. Proprietary versus open models.
7. Specialized models.
8. Model evaluation.

### Assessment

Given several hypothetical requirements, explain what characteristics would matter when selecting a model.

---

# Phase 7 — Prompting and Context Engineering

## Module 7.1 — Prompt Fundamentals

### Lessons

1. Objective.
2. Instructions.
3. Context.
4. Constraints.
5. Examples.
6. Desired output.
7. Iteration.

---

## Module 7.2 — Prompt Debugging

### Lessons

1. Ambiguity.
2. Missing context.
3. Conflicting instructions.
4. Overprompting.
5. Verification.
6. Decomposition.
7. Evaluating responses.

### Lab

Improve intentionally weak prompts and explain why the revised versions work better.

---

## Module 7.3 — Context Engineering

### Lessons

1. Prompt versus context.
2. Providing source material.
3. Context windows.
4. Relevant versus irrelevant context.
5. Maintaining state.
6. Handoffs.
7. Instruction hierarchy.
8. Context for coding agents.

### Outcome

Understand context as an engineered input rather than simply a longer prompt.

---

# Stop-and-Connect Session 3 — What Happens When I Ask an LLM Something?

Trace:

- User.
- AI application.
- Context.
- Prompt.
- Tokens.
- Model.
- Inference.
- Generated tokens.
- Application.
- User.

Then compare a chat application with direct model API usage.

---

# Phase 8 — AI Applications, IDEs, and Development Platforms

## Module 8.1 — Mapping the AI Tool Ecosystem

### Lessons

Distinguish:

- Model.
- Chat application.
- API.
- SDK.
- IDE.
- AI coding agent.
- Command-line coding agent.
- Agent framework.
- Orchestrator.
- Local model runtime.
- Self-hosted AI workspace.
- Cloud AI platform.
- MCP ecosystem.
- GitHub.

### Assessment

Classify unfamiliar hypothetical products into the correct layer of the stack.

---

## Module 8.2 — AI-Assisted Development

### Lessons

1. Repository context.
2. Context selection.
3. Planning before coding.
4. Small tickets.
5. Asking AI for implementation plans.
6. Reviewing diffs.
7. Testing.
8. Debugging.
9. Preventing cascading mistakes.
10. Rollback strategies.

### Lab

Give an AI coding assistant a deliberately small repository task, inspect its changes, test them, and decide whether to keep or revert them.

---

## Module 8.3 — Evaluating AI Tools

### Lessons

1. What layer does the tool occupy?
2. Hosted versus self-hosted.
3. Local versus cloud.
4. Permissions.
5. Data access.
6. Model access.
7. Cost.
8. Lock-in.
9. Marketing claims versus technical capabilities.

### Outcome

Build a transferable framework for evaluating future AI tools.

---

# Phase 9 — Model APIs and AI Application Engineering

## Module 9.1 — First Model API Call

### Lessons

1. API credential.
2. Model endpoint.
3. SDK.
4. Request.
5. Prompt input.
6. Model selection.
7. Response.
8. Token usage.
9. Cost.

### Lab

Build a minimal Python program that sends a request to a model and displays the response.

---

## Module 9.2 — Structured Outputs

### Lessons

1. Why machine-readable output matters.
2. JSON responses.
3. Schemas.
4. Validation.
5. Parsing.
6. Error handling.

### Lab

Request structured data from a model and validate the response.

---

## Module 9.3 — Streaming, Errors, and Reliability

### Lessons

1. Streaming.
2. Timeouts.
3. Rate limits.
4. Retries.
5. Logging.
6. API errors.
7. Cost tracking.
8. Basic reliability patterns.

---

# Stop-and-Connect Session 4 — First Complete AI Application

Trace:

- User input.
- Python application.
- API key.
- HTTP.
- JSON.
- Model provider.
- Model inference.
- Structured response.
- Application output.
- Logging.

The learner should identify which concepts came from earlier phases.

---

# Phase 10 — Embeddings, Vector Search, and RAG

## Module 10.1 — Embeddings

### Lessons

1. Why semantic representation is useful.
2. What an embedding represents.
3. Vectors.
4. Similarity.
5. Distance intuition.
6. Embedding models.

### Lab

Compare embeddings for several pieces of text.

---

## Module 10.2 — Vector Search

### Lessons

1. Similarity search.
2. Vector storage.
3. Metadata.
4. Retrieval.
5. Ranking.
6. Vector databases.

### Lab

Build a tiny semantic-search system.

---

## Module 10.3 — RAG

### Lessons

1. The problem RAG solves.
2. Documents.
3. Chunking.
4. Embedding.
5. Storage.
6. Retrieval.
7. Context injection.
8. Generation.
9. Grounding.
10. Failure modes.

### Project

Build a small document-question-answering system.

### Assessment

Draw and explain the full RAG architecture.

---

# Phase 11 — Tools, Functions, Memory, and Agents

## Module 11.1 — Tool Calling

### Lessons

1. Why models need tools.
2. Tool definitions.
3. Function schemas.
4. Arguments.
5. Model tool selection.
6. Executing the function.
7. Returning results.
8. Validation.
9. Permissions.

### Lab

Build a model interaction that calls one controlled tool.

---

## Module 11.2 — State and Memory

### Lessons

1. Stateless model requests.
2. Conversation state.
3. Application state.
4. Persistent state.
5. Context versus memory.
6. Database-backed memory.
7. Retrieval-backed memory.

### Assessment

Explain the difference between context and memory without using either term as its own definition.

---

## Module 11.3 — Single-Agent Systems

### Lessons

1. What makes something an agent?
2. Goal.
3. Observation.
4. Reasoning.
5. Action.
6. Tool.
7. Result.
8. Loop.
9. Stop condition.
10. Human approval.
11. Failure handling.

### Lab

Build a small tool-using agent.

### Outcome

Clearly distinguish:

- Chatbot.
- Workflow.
- Tool-using model.
- Agent.

---

# Stop-and-Connect Session 5 — Inside an Agent

Trace:

- User goal.
- Agent instruction.
- Model.
- Tool selection.
- Structured arguments.
- Function.
- External API or system.
- Tool result.
- State.
- Next model action.
- Final response.

---

# Phase 12 — Workflows, Multi-Agent Systems, and Orchestration

## Module 12.1 — Deterministic Workflows

### Lessons

1. Workflow.
2. Step.
3. State.
4. Branch.
5. Conditions.
6. Retry.
7. Human approval.
8. Deterministic versus agentic behavior.

### Outcome

Understand when a workflow is more appropriate than an agent.

---

## Module 12.2 — Multi-Agent Systems

### Lessons

1. Agent specialization.
2. Routing.
3. Supervisor patterns.
4. Shared state.
5. Agent communication.
6. Failure propagation.
7. Coordination overhead.
8. Cost.
9. Latency.
10. When not to use multiple agents.

### Lab

Design a multi-agent architecture before implementing anything.

Implementation should occur only if the architecture has a clear reason for multiple agents.

---

# Phase 13 — Containers, Infrastructure, and Local AI

## Module 13.1 — Infrastructure Foundations

### Lessons

1. Server.
2. Service.
3. Process.
4. Port.
5. Environment variable.
6. Configuration.
7. Secrets.
8. Storage.
9. Logs.

---

## Module 13.2 — Containers and Docker

### Lessons

1. Why containers exist.
2. Image.
3. Container.
4. Runtime.
5. Port mapping.
6. Volume.
7. Environment variables.
8. Dockerfile at an introductory level.
9. Docker Compose.
10. Multiple services.

### Lab

Run a small containerized application and explain each major configuration element.

---

## Module 13.3 — Local AI Models

### Lessons

1. CPU versus GPU.
2. GPU.
3. VRAM.
4. Model size.
5. Quantization.
6. Local inference.
7. Model runtime.
8. Inference server.
9. Local versus hosted model.
10. Hybrid systems.

### Lab

Run or interact with a modest local model if appropriate hardware and software are available.

No expensive hardware purchase is required.

---

## Module 13.4 — Cloud AI Infrastructure

### Lessons

1. Cloud computing.
2. Compute.
3. Storage.
4. Networking.
5. Managed services.
6. Hosted model APIs.
7. Cost.
8. Scaling.
9. Local versus cloud tradeoffs.

### Outcome

Understand what someone means when describing a home server as a small private cloud environment.

---

# Phase 14 — MCP, Tools, and AI Platforms

## Module 14.1 — MCP Concepts

### Lessons

1. Why tool protocols exist.
2. Client.
3. Server.
4. Tools.
5. Resources.
6. Permissions.
7. External capabilities.
8. Security boundaries.

### Outcome

Understand MCP as an integration mechanism rather than a magical agent technology.

---

## Module 14.2 — Self-Hosted AI Workspaces

### Lessons

Identify architectural components such as:

- Frontend.
- Backend.
- Model providers.
- Local models.
- Tools.
- MCP servers.
- Agents.
- Memory.
- Storage.
- Configuration.
- Containers.
- Networking.
- Secrets.
- Logs.

### Case Study — Odysseus Pass 1

Classify Odysseus conceptually:

- Model?
- Agent?
- IDE?
- Application?
- Orchestration layer?
- Self-hosted platform?

No installation is required during this pass.

---

# Phase 15 — AI Systems Engineering

## Module 15.1 — Reliability and Failure

### Lessons

1. Failure modes.
2. Timeouts.
3. Retries.
4. Fallbacks.
5. Validation.
6. Human escalation.
7. Recovery.

---

## Module 15.2 — Observability

### Lessons

1. Logs.
2. Metrics.
3. Traces at an introductory level.
4. Monitoring.
5. Model output tracking.
6. Tool execution tracking.
7. Debugging distributed workflows.

---

## Module 15.3 — Evaluations

### Lessons

1. Why AI evaluation is difficult.
2. Test cases.
3. Expected behavior.
4. Automated evaluation.
5. Human evaluation.
6. Regression testing.
7. Quality measurement.

---

## Module 15.4 — Security and Privacy

### Lessons

1. Credentials.
2. Secrets.
3. Permissions.
4. Authentication.
5. Authorization.
6. Data exposure.
7. Prompt injection at an appropriate level.
8. Tool permissions.
9. Security boundaries.
10. Local versus cloud privacy tradeoffs.

---

## Module 15.5 — Cost and Latency

### Lessons

1. Token cost.
2. Model cost.
3. Infrastructure cost.
4. Latency.
5. Model routing.
6. Caching at an appropriate level.
7. Quality versus cost.
8. Quality versus speed.

---

# Stop-and-Connect Session 6 — Full AI System Architecture

Analyze a hypothetical AI-enabled application containing:

- User interface.
- Backend.
- API.
- Database.
- Retrieval.
- LLM.
- Tools.
- Agent.
- External services.
- Containers.
- Logging.
- Authentication.
- Human approval.

Trace:

- Data.
- Requests.
- Credentials.
- Model calls.
- State.
- Failure points.

---

# Phase 16 — AI Product and Workflow Design

## Module 16.1 — What Should Be Automated?

### Lessons

1. Task decomposition.
2. Deterministic automation.
3. AI-assisted workflows.
4. Agentic workflows.
5. Human judgment.
6. Approval gates.
7. Risk.

---

## Module 16.2 — Designing Useful AI Features

### Lessons

1. User problem.
2. AI capability.
3. Reliability requirement.
4. Trust.
5. User experience.
6. Proactive versus annoying AI.
7. Metrics.
8. Feedback loops.

---

## Module 16.3 — Build Versus Buy

### Lessons

1. Existing product.
2. API.
3. Custom application.
4. Self-hosted system.
5. Maintenance cost.
6. Lock-in.
7. Security.
8. Operational complexity.

### Assessment

Given a realistic AI workflow problem, propose and defend an implementation approach.

---

# Phase 17 — Reading Unfamiliar Systems

## Module 17.1 — Reading GitHub Repositories

### Lessons

1. README.
2. Repository tree.
3. Documentation.
4. Configuration.
5. Dependencies.
6. Source folders.
7. Frontend and backend.
8. Issues.
9. Releases.
10. Contribution guides.

### Lab

Inspect an unfamiliar open-source repository without modifying it.

Create a simple architecture map.

---

## Module 17.2 — Architecture Teardown

### Lessons

Identify:

- Components.
- Responsibilities.
- Interfaces.
- Services.
- Dependencies.
- Data flow.
- Configuration.
- External integrations.
- Security boundaries.
- Failure surfaces.

Case Study — Odysseus Pass 2

After prerequisites are complete, inspect the Odysseus repository and identify:

- Application layer.
- Model providers.
- Local model services.
- API integrations.
- Tools.
- MCP servers.
- Storage.
- Memory.
- Docker.
- Networking.
- Authentication.
- Secrets.
- Frontend.
- Backend.
- Logs.

### Outcome

An unfamiliar real-world repository should begin to look like recognizable combinations of previously learned concepts.

---

# Phase 18 — Guided Self-Hosting and Integration

## Module 18.1 — Controlled Open-Source Installation

Possible Case Study

Odysseus or another educationally appropriate self-hosted AI platform.

### Lab Objectives

1. Clone the repository.
2. Read installation documentation.
3. Identify prerequisites.
4. Inspect configuration.
5. Inspect Docker Compose.
6. Configure environment variables.
7. Protect secrets.
8. Start services.
9. Inspect logs.
10. Connect a hosted model.
11. Optionally connect a local model.
12. Explore tools or agents.
13. Trace a request.
14. Make one controlled configuration change.
15. Preserve changes using Git.

### Final Assessment

Explain the platform's architecture without relying primarily on product-specific terminology.

---

# Phase 19 — Portfolio Projects and Capstone

### Project Progression

Potential projects include:

- Python utility.
- API application.
- Database application.
- AI API application.
- RAG application.
- Tool-using agent.
- Workflow automation.
- Local-model experiment.
- AI-enabled application.
- Open-source architecture teardown.
- Self-hosted system experiment.

---

### Optional Portfolio Project — Collection Price Monitor

A future price-monitoring system may incorporate:

- CSV ingestion.
- Database storage.
- External pricing APIs.
- Scheduled checks.
- Business rules.
- Reporting.
- Alerts.
- User interface.
- AI analysis where useful.

This project is optional and should only be used where it supports the curriculum.

---

### Capstone — Career OS

Career OS may later be revisited as a major capstone or final technical examination.

Possible work includes:

- Architecture audit.
- Repository analysis.
- Identifying previous mistakes.
- Refactoring.
- Git workflow.
- Testing.
- API integration.
- AI features.
- Agent task decomposition.
- Reliability improvements.
- Architecture redesign.

Career OS should demonstrate how the learner's technical judgment has evolved.

It should not become the textbook for the earlier curriculum.

---

### Final Capability Assessment

The final evaluation should not primarily test memorization.

The learner should receive an unfamiliar or partially unfamiliar technical system and be asked to reason through it.

The learner should be increasingly capable of:

1. Identifying major components.
2. Explaining why they exist.
3. Tracing data flow.
4. Identifying interfaces.
5. Identifying where AI is used.
6. Explaining local versus cloud responsibilities.
7. Identifying likely failure points.
8. Identifying security boundaries.
9. Evaluating architecture tradeoffs.
10. Proposing improvements.
11. Reading unfamiliar documentation.
12. Working with AI coding tools without surrendering technical judgment.

The strongest success signal is:

> I can understand enough of an unfamiliar technical system to begin asking the right questions, testing my assumptions, and learning the rest from first principles.

---

## Current Syllabus Status

**Version:** 0.1

**Status:** Initial detailed syllabus.

This document defines the intended learning path but should not yet be interpreted as a fixed calendar.

Lesson duration, number of exercises, exact assessment frequency, project timing, and depth should adapt to demonstrated understanding.

The next system-design task should define how an individual learning session actually operates from beginning to end.
