# Author Corpus Builder

![Skill](https://img.shields.io/badge/Codex-Skill-111827)
![Status](https://img.shields.io/badge/status-v1_ready-16a34a)
![License](https://img.shields.io/badge/license-MIT-blue)

Turn a self-interview into a durable creator corpus for X, Xiaohongshu, Douyin, newsletters, and personal IP writing.

Most AI writing starts too late.

It starts at the post.

This skill starts earlier: with the person.

## What it does

`author-corpus-builder` gives Codex a structured workflow for helping creators build their own content source material before asking AI to write.

It helps produce:

- a 50-question self-interview
- an author values source
- a minimal corpus unit pool
- a longform theme pool
- a voice and style calibration sheet
- platform-ready drafts based on real experience

The core pipeline:

```text
self-interview -> answer analysis -> author corpus -> topic pool -> platform drafts
```

## Why it exists

Many creators read growth advice like:

- prepare your own values
- build a personal corpus
- use lived experience
- balance self-expression with platform emotion
- make AI sound more human

The problem is that these steps are easy to agree with and hard to execute.

This skill turns that advice into a repeatable interview and extraction workflow.

## Quick start

Copy or install the skill folder:

```text
author-corpus-builder/
```

Then ask Codex:

```text
Use $author-corpus-builder to generate a 50-question self-interview for building my creator corpus.
```

Or paste your answers:

```text
Use $author-corpus-builder to analyze these answers and create my author values source, minimal corpus unit pool, longform theme pool, and voice calibration sheet.
```

## Example use cases

### 1. Build a personal content corpus

```text
Use $author-corpus-builder to interview me in 5 batches of 10 questions. I want to build a corpus for X longform and Xiaohongshu posts.
```

### 2. Analyze raw answers

```text
Use $author-corpus-builder to analyze this self-interview. Extract stable beliefs, lived scenes, reusable lines, contradictions, and longform themes.
```

### 3. Remove AI tone from a draft

```text
Use $author-corpus-builder to compare this draft with my human-written samples and rewrite it closer to my actual syntax.
```

## The 50-question interview

The question bank covers:

- identity and temperament
- lived experience
- work, tools, and AI
- media and expression
- money, freedom, and markets
- optional expansion for relationships, fear, and future goals

The questions are designed to extract facts, scenes, body-level details, beliefs, contradictions, and raw lines.

## Output assets

### Author values source

Your stable beliefs, aversions, pursuits, trusted topics, and recurring tensions.

### Minimal corpus unit pool

Small reusable content atoms:

- raw lines
- lived scenes
- beliefs
- market feedback
- tensions
- style rules

### Longform theme pool

Durable themes that can become X longform posts, Xiaohongshu image-card scripts, Douyin scripts, or newsletters.

### Voice calibration sheet

A practical style guide built from the creator's own writing samples.

It studies syntax, rhythm, repeated phrases, rough edges, and the way the creator moves from scene to judgment.

## Repository structure

```text
.
├── README.md
├── LICENSE
└── author-corpus-builder/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    ├── references/
    │   ├── question-bank.md
    │   ├── analysis-rubric.md
    │   ├── output-schemas.md
    │   └── style-calibration.md
    └── examples/
        ├── example-input-part-a.md
        ├── example-output-analysis.md
        └── example-output-corpus.md
```

## Design principles

- Start from lived experience, not abstract advice.
- Preserve raw phrasing before polishing.
- Separate observed fact from inference.
- Extract scenes before slogans.
- Use AI to organize the person, not replace the person.
- Calibrate syntax against human-written samples.

## License

MIT.

Use it, fork it, adapt it, and build your own corpus.
