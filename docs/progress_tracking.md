# Progress Tracking

## Purpose

This document defines how progress is tracked throughout the AI Curriculum.

Progress should reflect demonstrated understanding and practical capability rather than simply counting completed lessons, hours studied, or projects attempted.

The tracking system should answer four questions:

1. What has been introduced?
2. What is actually understood?
3. What needs reinforcement?
4. What should happen next?

---

## Core Principle

Completion is not the same as understanding.

A lesson may be finished while the underlying concept is still weak.

The primary unit of progress should therefore be demonstrated capability.

---

## Understanding Status Levels

Use the following status levels for important concepts, modules, and skills.

### Not Introduced

The learner has not formally studied the topic yet.

---

### Introduced

The learner has encountered the concept and can recognize the basic terminology.

The learner may not yet be able to explain or apply it independently.

---

### Developing

The learner understands some of the concept but still needs support.

Typical signs:

- Can explain parts of it.
- Needs prompting.
- Confuses related concepts.
- Can follow examples but struggles to create or modify one.
- Understanding is inconsistent.

---

### Functional

The learner can use and explain the concept at the level required for the current curriculum.

Typical signs:

- Can explain the concept in their own words.
- Understands why it exists.
- Can apply it in a simple situation.
- Can identify common mistakes.
- Can connect it to relevant neighboring concepts.

Functional is usually sufficient to continue to dependent topics.

---

### Strong

The learner demonstrates reliable understanding and application.

Typical signs:

- Explains the concept clearly without heavy prompting.
- Applies it in unfamiliar but reasonable scenarios.
- Debugs common problems.
- Compares alternatives.
- Connects the concept to larger architecture.

Strong does not mean expert.

---

### Needs Reinforcement

The learner previously studied the concept but current evidence shows that understanding is unstable or has degraded.

This status should trigger targeted review.

It should not be treated as failure.

---

## Status Assignment Rule

Do not assign a status only because a lesson was completed.

Status should be based on evidence such as:

- Verbal explanation.
- Written explanation.
- Prediction.
- Debugging.
- Lab performance.
- Code modification.
- Diagram interpretation.
- Architecture reasoning.
- Teach-back.
- Assessment results.

---

## Progress Record

The current course position should eventually be represented in a concise progress record.

A recommended format is:

Phase:
Module:
Lesson:
Status:
Primary objective:
Prerequisites:
Current understanding:
Needs reinforcement:
Labs completed:
Assessment result:
Open questions:
Recommended next step:
Last updated:

This format may be stored in a separate progress file once active learning begins.

---

## Concept Tracking

Important concepts may be tracked individually.

Example:

Concept: HTTP Request
**Status:** Functional

Evidence:
- Can explain request and response.
- Can identify method, URL, headers, and body.
- Successfully inspected a real request.

Needs reinforcement:
- Difference between headers and body still slightly fuzzy.

Next dependency:
- REST APIs

The goal is not to document every vocabulary word.

Track concepts that matter to future dependencies.

---

## Module Tracking

Each module should have a current state.

Possible states:

- Not started.
- In progress.
- Completed.
- Needs reinforcement.
- Revisit later.

A module should be considered Completed only when its required learning outcomes have reached sufficient understanding.

---

## Lesson Tracking

Individual lessons may use a simpler status:

- Not started.
- In progress.
- Complete.
- Review needed.

Lesson completion is useful for navigation but should not be confused with mastery.

---

## Lab Tracking

Labs should capture both completion and understanding.

Recommended fields:

Lab:
Date:
Objective:
Status:
Completed:
Concepts practiced:
What worked:
What failed:
What was debugged:
What I can explain now:
What still feels unclear:
Relevant repository path:

Possible lab status values:

- Not started.
- In progress.
- Completed with support.
- Completed independently.
- Needs revisit.

---

## Assessment Tracking

Assessments should capture more than a score.

Recommended fields:

Assessment:
Concepts tested:
Result:
Strengths:
Weak areas:
Misconceptions:
Recommended reinforcement:
Next action:

A numerical score may be used when useful, but it should not replace descriptive feedback.

---

## Evidence of Understanding

Examples of strong evidence include:

- Explaining a concept correctly without repeating memorized wording.
- Predicting behavior before running code.
- Debugging a small failure systematically.
- Drawing a correct architecture.
- Identifying where data moves.
- Explaining why one design is preferable to another.
- Modifying working code without breaking the underlying logic.
- Teaching the concept back clearly.
- Applying a concept in an unfamiliar example.

---

## Weak Evidence

The following should not automatically count as understanding:

- Recognizing terminology.
- Copying code that works.
- Following a tutorial step by step.
- Repeating an AI-generated explanation.
- Successfully running a command without knowing what it did.
- Completing a project almost entirely through an AI coding agent.
- Receiving the correct output by accident.

These may still be useful experiences, but additional evidence is needed.

---

## Prerequisite Tracking

Before beginning a dependent topic, review whether required prerequisites are sufficiently stable.

A prerequisite may be:

- Introduced.
- Functional.
- Strong.

The required level depends on the downstream topic.

Example:

Target topic: Tool Calling

Required prerequisites:

Python Functions: Functional
JSON: Functional
Model APIs: Functional
Structured Outputs: Functional
HTTP: Developing or higher

The dependency map should guide these decisions.

---

## Reinforcement Queue

Topics requiring review should be captured in a reinforcement queue.

Example:

## Reinforcement Queue

1. Python function return values
**Status:** Needs reinforcement
   Reason: Confusion during API lab
   Review before: Tool Calling

2. HTTP headers
**Status:** Developing
   Reason: Mixed up with request body
   Review before: Authentication lesson

The queue should remain short and actionable.

---

## Question Backlog

Questions that are useful but premature should be tracked separately from weak concepts.

Recommended fields:

Question:
Why it matters:
Why it was deferred:
Prerequisites needed:
Planned module:
Status:

Possible statuses:

- Backlogged.
- Ready.
- Answered.
- No longer relevant.

---

## Current Position

At any point, the learning system should be able to answer:

- What phase am I in?
- What module am I in?
- What lesson am I on?
- What did I last complete?
- What am I currently learning?
- What concepts are weak?
- What prerequisite is blocking progress?
- What lab comes next?
- What is the exact recommended next lesson?

If those questions cannot be answered, the progress system needs to be updated.

---

## Milestones

Important milestones may include:

- Technical Orientation complete.
- Git and GitHub fundamentals complete.
- First Python program.
- First Git recovery lab.
- First API client.
- First database-backed application.
- AI foundations assessment complete.
- First direct model API call.
- First RAG system.
- First tool-calling application.
- First agent.
- First local-model experiment.
- First unfamiliar repository teardown.
- First self-hosted AI deployment.
- First portfolio-quality AI system.
- Capstone complete.

Milestones should reflect capability rather than arbitrary timing.

---

## Stop-and-Connect Tracking

Integration sessions should record whether the learner can connect concepts across modules.

Example:

Stop-and-Connect Session:
Application Communication

Can explain:
- Client/server relationship
- HTTP request
- JSON payload
- API endpoint
- Database role

Weak connection:
- Authentication flow

Status:
### Developing

These sessions provide evidence of system-level understanding.

---

## Learning Profile Signals

Progress tracking should also identify evidence that may require changes to the Learning Profile.

Examples:

- Consistently stronger understanding after diagrams.
- Repeated confusion when too many new concepts appear together.
- Strong performance on debugging exercises.
- Weak retention after purely verbal explanations.
- Growing independence during labs.

Do not update the Learning Profile based on one isolated event unless the evidence is particularly clear.

---

## Review Rhythm

Review should happen when evidence indicates it is useful.

Possible triggers include:

- A prerequisite has not been used for a long time.
- A later lesson exposes misunderstanding.
- An assessment reveals a weak foundation.
- A project requires older knowledge.
- The learner explicitly feels uncertain.
- A long break occurs.

Avoid unnecessary review of concepts that remain strong.

---

## Long Break Recovery

After a significant break:

1. Read the latest progress record.
2. Review the latest handoff.
3. Identify the last stable curriculum position.
4. Perform a lightweight diagnostic.
5. Update any statuses that have weakened.
6. Resume from the nearest appropriate point.

Do not automatically restart the course.

---

## Progress Summary

At logical boundaries, create a short summary containing:

Current Phase:
Current Module:
Current Lesson:

Strong:
Functional:
Developing:
Needs Reinforcement:

Labs Completed:
Assessments Completed:

Open Questions:
Reinforcement Queue:

Recommended Next Lesson:

This summary should be easy for a new ChatGPT conversation to interpret.

---

## Progress File Strategy

This document defines the tracking system itself.

Once active coursework begins, create a separate living file for actual progress.

Recommended future path:

progress/current_progress.md

The rules belong here in "docs/progress_tracking.md".

The actual changing course status should live in the "progress" folder.

This separation keeps system design documents stable while allowing the active progress record to change frequently.

---

## Success Metric

Progress should ultimately move toward one capability:

> I can reason about technical systems I have not previously seen.

The learner should gradually become more capable of:

- Identifying components.
- Explaining dependencies.
- Tracing data.
- Debugging failures.
- Reading documentation.
- Evaluating AI-generated work.
- Comparing approaches.
- Learning unfamiliar technologies independently.

That capability matters more than the number of completed lessons.

---

## Current Status

**Version:** 1.0

**Status:** Initial progress tracking specification.

The actual learner progress record should be created when active coursework begins.
