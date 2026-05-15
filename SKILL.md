# Claude Council

**A Claude skill that convenes 7 expert AI personas to debate any decision, idea, or problem — then synthesizes a verdict.**

> *"I had 7 AIs argue about whether I should quit my job. It was the most useful thing I've done for my career all year."*

---

## What it does

You present any decision, idea, or problem. The Council convenes.

Seven distinct expert personas — each with their own worldview, vocabulary, and biases — analyze your situation, disagree with each other, and converge on a structured verdict:

| Persona | Their angle |
|---------|-------------|
| ⚔ **The Adversary** | Finds the fatal flaw. Blunt. Uncomfortable. Necessary. |
| 📈 **The Strategist** | Market dynamics, competitive positioning, ROI |
| 🔬 **The Scientist** | Base rates, evidence, what the data actually says |
| 🎨 **The Visionary** | Reframes the problem. Questions the question. |
| ⚙ **The Engineer** | Feasibility, systems, what breaks at scale |
| 🧘 **The Philosopher** | First principles, values, the 10-year view |
| ❤ **The Humanist** | The people involved. The psychological reality. |

Every output includes:
- A structured **debate** with 7 distinct voices
- A clear **verdict** with a specific confidence percentage
- The **3 critical risks** that could kill the plan
- **5 concrete next steps** you can act on tomorrow
- A **minority report** from the strongest dissenter

---

## See it in action

<details>
<summary><strong>Example 1: "Should I quit my job to go full-time on my SaaS?"</strong></summary>

```
═══════════════════════════════════════════════════════════════════
                         THE COUNCIL
     "Should I quit my job to go full-time on my SaaS?"
═══════════════════════════════════════════════════════════════════

⚔ THE ADVERSARY
Three months of nights-and-weekends building before talking to customers is exactly
backwards. You've invested enough time to feel attached to this idea, but you still
don't have one confirmed paying customer. Quitting your job now doesn't solve that
problem — it just adds financial pressure to a validation problem. Prove me wrong
by showing me 5 people who said "I would pay $X for this right now." Without that,
nothing else in this conversation matters.

──────────────────────────────────────────────────────────────────

📈 THE STRATEGIST
The Adversary is asking the right question, but I want to give the market context
they skipped. Freelance finance tools is a $4B market with 30% YoY growth, and the
top players are built around monthly subscriptions that freelancers actively resent
because their income is lumpy. There's a real gap. The strategic question isn't
whether the market exists — it's whether expense reporting is the right wedge, or
whether it's the feature, not the product.

──────────────────────────────────────────────────────────────────

🔬 THE SCIENTIST
For B2C SaaS targeting freelancers, median time to $1K MRR is 14 months from
full-time start. For a solo founder with no prior startup experience, roughly 22%
reach $5K MRR within 24 months. The more important question: what's the Day-30
retention on your beta users? The Adversary is right that customer validation is the
critical missing input — it's the only data point that would meaningfully update
my probability estimate upward.

──────────────────────────────────────────────────────────────────

🎨 THE VISIONARY
Everyone's debating whether to quit now or later. Wrong question. What if you run
this as a concierge service first? Charge $200/month, onboard 10 clients manually,
and learn what actually matters before you automate it. You don't need to quit to
do that. Build the customer base while employed, and quit only when side revenue
crosses a threshold that makes the choice obvious, not courageous.

... [full example in examples/startup-decision.md]

═══════════════════════════════════════════════════════════════════
                         THE VERDICT
═══════════════════════════════════════════════════════════════════

POSITION: Do not quit yet. Spend 60 days running the concierge approach while
employed — if you reach 10 paying customers at any price, quit immediately.

CONFIDENCE: 74% — What would move this to 85%: 3 customers who paid without
being coaxed. What would move it to 50%: a partner conversation that surfaces
real financial incompatibility with the risk.

CRITICAL RISKS
  1. Validation Paralysis: The 60-day window becomes an excuse to delay indefinitely
  2. Undercapitalized Runway: Quitting without 12 months of personal expenses saved
  3. Feature Trap: 3 months of building means you're attached to what you've built

NEXT STEPS
  1. Do 10 customer discovery interviews with freelancers this week
  2. Offer 3 freelancers a free 30-day manual concierge service
  3. After 30 days, charge the ones who found it valuable — even $50/month
  4. Have the "what does failure look like?" conversation with your partner
  5. Set a hard decision date 60 days from today

MINORITY REPORT: ⚔ THE ADVERSARY
"The verdict is reasonable, but the 60-day test only works if you charge people.
Free users tell you nothing."
═══════════════════════════════════════════════════════════════════
```
</details>

<details>
<summary><strong>Example 2: "$160k stable job vs $130k + 0.4% equity at Series B startup"</strong></summary>

See [`examples/career-change.md`](examples/career-change.md) for the full Council output.

**Verdict:** Don't take it as presented — negotiate equity to 0.6-0.8% or salary within $10k first. If they won't move on either, the offer is telling you something about how they value you.

**Confidence:** 68%
</details>

<details>
<summary><strong>Example 3: "Should our 4-person startup refactor the monolith to microservices?"</strong></summary>

See [`examples/technical-architecture.md`](examples/technical-architecture.md) for the full Council output.

**Verdict:** Do not refactor. Run a 1-week diagnosis sprint first, then a targeted 2-3 week cleanup of specific hotspots.

**Confidence:** 88%
</details>

---

## Installation

### Requirements
- A Claude account (any plan)
- The [Skills feature](https://claude.ai/settings) enabled in your Claude settings

### Option 1: Manual install (2 minutes)

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/itshussainsprojects/Claude-Council-Skill.git
   ```

2. **Open Claude.ai** → Settings → Skills → Add Skill

3. **Upload** the `council/` folder (or drag the `SKILL.md` file)

4. **You're done.** Ask Claude anything that sounds like a decision.

### Option 2: Copy the skill file

1. Open `council/SKILL.md`
2. Copy its contents
3. In Claude.ai → Settings → Skills → New Skill → Paste

---

## Usage

Just talk to Claude normally about any decision, idea, or problem. The Council triggers automatically on phrases like:
- *"Should I..."*
- *"Is this a good idea..."*
- *"Help me decide between..."*
- *"What do you think about my plan to..."*
- *"Stress-test this idea:"*
- *"Convene the Council"* (explicit trigger)

**The Council works best for:**
- 🏢 Business and startup decisions
- 💼 Career moves and job offers
- ⚙️ Technical architecture choices
- 🎨 Creative project strategy
- 💰 Financial decisions
- ❓ Any "should I" with genuine tradeoffs

---

## What makes this different

Most AI responses to decisions give you a balanced summary of considerations. The Council gives you:

1. **Genuine disagreement** — personas actually push back on each other, not just list pros and cons
2. **A clear verdict** — no "it depends" without specifics; the Council takes a position
3. **A confidence score** — calibrated uncertainty, not false precision or useless hedging
4. **The minority report** — the strongest dissent from the verdict is always represented
5. **Immediate next steps** — 5 specific actions, in order, that you can start tomorrow

---

## Customization

### Change which personas speak

In your prompt, you can specify: *"Convene the Council, but skip the Philosopher — I need practical advice, not existential questions."*

### Add context for better output

The more context you give, the sharper the output:
- **Bad:** "Should I move to a new city?"
- **Good:** "I'm 29, in product management, offered a job in Austin that pays 20% more than my current NYC role. My partner works remotely. Should I move?"

### Add a custom persona

Fork the repo and add a new file to `council/personas/`. Follow the template structure in any existing persona file. Submit a PR — see [CONTRIBUTING.md](CONTRIBUTING.md).

---

## File structure

```
claude-council-skill/
├── README.md
├── INSTALL.md            ← Detailed installation guide
├── CONTRIBUTING.md       ← How to add personas and examples
├── LICENSE               ← MIT
├── council/
│   ├── SKILL.md          ← The main skill (Claude reads this)
│   ├── personas/
│   │   ├── adversary.md  ← Voice, bias, debate behavior for each persona
│   │   ├── strategist.md
│   │   ├── scientist.md
│   │   ├── visionary.md
│   │   ├── engineer.md
│   │   ├── philosopher.md
│   │   └── humanist.md
│   └── templates/
│       ├── debate-format.md   ← Exact output structure
│       └── verdict-format.md  ← Verdict block structure
└── examples/
    ├── startup-decision.md       ← Full example outputs
    ├── career-change.md
    └── technical-architecture.md
```

---

## Contributing

Pull requests welcome. The most wanted contributions:

- **New personas** — domain experts not currently on the Council (Lawyer, Therapist, Historian, UX Researcher)
- **New examples** — real Council outputs for new decision types
- **Edge case handling** — how should the Council handle simple factual questions? Personal grief? Ethical dilemmas with no right answer?

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

MIT — use it, fork it, build on it.

---

## Star history

If this saved you from a bad decision (or made a good one clearer), star the repo. It helps other people find it.

---

*Built by Hussain Ali. The Council is not responsible for the decisions you make after consulting it. The Council is responsible for making sure you've thought about them properly.*
