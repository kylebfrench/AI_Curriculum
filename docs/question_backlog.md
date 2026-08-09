# Question Backlog

## Purpose

This document defines how interesting questions, side topics, and future investigations should be captured without disrupting curriculum sequencing.

Curiosity is a strength.

However, advanced questions often depend on concepts that have not yet been learned.

The question backlog preserves those questions so they can be revisited at the right time.

---

## Core Principle

Do not suppress curiosity.

Do not allow curiosity to destroy prerequisite order.

When a useful question appears that would significantly derail the current lesson:

1. Acknowledge the question.
2. Capture it.
3. Identify why it is being deferred.
4. Identify likely prerequisites.
5. Assign it to a future module or topic.
6. Return to the current lesson.

---

## When to Backlog a Question

A question should usually be backlogged when:

- It depends on several concepts not yet introduced.
- Answering it properly would require a major topic jump.
- It would interrupt an active lab.
- It belongs to a later module.
- A superficial answer would create more confusion than value.
- The question is valuable enough that it should not be forgotten.

---

## When Not to Backlog a Question

Answer the question immediately when:

- It directly supports the current lesson.
- It clarifies a prerequisite.
- It can be answered briefly without creating scope drift.
- The learner needs the answer in order to continue safely.
- Delaying it would create unnecessary confusion.

The backlog should not become an excuse to avoid useful discussion.

---

## Backlog Entry Format

Use the following format for meaningful questions:

Question:

Why it matters:

Why it is deferred:

Prerequisites:

Planned module:

Status:

Notes:

---

## Backlog Status Values

Use:

- Backlogged
- Ready
- In Progress
- Answered
- No Longer Relevant

---

## Example Entry

Question:
How do multiple AI agents share memory?

Why it matters:
This is important for understanding multi-agent systems and orchestration.

Why it is deferred:
Single-agent state, memory, and tool calling have not yet been completed.

Prerequisites:
- Application state
- Memory
- Tool calling
- Single-agent systems

Planned module:
Multi-Agent Systems and Orchestration

Status:
Backlogged

Notes:
Revisit after the learner can clearly explain the difference between context, state, and persistent memory.

---

## Initial Curiosity Backlog

The following questions were identified during early course planning and may be revisited later.

### AI Infrastructure

How does a home AI server compare to AWS?

Planned area:

- Local AI
- Cloud infrastructure
- Hybrid systems

---

How would you host local agents?

Planned area:

- Local AI
- Containers
- Agent infrastructure
- Self-hosted systems

---

When does running local models make economic sense?

Planned area:

- Local AI
- Cost engineering
- Infrastructure tradeoffs

---

### AI Models and Tools

What exactly is Codex?

Planned area:

- AI development tools
- Model/application/tool categories

---

What makes one model better at coding than another?

Planned area:

- Model comparison
- AI-assisted development
- Evaluations

---

How do AI IDE agents actually control a computer or repository?

Planned area:

- AI coding agents
- Tool use
- Permissions
- Git workflow

---

What layer of the AI stack does Odysseus occupy?

Planned area:

- AI platforms
- Self-hosted applications
- Architecture teardown

---

How does a self-hosted AI workspace connect models, tools, MCP, memory, and local infrastructure?

Planned area:

- Self-hosted AI
- MCP
- Agents
- Local infrastructure
- Architecture teardown

---

### Agents and Orchestration

How do multi-agent systems actually communicate?

Planned area:

- Multi-agent systems
- Orchestration
- Shared state
- Agent communication

---

What is happening in memory versus context?

Planned area:

- Context engineering
- Application state
- Memory systems
- Agents

---

When is an agent actually better than a deterministic workflow?

Planned area:

- Agents
- Workflow design
- Product and systems thinking

---

### Open-Source and GitHub

How do I safely read and understand an unfamiliar open-source repository?

Planned area:

- GitHub
- Repository reading
- Architecture teardown

---

How do I safely clone, configure, and modify an unfamiliar open-source project?

Planned area:

- Git
- GitHub
- Environment setup
- Containers
- Self-hosted systems

---

How should AI coding agents interact with Git branches and commits?

Planned area:

- Git workflow
- AI-assisted development
- Recovery

---

### Product and Workflow Questions

Can AI development reduce SaaS subscription costs?

Planned area:

- Build versus buy
- AI product design
- Cost engineering

---

How would a card price monitoring agent work?

Planned area:

- APIs
- Databases
- Automation
- Agents
- Reporting

---

Can AI glasses become a persistent workplace copilot?

Planned area:

- Multimodal AI
- Latency
- Privacy
- Context
- Edge versus cloud
- Proactive agents

---

## Backlog Review Rules

The backlog should be reviewed:

- At major module boundaries.
- During Stop-and-Connect sessions.
- When a prerequisite becomes complete.
- When the learner asks whether a previously deferred question is now ready.
- During major curriculum reviews.

Do not review the entire backlog constantly.

---

## Promotion Rule

A question may move from Backlogged to Ready when its required prerequisites are sufficiently understood.

Example:

Question:
How do several agents share memory?

Previous Status:
Backlogged

Prerequisites now complete:
- Application state
- Persistent memory
- Single-agent systems

New Status:
Ready

At that point, the question may become:

- A short discussion.
- A lesson.
- A lab.
- A Stop-and-Connect topic.
- Part of an existing module.

---

## Curriculum Feedback Rule

If the backlog repeatedly contains questions around the same missing concept, that may indicate a curriculum gap.

The instructor should consider:

- Adding a lesson.
- Expanding an existing module.
- Adding a Stop-and-Connect session.
- Revising the dependency map.

The backlog should therefore also serve as feedback on curriculum design.

---

## Avoiding Backlog Bloat

Do not capture every passing thought.

A question belongs in the backlog when it is:

- Meaningful.
- Likely to be revisited.
- Educationally useful.
- Relevant to the long-term curriculum.

Delete or mark questions No Longer Relevant when they no longer provide value.

---

## Relationship to Progress Tracking

The question backlog is not the same as the reinforcement queue.

Question Backlog

Represents curiosity or future topics.

Reinforcement Queue

Represents concepts already taught that remain weak.

Keep these separate.

---

## Relationship to the Syllabus

Most backlog questions should eventually map to:

- An existing lesson.
- A module.
- A project.
- A lab.
- A Stop-and-Connect session.

If a valuable question does not fit anywhere, evaluate whether the syllabus should be updated.

---

## Current Status

**Version:** 1.0

**Status:** Initial question backlog system with starting questions inherited from course planning.

This document may eventually remain a specification while active backlog entries move into a separate living file.
