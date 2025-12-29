# User Stories — Robinson R44 Raven II e-Learning (CBT)

This document provides **portfolio-style examples** of epics, user stories, and acceptance criteria that reflect typical Product Owner work for an aviation e-learning/CBT product. Details are generalized and non-confidential.

---

## Personas
- **Learner (Pilot / Trainee):** completes initial or recurrent theory training on R44 Raven II.
- **Training Manager / Instructor:** assigns training, tracks progress, and ensures readiness.
- **Compliance / Training Organization:** needs consistent delivery and evidence of completion aligned with expected training standards.

---

## Epic 1: Modular Course Experience (Core Learning Flow)

### US-1.1 — Module Navigation
**As a** Learner,  
**I want** to navigate the course by modules and topics,  
**so that** I can learn in a structured way and return to specific subjects when revising.

**Acceptance Criteria**
- The course is split into clearly labeled modules.
- The learner can enter any module from a course menu.
- The learner can resume from the last completed screen.
- Progress is visible at course and module level (e.g., % or completed/not completed).

---

### US-1.2 — Content Delivery & Readability
**As a** Learner,  
**I want** content to be presented in a clear and learner-friendly way,  
**so that** complex aircraft concepts are understandable.

**Acceptance Criteria**
- Each topic uses consistent layout (title, explanation, visuals where relevant).
- Key terms are explained or supported with short definitions.
- Content is readable on desktop and mobile without horizontal scrolling.
- Media elements (images/animations) load without breaking the lesson flow.

---

## Epic 2: Assessments & Knowledge Checks (Learning Validation)

### US-2.1 — In-Module Knowledge Checks
**As a** Learner,  
**I want** short knowledge checks during modules,  
**so that** I can confirm understanding before moving on.

**Acceptance Criteria**
- Knowledge checks appear at defined points in the module (not only at the end).
- Each check provides immediate feedback (correct/incorrect).
- When incorrect, the learner receives a brief explanation or hint.
- The learner can retry the question at least once.

---

### US-2.2 — Final Assessment
**As a** Training Manager/Instructor,  
**I want** learners to complete an end-of-course assessment,  
**so that** I can confirm readiness and training completion.

**Acceptance Criteria**
- A final assessment is available after completing required modules (or configured prerequisites).
- The assessment contains a configurable number of questions (example: 20–40).
- The learner sees a pass/fail outcome (or score) at completion.
- The system records the attempt result (date/time, score/pass status).
- A learner can reattempt based on defined rules (e.g., cooldown, max attempts).

---

## Epic 3: Walk-Around / Inspection Training (Practical Readiness)

### US-3.1 — Interactive Walk-Around Content
**As a** Learner,  
**I want** an interactive walk-around module,  
**so that** I can learn inspection points and improve readiness before practical training.

**Acceptance Criteria**
- The module includes a defined set of inspection zones/steps.
- Each zone provides a short explanation of what to check and why it matters.
- Interactions are clear (click/tap hotspots or step-based flow).
- The learner can repeat the module without penalty.

---

## Epic 4: Multi-Device Access (Accessibility)

### US-4.1 — Mobile-Friendly Learning
**As a** Learner,  
**I want** to access the course on mobile devices,  
**so that** I can learn anytime and anywhere.

**Acceptance Criteria**
- The course UI adapts to mobile screen sizes.
- Core interactions (next/prev, menu, knowledge checks) work on touch.
- Audio/video (if used) plays correctly on mobile.
- The learner’s progress syncs across devices (if the platform supports accounts).

---

## Epic 5: Tracking & Evidence of Completion (Training Ops)

### US-5.1 — Progress Tracking
**As a** Training Manager/Instructor,  
**I want** to track learner progress and completion,  
**so that** I can manage training and identify who needs support.

**Acceptance Criteria**
- The system shows learner status (not started / in progress / completed).
- The system shows module completion and assessment results.
- The system supports filtering by cohort/class (if applicable).
- Completion evidence includes date/time and assessment outcome (as applicable).

---

## Non-Functional Requirements (NFRs) — Portfolio Examples
- **Performance:** Lessons load within an acceptable time under normal conditions.
- **Usability:** Clear navigation and consistent UI patterns across modules.
- **Accessibility:** Basic readability and contrast considerations; keyboard navigation where applicable.
- **Reliability:** Progress is not lost if the user refreshes or disconnects briefly.
- **Security/Privacy:** Learner data is protected and access is role-based (as supported by the platform).

---

## Prioritization Notes (How I framed MVP)
MVP typically prioritized:
1) Core modular learning flow (Epic 1)  
2) Knowledge checks + final assessment (Epic 2)  
3) Walk-around module (Epic 3)  
4) Multi-device experience polish (Epic 4)  
5) Reporting depth and admin features (Epic 5)

Trade-offs were managed based on learner impact, regulatory expectations, and delivery constraints.
