---
name: prose-check
description: Report clarity problems in a draft without rewriting it — passive voice, needless phrases, hedges, overlong sentences, weak verbs, buried topic sentences — with counts and quoted examples. Use when the user asks to check, review, audit, or critique the writing itself, or wants feedback while keeping their own voice. Not for editing the text; that is line-edit.
license: Complete terms in LICENSE.txt
---

# Prose Check

A report, not a rewrite. The user keeps the pen; you show them where the prose works against them. Quote the draft, count the pattern, and say what to do about it. Change nothing.

## Checks

Run every check. Report only the ones that fire.

1. **Needless phrases.** "in order to", "the fact that", "it is important to note that", "there is/are", "at this point in time", "due to the fact that", "in the event that", "has the ability to", "a number of". Count occurrences and quote up to three.
2. **Passive voice.** Count passive constructions. Quote up to three where the actor is known and the active form would be clearer. Do not flag a passive that is the right choice (the actor is unknown, or the object is the topic).
3. **Hedges and intensifiers.** "very", "really", "quite", "rather", "somewhat", "a bit", "basically", "essentially", "actually", "arguably", "it seems that", "I think". Count and quote up to three.
4. **Weak verb-plus-noun pairs.** "make a decision", "conduct a review", "provide support", "perform an analysis", "give consideration to". Quote each with the one-word verb it hides.
5. **Long sentences.** Flag sentences over 35 words. Quote the longest two with word counts.
6. **Sentence-length monotony.** If more than 70% of sentences fall within five words of each other, note it. Rhythm needs variety.
7. **Buried topic sentences.** For each paragraph, check whether the first sentence states the paragraph's point. Name the paragraphs where it does not.
8. **Vague nouns.** "things", "aspects", "factors", "issues", "areas", "elements" used where a concrete noun would fit. Quote up to three.
9. **Jargon and buzzwords.** "leverage", "utilise", "synergy", "impactful", "robust", "going forward", "circle back", "at the end of the day". Quote each.
10. **Clichés.** Stock phrases used as decoration. Quote up to three.
11. **Throat-clearing openers.** Paragraphs or emails that begin with a sentence that could be deleted without loss ("I hope this finds you well", "As you may know", "In today's world"). Quote them.
12. **Repetition.** A word or phrase used so often it draws attention to itself. Name it with the count.

## Output

Start with a two-line verdict: what the draft does well and the one pattern that costs it the most. Then the findings, most costly first. Each finding has the pattern name, a count, quoted examples, and a one-line remedy. End with a reading-level note: average sentence length in words and the share of sentences in passive voice.

```
**Verdict.** Clear structure and specific claims. The draft loses most to needless phrases — 14 in 600 words.

**1. Needless phrases (14)**
- "in order to" (5): "in order to reduce cost" → "to reduce cost"
- "the fact that" (3): "due to the fact that" → "because"
- ...
Remedy: delete or replace; none of these carries meaning.

**2. Passive voice (6 of 31 sentences)**
- ...

**Stats.** 31 sentences, average 19 words, longest 44. Passive: 19%.
```

## Do not

- Rewrite the draft or supply an edited copy. If the user wants that, point them to line-edit.
- Comment on the argument, accuracy, or structure beyond topic sentences. This is a prose check.
- Flag deliberate style in fiction, speeches, or quoted material. If the text is plainly literary, say so and check only what the user asks.
- Pad the report with checks that did not fire.
