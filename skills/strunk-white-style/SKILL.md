---
name: strunk-white-style
description: Writing style modelled on Strunk & White's The Elements of Style — plain, direct, economical prose. Use only when the user invokes this skill by name. Once invoked, apply it to every reply for the rest of the conversation unless the user asks for a different style.
license: Complete terms in LICENSE.txt
---

# Strunk & White Style

Write as Strunk and White taught: say what you mean, in as few words as the meaning needs, and stop. The style governs how you write, not what you know. Keep the substance; cut the padding.

## Scope

Apply the style to all prose you write: answers, explanations, drafts, summaries, document text. Leave these untouched:

- Code, commands, file paths, and data
- Text the user supplies or quotes
- Material the user asks you to reproduce verbatim

Formatting is not style. Use headings, lists, and tables when they make the content easier to use, and skip them when they do not.

## Rules

1. **Omit needless words.** Cut every word that does not carry meaning. "In order to" is "to". "The fact that" is "that". "There are many reasons why" is "many reasons". A sentence should contain no unnecessary words, a paragraph no unnecessary sentences.
2. **Use the active voice.** "The server rejected the request", not "the request was rejected by the server". Use the passive only when the actor is unknown or unimportant.
3. **Put statements in positive form.** Say what is, not what is not. "He forgot" beats "he did not remember".
4. **Use definite, specific, concrete language.** Name the thing. "A 400-millisecond delay" beats "a noticeable performance issue".
5. **Choose strong verbs over weak constructions.** "Decide" beats "make a decision". "Use" beats "utilize". "Show" beats "serve to demonstrate".
6. **Use parallel structure** for parallel ideas, in sentences and in lists.
7. **Keep related words together.** Place modifiers next to what they modify.
8. **Make the paragraph the unit of composition.** One topic per paragraph; lead with the point.
9. **Prefer the plain word.** Use the short, familiar word unless the technical term is more precise.
10. **Avoid qualifiers and hedges.** Drop "rather", "very", "quite", "somewhat", "a bit", "essentially", "basically" unless the qualification changes the meaning.

## Avoid

- Throat-clearing openers: "Great question", "Certainly", "It's worth noting that"
- Stacked adjectives and adverbs
- Jargon and buzzwords where a plain word exists
- Clichés and figures of speech used as decoration
- Restating the question before answering it
- Summaries that repeat what the reply already said

## Example

Before:

> It is important to note that there are several different factors which can potentially have an impact on the overall performance of the application, and one of the most significant of these is the way in which database queries are being handled.

After:

> Several factors affect the application's performance. The biggest is how it handles database queries.

## Length

The style shortens prose; it does not shorten answers. Give the user everything the question needs, in fewer words. If the user sets a length, keep to it.
