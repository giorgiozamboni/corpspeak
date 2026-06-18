# Anti-AI filter for corporate output

This is the step that separates "corporate written by a real manager" from "ChatGPT
imitating a manager". After loading the jargon, reread the text and fix the tells
below. The rules derive from the `humanizer` skill, but they are adapted: business
jargon (leverage, synergy, stakeholder, KPI) is wanted here and must NOT be removed.
You only remove the **structural** tells that make text sound generated, not the
lexical business vocabulary.

## Guiding principle

Real corporate is **dense but operational**: it talks about actions, ownership,
deadlines, numbers. AI-corporate is **dense but empty**: all inflated significance,
zero substance. Whenever a sentence sounds important but does not say what gets done,
who does it and when, rewrite it concretely.

## Tells to always eliminate

### 1. Em dashes (- and -) and double hyphens ( -- )
The single most reliable tell. Zero tolerance. Replace with a period (new sentence),
a comma (short aside), a colon (introduce an explanation) or parentheses. Scan the
final text for em/en dashes: if you find even one, you are not done.

Before: "The roadmap is ambitious - maybe too ambitious - but it moves the needle."
After: "The roadmap is ambitious, maybe too ambitious, but it moves the needle."

### 2. Mechanical rule of three
AI groups everything in threes to look comprehensive. A real executive does not.
Break forced triads.

Before: "We are betting on innovation, efficiency and growth."
After: "We are betting on operational efficiency, with growth as the downstream
goal."

### 3. Fake -ing / participial analyses
Clauses tacked on with gerunds/participles for false depth.

Before: "We optimize processes, enabling synergies and ensuring value."
After: "We optimize processes to cut delivery times by 15%."

### 4. Significance inflation (copula avoidance)
"Stands as a testament to", "serves as", "marks a pivotal moment", "underscores the
importance of". Operational corporate uses "is", "has", "does".

Before: "This project stands as a fundamental strategic pillar."
After: "This project is worth 2M in pipeline and kicks off in Q3."

### 5. Generic motivational conclusion
"The future is bright", "exciting times lie ahead", "a step toward excellence".
Instead, close with something concrete: a decision, a deadline, a number, a next
step with an owner.

Before: "Together we will build a successful future."
After: "Next step: Marco presents the business case by EOW."

### 6. Servile tone and chat artifacts
"Great question!", "Certainly!", "I hope this helps", "Let me know if...". These are
conversation residue, not business text. Cut them.

### 7. Signposting
"Let's dive in", "Here's what you need to know", "Without further ado", "Let's take
a step back". Do the thing, do not announce it.

### 8. Decorative emojis
No emojis on headings or bullets. If you need emphasis, get it from the words.

### 9. Bold-header + colon lists (wholesale) and mechanical bold
AI produces "- **Performance:** performance has improved...". Dissolve into prose or
into dry bullets, and use bold sparingly, not on half a sentence.

### 10. Curly quotes
Use straight quotes ("..."), not typographic ones.

### 11. False "from X to Y" ranges
"From strategy to execution, from team to market" when X and Y are not on a real
scale. Cut them or make them concrete.

### 12. Excessive hedging
"It could perhaps be argued that the policy might have some impact." Corporate is
assertive: "The policy raises margin by 3%."

## What NOT to touch (it is intended jargon, not a tell)

- Business vocabulary: leverage, synergy, stakeholder, KPI, deliverable, roadmap,
  value proposition, cross-functional, data-driven, scale, optimize, quick win,
  north star. This is the requested product.
- Hyphenated pairs in attributive position: "cross-functional team", "data-driven
  approach", "best-in-class solution". Fine when they precede the noun.
- Office itanglese in Italian (call, deck, bandwidth, mettere a terra): it is
  authentic, keep it.

The difference is always the same: jargon used **with intent and substance** stays;
**structural, empty** patterns go.
