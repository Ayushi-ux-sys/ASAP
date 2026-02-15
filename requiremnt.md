# ASAP (Autonomous Smart Agent Project)
## Requirements Document

---

## 1. Problem Statement

Most existing LLM-based development assistants encourage a *copy-paste loop* that bypasses critical cognitive development. Beginner developers often complete projects without understanding the underlying architecture, leading to long-term dependency on tutorials and shallow problem-solving skills commonly referred to as "Tutorial Hell."

---

## 2. Project Objective

The objective of ASAP (Autonomous Smart Agent Project) is to engineer an **autonomous agentic builder** that prioritizes *architectural retention and conceptual mastery*.

The platform must function as a **pedagogical senior software architect**, transforming high-level goals into structured technical roadmaps while using **Root Cause Analysis (RCA)** to convert programming errors into guided learning opportunities.

---

## 3. Functional Requirements

- **Recursive Goal Decomposition**  
  The system shall autonomously decompose any natural language project goal into a structured, milestone-driven five-node technical roadmap.

- **ThinkFix Error Analysis**  
  Upon ingestion of a stack trace, compiler error, or source code snippet, the system shall identify the underlying conceptual gap instead of providing an immediate corrective solution.

- **Mental Model Explanation**  
  The system shall generate concise *micro-lessons* that explain the logical or architectural reasoning behind a failure, emphasizing the "why" over the "what."

- **Progressive Hinting Mechanism**  
  The system shall provide iterative, increasingly specific hints to guide users toward a self-authored solution rather than delivering direct fixes.

- **Milestone-Scoped Code Generation**  
  Any boilerplate or logic generation must be strictly constrained to the UUID of the currently active project milestone to prevent premature abstraction.

- **Agentic Learning Memory**  
  The system shall maintain a session-level history of user errors and learning patterns to personalize future explanations and guidance.

---

## 4. Non-Functional Requirements

- **Deterministic Behavior**  
  Agent responses must follow structured schemas to ensure predictable UI rendering and consistent learning outcomes.

- **Security**  
  All AI service credentials must be securely stored and accessed only from the backend.

- **Scalability**  
  The architecture must support the addition of new agents, learning modes, and AI models without core system refactoring.

---

## 5. Success Criteria

- **Architectural Retention**  
  Users must be able to verbally or textually explain the architectural structure and logic of their project after a guided session.

- **Debugging Proficiency**  
  Users must successfully identify and fix programming errors independently using the hints and explanations provided by the system.

- **Reduced AI Dependency**  
  Users should demonstrate decreasing reliance on direct AI-generated solutions over time.

---
