# Contributing to Claude Council

Contributions are welcome and encouraged. This is a living skill — the personas, templates, and examples should improve over time based on how people actually use it.

---

## What we need most

### 1. New personas
The Council currently has 7 generalist experts. The most requested additions:

- **The Lawyer** — legal risk, contracts, liability, regulatory exposure
- **The Therapist** — deeper psychological analysis, attachment patterns, trauma-informed perspective
- **The Historian** — pattern recognition across history, "this has happened before and here's how it ended"
- **The UX Researcher** — user behavior, product usability, what people actually do vs what they say
- **The Parent** — long-term human development, generational thinking, relationship to dependents
- **The Financial Planner** — personal finance specifics, tax implications, retirement impact

### 2. New example outputs
Real, full Council outputs for decision types not yet covered:
- Relationship decisions
- Creative career choices (publishing a book, releasing an album)
- Health and medical decisions
- Educational choices (grad school, bootcamp, self-study)
- Investment decisions
- Hiring decisions (should I hire this person?)

### 3. Edge case handling
How should the Council handle:
- Decisions that are already made (post-hoc rationalization?)
- Ethical dilemmas with no good answer
- Questions that are actually just grief or loss dressed as decisions
- Decisions where all options are genuinely equal

---

## How to add a new persona

### File location
`council/personas/[name].md`

### Required sections

```markdown
# [Emoji] [Name]

## Identity
[2-3 sentences. Who is this person? What's their background?
What do they care about most?]

## Core Belief
**"[Their governing maxim — one sentence in quotes.]"**

[2-3 sentences expanding on the belief and where it comes from.]

## Voice and Vocabulary
- [How they talk. Pace, tone, register.]
- [What vocabulary they use or avoid.]
- [Their characteristic rhetorical moves.]
- [What makes them sound like themselves and not like the others.]

## Signature Phrases
- "[Phrase they use]"
- "[Another phrase]"
- "[And another]"
(Aim for 5-7 phrases that are genuinely distinctive)

## What They Look For
1. **[Category]** — [what they notice and why]
2. **[Category]** — [what they notice and why]
(4-6 items)

## Bias
[1-2 sentences. What do they systematically underweight or overweight?
Be honest — a persona with no bias is a useless persona.]

## Blind Spot
[1-2 sentences. What do they reliably miss? What type of situation
do they handle worst?]

## Debate Behavior
[Who they align with, who they push back on, and why.]

## Example Statement
*"[A 4-6 sentence example of this persona speaking in a real Council
   session. Should be recognizably theirs — you should be able to
   cover the name and know who's talking.]"*
```

### Quality bar for new personas

A persona passes the quality bar if:
- You can cover their name and still know who's talking after reading 2 sentences
- They disagree with at least 2 of the existing personas on something specific
- Their blind spot is real and somewhat uncomfortable (not just "they can be too [their main virtue]")
- Their example statement makes a specific claim, not a general one

---

## How to submit a new example

Examples live in `examples/[topic].md`. 

Use a real question (anonymized if needed) — not a contrived one. Fake questions produce sanitized outputs. The best examples come from actual decisions people were wrestling with.

Format: follow the structure in the existing examples exactly. The banner, dividers, and verdict structure must be preserved.

---

## Pull request checklist

- [ ] New persona file follows the full template structure
- [ ] Persona passes the quality bar (cover-name test, real blind spot, specific example)
- [ ] If adding to SKILL.md, the persona table is updated
- [ ] Examples use the correct banner and divider format
- [ ] No placeholder text anywhere

---

## Code of conduct

The Council is direct and sometimes uncomfortable — that's the point. Contributions should make the personas sharper, more distinct, and more useful, not softer or more agreeable. 

The one line: don't make the Adversary nicer. That's the most common mistake.
