# Author Corpus Builder

![Codex Skill](https://img.shields.io/badge/Codex-Skill-111827)
![Version](https://img.shields.io/badge/version-v1-16a34a)
![License](https://img.shields.io/badge/license-MIT-blue)
![Made for creators](https://img.shields.io/badge/made_for-creators-f97316)

> 中文优先 / English below

用 50 个自我问话，先把“你自己”准备好，再让 AI 帮你写内容。

`author-corpus-builder` 是一个 Codex Skill。它会通过一组 50 问，把创作者的真实经历、价值观、表达习惯、恐惧、欲望、市场判断整理成可复用的个人内容语料库。

它适合想在 X、小红书、抖音、公众号、newsletter 或个人博客上持续输出的人，尤其适合那些明明有经历、有想法，但一用 AI 写就变得很像模板的人。

## 这个项目解决什么问题

很多人用 AI 写内容时，第一句话就是：

```text
帮我写一条关于某某赛道的爆款内容。
```

AI 当然能写。

它能写得顺，写得完整，甚至看起来挺正确。

但如果背后没有自己的语料库，最后经常会出现一个问题：

```text
这段话没错，但不像我。
```

这个 Skill 处理的是更前面那一步：

- 你到底相信什么？
- 哪些经历真的改变过你？
- 你最想逃离什么？
- 你最想得到什么？
- 你发内容时怕什么？
- 你有哪些话，其实已经很像你自己？

先把这些东西问出来，再进入写作。

## 它会生成什么

```text
50 个自我问话
        ↓
回答分析
        ↓
作者价值观真源
        ↓
最小语料单元池
        ↓
长文母题池
        ↓
表达风格校准表
```

这些资产后面可以继续用于：

- X 长文
- X 短判断
- 小红书图文脚本
- 抖音口播稿
- 公众号文章
- 个人 IP 定位
- AI 写作去模板化

v1 的边界很清楚：先把个人语料库做出来。

## 适合谁

如果你有这些问题，可以试试：

- 想做内容，但写出来总像泛泛而谈
- 有很多经历，却不知道怎么变成选题
- 用 AI 写东西，老觉得不像自己
- 想做个人 IP，但还没整理过自己的底层素材
- 看过很多起号方法论，真正动手时还是卡在“我能写什么”
- 想让 Codex 帮你抽取价值观、经历、母题和表达习惯

尤其适合读过类似“先建立自己的语料库”这种建议，但不知道从哪里问起的人。

## 快速开始

复制或安装这个 Skill 文件夹：

```text
author-corpus-builder/
```

然后对 Codex 说：

```text
Use $author-corpus-builder to generate a 50-question self-interview for building my creator corpus.
```

如果你想分批回答：

```text
Use $author-corpus-builder to interview me in 5 batches of 10 questions.
```

如果你已经有一批回答：

```text
Use $author-corpus-builder to analyze these answers and create my author values source, minimal corpus unit pool, longform theme pool, and voice calibration sheet.
```

如果你觉得草稿还有 AI 味：

```text
Use $author-corpus-builder to compare this draft with my human-written samples and rewrite it closer to my actual syntax.
```

## 50 问覆盖哪些部分

问题分成 5 组：

1. 你是谁：身份、气质、稳定特征
2. 真实经历：失败、转折、消耗、开窍
3. 工作、工具与 AI：技术、效率、自由感、工具陷阱
4. 自媒体与表达：发布恐惧、人味、真实语气、内容边界
5. 钱、自由与市场：赚钱、市场反馈、副业、时间主权

每个问题都在尽量抽取 6 类素材：

- 真实事实
- 具体场景
- 身体感受
- 稳定信念
- 内在矛盾
- 可复用原话

这些才是后面让内容变得像你的材料。

## 输出资产说明

### 作者价值观真源

整理你的核心追求、厌恶、信念、长期矛盾和可持续表达边界。

### 最小语料单元池

把回答拆成更小的内容原子：

- 原话
- 场景
- 信念
- 矛盾
- 市场反馈
- 风格规则

### 长文母题池

从你的经历和判断里，生成可以长期写下去的主题。

### 表达风格校准表

根据你自己的文字样本，提取句法、节奏、重复词、毛边、转折习惯和禁用表达。

## 这个 Skill 的定位

它不是一个完整的起号课程。

它只做很多人跳过的那一步：

```text
在生成内容之前，先准备好这个人
```

热点会变。

算法会变。

平台形式会变。

但你的经历、信念、语气和表达习惯，是更慢、更耐用的资产。

先把这些资产整理出来，再去做分发。

## 项目结构

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

## 设计原则

- 先问经历，再写观点
- 先保留原话，再考虑润色
- 区分事实、推断和可写内容
- 先抽场景，再抽金句
- 学句法，不只学主题
- 让创作者本人留在输出里

## Roadmap

v1:

- 50 问自我访谈
- 回答分析规则
- 作者语料库输出模板
- 表达风格校准规则

可能的 v2:

- 语料库转 X 长文
- 语料库转短判断
- 语料库转图文脚本
- 发布反馈回写

v1 保持这个边界是有意的。一个好用的语料库，应该先于分发机器存在。

## License

MIT.

欢迎使用、fork、改造，然后建立你自己的作者语料库。

---

# Author Corpus Builder (English)

Build a creator corpus before asking AI to write for you.

`author-corpus-builder` is a Codex Skill that uses a 50-question self-interview to turn your lived experience, values, fears, voice, and market beliefs into reusable content assets.

It is built for creators who want to write on X, Xiaohongshu, Douyin, newsletters, or personal blogs without sounding like generic AI copy.

## What problem does it solve?

Many AI writing workflows start with a prompt like:

```text
Write me a viral post about my niche.
```

The model can produce something clean. It may even sound correct. But when there is no personal corpus behind the writing, the output often has no private source.

This skill starts one layer earlier.

It asks:

- What do you actually believe?
- What happened to you that made you believe it?
- What are you trying to escape?
- What do you want that feels slightly embarrassing?
- What scares you when publishing?
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

- want to make content but keep writing generic posts
- have life experience but cannot turn it into reusable topics
- rely on AI and dislike the flattened "AI voice"
- want to build a personal IP from real memories and beliefs
- need a repeatable way to prepare yourself before writing
- want Codex to help you extract voice, themes, and raw material

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

## Design principles

- Start from lived experience.
- Preserve raw phrasing before polishing.
- Separate observed fact from inference.
- Extract scenes before slogans.
- Study syntax, not only topics.
- Keep the creator visible inside the output.

## License

MIT.
