---
name: context-engineering-negative-prompting
description: Structuring system prompts, context windows, and negative prompt registries ('DONTS') to eliminate AI hallucinations and scope drift.
---

# Context Engineering & Negative Prompting

## Overview & Purpose
Structuring system prompts, context windows, and negative prompt registries ('DONTS') to eliminate AI hallucinations and scope drift.

## Core Technical Concepts
- **Negative Prompting**:  Explicitly cataloging what NOT to do based on past landmines
- **Context Window Optimization & Dynamic Context Injection**: Context Window Optimization & Dynamic Context Injection
- **Role Definition & Persona Scoping (e.g. Skeptical Auditor, Engineer, Client)**: Role Definition & Persona Scoping (e.g. Skeptical Auditor, Engineer, Client)
- **System Prompt Versioning & Modularity**: System Prompt Versioning & Modularity

## Operational & Execution Workflow
1. **Analyze Requirements & Constraints**: Identify input payloads, boundaries, and failure modes.
2. **Implement Core Logic**: Build modular execution steps adhering to tool-agnostic standards.
3. **Embed Verification Gates**: Verify outputs using automated checks or golden dataset benchmarks.
4. **Deploy & Monitor**: Monitor execution metrics, token cost efficiency, and error rates.

## 💡 Connecting This Skill to Your Ideas

### Applicable to Current & Unfinished Ideas:
- 🎯 **AI Agent Hardening**:  Inject negative prompt registries into property search agents so they never infer missing parcel data.
- 🎯 **Client Communication Bot**:  Prevent AI from making unauthorized promises or hallucinating pricing details.
- 🎯 **Code Generation Harness**:  Ensure generated code strictly adheres to project lint rules and architectural constraints.

### How to Use for New Ideas:
When brainstorming a new project or automation:
1. Identify if this skill solves an input, process, or quality bottleneck in your concept.
2. Reference the core technical concepts above to quickly integrate this pattern into your implementation plan.
3. Combine with complementary skills (e.g., pairing *Agentic Workflow Design* with *Autonomous Verification Loops*).
