# Compression

*Every sentence must collapse to its minimum word count without loss of propositional content. Words that can be removed without changing what the sentence asserts are violations.*

## The Principle

A sentence has a propositional content: the claim it asserts, the information it conveys, the action it specifies. Compression is the process of removing every word that is not required to deliver that content.

This is not a matter of style. It is a word-removal test applied to every sentence.

## The Test

For every sentence over 10 words, execute this procedure:

**Step 1.** Identify the propositional content of the sentence in one phrase (the claim, the action, the information being conveyed).

**Step 2.** For each word in the sentence, ask: if this word is removed, is the propositional content still fully delivered?

**Step 3.** If yes — remove the word. If no — keep it.

**Step 4.** Repeat until no further words can be removed.

## Detectable Categories of Removable Words

These word classes are frequently removable. Their presence triggers inspection:

**Hedges.** Words that soften a claim without adding meaning:
- "just," "really," "actually," "basically," "essentially," "literally," "pretty much," "sort of," "kind of," "somewhat," "a bit," "a little"

**Intensifier filler.** Adverbs that modify the intensity of another word without adding information:
- "very," "quite," "extremely," "highly," "truly," "simply," "completely," "totally," "absolutely"

**Throat-clearing openers.** Phrases that delay the actual content of a sentence:
- "What I want to say is...", "The thing is...", "Here's the thing...", "It's important to note that...", "It's worth mentioning that...", "I'd like to point out that..."

**Redundant connectives.** Phrases that pad transitions:
- "in order to" → "to"
- "due to the fact that" → "because"
- "at this point in time" → "now"
- "in the event that" → "if"
- "for the purpose of" → "for"
- "in light of" → "given"

**Redundant pairs.** Two words used together where one is sufficient:
- "each and every" → "every"
- "first and foremost" → "first"
- "any and all" → "all"
- "basic and fundamental" → "fundamental"
- "final outcome" → "outcome"
- "future plans" → "plans"
- "advance warning" → "warning"

**The "that" filler.** The word "that" is often removable when used as a relative pronoun or conjunction. Test each "that" by removing it and checking if the sentence still parses:
- "I said that I would help" → "I said I would help"
- "The thing that matters" → "The thing matters" (in this case, "that" is required; keep)

Apply the removal test to every occurrence of "that."

## Structural Patterns That Invite Compression

**Nominalization.** Noun forms of verbs. These typically inflate sentence length:
- "made the decision to" → "decided to"
- "conducted an investigation of" → "investigated"
- "carried out an analysis" → "analyzed"
- "reached an agreement" → "agreed"
- "made a recommendation" → "recommended"

**Passive voice with "by" phrase.** Passive constructions typically add words compared to active alternatives. Detect and rewrite:
- "The decision was made by the team" → "The team decided"
- "Mistakes were made by Claude" → "Claude made mistakes"

**Expletive constructions.** Sentences starting with "There is," "There are," "It is" followed by a relative clause. These typically hide the real subject:
- "There are three reasons why this works" → "This works for three reasons"
- "It is important that we act" → "We must act"

## The Test Applied to Longer Sentences

Sentences over 25 words require a second pass. After compression, check if the sentence still exceeds 25 words. If yes, one of two conditions should be true:

**Condition 1:** The sentence is doing multiple propositional jobs. Split it into two sentences at a natural clause boundary.

**Condition 2:** The sentence is a deliberate long-form build (a rare exception). This should occur no more than once per paragraph and only when the length itself serves the argument — typically a sentence that accumulates detail toward a terminal point.

If neither condition holds, the sentence is still over-compressed. Continue removing words.

## The Fix

Apply the removal test in priority order:

1. Remove all hedges unless removing them changes the propositional content
2. Remove all intensifier filler
3. Remove all throat-clearing openers
4. Replace all redundant connectives with their short forms
5. Collapse all redundant pairs
6. Test every "that"
7. Denominalize all nominalizations
8. Rewrite all passives where the actor is known
9. Rewrite all expletive constructions

After all nine categories processed, count the sentence words. If over 25, split or continue compressing.

## The Target

Zinsser's observation: most first drafts can be cut by 50 percent. This is the target magnitude of compression across the draft as a whole. Individual sentences may compress less; others may compress more. Aim for the draft to shrink by 30-50 percent when compression is applied aggressively to a bloated source.
