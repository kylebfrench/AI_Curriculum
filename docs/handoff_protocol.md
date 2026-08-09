# Handoff Protocol

## Purpose

This document defines how the AI Curriculum should transition between ChatGPT conversations without losing continuity.

The course should not depend on one extremely long conversation.

The GitHub repository should remain the durable source of truth.

ChatGPT conversations should be treated as temporary working sessions that read from and update that durable course state.

---

## Core Principle

A fresh conversation should be able to resume the learning journey without requiring access to the entire previous chat history.

The handoff should answer:

- Where are we in the curriculum?
- What was just learned?
- What does the learner currently understand?
- What remains weak?
- What work was completed?
- What files changed?
- What questions remain open?
- What should happen next?
- Did the instructor discover anything important about how the learner learns?

---

## When to Start a Fresh Chat

Do not wait until a conversation becomes unusably long.

Consider beginning a fresh conversation at logical boundaries such as:

- Completion of a major module.
- Completion of a significant lab.
- Completion of a project milestone.
- Completion of an assessment sequence.
- Transition into a substantially different technical topic.
- Completion of a Stop-and-Connect session.
- Excessive conversation length.
- Noticeable context drift.
- Too many unrelated subtopics accumulating.
- A point where a clean context would improve reasoning.

A new conversation is not a failure of continuity.

It is an intentional part of the learning architecture.

---

## When Not to Start a New Chat

Do not create a new conversation after every small lesson.

Keep the current conversation when:

- The current learning thread remains coherent.
- Necessary context is still manageable.
- A lab is actively in progress.
- The learner is working through one connected conceptual sequence.
- A fresh context would create more overhead than benefit.

The goal is clean context management, not constant restarting.

---

## Required Handoff Information

A meaningful handoff should capture the following.

### 1. Curriculum Position

Record:

- Phase.
- Module.
- Lesson.
- Session type.
- Current objective.

Example:

Phase: 4 — Networking, HTTP, and APIs
Module: 4.2 — HTTP
Lesson: HTTP Requests and Responses
Session Type: Concept + Exercise

---

### 2. What Was Covered

Briefly summarize the concepts addressed.

Do not reproduce the entire conversation.

Focus on durable learning information.

Example:

Covered:
- Client/server request flow
- HTTP request structure
- HTTP response structure
- Methods
- Headers
- Body
- Status codes

---

### 3. Demonstrated Understanding

Record what the learner can now explain or do.

Example:

Learner can now:
- Explain the difference between a client and server
- Describe the basic lifecycle of an HTTP request
- Identify method, URL, headers, and body

This section should be based on actual evidence rather than assumptions.

---

### 4. Weak or Developing Concepts

Record concepts that remain unstable.

Example:

Developing:
- Difference between HTTP headers and request body

Needs reinforcement:
- Authentication header flow

Do not hide weak understanding in order to make the handoff look successful.

---

### 5. Misconceptions Discovered

Record important misunderstandings that future instruction should remember.

Example:

Misconception:
The learner initially believed that HTTP headers contain the main application data.

Correction:
Headers primarily carry metadata about the request or response, while the body commonly carries the primary payload.

Only record misconceptions worth preserving.

---

### 6. Labs and Exercises Completed

Record meaningful hands-on work.

Include:

- Lab or exercise name.
- Completion status.
- Important result.
- Relevant repository location.

Example:

Lab:
Inspect an HTTP request

Status:
Completed with support

Repository:
labs/http/inspect_request/

---

### 7. Files Created or Changed

Record repository changes made during the session.

Example:

Files changed:
- notes/http_requests.md
- labs/http/inspect_request/README.md
- progress/current_progress.md

This helps the next conversation know which files may need to be reviewed.

---

### 8. Assessment Results

If an assessment occurred, summarize:

- What was tested.
- What was demonstrated.
- Weak areas.
- Resulting action.

Example:

Assessment:
HTTP Mental Model Check

Result:
Functional

Strength:
Can trace request and response direction

Weakness:
Still developing understanding of authentication headers

Action:
Quick reinforcement before API authentication lesson

---

### 9. Learning Profile Signals

Record only meaningful instructional discoveries.

Examples:

Learning Profile Signal:
The visual request/response diagram significantly improved understanding.

Possible future adaptation:
Use simple architecture diagrams when introducing communication flows.

Do not modify the Learning Profile for every isolated observation.

---

### 10. Question Backlog Updates

Record important deferred questions.

Example:

Question:
How do several AI agents communicate with each other?

Deferred because:
Single-agent state and tool calling have not yet been completed.

Planned module:
Multi-Agent Systems and Orchestration

---

### 11. Reinforcement Queue

Record any concepts that need future review.

Example:

Reinforcement:
HTTP headers

Review before:
API authentication

---

### 12. Exact Recommended Next Step

Every handoff should end with a specific next action.

Avoid vague statements such as:

> Continue networking.

Prefer:

> Begin Module 4.3, Lesson 1: JSON Objects, after a five-minute review of HTTP headers versus request bodies.

The next conversation should not have to reconstruct the sequencing decision.

---

## Standard Handoff Template

Use the following structure for a formal handoff:

```markdown
# Session Handoff

## Session Information

Date:
Session:
Phase:
Module:
Lesson:
Session Type:

## Primary Objective

## What Was Covered

## What the Learner Can Now Explain or Do

## Current Understanding Status

Strong:

Functional:

Developing:

Needs Reinforcement:

## Misconceptions Discovered

## Labs / Exercises Completed

## Assessments Completed

## Repository Changes

## Learning Profile Signals

## Question Backlog Updates

## Reinforcement Queue

## Unresolved Questions

## Current Curriculum Position

## Exact Recommended Next Lesson

## Files the Next Chat Should Read

## Additional Instructor Notes
```

Sections with no meaningful content may be marked:

None

Do not invent information simply to fill every section.

---

## Handoff File Naming

Actual handoff files should eventually live in:

handoffs/

Recommended naming convention:

handoffs/YYYY-MM-DD_session-handoff.md

Example:

handoffs/2026-08-08_session-handoff.md

If multiple handoffs occur on the same day, use:

handoffs/2026-08-08_session-01-handoff.md
handoffs/2026-08-08_session-02-handoff.md

Use simple, predictable names.

---

## Latest Handoff Strategy

The most recent handoff should always be easy to identify.

Possible future approaches include:

- Sorting handoffs by date.
- Maintaining an index.
- Maintaining a small "latest_handoff.md" file.

Do not create unnecessary duplicate systems yet.

Initially, date-based filenames are sufficient.

---

## Fresh Chat Startup Package

When beginning a new ChatGPT conversation, provide the minimum repository context required to re-establish the course.

The ideal package is:

### 1. Core course instructions.
### 2. Latest session handoff.
### 3. Current progress record.
### 4. Specific files needed for the upcoming lesson.

Do not automatically provide the entire repository.

The purpose is to provide enough context without recreating the same context-window problem the repository was designed to solve.

---

## Core Documents for Re-Anchoring

If the instructor begins drifting from the learning system, re-anchor using relevant core documents.

Important documents include:

README.md
docs/course_charter.md
docs/instructor_operating_guidelines.md
docs/learning_profile.md
docs/curriculum_architecture.md
docs/concept_dependency_map.md
docs/syllabus.md
docs/session_template.md
docs/progress_tracking.md
docs/reflection_system.md
docs/handoff_protocol.md

Not every fresh conversation needs every document.

Use only what is necessary for the task.

---

## Recommended Fresh Chat Opening

A new conversation may begin with an instruction similar to:

> We are continuing my AI Curriculum learning journey. Treat the attached repository files as the source of truth. Read the latest handoff and current progress record first. Re-anchor to the Course Charter and Instructor Operating Guidelines when necessary. Do not restart the curriculum. Continue from the exact recommended next lesson unless the handoff reveals a prerequisite that needs reinforcement.

This opening may evolve as the learning system matures.

---

## Source-of-Truth Rule

When information conflicts:

### 1. The most recently and deliberately updated repository artifact should generally be preferred.
### 2. Current progress evidence should override outdated assumptions.
### 3. The latest handoff should describe the current session state.
### 4. The Course Charter should govern stable learning principles.
### 5. The Learning Profile should reflect current instructional preferences.
### 6. The syllabus should guide sequencing.
### 7. The dependency map should govern prerequisites.

If a conflict is significant, identify it rather than silently choosing one version.

---

## Context Efficiency Rule

Do not use handoffs as transcripts.

A good handoff preserves decisions and state, not conversation history.

Avoid including:

- Repeated explanations.
- Long conversational exchanges.
- Irrelevant tangents.
- Full code unless specifically needed.
- Every question asked.
- Every minor correction.

Capture only what the next conversation needs to continue accurately.

---

## Lab Handoff Rule

Do not switch conversations in the middle of an active technical problem unless necessary.

If a conversation must change during a lab, preserve additional technical state such as:

- Current repository branch.
- Last successful command.
- Current error.
- Relevant log output.
- Files being modified.
- Hypotheses already tested.
- Exact next debugging action.

This prevents the next conversation from repeating failed troubleshooting.

---

## Project Handoff Rule

For larger projects, include:

- Current architecture.
- Current milestone.
- Recent implementation decisions.
- Known bugs.
- Pending tasks.
- Relevant branches.
- Relevant commits where useful.
- Testing status.
- Important constraints.

The project repository itself should remain the primary technical source of truth.

---

## Long-Break Handoff Rule

If the learner expects a substantial break:

Include additional orientation such as:

- Last major milestone.
- Key concepts worth reviewing.
- Likely knowledge decay risks.
- Recommended lightweight diagnostic when returning.

Do not assume the learner will remember the exact prior context months later.

---

## Handoff Quality Check

Before closing a conversation, verify that a fresh instructor could answer:

- Where are we?
- What was learned?
- What is weak?
- What changed?
- What do I need to read?
- What exactly happens next?

If any of these are unclear, improve the handoff before ending the session.

---

## Relationship to Progress Tracking

The handoff and progress system overlap but serve different purposes.

### Progress Tracking

Represents the durable state of the overall course.

### Handoff

Represents the transition state between conversations.

The handoff may reference the progress record rather than duplicating all of it.

---

## Relationship to Reflection

Reflection captures:

> What did we learn about the learning process?

Handoff captures:

> What does the next conversation need to continue?

Important reflection findings may be summarized in the handoff when they affect future instruction.

---

## Handoff Creation Frequency

Create a formal handoff when:

- Starting a fresh conversation.
- Completing a major module.
- Completing a major project stage.
- Ending a long or context-heavy learning sequence.
- Taking a significant break.

Do not create a formal handoff after every minor lesson unless the conversation is actually ending.

---

## Ultimate Goal

The repository should make conversations replaceable without making the learning journey disposable.

A fresh ChatGPT session should be able to enter the course, understand the learner's current position, follow the established teaching system, and continue the journey without requiring access to months of previous chat history.

---

## Current Status

**Version:** 1.0

**Status:** Initial handoff protocol.

Actual handoff files should begin when active coursework starts or when the current design conversation ends.
