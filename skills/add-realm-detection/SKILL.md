---
description: Centralized ADD realm detection patterns. Use to identify which realm (Assess/Decide/Do) a user is operating in based on language, behavior, and context.
---

# ADD Realm Detection

Centralized reference for detecting which ADD realm a user is currently in or needs to transition to.

## Detection Philosophy

- **Implicit detection** — Don't announce "I detect you're in Assess mode"
- **Pattern-based** — Look for clusters of signals, not single indicators
- **Context-aware** — Consider the broader conversation flow
- **Non-judgmental** — Detection informs response, not correction

## ASSESS Realm Detection

### High-Confidence Signals

**Language patterns:**
- "I'm thinking about..."
- "What are my options for..."
- "Help me understand..."
- "What if I..."
- "I'm not sure yet, but..."
- "Can you explain..."
- "What would it take to..."
- "I'm curious about..."

**Verb tense & modality:**
- Future/Conditional: "might", "could", "would if", "considering"
- Subjunctive: "if I were to...", "suppose I..."

**Commitment level:**
- Low: "maybe", "thinking about", "not sure", "possibly"

### Behavioral Indicators
- Asking for research or analysis
- Requesting multiple options or perspectives
- Processing new inputs (inbox, ideas, information)
- Reviewing or organizing existing items
- Brainstorming without narrowing

### Context Clues
- Early project phase
- New topic introduction
- "I just heard about..." or "I'm starting to think about..."
- Multiple competing ideas mentioned without preference

---

## DECIDE Realm Detection

### High-Confidence Signals

**Language patterns:**
- "Should I..."
- "I need to choose between..."
- "When should I..."
- "What's the priority..."
- "I want to commit to..."
- "Which one is better..."
- "Help me decide..."
- "I'm leaning toward..."

**Verb tense & modality:**
- Present/Committed: "I want to", "I'm choosing", "This matters"
- Comparative: "better", "more important", "rather"

**Commitment level:**
- Medium: "leaning toward", "drawn to", "starting to see"
- Rising: "I think I want...", "probably going to..."

### Behavioral Indicators
- Comparing specific options
- Asking for recommendations
- Weighing trade-offs explicitly
- Setting priorities or timeframes
- Narrowing from many to few

### Context Clues
- Sufficient information already gathered
- External pressure to choose
- "I've been thinking about this for a while..."
- Limited time or resources forcing decision

---

## DO Realm Detection

### High-Confidence Signals

**Language patterns:**
- "How do I actually..."
- "I need to complete..."
- "Walk me through the steps..."
- "I'm working on..."
- "What's the next step..."
- "Help me finish..."
- "I've decided to..." (past tense)
- "Let's get this done..."

**Verb tense & modality:**
- Active/Immediate: "I'm doing", "working on", "completing", "finished"
- Imperative: "Show me how", "Tell me the steps"

**Commitment level:**
- High/Execution: "let's do this", "next step", "implementing now"
- Past-tense decision: "I've committed to...", "I'm going with..."

### Behavioral Indicators
- Asking for step-by-step guidance
- Working on a specific committed task
- Seeking efficiency improvements
- Not questioning whether to do it
- Progress updates and completion acknowledgments

### Context Clues
- Decision clearly already made
- Deadline or timeframe mentioned
- Partial work already completed
- "I just need to..."

---

## Confidence Assessment

### High Confidence
Multiple signals from same realm, consistent context, clear pattern.
→ Respond fully aligned to detected realm.

### Medium Confidence
Mixed signals but predominant pattern clear.
→ Respond to predominant realm, stay flexible.

### Low Confidence
Conflicting signals, realm unclear.
→ Gently probe before committing to response style:
- "Are you still exploring options, or ready to decide?"
- "Have you committed to this approach, or weighing alternatives?"

---

## Transition Detection

### Assess → Decide Signals
- "I think I have enough information"
- "OK, so my options are basically..."
- "Now I need to figure out which one"
- Natural summarization of explored territory
- Shift from "what if" to "which one"

### Decide → Do Signals
- "OK, I've decided"
- "Let's do it"
- "I'm going with option X"
- Confident, past-tense language about the choice
- Shift from "which" to "how"

### Do → Assess Signals
- "Done!"
- "That's finished"
- "What else is there?"
- "What's next?" (after completion)
- Natural pause after execution

---

## Realm Confusion Detection

### Assess-Decide Mixing
**Pattern:** Endless research without narrowing
**Signal:** "I need just a bit more information before I can decide" (repeated)
**Response:** Acknowledge the pattern, offer to help transition

### Decide-Do Mixing
**Pattern:** Starting execution, then stopping to re-prioritize
**Signal:** "Wait, should I even be doing this?"
**Response:** Protect the decision, refocus on execution

### Assess-Do Mixing
**Pattern:** Diving into execution without clarity
**Signal:** "I'll figure it out as I go" (for complex tasks)
**Response:** Pause to clarify scope before continuing

### Do-Assess Mixing
**Pattern:** Opening research during implementation
**Signal:** "Let me look up one more thing..." (mid-task)
**Response:** Distinguish genuine need from avoidance

---

## Detection Principles

1. **Look for clusters** — Single words aren't definitive; patterns are
2. **Trust context** — Conversation history matters
3. **Stay flexible** — People shift realms mid-sentence sometimes
4. **Don't force** — If unclear, it's okay to gently ask
5. **Serve the user** — Detection enables better support, not categorization
