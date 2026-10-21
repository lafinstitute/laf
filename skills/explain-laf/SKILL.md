---
name: explain-laf
description: Explain the Lean Architecture Framework (LAF) using this repository's LAF 1.6 knowledge base, adapting depth and language to CIOs, architects, analysts, or other learners. Use for questions about LAF concepts, artifacts, roles, practices, metrics, or AI-augmented SDLC.
---

# Explain LAF

## Purpose

Give accurate, audience-appropriate explanations of LAF. Use the repository knowledge base as the source of truth for this skill. Do not confuse a source summary with an implementation recommendation or an illustrative example.

## Read the relevant context

Start with `README.md`, `SOURCES.md`, `context/overview/what-is-laf.md`, and `context/glossary.md`. Then read only the relevant topic files under `context/framework/`, `context/ai-augmented-sdlc/`, or `context/learning/`. Follow linked files when a relationship matters.

## Workflow

1. Identify the question and likely audience. If unspecified, answer for a technically literate general audience.
2. State the short answer first, then explain the relevant LAF concept and its relation to other artifacts or practices.
3. Ground claims in the knowledge files and include the LAF 1.6 section named there when useful.
4. Label added interpretation and examples. Never present them as prescribed LAF rules.
5. If the guide leaves a choice to an organization, say so and identify the decision needed.
6. If the source material is insufficient or ambiguous, say what is not established and avoid inventing a rule. Mention that this repository is based on v1.6 and advise checking the applicable course/source edition if version currency matters.

## Audience adjustment

- **CIO / executive:** focus on outcomes, decision rights, investment, risk, and measures; minimize jargon and define terms.
- **Architect / analyst:** explain artifacts, inputs/outputs, relationships, lifecycle, roles, and trade-offs.
- **Learner:** define terms, give a simple example, then ask a short check-for-understanding question if helpful.

## Response shape

Use only the sections that help:

1. **W skrócie** — direct answer in one to three sentences.
2. **Jak to działa w LAF** — concept and links to related LAF elements.
3. **Przykład** — clearly labeled as illustrative, if useful.
4. **Co zależy od organizacji** — open implementation choices, if relevant.
5. **Źródło** — knowledge-base filename and guide section/version when useful.

Answer in the user's language. Preserve canonical English LAF terms in parentheses on first mention when translation could blur meaning. Be concise by default; expand when asked.

## Boundaries

- Do not claim that this summary is the official LAF guide or that v1.6 is the latest version.
- Do not invent mandatory templates, approval authorities, metric thresholds, schemas, or frequencies beyond what the cited source says.
- Do not infer that MRAC replaces human-readable RA/Standards/CP: LAF 1.6 describes it as a synchronized derivative, with human-readable artifacts as the primary source of truth.
- LAF section 5 does not define enterprise governance for AI models/services; state this boundary when asked.
