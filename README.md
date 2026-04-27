# Author Corpus Builder

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827)
![Version](https://img.shields.io/badge/version-v1-16a34a)
![License](https://img.shields.io/badge/license-MIT-blue)
![Made for creators](https://img.shields.io/badge/made_for-creators-f97316)

Build a creator corpus before asking AI to write for you.

`author-corpus-builder` is a Codex skill that uses a 50-question self-interview to turn your lived experience, values, fears, voice, and market beliefs into reusable content assets.

It is built for creators who want to write on X, Xiaohongshu, Douyin, newsletters, or personal blogs without sounding like generic AI copy.

## The idea

Most AI writing starts at the wrong layer.

People open a blank prompt and ask:

```text
Write me a viral post about my niche.
```

The model can produce something clean. It may even sound correct. But if there is no personal corpus behind it, the writing has no private source.

This skill starts earlier.

It asks:

- What do you actually believe?
- What happened to you that made you believe it?
- What do you want that sounds a little embarrassing?
- What kind of writing makes you uncomfortable?
- Which real scenes can support your ideas?
- Which phrases already sound like you?

Then it turns the answers into structured content assets.

## What it creates

```text
50-question self-interview
        ↓
answer analysis
        ↓
author values source
        ↓
minimal corpus unit pool
        ↓
longform theme pool
        ↓
voice calibration sheet
```

You can later use these assets for:

- X longform posts
- short judgments
- Xiaohongshu image-card scripts
- Douyin scripts
- newsletters
- personal brand positioning
- AI writing style calibration

The v1 focus is deliberately narrow: build the creator corpus first.

## Who this is for

Use this if you:

- want to make content but keep writing posts that feel generic
- have life experience but cannot turn it into reusable topics
- rely on AI and dislike the flattened "AI voice"
- want to build a personal IP from real memories and beliefs
- need a repeatable way to prepare yourself before writing
- want Codex to help you extract voice, themes, and raw material

This is especially useful if you have read content-growth advice like "build your own corpus" and thought:

```text
Okay, but what do I actually ask myself?
```

## Quick start

Copy or install the skill folder:

```text
author-corpus-builder/
```

Then ask Codex:

```text
Use $author-corpus-builder to generate a 50-question self-interview for building my creator corpus.
```

If you want to answer gradually:

```text
Use $author-corpus-builder to interview me in 5 batches of 10 questions.
```

If you already have answers:

```text
Use $author-corpus-builder to analyze these answers and create my author values source, minimal corpus unit pool, longform theme pool, and voice calibration sheet.
```

If a draft still sounds too AI-generated:

```text
Use $author-corpus-builder to compare this draft with my human-written samples and rewrite it closer to my actual syntax.
```

## The 50-question interview

The question bank covers five core areas:

1. Identity and temperament
2. Lived experience
3. Work, tools, and AI
4. Media and expression
5. Money, freedom, and markets

Each question is designed to pull out one of six things:

- raw facts
- concrete scenes
- body-level feelings
- stable beliefs
- productive contradictions
- reusable lines

That is the material most AI drafts are missing.

## Output assets

### Author values source

Your core pursuits, aversions, beliefs, trusted topics, and recurring tensions.

### Minimal corpus unit pool

Small reusable content atoms:

- raw lines
- lived scenes
- beliefs
- tensions
- market feedback
- style rules

### Longform theme pool

Durable themes that can become long posts, short posts, image cards, or scripts.

### Voice calibration sheet

A practical style guide built from your own writing samples.

It studies sentence length, rhythm, repeated words, rough edges, transitions, favorite moves, and patterns to avoid.

## What makes it different

This skill does not try to be a complete growth course.

It focuses on the part most creators skip:

```text
prepare the person before generating the content
```

Trends change. Algorithms change. Platform formats change.

Your lived experience, beliefs, and voice are slower assets.

Build those first, then reuse them everywhere.

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

- Start from lived experience.
- Preserve raw phrasing before polishing.
- Separate observed fact from inference.
- Extract scenes before slogans.
- Study syntax, not only topics.
- Keep the creator visible inside the output.

## Roadmap

v1:

- 50-question interview
- answer analysis rubric
- author corpus output schemas
- voice calibration rules

Possible v2:

- corpus-to-X-longform workflow
- corpus-to-short-post workflow
- corpus-to-image-card workflow
- publishing feedback loop

The v1 boundary is intentional. A useful corpus should exist before the distribution machine starts.

## License

MIT.

Use it, fork it, adapt it, and build your own corpus.
