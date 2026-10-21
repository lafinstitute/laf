<p align="center">
  <img src="static/cropped-cropped-bro-1-small-1-1.png" alt="Lean Architecture Framework (LAF)" width="260">
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

#### Quick start: use the repository as project context

1. **Get the files.** Clone the repository with Git, or download the repository as a ZIP file and extract it. For example:

   ```bash
   git clone <repository-url>
   ```

2. **Open the project in your AI tool.** In Claude, start a conversation in a Project and add the repository files to that Project's knowledge or uploaded files. In ChatGPT, create or open a Project and add the repository files to the Project's files. If your client supports opening a local folder or workspace directly, open the cloned repository instead.
3. **Ask the model to read the instructions.** Tell it to read `README.md`, `SOURCES.md`, the relevant files in `context/`, and the selected skill's `SKILL.md`. For reliable answers, make the whole `context/` directory and the chosen skill file available, not just the README.
4. **Start the skill by asking for the task.** The skill is the instruction file; in clients that support automatic skills, enable or install the skill using that client's documented skill workflow. Otherwise, ask the model to follow the skill file explicitly. For example:

   ```text
   Read skills/explain-laf/SKILL.md and use it to explain LAF to a CIO. Focus on how CPA and Reference Architecture support portfolio decisions.
   ```

   ```text
   Read skills/prepare-for-laf-course/SKILL.md and use it to prepare me for an LAF course. I have 30 minutes a day for three days. Start with a short diagnostic quiz.
   ```

The skill does not run as a program or install itself when you open the repository. The AI assistant follows its `SKILL.md` instructions and uses the linked knowledge files as its source. If the conversation cannot access repository files, upload the files or paste the relevant `SKILL.md` and context documents into the conversation.

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
