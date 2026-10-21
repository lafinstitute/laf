<p align="center">
  <img src="https://laf.institute/wp-content/uploads/2022/04/laf-logo.png" alt="Lean Architecture Framework (LAF)" width="260">
</p>

<h1 align="center">Lean Architecture Framework</h1>
<p align="center"><strong>A guide to LAF for people and AI assistants</strong></p>

This repository helps you get to know the **Lean Architecture Framework (LAF)**, understand its concepts, and prepare for a course. It contains accessible materials based on **LAF Guide 1.6**, learning exercises, and two AI skills.

> This is supporting material, not the official guide or a replacement for course materials. See [SOURCES.md](SOURCES.md) for source and licensing details.

## What can you do here?

### Learn about LAF

Start with [What is LAF?](context/overview/what-is-laf.md), then read about its [goals and characteristics](context/overview/goals-and-principles.md) and review the [glossary](context/glossary.md). The materials explain the framework's three parts: Definition, Execution, and Improvement and Monitoring.

### Understand the practical elements of the framework

- [Reference Architecture](context/framework/artifacts/reference-architecture.md) — the direction for the application environment.
- [CPA and Component Passport](context/framework/artifacts/component-portfolio-assessment.md) — assessment and description of the current portfolio.
- [Solution Vision](context/framework/artifacts/solution-vision.md) — an architectural design for an incremental change driven by a business need.
- [Metrics](context/framework/artifacts/metrics.md) — example measures of architectural progress and health.
- [MRAC and AI in the SDLC](context/ai-augmented-sdlc/overview.md) — LAF 1.6 additions for AI-assisted software development.

Other topics—including standards, the repository, the architecture team, the Architectural Forum, practices, and anti-patterns—are available in [`context/`](context/).

### Prepare for a course

Use the [course preparation plan](context/learning/course-preparation.md), choose the [practitioner path for architects and analysts](context/learning/practitioner-path.md) or the [executive path](context/learning/executive-path.md), and reinforce your knowledge with [questions and exercises](context/learning/questions-and-exercises.md).

### Work with an AI assistant

The repository includes two skills in the standard `SKILL.md` format:

| Skill | What it does | Example prompt |
|---|---|---|
| [Explain LAF](skills/explain-laf/SKILL.md) | Explains LAF concepts and how they relate, adapting the level of detail for CIOs, architects, analysts, or learners. | “Explain to a CIO how CPA and Reference Architecture support portfolio decisions.” |
| [Prepare for LAF course](skills/prepare-for-laf-course/SKILL.md) | Creates a study plan, teaches topics, asks practice questions, and helps identify knowledge gaps. | “Help me prepare for an LAF course. I have 30 minutes a day for three days. Start with a short quiz.” |

To use a skill, make this repository available to your AI assistant, or copy the skill's directory to the skills location supported by your AI tool. Keep the `context/` directory available because the skill uses these materials as its knowledge source.

## How to use these materials

The content distinguishes between:

- **LAF 1.6** — a summary of what the guide says;
- **Explanation** — additional context to make the material easier to understand;
- **Example / exercise** — learning material, not an official LAF rule.

Where LAF leaves a choice to the organization—for example, tools, metric thresholds, or the details of an MRAC schema—the materials say so. This repository describes version 1.6; check which version your course uses before attending.

## Repository structure

```text
context/   knowledge base, glossary, learning paths, and exercises
skills/    instructions for the Explain LAF and Prepare for LAF course skills
SOURCES.md source attribution and licensing information
```

## Maintaining the materials

When updating the materials for a newer LAF version, update the source information, review the related summaries and exercises, and check the links. Preserve the distinction between content from the guide, explanations, and examples.
