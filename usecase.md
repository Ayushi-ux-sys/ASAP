START
  │
  ▼
User Opens ASAP Platform
  │
  ▼
Select Mode?
 ┌────────────────┐
 │  Build Mode    │◄──────────────────────────────┐
 │  Learning Mode │                               │
 └────────────────┘                               │
        │                                         │
        ▼                                         │
Normalize User Input                              │
(NL Goal / Code / Error)                          │
        │                                         │
        ▼                                         │
Intent Classification (Orchestrator)              │
        │
        ├──────────────► BUILD INTENT
        │                    │
        │                    ▼
        │          Architect Agent
        │        (Goal → Roadmap)
        │                    │
        │                    ▼
        │          Activate Milestone
        │                    │
        │                    ▼
        │          Execution Agent
        │     (Scoped Code Generation)
        │                    │
        │                    ▼
        │         Explain "Why This Step"
        │                    │
        │                    ▼
        │          Update Project State
        │                    │
        │                    ▼
        │               UI Render
        │
        └──────────────► LEARN INTENT
                             │
                             ▼
                     ThinkFix Agent
                  (Root Cause Analysis)
                             │
                             ▼
                  Identify Conceptual Gap
                             │
                             ▼
                   Generate Micro-Lesson
                             │
                             ▼
                  Progressive Hint Loop
                  ┌──────────────────┐
                  │  Hint Level 1    │
                  │  Hint Level 2    │
                  │  Hint Level 3    │
                  └──────────────────┘
                             │
                             ▼
                     User Attempts Fix
                             │
                             ▼
                    Error Resolved?
                     │           │
                    No          Yes
                     │           │
                     ▼           ▼
             Loop Back to     Update Learning
             ThinkFix Agent  Memory & UI
