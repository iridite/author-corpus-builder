---
name: author-corpus-builder
description: Build a reusable creator corpus from self-interview answers. Use when a user wants to prepare themselves for X/Twitter longform, personal IP writing, Xiaohongshu/Douyin content, "human-sounding" AI-assisted writing, author voice extraction, self-question prompts, value-system extraction, longform topic pools, or content assets based on personal experiences and beliefs.
---

# Author Corpus Builder

## Overview

Use this skill to turn a creator's lived experience into durable content assets.

The workflow is:

`self-interview -> answer analysis -> author corpus -> topic pool -> platform-ready drafts`

The skill is designed for creators who do not want generic AI copy. It forces writing to begin from real memories, body-level details, personal stakes, market beliefs, and observed phrasing.

## Quick Decision

If the user asks for questions, read `references/question-bank.md`.

If the user pasted answers and asks for analysis, read `references/analysis-rubric.md` and `references/output-schemas.md`.

If the user complains that writing still feels AI-generated, read `references/style-calibration.md`.

If the user wants publishable content, first build the corpus assets, then draft content from those assets. Do not jump straight from a topic to a polished post.

## Workflow

### 1. Generate the self-interview

Use 30 to 50 questions depending on the user's appetite.

Default to the full 50-question interview for creator corpus building.

Ask questions in batches if the user wants to answer gradually. A good batch size is 10 questions.

Use the six modules from `references/question-bank.md`:

- identity and temperament
- lived experience
- work, tools, and AI
- media and expression
- money, freedom, and markets
- relationships, fear, and future optional expansion

### 2. Accept raw answers

Preserve raw answers. Do not clean them too early.

Raw language contains the user's cadence, anxiety, slang, repeated words, and sentence shapes. These are part of the corpus.

If answers arrive in parts, analyze one part at a time and keep a running synthesis.

### 3. Analyze answers

For each answer batch, extract:

- stable beliefs
- lived scenes
- body-level details
- contradictions and tensions
- reusable lines
- possible longform themes
- platform-fit notes
- follow-up questions

Use `references/analysis-rubric.md` for the scoring and extraction rules.

### 4. Build corpus assets

Produce these four assets first:

1. Author values source
2. Minimal corpus unit pool
3. Longform theme pool
4. Voice and style calibration sheet

Use `references/output-schemas.md` for the exact shapes.

### 5. Draft from the corpus

When drafting X posts, longform threads, Xiaohongshu image-card scripts, or Douyin scripts:

1. Pick one longform theme.
2. Pull 3 to 7 minimal corpus units.
3. Identify one audience emotion or platform context.
4. Draft in the user's calibrated syntax.
5. Remove generic explanation patterns.
6. Add a feedback field so the content can return data to the corpus.

## Core Rules

- Start from real experience, not abstract advice.
- Preserve imperfect human rhythm when it carries identity.
- Separate observed facts from interpretation.
- Never invent life events.
- Ask follow-up questions when an answer contains a strong claim without a scene.
- Avoid "template wisdom" and overly even paragraphing.
- Do not polish away the user's odd phrasing if that phrasing is part of their voice.

## Bundled References

- `references/question-bank.md`: 50-question self-interview.
- `references/analysis-rubric.md`: how to extract durable content assets.
- `references/output-schemas.md`: reusable Markdown output formats.
- `references/style-calibration.md`: how to compare drafts against human-written samples.
