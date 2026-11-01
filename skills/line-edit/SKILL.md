---
name: line-edit
description: Tighten a draft the user supplies — cut needless words, convert passive to active, replace weak verbs and vague phrases — and return the edited text with a short list of changes. Use when the user asks to edit, tighten, polish, clean up, or sharpen prose they wrote. Not for writing new text, reporting problems without fixing them, or hitting a stated word count.
license: Complete terms in LICENSE.txt
---

# Line Edit

The user wrote it. You make it clearer and shorter without making it yours. A line edit changes words and sentences; it leaves the argument, the order, and the voice alone.

## Procedure

1. Read the whole draft once before changing anything. Note the register (formal, casual, technical) and keep it.
2. Edit sentence by sentence, applying the rules below.
3. Return the full edited text first, in the same format the user gave you.
4. Below it, list the changes that matter under **Changes**: five to ten lines, each naming the pattern and one example from the draft. Skip one-word swaps unless they recur.
5. If a passage is unclear enough that you cannot edit it without guessing the meaning, leave it as written and flag it under **Questions**.

## Rules

- Omit needless words. Cut "in order to", "the fact that", "it is important to note", "there is/are", "really", "very", "actually", and every phrase that restates what the sentence already says.
- Prefer the active voice. Convert the passive when the actor is known and matters.
- Replace weak verb-plus-noun pairs with the verb: "make a decision" → "decide", "conduct an analysis" → "analyse", "provide assistance" → "help".
- Replace vague words with specific ones where the draft supplies the specifics. Do not invent facts to be specific with.
- Put statements in positive form.
- Keep related words together; move misplaced modifiers.
- Make lists and paired clauses parallel.
- Break a sentence that carries more than one idea. Join two short sentences only when they share one idea.
- Keep one topic per paragraph. Merge or split paragraphs only when a paragraph plainly breaks this rule.

## Do not

- Change the meaning, the claims, or the order of points.
- Add content, examples, or transitions the user did not write.
- Change terminology the user uses deliberately (product names, legal terms, field jargon the audience expects).
- Americanise or Anglicise spelling. Keep the draft's variety.
- Rewrite quotations or cited text.
- Change code, data, URLs, or anything inside code fences.

## Output

```
[Edited text, complete, same format as the input]

**Changes**
- Passive to active: "the report was reviewed by the board" → "the board reviewed the report" (4 places)
- Cut "in order to" (6 places)
- ...

**Questions** (only if needed)
- Paragraph 3, "the second option": the first and second options are not named earlier. Which is meant?
```

If the user asks for a diff or a marked-up version, use ~~strikethrough~~ for cuts and **bold** for insertions instead of a clean copy.
