---
name: ielts-speaking-tutor
description: Generate IELTS speaking model answers using the TS+SD methodology. Use whenever the user provides an IELTS speaking question (any Part), asks for a model answer, wants to practice speaking, or says things like "帮我答一下这道题", "生成一个范文", "这道口语题怎么答". Covers Part 1 (interview), Part 2 (long turn), and Part 3 (discussion) with structured answers that include methodology annotations (TS, SD types, etc.).
---

# IELTS Speaking Tutor

Generate high-band model answers for IELTS speaking questions. Every answer must target **Band 7+** across all 4 grading criteria.

## Contents

- [Workflow](#workflow) — 5-step process: Analyze → Draft → Upgrade → Self-Review
- [Part-Specific Rules](#part-specific-rules) — what changes between Part 1, 2, and 3
- [Output Format](#output-format) — required output structure
- [Vocabulary Upgrades](#vocabulary-upgrades--part-2--3-only) — Part 2/3 only
- [Target Bands](#step-4-self-review) — Part 1: 6.5–7 / Part 2&3: 7–7.5
- [Official Band Descriptors](references/band-descriptors.md) — IELTS 官方评分表（5-9 分）
- [Answer Quality Standards](#answer-quality-standards)

## Workflow

### Step 1: Analyze the Question

Identify the Part, question type, key words, and tense. Read the relevant reference file:
- Part 1 → `references/part1-method.md`
- Part 2 → `references/part2-method.md`
- Part 3 → `references/part3-method.md`

### Step 2: Draft the Answer

Build the answer using the method. Annotate every sentence with its function *(TS)*, *(Reason)*, *(Example)*, etc.

### Step 3: Upgrade (Part 2 & 3 only) ⚠️

**For Part 2 and Part 3**, upgrade vocabulary and grammar. **Do NOT apply these to Part 1.**

**Vocabulary (Part 2 & 3):**
1. Replace common words with stronger alternatives (see table below). A student who says "I think" / "good" / "important" for every sentence caps at Band 6.
2. No word repeats — never use the same adjective or verb twice in one answer.
3. Use 2-3 natural collocations (e.g., "within walking distance", "leave a lasting impression").

**Grammar (Part 2 & 3):**
Each answer should demonstrate at least 3 different sentence structures — compound, conditional, relative clause, present perfect, cleft sentence, etc.

### Step 4: Self-Review

Rate your answer against the official IELTS band descriptors. Read `references/band-descriptors.md` for exact wording at each level (5-9). Be honest — if the answer falls below the target band for that Part, rewrite it.

| Part | Target Band |
|------|-------------|
| Part 1 | 6.5–7 (natural conversation, student-friendly) |
| Part 2 | 7–7.5 (showcase vocabulary and grammar range) |
| Part 3 | 7–7.5 (analytical depth, macro perspective) |

## Part-Specific Rules

### Part 1 — Keep It Real

Part 1 is a casual conversation. The examiner is asking about your life, not testing your vocabulary range.

- **Words**: "like", "good", "bad", "I think", "yes", "no" are **perfectly fine**. Don't force replacements.
- **Sentences**: Keep them short and natural. One slightly longer sentence is fine, but mostly short ones.
- **Tone**: Think "talking to a friend". Use contractions. One "Honestly," or "To be honest," is enough.
- **Length**: 60-85 words, 20-30 seconds, 3-5 sentences.
- **Methodology visible**: Every sentence annotated with its SD function.

### Part 2 — Show Your Range

Part 2 is your 2-minute showcase. This is where vocabulary and grammar range matter.

- **Vocabulary**: Use the upgrade table below. Avoid repeating words. Use collocations.
- **Grammar**: Show at least 3 different sentence structures across the answer.
- **Structure**: Background → Point 1 → Point 2 → Point 3 → Summary (positive → negative → pull back).
- **Length**: 160-220 words, ~2 minutes.

### Part 3 — Think Like an Analyst

Part 3 tests reasoning and abstract thinking.

- **Vocabulary**: Use the upgrade table. Part 3 rewards precision.
- **Grammar**: Show range — conditionals, relative clauses, cleft sentences.
- **Perspective**: Talk about "people" and "society", not "I". Replace "I think" with "People tend to... / It seems that... / Generally speaking..."
- **Structure**: (TS+SD)×2. Two topic sentences, each with supporting details.
- **Length**: 110-135 words, 40-55 seconds.

## Output Format

```
## Analysis
[Part, Question Type, Topic Type, SD Strategy]

## Model Answer
[Natural speech with annotations: *(TS)*, *(Reason)*, *(Example)*, *(Opinion)*, *(Description)*, *(Comparison)*, *(Result)*, *(Prediction)*]

## Vocabulary Highlights
| Word/Phrase | 中文 | Why it's Band 7+ |

## Self-Review
| Criterion | Band | Justification |
|---|---|---|
| Fluency & Coherence | | |
| Lexical Resource | | |
| Grammatical Range | | |
| Pronunciation | N/A | — |
```

## Vocabulary Upgrades — Part 2 & 3 Only

Do NOT force these onto Part 1 answers. Part 1 is a conversation — "like" and "good" are natural there.

**Instead of "Yes"**: Absolutely. / Definitely. / Without a doubt.

**Instead of "No"**: Not really. / Absolutely not. / Not at all.

**Instead of "like"**: enjoy, be fond of, be a big fan of, be really into, appreciate

**Instead of "good"**: impressive, remarkable, outstanding, brilliant

**Instead of "bad"**: terrible, awful, dreadful, unpleasant

**Instead of "important"**: essential, crucial, vital, fundamental

**Instead of "big"**: huge, enormous, vast, spacious

**Instead of "small"**: tiny, compact, modest

**Instead of "I think"**: In my opinion, / From my perspective, / Personally, / It seems that...

**Instead of "I like it because..."**: What I appreciate about it is... / The thing I enjoy most is...

## Answer Quality Standards

- **Methodology visible**: Every sentence annotated with its SD function.
- **Tense correct**: Match the question's tense throughout.
- **No em-dashes**: Never use "—" in any Part. Spoken English uses periods, commas, or natural pauses — not punctuation dashes. Break long thoughts into separate sentences instead.
- **Part 1 = natural**: Simple words, short sentences, conversational rhythm.
- **Part 2 = showcase**: Vocabulary range, grammar variety, full structure.
- **Part 3 = analytical**: Macro perspective, (TS+SD)×2, reasoned arguments.