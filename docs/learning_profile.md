# Learning Profile

## Purpose

This document is a living profile of how I learn best, what I currently understand, where my technical foundations are incomplete, and how the instructional approach should adapt over time.

This profile should not be treated as permanent.

It should evolve based on evidence from lessons, labs, assessments, reflections, and actual learning outcomes.

---

## Current Learning Preferences

### Conversation First

I learn well through conversation.

Talking through concepts helps me reason, identify gaps, ask follow-up questions, and connect new ideas to things I already understand.

Voice conversation should be used frequently for:

- Concept explanations.
- Socratic questioning.
- Mental-model development.
- Reviewing understanding.
- Brainstorming.
- Reflection.
- Connecting concepts across modules.

Voice should not be forced when text, code, diagrams, tables, logs, or other visual formats would provide a clearer learning experience.

---

### Granularity Preference

I prefer highly granular explanations.

When learning an important technical concept, I generally want to understand:

- What it is.
- Why it exists.
- What problem it solves.
- What came before it.
- What it communicates with.
- What information goes into it.
- What information comes out of it.
- What happens internally at an appropriate level.
- What can go wrong.
- What alternatives exist.
- Where it fits in the larger technical stack.
- How it appears in a real system.

Large conceptual jumps should be avoided.

If a concept feels confusing, the default response should be to break it into smaller pieces rather than simply repeating the same explanation.

---

### Understanding Before Implementation

I want to understand concepts before relying heavily on tools or abstractions.

AI should not be allowed to hide important technical details merely because it can generate working code.

When possible, I should understand the underlying operation before depending on a tool that automates it.

Examples include:

- Understanding Git concepts before relying entirely on an IDE's Git interface.
- Understanding HTTP before heavily using REST APIs.
- Understanding databases before vector databases.
- Understanding model APIs before tool calling and agents.
- Understanding containers before using them as unexplained infrastructure.

---

### Systems Thinking

I prefer understanding how pieces connect.

Individual concepts should frequently be tied back to a larger system.

Useful questions include:

- What happens before this component?
- What happens after it?
- What does it depend on?
- What depends on it?
- Where does the data move?
- What would happen if this component disappeared?
- Which part of the system owns this responsibility?

The curriculum should periodically include dedicated sessions focused on connecting previously learned concepts.

---

### Practical Learning

I want practical examples and hands-on labs.

Labs should resemble structured coursework rather than demonstrations where the instructor performs every step.

I should make meaningful decisions during labs and be expected to explain what happened.

Early labs should remain intentionally small.

Complexity should increase only as the required prerequisites become familiar.

---

### Assessment Preference

I want assessments to help determine whether I genuinely understand a concept.

Useful assessment methods may include:

- Explaining a concept in my own words.
- Predicting what will happen.
- Debugging a small problem.
- Interpreting code.
- Writing simple code.
- Writing pseudocode.
- Reading a diagram.
- Drawing a simple architecture.
- Comparing two approaches.
- Identifying a flawed design.
- Teaching a concept back to the instructor.

Assessments should be diagnostic, not punitive.

The purpose is to find weak foundations early.

---

### Current Technical Position

I am not starting from zero.

I already have some conceptual familiarity with:

- AI tools.
- Agent-based workflows.
- Nodes and multi-step workflows.
- Outputs feeding later steps in a workflow.
- Agents.
- Agent orchestration.
- Local AI models.
- Cloud AI models.
- AI-assisted development.
- AI-enabled project work.
- Basic GitHub repository usage.

However, familiarity with terminology should not automatically be treated as technical understanding.

Many foundational concepts remain incomplete, fuzzy, or untested.

The course should therefore diagnose my actual understanding before deciding how deeply each topic needs to be taught.

---

### Known Strengths

Current likely strengths include:

- Logical reasoning.
- Thinking in terms of systems and dependencies.
- Comfort working through rules and structured processes.
- Curiosity about how systems work underneath the interface.
- Willingness to ask "why."
- Interest in understanding technical relationships rather than isolated facts.
- Practical motivation to build useful systems.
- Willingness to revisit foundational topics.

These assumptions should be tested rather than permanently accepted.

---

### Known Learning Risks

### Taking Steps That Are Too Large

A recurring risk is attempting a project or implementation step that contains too many unfamiliar concepts at once.

The instructor should actively watch for this.

When a task becomes too large:

1. Stop.
2. Identify the individual concepts involved.
3. Determine which of those concepts are already understood.
4. Separate unfamiliar pieces.
5. Reduce the task to the smallest useful next step.

The default should be smaller steps than might ordinarily seem necessary.

---

### Allowing AI to Create False Progress

Because modern AI tools can generate code and entire applications quickly, there is a risk of producing working systems without actually understanding them.

The instructor should distinguish between:

- Something I built and understand.
- Something AI generated that I can explain.
- Something AI generated that works but I do not yet understand.

Only the first two should count as meaningful learning progress.

---

### Recognizing Words Without Understanding Them

Familiar terminology can create an illusion of understanding.

The instructor should periodically test important concepts with questions such as:

- Explain it without using the term itself.
- What problem does it solve?
- Why was it created?
- What happens if we remove it?
- What does it communicate with?
- How is it different from a related concept?

---

### Curiosity Causing Scope Drift

I frequently generate additional questions and ideas while learning.

This curiosity is useful, but it can pull the lesson away from its prerequisites.

Interesting questions that would create significant scope drift should be captured in a question backlog and revisited when the necessary foundations have been learned.

---

## AI and Coding Tools

I want to learn how to use AI development tools effectively, but I do not want my technical ability to become dependent on any single product.

The learning system should distinguish between categories such as:

- Foundation models.
- Chat applications.
- APIs and SDKs.
- IDEs.
- AI coding agents.
- Command-line coding agents.
- Agent frameworks.
- Orchestration systems.
- Local model runtimes.
- Self-hosted AI workspaces.
- Cloud AI platforms.
- Version-control platforms.
- Tool and MCP ecosystems.

Specific tools may be used as case studies, but transferable concepts should come first.

---

## Git and GitHub

Git and GitHub should be treated as foundational engineering skills.

I currently have basic exposure to GitHub repositories, but Git and GitHub fundamentals should be taught explicitly.

Important future areas include:

- Version control.
- Repositories.
- Commits.
- Staging.
- Branches.
- Merging.
- Diffs.
- Pull requests.
- Rollbacks.
- Merge conflicts.
- Remote repositories.
- Safe handling of secrets.
- Working with AI coding tools while preserving version control.

The AI Curriculum repository itself should eventually become part of this learning process.

---

## Professional Direction

This learning journey should support practical capability that transfers into professional environments involving AI operations, AI enablement, AI-assisted workflows, and modern technical systems.

The curriculum should emphasize capabilities that remain useful even as specific tools change.

Examples include:

- Understanding system architecture.
- Reasoning about workflows.
- Evaluating AI tools.
- Designing human and AI responsibilities.
- Working with developers and technical teams.
- Understanding APIs, infrastructure, models, data, agents, and automation.
- Debugging AI-enabled systems.
- Communicating technical concepts clearly.
- Making informed implementation and architecture decisions.

---

## Home Lab and Personal Building Goals

The learning journey should also support hands-on experimentation outside of work.

Potential areas include:

- Small Python applications.
- API projects.
- Databases.
- AI-enabled applications.
- Local models.
- Home AI infrastructure.
- Agents.
- Tool-using agents.
- Automation.
- RAG systems.
- Model experimentation.
- Open-source software.
- Self-hosted AI applications.
- Hardware and infrastructure experiments when justified.

Expensive hardware should not be treated as an early prerequisite.

Learn first.

Scale infrastructure when the learning goals justify it.

---

## Reflection Questions

At the end of meaningful lessons, modules, or labs, the instructor should periodically consider:

- What explanation worked?
- What explanation did not work?
- Was the pace appropriate?
- Were the steps small enough?
- Did conversation help?
- Did a diagram or visual help?
- Did the analogy help?
- Was the exercise useful?
- What concepts remain fuzzy?
- Where did I demonstrate strong understanding?
- Where did I rely too heavily on AI?
- What should change in the next lesson?

Not every lesson requires a formal written reflection.

Important findings should be captured when they are likely to improve future instruction.

---

## Adaptation Rules

Teaching tactics may change as evidence accumulates.

Examples:

- Increase visual explanations if diagrams consistently improve understanding.
- Increase hands-on work if practical exercises produce stronger retention.
- Slow the pace if foundational gaps appear.
- Move faster through concepts that can already be clearly explained and applied.
- Use different analogies when an explanation fails.
- Increase independent work as technical confidence improves.

The learning system should adapt without constantly rewriting its core philosophy.

---

## Learning Profile Version

**Version:** 1.0

**Status:** Initial profile based on the pre-course design conversation and starting assumptions.

This profile should be revised when actual learning evidence demonstrates that an assumption is incomplete, incorrect, or no longer useful.
