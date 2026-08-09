# Curriculum Architecture

## Purpose

This document defines the high-level architecture of the AI Curriculum.

It is not yet the complete syllabus.

Its purpose is to establish the major learning phases, the relationships between them, and the progression logic that should guide the eventual detailed curriculum.

The curriculum should remain adaptable as:

- My technical understanding grows.
- New tools and frameworks emerge.
- Existing technologies change.
- Labs reveal strengths or weaknesses.
- Professional goals evolve.
- Better teaching approaches are discovered.

The architecture should remain relatively stable even when individual lessons or tools change.

---

## Core Curriculum Principle

The curriculum should teach:

> Computer science through the lens of AI.

The goal is not to create separate disconnected courses in:

- Programming.
- Artificial intelligence.
- Git.
- Databases.
- APIs.
- Infrastructure.
- Agents.

Instead, these subjects should progressively connect into one coherent mental model of how modern AI-enabled systems work.

---

## Progression Philosophy

The curriculum should be built around prerequisites rather than excitement or trendiness.

A topic should generally appear only when the learner understands enough of its prerequisites for the topic to make meaningful sense.

Examples include:

- Files and command-line basics before serious repository work.
- Git fundamentals before relying heavily on GitHub workflows.
- Variables before functions.
- Basic Python before Python-based API clients.
- HTTP before REST APIs.
- JSON before API payloads.
- Databases before vector databases.
- Embeddings before vector search.
- Model APIs before tool calling.
- Tool calling before agents.
- Single-agent systems before multi-agent orchestration.
- Containers before meaningful self-hosted AI deployments.
- Local and cloud model fundamentals before configuring multi-model platforms.

The curriculum may be presented linearly, but the underlying learning model should be treated as a dependency graph.

---

## Capability Progression

The program should progressively develop several capability levels.

These levels are directional rather than rigid certifications.

## Level 0 — Technical Orientation

Develop a coherent mental model of:

- Computers.
- Software.
- Data.
- Networks.
- Programs.
- Models.
- AI.
- Cloud systems.
- Local systems.

The learner should begin understanding where different technologies sit within the overall stack.

---

## Level 1 — AI-Literate Operator

Develop the ability to work deliberately with modern AI systems.

Capabilities should include:

- Understanding what LLMs are at an intuitive technical level.
- Understanding model limitations.
- Prompting effectively.
- Structuring context.
- Evaluating model output.
- Understanding common AI applications.
- Identifying major layers of the AI ecosystem.
- Distinguishing models, applications, agents, IDEs, runtimes, and orchestration platforms.

---

## Level 2 — Technical Builder

Develop foundational software engineering capability.

Capabilities should include:

- Basic command-line use.
- Git and GitHub.
- Python.
- SQL.
- Data handling.
- APIs.
- HTTP.
- JSON.
- Basic debugging.
- Basic application architecture.
- Basic cloud concepts.

The learner should be capable of creating small working software systems with AI assistance while understanding the major components.

---

## Level 3 — AI Application Builder

Develop the ability to build AI-enabled applications.

Capabilities should include:

- Model APIs.
- SDKs.
- API authentication.
- Structured outputs.
- Streaming.
- Error handling.
- Tool calling.
- Function calling.
- Embeddings.
- Vector search.
- RAG.
- Memory.
- State.
- Single-agent systems.
- Workflow design.
- Evaluations.
- Basic observability.

---

## Level 4 — AI Systems Operator

Develop the ability to understand and operate larger AI systems.

Capabilities should include:

- Multi-component architectures.
- Agent orchestration.
- Local models.
- Cloud models.
- Model routing.
- Containers.
- Infrastructure.
- Logging.
- Monitoring.
- Reliability.
- Latency.
- Cost management.
- Privacy.
- Security boundaries.
- Human-in-the-loop systems.
- Self-hosted AI applications.

---

## Level 5 — AI Systems Architect

Develop the ability to reason about unfamiliar systems and design appropriate architectures.

Capabilities should include:

- Selecting architectural patterns.
- Evaluating tools and frameworks.
- Comparing build-versus-buy options.
- Designing system boundaries.
- Designing agent workflows.
- Selecting local versus cloud infrastructure.
- Managing tradeoffs between cost, latency, quality, privacy, and reliability.
- Directing AI coding tools safely.
- Evaluating unfamiliar repositories.
- Designing systems from requirements rather than from favorite tools.

---

## Proposed Curriculum Phases

The detailed modules inside these phases will be designed separately.

---

# Phase 0 — Orientation and Baseline

## Purpose

Establish the initial technical mental model and diagnose current understanding.

### Major Areas

- What computers actually do.
- What software is.
- What a program is.
- What data is.
- What computation means.
- What AI is.
- What machine learning is.
- What an AI model is.
- What makes AI different from ordinary software.
- Where local and cloud computing fit.
- Initial technical baseline assessment.

### Outcome

The learner should have a basic map of the territory before deeper instruction begins.

---

# Phase 1 — Computer and Software Foundations

## Purpose

Build the software and computing concepts required for later engineering work.

### Major Areas

- CPU.
- RAM.
- Storage.
- Operating systems.
- Processes.
- Files and directories.
- Command line.
- Source code.
- Programs.
- Compilation versus interpretation.
- Variables.
- Data types.
- Logic.
- Functions.
- Control flow.
- Errors.
- Debugging.
- Data structures.
- Algorithms at an appropriate practical level.

### Outcome

The learner should understand the basic machinery underneath software development.

---

# Phase 2 — Git, GitHub, and Engineering Workflow

## Purpose

Establish safe, professional project workflow early enough that later labs use version control correctly from the beginning.

### Major Areas

- Version control.
- Git versus GitHub.
- Local versus remote repositories.
- Repository structure.
- README files.
- .gitignore.
- Staging.
- Commits.
- Commit history.
- Diffs.
- Branches.
- Merging.
- Merge conflicts.
- Pull requests.
- Issues.
- Cloning.
- Pulling.
- Fetching.
- Pushing.
- Reverting.
- Recovery.
- Secrets and credentials.
- GitHub as a portfolio surface.
- Reading unfamiliar repositories.
- Safe Git workflows with AI coding agents.

### Core Lab

Create a small repository, make intentional changes, commit them, create a branch, introduce a controlled mistake, inspect the diff, and recover from the mistake.

### Outcome

The learner should understand how version control protects engineering work and enables experimentation.

---

# Phase 3 — Programming With Python

## Purpose

Build enough programming capability to reason about and create small software systems.

### Major Areas

- Python syntax.
- Variables.
- Data types.
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
- Errors and exceptions.
- Basic testing.
- Debugging.
- Packages.
- Virtual environments.
- Reading documentation.

### Example Labs

- Calculator.
- Simple command-line utility.
- File-processing utility.
- Small data transformation program.

### Outcome

The learner should be able to read, modify, and write small Python programs and explain their behavior.

---

# Phase 4 — Networking, HTTP, APIs, and Data Exchange

## Purpose

Explain how software systems communicate.

### Major Areas

- Client and server.
- Internet fundamentals.
- Networking concepts.
- IP addresses.
- Ports.
- DNS at an appropriate level.
- HTTP.
- Requests.
- Responses.
- Methods.
- Headers.
- Status codes.
- JSON.
- REST concepts.
- APIs.
- API keys.
- Authentication.
- Rate limits.
- Errors.
- SDKs.

### Example Labs

- Inspect an HTTP request.
- Call a simple public API.
- Build a basic Python API client.
- Build a weather-style application using an API.

### Outcome

The learner should understand what happens when one software system requests information or functionality from another.

---

# Phase 5 — Databases and Persistent Data

## Purpose

Build the data foundations required for applications, memory systems, analytics, and RAG.

### Major Areas

- Why databases exist.
- Tables.
- Rows.
- Columns.
- Schemas.
- Primary keys.
- Relationships.
- SQL.
- Queries.
- Filtering.
- Sorting.
- Joins.
- Inserts.
- Updates.
- Deletes.
- Indexes at an appropriate level.
- Application-to-database communication.

### Example Labs

- Tiny SQL database.
- Small application storing persistent data.
- Query and update exercises.

### Outcome

The learner should understand how structured data is stored, retrieved, and connected to software applications.

---

# Phase 6 — AI and LLM Foundations

## Purpose

Develop a meaningful technical mental model of modern AI systems.

### Major Areas

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
- Embeddings.
- Transformers.
- Attention at an intuitive level.
- Model families.
- Model providers.
- Model size and capability tradeoffs.

### Outcome

The learner should understand what an LLM is, what it is doing at a meaningful conceptual level, and what it is not doing.

---

# Phase 7 — Prompting and Context Engineering

## Purpose

Develop deliberate techniques for interacting with models before building larger AI systems.

### Major Areas

- Prompt objectives.
- Constraints.
- Examples.
- Context.
- Roles when useful.
- Structured output.
- Decomposition.
- Iteration.
- Verification.
- Prompt debugging.
- Context engineering.
- Source material.
- Instruction hierarchy.
- Maintaining state.
- Handoffs.
- Model limitations.
- Output evaluation.

### Important Principle

Large tasks should usually be decomposed into smaller, verifiable steps rather than delegated as one enormous prompt.

### Outcome

The learner should be able to reason about why a model receives particular instructions and why those instructions produce different outcomes.

---

# Phase 8 — AI Development Tools and Platforms

## Purpose

Teach how modern AI development environments fit into the larger technical ecosystem.

### Categories

- Foundation models.
- Chat applications.
- APIs.
- SDKs.
- IDEs.
- AI coding agents.
- Command-line agents.
- Agent frameworks.
- Orchestration systems.
- Self-hosted AI workspaces.
- Local model runtimes.
- Cloud AI platforms.
- MCP and tool ecosystems.
- Git and repository platforms.

### Major Skills

- Repository context.
- Context selection.
- Planning before coding.
- Small-ticket implementation.
- Reviewing diffs.
- Testing AI-generated code.
- Debugging.
- Reading logs.
- Model selection.
- Cost management.
- Environment setup.
- Package management.
- Preventing AI coding agents from drifting.
- Evaluating new AI products by category and underlying function.

### Outcome

The learner should be able to use modern AI development tools while understanding what they are doing underneath.

---

# Phase 9 — Model APIs and AI Application Engineering

## Purpose

Move from using AI applications to building software that communicates directly with models.

### Major Areas

- Model APIs.
- SDKs.
- Authentication.
- API keys.
- Requests.
- Responses.
- JSON payloads.
- Streaming.
- Error handling.
- Rate limits.
- Logging.
- Costs.
- Structured output.
- Application state.

### Example Labs

- Basic model API call.
- Structured-response application.
- Small AI-enabled command-line application.

### Outcome

The learner should understand the complete path between an application and an AI model.

---

# Phase 10 — Embeddings, Vector Search, and RAG

## Purpose

Teach how applications retrieve external knowledge for model use.

### Major Areas

- Embeddings.
- Semantic similarity.
- Vector representation.
- Vector search.
- Vector databases.
- Chunking.
- Retrieval.
- Context injection.
- RAG architecture.
- Retrieval quality.
- Common failure modes.
- Evaluation.

### Example Labs

- Simple embedding experiment.
- Document similarity search.
- Small document-search application.
- Basic RAG system.

### Outcome

The learner should understand why retrieval exists, what problem it solves, and how information moves through a RAG system.

---

# Phase 11 — Tools, Function Calling, and Agents

## Purpose

Progress from model responses to systems capable of taking structured actions.

### Major Areas

- Tool calling.
- Function calling.
- Tool schemas.
- Agent loops.
- State.
- Memory.
- Planning.
- Observation.
- Action.
- Human approval.
- Failure recovery.
- Single-agent architecture.
- Workflow architecture.

### Example Labs

- Tool-calling model.
- Simple single agent.
- Tool-using agent.
- Multi-step workflow.

### Outcome

The learner should understand exactly what makes a system an agent rather than simply a chatbot.

---

# Phase 12 — Multi-Agent and Orchestration Systems

## Purpose

Explore more complex systems only after single-agent design is understood.

### Major Areas

- Agent responsibilities.
- Agent communication.
- Shared state.
- Orchestration.
- Routing.
- Supervisors.
- Specialized agents.
- Failure propagation.
- Observability.
- Cost.
- Latency.
- Coordination overhead.
- When multiple agents are unnecessary.

### Outcome

The learner should understand both the advantages and the costs of multi-agent architectures.

---

# Phase 13 — Local AI and Infrastructure

## Purpose

Understand how AI workloads run on hardware and infrastructure.

### Major Areas

- CPU versus GPU.
- GPU fundamentals.
- VRAM.
- Model sizes.
- Quantization.
- Local models.
- Local inference.
- Inference servers.
- Home servers.
- Cloud infrastructure.
- Local versus cloud.
- Hybrid architecture.
- Containers.
- Virtualization.
- Docker.
- Services.
- Networking.
- Environment variables.
- Secrets.
- Storage.
- Infrastructure cost.

### Outcome

The learner should understand enough infrastructure to reason about hosting and operating AI systems without immediately purchasing expensive hardware.

---

# Phase 14 — AI Systems Engineering

## Purpose

Combine application, agent, data, and infrastructure knowledge into larger system thinking.

### Major Areas

- Reliability.
- Latency.
- Cost engineering.
- Logging.
- Monitoring.
- Observability.
- Evaluations.
- Guardrails.
- Privacy.
- Security.
- Authentication.
- Permissions.
- Human-in-the-loop design.
- Failure recovery.
- Data boundaries.
- Production tradeoffs.

### Outcome

The learner should be able to identify likely failure points and operational risks in an AI-enabled system.

---

# Phase 15 — AI Product and Workflow Design

## Purpose

Build judgment about where AI should and should not be used.

### Major Areas

- Workflow decomposition.
- Automation opportunities.
- Human control.
- Approval gates.
- AI feature usefulness.
- When agents are overkill.
- Trust.
- User experience.
- Proactive AI.
- Monitoring.
- Metrics.
- Build versus buy.
- Horizontal versus vertical AI systems.
- Product-market-fit concepts at an appropriate level.

### Outcome

The learner should be able to distinguish technically interesting AI from genuinely useful system design.

---

# Phase 16 — Open-Source Repository Reading and Architecture Teardown

## Purpose

Develop the ability to understand unfamiliar real-world software.

### Major Areas

- Reading README files.
- Documentation.
- Repository trees.
- Source folders.
- Configuration.
- Issues.
- Releases.
- Contribution guides.
- Dependencies.
- Frontend versus backend.
- Services.
- APIs.
- Containers.
- Logs.
- Secrets.
- Security boundaries.

### Progressive Case Study

Odysseus / Project Odysseus may be used here as a real-world case study once the necessary prerequisites are familiar.

The goal is to transform an initially intimidating repository into a system whose components can be recognized and explained.

### Outcome

The learner should become increasingly comfortable opening an unfamiliar repository and forming an accurate architectural mental model.

---

# Phase 17 — Guided Self-Hosted AI Lab

## Purpose

Apply infrastructure, Git, API, agent, model, container, and security concepts in a controlled environment.

A later Odysseus installation or similar self-hosted platform may be used if it remains educationally appropriate.

### Possible Learning Objectives

- Clone an unfamiliar repository.
- Read documentation before executing commands.
- Understand Docker Compose at a practical level.
- Configure environment variables.
- Protect credentials.
- Connect a hosted model.
- Connect a local model where practical.
- Explore tools or agents.
- Inspect logs.
- Trace requests across components.
- Make controlled configuration changes.
- Use Git to isolate modifications.
- Explain the architecture afterward.

### Outcome

The learner should understand what the installation is doing rather than merely following setup instructions.

---

# Phase 18 — Portfolio and Capstone Systems

## Purpose

Demonstrate integrated technical understanding through larger projects.

Projects should require progressively greater independence.

Potential projects may include:

- AI-enabled applications.
- Data and API automation.
- RAG applications.
- Agent systems.
- Local AI experiments.
- Workflow automation.
- Open-source modifications.
- Portfolio-quality technical systems.

Career OS may be revisited at this stage as a capstone or architecture case study.

It should not organize the earlier curriculum.

### Outcome

The learner should demonstrate the ability to reason about architecture, implementation, debugging, AI assistance, Git workflow, and technical tradeoffs in a substantial system.

---

## Stop-and-Connect Sessions

Dedicated integration sessions should appear throughout the curriculum.

These sessions introduce little or no major new material.

Their purpose is to connect concepts already learned.

Examples include:

## Connection Session — Software Stack

Connect:

- Operating system.
- Programs.
- Python.
- Files.
- Processes.
- Memory.

## Connection Session — Application Communication

Connect:

- Client.
- Server.
- HTTP.
- JSON.
- APIs.
- Authentication.
- Databases.

## Connection Session — AI Application Request

Trace:

- User input.
- Application.
- Model API.
- HTTP request.
- JSON payload.
- Model inference.
- Response.
- Application output.

## Connection Session — RAG System

Trace:

- Documents.
- Chunking.
- Embeddings.
- Vector database.
- Retrieval.
- Prompt context.
- Model.
- Answer.

## Connection Session — Agent System

Trace:

- User goal.
- Model reasoning.
- Tool selection.
- Function call.
- External system.
- Tool result.
- Model response.
- State or memory.

## Connection Session — Full AI System

Trace a realistic architecture containing:

- User interface.
- Backend.
- APIs.
- Database.
- Model.
- Retrieval.
- Tools.
- Agents.
- Infrastructure.
- Logging.
- Security boundaries.

---

## Lab Progression

Labs should increase in complexity gradually.

A general progression may resemble:

1. Observe.
2. Modify.
3. Build with guidance.
4. Build from a specification.
5. Debug intentionally broken systems.
6. Design a small solution.
7. Build independently with instructor review.
8. Architect and justify a larger system.

AI assistance may be used at every level, but learner responsibility should increase over time.

---

## Project Progression

Projects should not begin as large applications.

A possible progression includes:

- Tiny utilities.
- Single-concept labs.
- Small Python programs.
- API clients.
- Database applications.
- AI API applications.
- Document search.
- RAG systems.
- Tool-using agents.
- Workflow systems.
- Local-model experiments.
- Open-source architecture analysis.
- Integrated AI applications.
- Capstone systems.

Every project should have a clear educational purpose.

---

## Assessment Architecture

Assessment should occur at multiple levels.

### Lesson Checks

Small conversational checks for immediate comprehension.

### Module Assessments

More substantial checks of concepts and application.

### Practical Assessments

Tasks involving debugging, building, comparison, or system reasoning.

### Integration Assessments

Exercises that require connecting multiple previously learned concepts.

### Capstone Assessment

Evaluation based on the ability to reason about and build a larger unfamiliar or partially unfamiliar technical system.

---

## Curriculum Adaptation

The curriculum should not be followed mechanically.

Future instruction may:

- Compress material already understood.
- Expand weak areas.
- Insert prerequisite lessons.
- Change examples.
- Replace outdated tools.
- Add important new technologies.
- Remove low-value technologies.
- Reorder lessons when the dependency graph justifies it.

Any significant architectural change should preserve the North Star:

> Build transferable understanding of how modern software and AI systems work and how their components connect.

---

## Curriculum Status

**Version:** 0.1

**Status:** High-level architecture only.

The next stage is to build a formal concept dependency map and then use that map to refine the sequencing of modules, chapters, labs, and assessments.

This document should not yet be treated as the final detailed syllabus.
