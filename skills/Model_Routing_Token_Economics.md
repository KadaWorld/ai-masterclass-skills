---
name: model-routing-token-economics
description: Optimizing AI API costs by routing low-complexity tasks to fast, low-cost/local models and reserving frontier models for complex reasoning.
---

# Model Routing & Token Economics

## Overview & Purpose
Optimizing AI API costs by routing low-complexity tasks to fast, low-cost/local models and reserving frontier models for complex reasoning.

## Core Technical Concepts
- **Dynamic Model Routing based on task complexity**: Dynamic Model Routing based on task complexity
- **Token Budgeting & Cost Calculation per execution**: Token Budgeting & Cost Calculation per execution
- **Tiered Model Cascade (Grunt Work -> cheap model, Reasoning -> frontier model)**: Tiered Model Cascade (Grunt Work -> cheap model, Reasoning -> frontier model)
- **Local Model Integration (Ollama, Llama 3, local embedding models)**: Local Model Integration (Ollama, Llama 3, local embedding models)

## Operational & Execution Workflow
1. **Analyze Requirements & Constraints**: Identify input payloads, boundaries, and failure modes.
2. **Implement Core Logic**: Build modular execution steps adhering to tool-agnostic standards.
3. **Embed Verification Gates**: Verify outputs using automated checks or golden dataset benchmarks.
4. **Deploy & Monitor**: Monitor execution metrics, token cost efficiency, and error rates.

## 💡 Connecting This Skill to Your Ideas

### Applicable to Current & Unfinished Ideas:
- 🎯 **Bulk Real Estate Scraper**:  Use cheap/fast models to summarize raw property descriptions, routing only high-priority deals to Opus/Sonnet.
- 🎯 **High-Volume Customer Support**:  Route 80% of routine FAQs through low-cost models, escalating edge cases to frontier models.
- 🎯 **Cost-Effective Data Pipeline**:  Reduce monthly LLM API spend by 90% across background indexing tasks.

### How to Use for New Ideas:
When brainstorming a new project or automation:
1. Identify if this skill solves an input, process, or quality bottleneck in your concept.
2. Reference the core technical concepts above to quickly integrate this pattern into your implementation plan.
3. Combine with complementary skills (e.g., pairing *Agentic Workflow Design* with *Autonomous Verification Loops*).
