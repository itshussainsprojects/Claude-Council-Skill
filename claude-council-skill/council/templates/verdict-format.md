# Council Verdict Format Template

The verdict follows immediately after the debate section, separated by a blank line and then the verdict banner. It synthesizes the debate into a clear, actionable position.

---

## The Verdict Structure

```
═══════════════════════════════════════════════════════════════════
                         THE VERDICT
═══════════════════════════════════════════════════════════════════

POSITION: [One clear sentence. No hedging. Takes a side.]

CONFIDENCE: [X]% — [One sentence explaining what drives that number
             and what would move it up or down.]

──────────────────────────────────────────────────────────────────

CRITICAL RISKS  (exactly 3)

  1. [Risk name in bold]: [One concrete sentence. Specific, not generic.]
  2. [Risk name in bold]: [One concrete sentence. Specific, not generic.]
  3. [Risk name in bold]: [One concrete sentence. Specific, not generic.]

──────────────────────────────────────────────────────────────────

NEXT STEPS  (exactly 5, in order of priority)

  1. [Action verb + specific action]. [Optional: why this is first.]
  2. [Action verb + specific action].
  3. [Action verb + specific action].
  4. [Action verb + specific action].
  5. [Action verb + specific action].

──────────────────────────────────────────────────────────────────

MINORITY REPORT: [THE PERSONA WHO WOULD DISAGREE MOST]
"[1-2 sentences in that persona's voice, summarizing the strongest
  dissent from the majority position. Starts with their emoji.]"

═══════════════════════════════════════════════════════════════════
```

---

## Verdict Rules

### POSITION
- One sentence. Active voice. Clear stance.
- NOT: "It depends on several factors, but generally..."
- NOT: "There are valid points on both sides..."
- YES: "Launch the side project now, but do not quit your job until you have 3 paying customers."
- YES: "Don't take the job. The compensation is good but the equity is structured against you."
- YES: "Build the microservices architecture, but start monolithic and extract only when you hit the specific scaling limit."

### CONFIDENCE
- A specific percentage between 30% and 90%. (Below 30% = not enough info to proceed. Above 90% = overconfident given typical decision complexity.)
- The rationale must name what drives the confidence UP or DOWN, not just say "there's uncertainty."
- Example: `72% — The market timing and product-market fit signals are strong; what would move this to 85% is evidence of 5 paying customers in the target segment.`

### CRITICAL RISKS
- Exactly 3. Not 2, not 4.
- Each risk has a NAME (2-4 words) and a DESCRIPTION (one specific sentence).
- These are the risks that could actually kill the plan — not minor concerns, not low-probability tail risks.
- The names should be memorable: "Runway Compression Risk", "Distribution Moat Problem", "Founder Identity Collapse"
- Example: `**Runway Compression Risk**: At current burn, a 3-month delay in first customer acquisition depletes cash before any revenue comes in.`

### NEXT STEPS
- Exactly 5. In order of priority (do this first, then this, etc.)
- Each step starts with an action verb: "Run", "Talk to", "Build", "Decide", "Validate", "Test", "Map out", "Define"
- Specific enough to do tomorrow — not "think about your strategy" but "Write a 1-page spec for the MVP with the 3 features you'd cut if you had to ship in 4 weeks"
- The 5 steps should form a coherent sequence, not a random list

### MINORITY REPORT
- This is the one persona whose dissent from the verdict is strongest and most credible
- Write it in their voice, with their signature phrasing
- It must present a genuine counterargument, not just say they disagree
- It makes the verdict feel more earned — the Council considered the dissent and still landed here

---

## Verdict Quality Checklist

Before finalizing:
- [ ] Does the POSITION take a clear side? (If it reads like a non-answer, rewrite it.)
- [ ] Is the CONFIDENCE percentage calibrated? (Does 72% feel right given the uncertainty in the debate?)
- [ ] Are the 3 CRITICAL RISKS the actual killers, or are they generic concerns dressed up as specific ones?
- [ ] Are the 5 NEXT STEPS genuinely actionable tomorrow, or are they strategic platitudes?
- [ ] Does the MINORITY REPORT present a genuinely uncomfortable counterpoint?
- [ ] Would a reader who skips the debate and reads only the verdict still understand what to do?
