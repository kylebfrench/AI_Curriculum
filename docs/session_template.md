# Session Template

## Purpose

This document defines the default structure for individual learning sessions in the AI Curriculum.

The structure is intended to provide consistency without becoming rigid.

Not every session must use every section.

The instructor should adapt the session based on:

- The topic.
- The learner's current understanding.
- Whether the session is conceptual, practical, diagnostic, or reflective.
- Whether voice, text, code, diagrams, or another format is most appropriate.

---

## Standard Session Flow

## 1. Session Position

At the beginning of the session, establish:

- Current phase.
- Current module.
- Current lesson.
- Relevant prerequisites.
- What was covered previously.
- Any unresolved questions that affect today's topic.

The learner should understand where the session sits within the larger curriculum.

---

## 2. Learning Objective

State the primary objective in simple language.

Prefer one clear objective over a long list.

Example:

> By the end of this lesson, I should be able to explain what an HTTP request is and identify its major parts.

When appropriate, include a secondary objective.

---

## 3. Prerequisite Check

Before introducing an important concept, briefly confirm that the required prerequisites are stable enough.

Possible approaches:

- One or two verbal questions.
- A small prediction.
- A quick explanation in the learner's own words.
- A tiny practical task.

Do not repeat full assessments unnecessarily.

If a prerequisite is weak, address it before moving forward.

---

## 4. Concept Introduction

Introduce the concept conversationally.

Begin with:

- What it is.
- Why it exists.
- What problem it solves.

Avoid immediately overwhelming the learner with every detail.

Start with the smallest useful mental model.

---

## 5. Build the Mental Model

Progressively expand the explanation.

For important concepts, consider:

- What came before it.
- What communicates with it.
- What goes into it.
- What comes out of it.
- What happens internally at an appropriate level.
- What can fail.
- What alternatives exist.
- Where it fits in the larger system.

Use analogies when they genuinely improve understanding.

Do not let the analogy replace the real technical explanation.

---

## 6. Learner Reasoning

Give the learner opportunities to reason before revealing every answer.

Possible prompts include:

- What do you think happens next?
- Why do you think this component exists?
- What would happen if we removed it?
- Which part of the system should handle this?
- How would you explain this in your own words?

The goal is active reasoning rather than passive listening.

---

## 7. Visual or Text Switch

When the concept is easier to understand visually, deliberately switch formats.

Useful formats may include:

- Architecture diagrams.
- Flowcharts.
- Repository trees.
- Code.
- JSON.
- SQL.
- Tables.
- Logs.
- API requests and responses.
- Command-line output.

The instructor should explicitly indicate when another format is likely to improve understanding.

---

## 8. Simple Example

Work through one small example.

The example should isolate the current concept as much as possible.

Avoid examples that introduce many unrelated technologies at the same time.

The learner should understand what the example demonstrates and why it works.

---

## 9. Comprehension Check

Check the current mental model before adding significant complexity.

Possible approaches:

- Explain it back.
- Predict behavior.
- Compare two concepts.
- Identify an error.
- Trace a simple data flow.
- Answer a scenario question.

This should be diagnostic rather than adversarial.

---

## 10. Exercise

When appropriate, provide a small exercise that requires the learner to act.

Examples:

- Modify one line of code.
- Predict command output.
- Write a simple query.
- Identify parts of a JSON object.
- Arrange system components in order.
- Explain a short architecture.
- Make a small Git change.
- Write pseudocode.

Exercises should remain narrower than full labs.

---

## 11. Lab or Practical Application

When the lesson supports hands-on work, complete a lab.

Before beginning, establish:

- Lab objective.
- Required prerequisites.
- Expected outcome.
- What the learner is responsible for doing.

During the lab:

- Prefer small controlled steps.
- Explain unfamiliar commands.
- Inspect errors.
- Use Git checkpoints when appropriate.
- Let the learner make meaningful decisions.
- Avoid allowing AI to perform the entire lab without explanation.

---

## 12. Debugging and Error Review

If something fails, treat the failure as part of the lesson.

Use the sequence:

## 1. Observe the failure.
## 2. Read the error.
## 3. Locate where it occurred.
## 4. Form a hypothesis.
## 5. Test the hypothesis.
## 6. Make one controlled change.
## 7. Test again.
## 8. Explain the result.

Do not immediately discard broken work unless doing so is necessary.

---

## 13. Mental-Model Teach-Back

For important concepts, ask the learner to explain the concept back in plain language.

Possible prompts:

- Explain this as if I were a new coworker.
- Explain what problem this solves.
- Explain how this fits into the larger system.
- Explain the data flow.
- Explain what would break if this component disappeared.

The instructor should correct weak or incomplete reasoning before treating the concept as stable.

---

## 14. Connection Check

When useful, connect the lesson to previously learned material.

Examples:

- How does this relate to Python?
- Where does HTTP fit here?
- Where is the database?
- What would Git be protecting during this workflow?
- Where would an AI model appear in this architecture?
- What part would run locally versus in the cloud?

This helps prevent isolated vocabulary from accumulating.

---

## 15. Session Summary

End the instructional portion with a short summary.

Capture:

- What was learned.
- What the learner can now explain or do.
- Any important terminology.
- Any concept still unclear.

The summary should remain concise.

---

## 16. Reflection

Use reflection when it provides useful teaching information.

Possible questions:

- What clicked?
- What was confusing?
- Was the pace appropriate?
- Did the example help?
- Did the visual help?
- Was the lab useful?
- Is anything still fuzzy?

Not every session requires formal written reflection.

---

## 17. Progress Update

When appropriate, update the learner's progress state.

Possible understanding levels:

- Not introduced.
- Introduced.
- Developing.
- Functional.
- Strong.
- Needs reinforcement.

Progress should reflect demonstrated understanding rather than simply session completion.

---

## 18. Learning Profile Update

Update the Learning Profile only when meaningful evidence appears.

Examples:

- A new teaching method works particularly well.
- A recurring misconception appears.
- The learner consistently prefers a certain type of explanation.
- A previously assumed weakness is clearly no longer present.
- A new strength becomes apparent.

Avoid unnecessary profile changes after every lesson.

---

## 19. Question Backlog Update

If important future questions appeared during the session:

- Record the question.
- Note why it was deferred.
- Identify the likely future module or prerequisite.

This preserves curiosity without disrupting sequencing.

---

## 20. Determine the Next Step

Before ending, identify the exact recommended next lesson or activity.

The next step should be based on:

- Current understanding.
- Dependency requirements.
- Any reinforcement needed.
- Current syllabus position.

Do not simply choose the most exciting next topic.

---

## Session Types

Not every session is a normal lesson.

Possible session types include:

### Concept Session

Primarily explanation, reasoning, mental models, and examples.

### Lab Session

Primarily hands-on implementation and debugging.

### Assessment Session

Primarily evaluation of understanding and application.

### Stop-and-Connect Session

Primarily connecting previously learned concepts.

### Review Session

Primarily reinforcing weak or older material.

### Project Session

Primarily building a larger artifact using already learned concepts.

### Architecture Session

Primarily reading, mapping, or designing technical systems.

### Reflection Session

Primarily reviewing progress and adapting the learning approach.

---

## Session Size Rule

A session should not attempt to cover too much simply because time is available.

A long session may contain several small instructional cycles.

It should not become one enormous lesson.

For longer sessions, alternate between:

- Talking.
- Looking.
- Building.
- Testing.
- Reflecting.

The amount of material should be determined by understanding, not by the number of available hours.

---

## Completion Rule

A session is complete when:

- The primary learning objective has been addressed.
- The learner's understanding has been checked.
- Any major confusion has been identified.
- The next step is clear.

The session does not need to exhaust the topic.

---

## Current Status

**Version:** 1.0

**Status:** Initial standard session template.

This structure should be adjusted when real learning evidence shows that a different session rhythm is more effective.
