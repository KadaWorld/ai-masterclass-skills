---
name: autonomous-verification-loops
description: Building self-correcting AI loops where agents verify, test, and score their own deliverables before handing off work.
---

# Autonomous Verification Loops & Quality Gates

## Overview & Purpose
Building self-correcting AI loops where agents verify, test, and score their own deliverables before handing off work.

## Core Technical Concepts
- **Self-Correction & Quality Threshold Gates (60% -> 95%+ completion)**: Self-Correction & Quality Threshold Gates (60% -> 95%+ completion)
- **Visual Verification via Headless Browser Screenshot Loops**: Visual Verification via Headless Browser Screenshot Loops
- **Functional Verification (Synthetic API calls, JSON Schema validation)**: Functional Verification (Synthetic API calls, JSON Schema validation)
- **Iterative Feedback Loops without human intervention**: Iterative Feedback Loops without human intervention

## Operational & Execution Workflow
1. **Analyze Requirements & Constraints**: Identify input payloads, boundaries, and failure modes.
2. **Implement Core Logic**: Build modular execution steps adhering to tool-agnostic standards.
3. **Embed Verification Gates**: Verify outputs using automated checks or golden dataset benchmarks.
4. **Deploy & Monitor**: Monitor execution metrics, token cost efficiency, and error rates.

## 💡 Connecting This Skill to Your Ideas

### Applicable to Current & Unfinished Ideas:
- 🎯 **Web Scraper Self-Healing**:  Verify scraped data against JSON schemas; re-try selector strategies automatically if validation fails.
- 🎯 **Automated Code Quality Gate**:  Run unit tests / linters inside agent loops before declaring code finished.
- 🎯 **Data Pipeline Validation**:  Check BigQuery / SQL ingestion counts against raw input counts before approving table writes.

### How to Use for New Ideas:
When brainstorming a new project or automation:
1. Identify if this skill solves an input, process, or quality bottleneck in your concept.
2. Reference the core technical concepts above to quickly integrate this pattern into your implementation plan.
3. Combine with complementary skills (e.g., pairing *Agentic Workflow Design* with *Autonomous Verification Loops*).
