# ASAP (Autonomous Smart Agent Project)
## Design Document

---

## 1. System Overview

ASAP (Autonomous Smart Agent Project) is a high-orchestration agentic AI system designed to bridge the gap between project ideation and deep conceptual mastery. It leverages a Multi-Agent Orchestration (MAO) layer to manage complex software development lifecycles while preserving architectural integrity and reasoning continuity.

The system operates in dual roles:
- As a Senior Software Architect guiding structured project construction
- As a Learning Copilot performing diagnostic error analysis to promote conceptual understanding rather than surface-level fixes

---

## 2. Technical Architecture

- **Frontend**:  
  React 18+ "Cockpit" interface powered by a state-machine architecture, locking UI components to defined project milestones and configurable Learning Mode states.

- **Backend**:  
  Node.js with Express acting as an orchestration layer and context gateway, coordinating communication between the frontend and AI agents.

- **AI Engine**:  
  Claude 3.5 Sonnet and Gemini 1.5 Flash accessed via multi-agent prompting and controlled internal reasoning flows.

- **Data Protocol**:  
  Stateless RESTful APIs utilizing strict JSON schemas to ensure predictable UI rendering and deterministic agent responses.

---

## 3. Agentic Orchestration Loop (Kiro Framework)

The ASAP system operates through a specialized agentic loop composed of the following sub-agents:

1. **Architect Agent (Strategic Layer)**  
   Performs recursive decomposition of high-level natural language goals into a structured, milestone-driven JSON roadmap.

2. **ThinkFix Agent (Diagnostic Layer)**  
   A pedagogical agent responsible for Root Cause Analysis (RCA) of code errors. It explains conceptual gaps, failure patterns, and heuristics instead of providing direct fixes.

3. **Execution Agent (Construction Layer)**  
   Generates scoped, modular boilerplate and business logic strictly constrained to the currently active milestone identifier.

4. **Deep-Dive Agent (Research Layer)**  
   An on-demand agent that performs architectural and pattern analysis, explaining the rationale behind implementation choices such as middleware design, data normalization, and system flow.

---

## 4. Communication & Logical Flow

- **Ingestion**  
  Normalization of natural language project goals or raw stack traces, compiler errors, and source code snippets.

- **Intent Routing**  
  The orchestration layer classifies intent (Build vs Learn) and routes requests to the appropriate agent.

- **Context Injection**  
  Each request is pre-pended with a session state map containing project history, architectural decisions, and prior errors to maintain reasoning continuity without persistent storage.

---

## 5. Security Design

- API keys stored securely in environment variables
- AI APIs accessed exclusively from the backend
- No sensitive user data stored permanently

---

## 6. Scalability and Extensibility

- Modular backend services
- Model-agnostic AI layer for future provider switching
- Support for additional agents and learning modes

---

## 7. Future Enhancements

- Learning history and progress tracking
- Concept dependency and architecture visualization
- Accessibility features such as voice-based explanations
