---
name: coarse-sandpaper
description: Second-pass editing skill for any long-form writing. Translates the principles of good writing into AI-perceivable rules that reference only what is present in the text — word counts, sentence structures, semantic relationships, and detectable patterns. Use after a skeleton/assembly pass, before voice polish. Works on Substack posts, essays, sales pages, YouTube scripts, anything 1,000+ words.
---

# coarse-sandpaper

Second-pass editing skill. The skeleton is written. Now tighten the bones.

This skill only uses rules that can be verified by reading the text. No rules reference sound, rhythm-by-ear, flow, feel, or any human sensory judgment. Every rule is testable against detectable properties of the text itself.

## When to Use

Run on any draft that has structure but feels flat, bloated, or repetitive. After assembly, before voice polish.

## Prerequisites

Before editing, load the six principle files in `references/`. Each file defines ONE principle as an AI-perceivable test. Read each file at the start of every session. Do not apply from memory.

1. `references/forward-motion.md` — each sentence must add new information to the one before it
2. `references/sentence-variance.md` — consecutive sentences must differ on measurable dimensions
3. `references/specificity.md` — concrete, countable, named references beat abstractions
4. `references/compression.md` — sentences must collapse to their minimum word count without loss of meaning
5. `references/active-subject.md` — the actor must appear before the action
6. `references/trust.md` — after a complete statement, the next sentence must either advance or stop

## Workflow

**Step 1: Read the draft in full.** Hold the argument in working memory. Do not edit yet.

**Step 2: Apply the six principles in order, paragraph by paragraph.** For each paragraph:
- Run `forward-motion.md` test on every sentence pair
- Run `sentence-variance.md` test on every 4-sentence window
- Run `specificity.md` test on every abstract noun
- Run `compression.md` test on every sentence over 15 words
- Run `active-subject.md` test on every sentence
- Run `trust.md` test after every complete statement

**Step 3: Execute the fix specified by each rule when triggered.** Do not judge; act on the rule.

**Step 4: After all paragraphs processed, check section length balance.** Any section more than 1.5x the length of the shortest section — verify it is earning its length. Cut if not.

**Step 5: Output revised draft plus a Pass 2 Notes section.** Notes contain: rule violations found and fixed, sections flagged for Pass 3 (judgment calls outside these rules), word count before/after.

## Principle of Precedence

When two rules conflict, the rule that removes content wins over the rule that adds content. Coarse-sandpaper is a subtractive pass. The draft should always shrink.

## What This Skill Does NOT Do

- Does not add voice, personality, humor, warmth
- Does not change structure, section order, or argument
- Does not insert new content
- Does not judge taste (that is Pass 3, directed by the user)

## Output Format

```
[REVISED DRAFT]

---

## Pass 2 Notes

### Violations found and fixed:
- [paragraph N: rule violated, fix applied]

### Flagged for Pass 3:
- [judgment calls outside these rules]

### Word count: [before] → [after]
```

## Iteration

When a new failure mode appears that no existing rule catches, add a new principle file in `references/` following the same format: TRIGGER → TEST → FIX, using only AI-perceivable properties of text.

---

*V2. Rebuilt April 18, 2026. Every rule in the references is stated in terms of text properties the model can directly perceive. No rules reference sound, ear, flow, or reading aloud.*
