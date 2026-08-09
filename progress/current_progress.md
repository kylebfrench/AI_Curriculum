Current Progress

Purpose

This file is the living progress record for the AI Curriculum.

It should provide enough current-state information for a new ChatGPT conversation to determine:

- Where I am in the curriculum.
- What I have completed.
- What I currently understand.
- What needs reinforcement.
- What labs or assessments have been completed.
- What questions remain open.
- What should happen next.
- What durable instructional adaptations have been discovered.

The repository is the durable source of truth.

Individual ChatGPT conversations are temporary instructional sessions and should not be relied upon as the permanent course record.

This file should be updated at meaningful learning boundaries, especially before beginning a fresh ChatGPT conversation.

---

Current Course Status

Course Stage: Active Coursework

Session Zero Status: Complete

Current Phase: Phase 0 — Technical Orientation and Baseline

Current Module: Module 0.1 — Mapping the Technical World

Completed Lessons:

1. Lesson 1 — What Does a Computer Actually Do?
2. Lesson 2 — What Is Computation?
3. Lesson 3 — Hardware Versus Software
4. Lesson 4 — What Is a Program?
5. Lesson 5 — What Is Data?

Current / Next Lesson:

Lesson 6 — Traditional Software Versus AI Systems

Learning Status: Ready to continue

---

Module 0.1 Progress

Lesson 1 — What Does a Computer Actually Do?

Status: Completed

Established the high-level mental model that computers ultimately execute very small, literal operations extremely quickly.

Covered:

- Binary as a representation grounded in physical electronic states.
- Transistors as tiny electronic switches.
- CPU as an instruction-executing processor.
- RAM as temporary working space.
- Storage as persistent storage.
- Operating systems as coordination layers.
- Applications as software above the operating system.
- AI ultimately running on ordinary computing hardware.
- The preliminary stack of:
  - Hardware.
  - Operating system.
  - Applications.
  - AI models.
  - Agents.
  - Larger AI systems.

Demonstrated understanding:

- Computers operate using binary representations.
- Hardware physically implements the states behind binary.
- Computers execute logic-based sequences.
- CPU, memory, storage, operating systems, and applications have different roles.
- Complex behavior can emerge from enormous numbers of simple operations.
- AI ultimately depends on ordinary computing machinery.

---

Lesson 2 — What Is Computation?

Status: Completed

Core mental model:

«Computation is the process of taking information or state, applying operations or rules to it, and producing a new result or state.»

Useful simplified pattern:

Input → Computation → Output

Demonstrated understanding through the Spotify recommendation example:

- Listening history can serve as input.
- The system performs computation by analyzing or processing that information.
- Recommendations are the resulting output.

The learner does not need further basic repetition of input → computation → output unless a later misunderstanding appears.

---

Lesson 3 — Hardware Versus Software

Status: Completed at the level required for Module 0.1

Covered:

- Hardware as the physical computing machinery.
- Software as instructions and organized behavior running on hardware.
- Operating systems as an intermediate coordination layer.
- Applications using operating-system services.
- Higher-level software depending on lower-level layers.
- The usefulness of reasoning about which layer owns a problem.

The learner showed useful layer-based troubleshooting intuition.

Example:

If a web application does not load, the learner naturally identified the network connection as an early layer to investigate rather than assuming the AI model itself was the problem.

---

Lesson 4 — What Is a Program?

Status: Completed

Core mental model:

«A program is an organized set of instructions that describes useful computation.»

Covered:

- Humans normally write instructions at a higher level than raw machine instructions.
- Programming languages allow humans to express instructions in manageable forms.
- Lower layers ultimately translate or interpret those instructions into operations hardware can execute.
- One high-level action may result in very many lower-level operations.
- Abstraction allows programmers to work without manually controlling every hardware operation.

Demonstrated understanding:

The learner correctly identified the Python file or program as the place where the programmer's high-level instructions live.

The learner also correctly distinguished visible program output from the underlying computation that produced it.

---

Lesson 5 — What Is Data?

Status: Completed, with one useful clarification

Core mental model:

«Data is information represented in a form a computer can store, manipulate, transmit, or interpret according to agreed rules.»

Covered:

- Text, images, audio, numbers, AI parameters, and other information can all be represented as data.
- At the lowest level, the hardware ultimately operates on binary states.
- Higher-level representations allow us to think in terms of characters, pixels, numbers, records, and other useful abstractions.
- Meaning depends on interpretation and representation, not merely on the raw bit pattern.

Clarification Discovered

When discussing an image, the learner initially described the squares as corresponding directly to the binary code needed to display the picture.

Correction:

At the useful conceptual layer, the squares correspond to pixel values representing properties such as color and brightness. Those pixel values are themselves ultimately encoded in binary.

This was a refinement rather than a major misconception.

---

Material Introduced Ahead of the Formal Sequence

During the session, the conversation occasionally moved ahead of the formal syllabus.

Topics introduced included:

- Traditional software versus AI responsibilities.
- Using AI only for portions of a workflow that benefit from model capabilities.
- Libraries.
- APIs.
- AI service calls.
- Application orchestration.
- Conventional code surrounding AI components.
- Failure handling and fallbacks.
- A Career OS-style workflow containing both traditional software and AI steps.

These topics should not automatically be marked complete merely because they were discussed.

The formal syllabus sequence remains authoritative.

The next session should resume at Lesson 6 and establish these ideas cleanly in prerequisite order.

---

Current Understanding Status

Strong / Functional

The learner currently demonstrates functional or stronger understanding of:

- Computers as instruction-executing systems rather than magical reasoning machines.
- Basic distinction between CPU, RAM, storage, operating system, and applications.
- Input → computation → output.
- Programs as organized instructions.
- High-level instructions versus underlying machine operations.
- Abstraction layers.
- Basic distinction between hardware and software.
- Data as represented information.
- Layer-based systems thinking.
- The idea that AI is one component within a larger software system rather than the entire system.

The learner is progressing faster through these orientation concepts than the original highly granular starting assumptions suggested.

Do not artificially slow the course when demonstrated understanding is already stable.

---

Developing

The following have been introduced but should be formally developed according to the syllabus:

- Traditional software versus AI systems.
- What a model actually is.
- How model behavior differs from deterministic software logic.
- What physically happens when an AI application receives a request.
- Local versus cloud computation.
- Modern AI application architecture.
- APIs and service boundaries.

---

Needs Reinforcement

No major reinforcement queue currently exists.

Minor clarification to retain:

- Distinguish a useful high-level data representation, such as pixels, from the binary encoding underneath that representation.

This does not require dedicated remediation unless it reappears.

---

Learning Evidence and Instructional Adaptations

Several durable learning-style findings were established during the first active coursework sessions.

Instructor-Led Teaching Works Better Than Continuous Socratic Teaching

The learner prefers the instructor to teach coherent conceptual chunks first.

Questions should primarily be used as:

- Checkpoints.
- Diagnostic tools.
- Reasoning exercises.
- Teach-backs at meaningful boundaries.

Do not ask a new question after every sentence or micro-concept.

Preferred rhythm:

Teach → Example → Connect → Checkpoint → Continue

---

Avoid Repetition After Demonstrated Understanding

Repeatedly restating the same mental model after the learner has demonstrated understanding reduces momentum.

Once understanding is sufficiently demonstrated:

- Record it.
- Build forward.
- Spiral back later if needed.

Granularity should mean sufficient depth and clear decomposition, not artificially slow pacing.

---

Voice Is Preferred for Conceptual Learning

Voice conversation works well for:

- Concept teaching.
- Mental-model development.
- Architecture discussion.
- Reasoning.
- Reflection.
- Verbal checkpoints.
- Connecting concepts.

A useful startup workflow for future sessions is:

1. Open a fresh ChatGPT conversation only when a new conversation is actually warranted.
2. Enter voice mode.
3. Paste the prepared curriculum handoff/startup prompt into that voice conversation.
4. Provide the newest repository version.
5. Have the instructor inspect the repository and resume from the exact course position.

The instructor cannot assume the learner wants a new chat after each lesson.

---

Text Should Be Used Deliberately for Labs

When a lesson reaches a point where code, commands, repository editing, debugging, diagrams, structured data, or other visual material becomes central, the instructor should explicitly recommend temporarily leaving voice and switching to text.

Expected pattern:

Voice concept instruction → Text-based lab → Voice debrief when useful

This should be treated as a normal part of the curriculum rather than a disruption.

---

Chat Continuity Strategy

Do not create a new conversation after every lesson.

Continue within the current conversation while:

- Context remains coherent.
- Performance remains good.
- Several connected lessons can naturally be taught together.

Begin a new conversation when:

- A module or major learning boundary is reached.
- A substantial lab or assessment creates a natural transition.
- Conversation length becomes excessive.
- Context quality begins deteriorating.
- A fresh context would materially improve instruction.

The learner may also choose the transition point.

When transitioning, generate a compact startup/handoff prompt.

---

Labs Completed

None yet.

This is appropriate for the current point in Module 0.1.

Labs remain an important part of the curriculum and should begin when the prerequisites make hands-on work educationally useful rather than being added merely for activity.

Early labs should remain small and focused.

When a lab begins, the instructor should explicitly indicate whether the learner should switch from voice to text.

---

Assessments Completed

No formal assessment completed yet.

Informal verbal checkpoints have provided useful learning evidence.

The formal Module 0.1 assessment remains ahead.

---

Projects Completed

None as part of the formal curriculum.

Existing projects may be used as examples when they illuminate a concept without allowing the project to dictate the curriculum sequence.

---

Reinforcement Queue

No dedicated reinforcement currently required.

Monitor:

- Data representation versus underlying binary encoding.

---

Question / Curiosity Notes

The learner asked when labs would begin and confirmed that hands-on work remains an important expected part of the curriculum.

Instructional implication:

Do not allow the course to become an extended lecture sequence. Transition into practical exercises and labs when prerequisites make them meaningful.

---

Repository Update Status

Following this session, durable instructional discoveries warrant updates to:

- "docs/learning_profile.md"
- "docs/instructor_operating_guidelines.md"
- "progress/current_progress.md"

No new learning-adjustment markdown file is necessary.

Existing repository documents already provide the appropriate durable locations.

"docs/handoff_protocol.md" already establishes that a new chat should not be created after every small lesson, so no structural change is currently necessary there.

---

Exact Recommended Next Step

Continue:

Phase 0 — Technical Orientation and Baseline

Module 0.1 — Mapping the Technical World

Lesson 6 — Traditional Software Versus AI Systems

Primary objective:

Develop a clean mental model of how traditional deterministic software differs from machine-learning or AI model behavior, while also understanding how both can coexist inside the same application.

Do not skip directly to detailed API instruction simply because APIs were informally introduced during the previous session.

After Lesson 6, continue according to the repository sequence:

7. What Is a Model?
8. What Physically Happens When an AI Application Receives a Request?
9. Local Computing Versus Cloud Computing.
10. First Map of the Modern AI Technology Stack.

Then complete the Module 0.1 assessment before progressing according to the syllabus.

---

Next Session Instruction

At the start of the next session:

1. Inspect the newest repository.
2. Read "progress/current_progress.md" first.
3. Review "docs/course_charter.md", "docs/instructor_operating_guidelines.md", "docs/learning_profile.md", "docs/syllabus.md", "docs/concept_dependency_map.md", and "docs/session_template.md" as needed.
4. Resume at the exact current course position.
5. Teach primarily in coherent instructor-led chunks.
6. Use checkpoint questions selectively.
7. Do not repeat concepts already demonstrated unless needed.
8. Maintain forward momentum.
9. Recommend switching from voice to text when a lab or visual/code-heavy activity makes text the better medium.
10. Keep the repository as the durable source of truth.

---

Last Updated

Date: 2026-08-09

Course State: Active coursework underway.

Current Position: Phase 0 → Module 0.1 → Lesson 6.

Next Lesson: Traditional Software Versus AI Systems.
