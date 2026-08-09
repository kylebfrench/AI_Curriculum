# Repository Structure

## Purpose

This document defines how the AI Curriculum repository should be organized.

The repository serves as the durable source of truth for the learning journey.

It should remain:

- Easy to navigate.
- Easy to understand.
- Easy to update.
- Easy to hand off to a fresh ChatGPT conversation.
- Flexible enough to grow with the curriculum.
- Structured enough to prevent unnecessary clutter.

The repository should grow in response to actual learning activity.

Do not create large numbers of empty folders or files simply because they may be useful someday.

---

## Core Principle

Each type of information should have a clear home.

The repository should separate:

- Stable course governance.
- Active progress.
- Learning content.
- Labs.
- Projects.
- Reflections.
- Handoffs.
- Questions.
- References.
- Visual assets.

This separation helps prevent changing operational information from becoming mixed with relatively stable course design documents.

---

## Recommended Repository Architecture

The intended long-term structure is:

```text
AI_Curriculum/
│
├── README.md
│
├── docs/
│
├── progress/
│
├── lessons/
│
├── notes/
│
├── labs/
│
├── projects/
│
├── assessments/
│
├── reflections/
│
├── handoffs/
│
├── backlog/
│
├── references/
│
└── assets/
```

Not all folders need to be created immediately.

Create them when the first real file needs to live there.

---

## Root Directory

The repository root should remain relatively clean.

Recommended root-level contents include:

```text
README.md
docs/
progress/
lessons/
notes/
labs/
projects/
assessments/
reflections/
handoffs/
backlog/
references/
assets/
```

Avoid placing random lesson files, screenshots, scripts, or temporary notes directly in the root.

---

## README.md

## Purpose

The README is the front door to the repository.

It should explain:

- What the repository is.
- Why it exists.
- The learning philosophy.
- The long-term goal.
- Where major repository content lives.
- Where to find the current course position.

The README should remain concise.

It should not become the complete Course Charter or syllabus.

As the repository grows, the README may link to important files such as:

docs/course_charter.md
docs/syllabus.md
progress/current_progress.md

---

## docs/

## Purpose

The "docs/" folder contains relatively stable documents that define how the learning system operates.

Current expected contents include:

## docs/
├── course_charter.md
├── learning_profile.md
├── instructor_operating_guidelines.md
├── curriculum_architecture.md
├── concept_dependency_map.md
├── syllabus.md
├── session_template.md
├── progress_tracking.md
├── reflection_system.md
├── handoff_protocol.md
├── question_backlog.md
└── repository_structure.md

These are governance and design documents.

They may evolve, but they should not change constantly during ordinary lessons.

---

## progress/

## Purpose

The "progress/" folder stores the current state of the learner's journey.

Recommended starting file:

progress/current_progress.md

This file should answer:

- Current phase.
- Current module.
- Current lesson.
- Current understanding status.
- Completed labs.
- Completed assessments.
- Reinforcement needs.
- Exact recommended next step.

Additional historical progress files may be added later only if useful.

---

## lessons/

## Purpose

The "lessons/" folder contains structured lesson material that is worth preserving.

Do not automatically create a permanent file for every conversational explanation.

Create lesson files when the material is useful as durable reference material.

A future structure may resemble:

## lessons/
├── phase-00-orientation/
├── phase-01-computer-foundations/
├── phase-02-git-github/
├── phase-03-python/
├── phase-04-networking-apis/
└── ...

Inside a phase:

## lessons/
└── phase-04-networking-apis/
    ├── 01-client-server.md
    ├── 02-http.md
    ├── 03-json.md
    └── 04-apis.md

Do not create all phase folders in advance.

---

## notes/

## Purpose

The "notes/" folder contains learner-oriented concept notes and summaries.

These should differ from formal lessons.

A lesson may represent the instructional material.

A note should represent a useful distilled understanding.

Examples:

## notes/
├── git/
├── python/
├── networking/
├── ai-foundations/
└── agents/

Potential note files:

notes/git/commits.md
notes/networking/http-mental-model.md
notes/ai-foundations/tokens.md

Notes may be written collaboratively or by the learner.

---

## labs/

## Purpose

The "labs/" folder contains hands-on exercises and technical experiments.

Labs should be organized by topic or curriculum phase.

Example:

## labs/
├── git/
├── python/
├── APIs/
├── databases/
├── model-apis/
├── rag/
├── agents/
└── local-ai/

A specific lab may contain:

## labs/
└── git/
    └── branch-and-recovery/
        ├── README.md
        ├── lab_notes.md
        └── supporting-files/

The "README.md" inside a lab should generally explain:

- Objective.
- Prerequisites.
- Instructions.
- Expected outcome.
- Completion criteria.

---

## projects/

## Purpose

The "projects/" folder contains larger work that combines multiple concepts.

Projects should generally appear only after the required prerequisites are familiar.

Example:

## projects/
├── api-client/
├── database-app/
├── rag-app/
├── agent-project/
└── capstone/

Some larger projects may eventually live in their own GitHub repositories instead of inside AI Curriculum.

If that happens, this repository should contain documentation and links to those projects rather than duplicate the entire project.

---

## assessments/

## Purpose

The "assessments/" folder stores meaningful evaluations of understanding.

Possible structure:

## assessments/
├── quizzes/
├── practical/
├── module/
└── milestone/

Assessment files may include:

- Questions.
- Practical tasks.
- Learner answers.
- Instructor feedback.
- Reinforcement recommendations.

Not every comprehension check needs a permanent assessment file.

---

## reflections/

## Purpose

The "reflections/" folder stores meaningful reflections that should influence future learning.

Possible structure:

## reflections/
├── sessions/
├── labs/
├── modules/
└── milestones/

Example:

## reflections/
└── modules/
    └── 2026-08-git-foundations.md

Do not create reflection files merely because a session occurred.

Create them when they contain useful instructional information.

---

## handoffs/

## Purpose

The "handoffs/" folder preserves continuity between ChatGPT conversations.

Recommended naming:

handoffs/YYYY-MM-DD_session-handoff.md

If multiple handoffs occur on the same date:

handoffs/YYYY-MM-DD_session-01-handoff.md
handoffs/YYYY-MM-DD_session-02-handoff.md

A handoff should contain only information required to continue the journey accurately.

Do not use handoffs as chat transcripts.

---

## backlog/

## Purpose

The "backlog/" folder stores active questions and future topics that should not interrupt current curriculum sequencing.

Recommended future file:

backlog/questions.md

This is separate from:

docs/question_backlog.md

The distinction is:

docs/question_backlog.md

defines the rules for managing questions.

backlog/questions.md

contains the actual active questions.

---

## references/

## Purpose

The "references/" folder contains curated external learning resources.

Examples may include:

- Documentation links.
- Research papers.
- Articles.
- Books.
- Tutorials.
- GitHub repositories.
- Videos.
- Tool documentation.

Possible structure:

## references/
├── git.md
├── python.md
├── networking.md
├── ai-models.md
├── agents.md
└── infrastructure.md

References should be curated.

Do not turn the folder into a massive collection of links.

---

## assets/

## Purpose

The "assets/" folder contains supporting visual or media files.

Examples:

- Architecture diagrams.
- Screenshots.
- Flowcharts.
- Images used in documentation.

Possible structure:

## assets/
├── diagrams/
├── screenshots/
└── images/

Avoid storing unnecessary large files in the repository.

---

## File Naming Rules

Use predictable lowercase names where practical.

Preferred:

course_charter.md
concept_dependency_map.md
current_progress.md
http_requests.md
branch_recovery_lab.md

Avoid inconsistent names such as:

HTTP Lesson FINAL 2.md
myNewThing.md
notes-final-FINAL.md

Use:

lowercase
underscores
clear descriptive names

Consistency matters more than the specific style.

---

## Folder Naming Rules

Use lowercase folder names.

Preferred:

## docs/
## progress/
## labs/
## projects/
## handoffs/

For multi-word folders, prefer hyphens if needed:

ai-foundations/
model-apis/
local-ai/

Do not mix naming conventions without a reason.

---

## Date Formatting

When dates appear in filenames, use:

YYYY-MM-DD

Example:

2026-08-08_session-handoff.md

This format sorts correctly and avoids ambiguity.

---

## Versioning Rule

Git should provide the primary history for repository files.

Do not routinely create filenames such as:

syllabus_v2.md
syllabus_final.md
syllabus_final_final.md

Instead, update:

syllabus.md

and let Git preserve the previous versions.

Document versions inside important files may still be useful.

Example:

**Version:** 1.1

---

## Git Commit Philosophy

As Git skills develop, repository changes should use small, understandable commits.

Examples:

Add initial course charter

Create curriculum architecture

Add progress tracking system

Update syllabus after dependency review

Avoid vague commit messages such as:

stuff

changes

update

final

The learner should eventually be able to inspect repository history and understand how the learning system evolved.

---

## Temporary Files

Avoid committing unnecessary temporary files.

Examples may eventually include:

- Editor cache files.
- Operating-system metadata.
- Environment folders.
- Secret files.
- API keys.
- Generated temporary output.

A ".gitignore" should be added when the repository begins containing file types that require exclusions.

Do not add secrets to Git history.

---

## Secret Management Rule

Never commit:

- API keys.
- Passwords.
- Access tokens.
- Private credentials.
- Sensitive environment files.

When environment variables are introduced later, the curriculum should explain patterns such as:

.env
.env.example

The actual ".env" file containing secrets should normally be excluded with ".gitignore".

---

## Source-of-Truth Hierarchy

Different repository files serve different purposes.

### Stable Course Principles

docs/course_charter.md
docs/instructor_operating_guidelines.md

### Learning Adaptation

docs/learning_profile.md

### Curriculum Direction

docs/curriculum_architecture.md
docs/concept_dependency_map.md
docs/syllabus.md

### Active Course State

progress/current_progress.md

### Conversation Continuity

## handoffs/

### Active Curiosity

backlog/questions.md

This separation should make conflicts easier to resolve.

---

## Repository Growth Rule

Do not build the entire directory tree immediately.

Create a folder when the first real artifact belongs there.

Example:

When the first formal lab begins:

## labs/

should be created.

When the first handoff occurs:

## handoffs/

should be created.

When active coursework begins:

progress/current_progress.md

should be created.

This keeps the repository intentional rather than decorative.

---

## External Project Rule

Some future projects may become substantial enough to deserve their own repositories.

Possible examples:

- Portfolio applications.
- Large agent systems.
- Career OS.
- Significant self-hosted experiments.

In those cases, AI Curriculum should remain the learning hub.

It may contain:

projects/project-name/README.md

with:

- Learning objective.
- Project summary.
- External repository location.
- Curriculum concepts practiced.
- Reflection.
- Assessment notes.

---

## Archive Rule

Do not delete useful historical learning artifacts simply because they are no longer current.

Git already preserves file history.

Archive folders should only be introduced if active repository navigation becomes difficult.

Avoid premature archiving systems.

---

## Repository Navigation Goal

A future instructor entering this repository should be able to quickly find:

1. The learning philosophy.
2. The curriculum.
3. The learner's current position.
4. The latest handoff.
5. Current questions.
6. Relevant lesson materials.
7. Relevant labs or projects.

If those items become difficult to locate, the repository structure should be reviewed.

---

## Initial Repository State

During Session Zero, only the core design documents need to exist.

The expected initial state is approximately:

AI_Curriculum/
│
├── README.md
│
└── docs/
    ├── course_charter.md
    ├── learning_profile.md
    ├── instructor_operating_guidelines.md
    ├── curriculum_architecture.md
    ├── concept_dependency_map.md
    ├── syllabus.md
    ├── session_template.md
    ├── progress_tracking.md
    ├── reflection_system.md
    ├── handoff_protocol.md
    ├── question_backlog.md
    └── repository_structure.md

Additional directories should appear as actual coursework begins.

---

## Current Status

**Version:** 1.0

**Status:** Initial repository architecture.

The repository structure should evolve only when a real organizational need appears.

The goal is a clean learning system, not the largest possible folder tree.
