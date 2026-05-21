<div align="center">

```
╔═══════════════════════════════════════════════════════════════╗
║                                                               ║
║        ⚔  📈  🔬  🎨  ⚙  🧘  ❤                            ║
║                                                               ║
║              C L A U D E   C O U N C I L                     ║
║                                                               ║
║     7 expert AI personas debate your decisions.               ║
║     They disagree. They give you a verdict.                   ║
║                                                               ║
╚═══════════════════════════════════════════════════════════════╝
```

[![GitHub Stars](https://img.shields.io/github/stars/itshussainsprojects/Claude-Council-Skill?style=for-the-badge&color=FFD700&labelColor=1a1a2e)](https://github.com/itshussainsprojects/Claude-Council-Skill/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge&labelColor=1a1a2e)](LICENSE)
[![Free to Use](https://img.shields.io/badge/Free-100%25-brightgreen?style=for-the-badge&labelColor=1a1a2e)](https://github.com/itshussainsprojects/Claude-Council-Skill)
[![Claude Skill](https://img.shields.io/badge/Claude-Skill-orange?style=for-the-badge&labelColor=1a1a2e)](https://claude.ai)

**Stop getting "it depends" from AI. Get a verdict.**

[Install in 2 minutes](#installation) · [See Examples](#see-it-in-action) · [Add a Persona](#contributing)

</div>

---

## The Problem with AI Advice

Every AI gives you the same thing:

```
✅ On one hand...
✅ On the other hand...
✅ It really depends on your situation...
✅ Here are some things to consider...
```

**Nobody takes a position. Nobody disagrees. Nobody tells you the uncomfortable truth.**

Claude Council fixes this.

---

## How it works

```
You describe a decision, idea, or problem
              │
              ▼
┌─────────────────────────────────────────────────────┐
│                  THE COUNCIL                        │
│                                                     │
│  ⚔ Adversary ──── finds the fatal flaw             │
│  📈 Strategist ─── market, ROI, timing              │
│  🔬 Scientist ──── base rates, evidence             │
│  🎨 Visionary ──── reframes the problem             │
│  ⚙  Engineer ───── what breaks at scale             │
│  🧘 Philosopher ── first principles, 10-yr view     │
│  ❤  Humanist ───── the people, the psychology       │
│                                                     │
│  They debate each other. They disagree.             │
└─────────────────────────────────────────────────────┘
              │
              ▼
┌─────────────────────────────────────────────────────┐
│                  THE VERDICT                        │
│                                                     │
│  POSITION:    Clear stance. No hedging.             │
│  CONFIDENCE:  74% (and why)                         │
│  RISKS:       3 things that could kill this         │
│  NEXT STEPS:  5 actions for tomorrow                │
│  DISSENT:     The strongest counterargument         │
└─────────────────────────────────────────────────────┘
```

---

## The 7 Personas

```
┌──────────────────┬──────────────────────────────────────────────────┐
│  ⚔  ADVERSARY    │ Finds what everyone else is afraid to say.        │
│                  │ "That's not a plan. That's a hope."               │
├──────────────────┼──────────────────────────────────────────────────┤
│  📈 STRATEGIST   │ Market size, moats, timing, competitive dynamics. │
│                  │ Thinks in years, not weeks.                        │
├──────────────────┼──────────────────────────────────────────────────┤
│  🔬 SCIENTIST    │ Base rates, evidence, what the data says.         │
│                  │ "The reference class for this decision shows..."   │
├──────────────────┼──────────────────────────────────────────────────┤
│  🎨 VISIONARY    │ Questions the question. Finds the back door.      │
│                  │ "You're playing the wrong game entirely."         │
├──────────────────┼──────────────────────────────────────────────────┤
│  ⚙  ENGINEER     │ Feasibility, systems, edge cases, failure modes.  │
│                  │ "This breaks at 10x. Here's exactly how."         │
├──────────────────┼──────────────────────────────────────────────────┤
│  🧘 PHILOSOPHER  │ First principles, values, 10-year consequences.   │
│                  │ "What are you actually optimizing for?"           │
├──────────────────┼──────────────────────────────────────────────────┤
│  ❤  HUMANIST     │ The people. The psychology. The real cost.        │
│                  │ "Who else lives with this decision?"              │
└──────────────────┴──────────────────────────────────────────────────┘
```

Each persona has a documented **voice**, **bias**, **blind spot**, and **debate behavior** — they aren't just labels. They genuinely disagree.

---

## See it in action

<details>
<summary><strong>💼 "Should I quit my job to go full-time on my SaaS?" (click to expand)</strong></summary>

```
═══════════════════════════════════════════════════════════════════
                         THE COUNCIL
     "Should I quit my job to go full-time on my SaaS?"
═══════════════════════════════════════════════════════════════════

⚔ THE ADVERSARY
Three months of building before talking to customers is exactly
backwards. You've invested enough time to feel attached to this idea,
but you still don't have one confirmed paying customer. Quitting now
doesn't solve that — it just adds financial pressure to a validation
problem. Show me 5 people who said "I would pay $X for this right now."
Without that, nothing else in this conversation matters.

──────────────────────────────────────────────────────────────────

📈 THE STRATEGIST
The market gap is real — freelance finance tools is $4B with 30% YoY
growth. But expense reporting might be the feature, not the product.
The strategic question isn't whether the market exists — it's whether
this is the right wedge. I want to give the context the Adversary skipped.

──────────────────────────────────────────────────────────────────

🔬 THE SCIENTIST
For B2C SaaS targeting freelancers, median time to $1K MRR is 14 months
from full-time start. For solo founders with no prior startup experience,
roughly 22% reach $5K MRR within 24 months. What's your Day-30 retention?
That's the only number that would update my probability estimate upward.

──────────────────────────────────────────────────────────────────

🎨 THE VISIONARY
Wrong question. Don't debate quit vs stay. What if this starts as a
concierge service? Charge $200/month, do the work manually, learn what
actually matters before you automate it. Build customers while employed.
Quit only when the decision is obvious — not courageous.

──────────────────────────────────────────────────────────────────

⚙ THE ENGINEER
The Visionary's approach is sound — but design the manual service like
it's a software spec from day one. Three months of solo development means
architectural decisions that made sense in week 2 will need undoing in
week 20. Freeze features. Instrument what you have. Find the one workflow
users actually need before building anything else.

──────────────────────────────────────────────────────────────────

🧘 THE PHILOSOPHER
What does this mean to you beyond the outcome? Because if you're
optimizing for "successful business" — the others are giving you the
right advice. But if this is about autonomy, about building something
that's yours — you're making a different decision entirely. Get clear
on that first. Everything else follows.

──────────────────────────────────────────────────────────────────

❤ THE HUMANIST
You've been building nights and weekends for 3 months. What has that
cost? The people around you have been watching. Have you had the honest
conversation with your partner about what month 12 looks like when
growth is slower than expected and financial pressure is real?
That conversation matters more than anything else here.

═══════════════════════════════════════════════════════════════════
                         THE VERDICT
═══════════════════════════════════════════════════════════════════

POSITION: Do not quit yet. Run a 60-day concierge test while employed.
          Get 5 paying customers → then quit immediately.

CONFIDENCE: 74% — Strong market signals and founder conviction; drops
            to 50% if the partner conversation reveals real incompatibility.

CRITICAL RISKS:
  1. Validation Paralysis    — 60 days becomes an excuse to delay forever
  2. Undercapitalized Runway — quitting without 12 months expenses saved
  3. Feature Trap            — 3 months building = attached to wrong product

NEXT STEPS:
  1. Do 10 customer discovery interviews THIS week (not pitch — listen)
  2. Offer 3 freelancers a free 30-day manual concierge service
  3. Charge them after 30 days — even $50/month counts
  4. Have the "what does failure look like?" talk with your partner
  5. Set a hard decision date: 60 days from today, quit or pivot

MINORITY REPORT: ⚔ THE ADVERSARY
"The verdict is reasonable — but the test only works if you charge.
Free users tell you nothing. One paying customer beats 100 signups."
═══════════════════════════════════════════════════════════════════
```
</details>

<details>
<summary><strong>💰 "$160k stable job vs $130k + 0.4% equity at a Series B startup"</strong></summary>

```
POSITION: Don't take it as presented. Negotiate equity to 0.6-0.8%
          or salary within $10k first. Their response is data.

CONFIDENCE: 68%

CRITICAL RISKS:
  1. Equity Dilution Reality — 0.4% at Series B = ~0.27% at exit
  2. Staff Title Trap        — clarify if it's architecture or just IC work
  3. Financial Stress        — $30k cut creates monthly anxiety that distorts decisions

MINORITY REPORT: 🎨 THE VISIONARY
"7 years of stability is a long time. Sometimes the right move
is to bet on yourself and stop modeling the median."
```

[See full output →](examples/career-change.md)
</details>

<details>
<summary><strong>⚙️ "Should our 4-person startup refactor monolith to microservices?"</strong></summary>

```
POSITION: Do not refactor. Run a 1-week diagnosis sprint to find
          the actual pain points. Then targeted 2-3 week cleanup only.

CONFIDENCE: 88%

CRITICAL RISKS:
  1. Misdiagnosis Debt    — solving wrong problem loses 3-4 months
  2. Morale Delay         — "not yet" without a cleanup plan demotivates engineers
  3. Premature Extraction — "just one service" always becomes three

MINORITY REPORT: ⚔ THE ADVERSARY
"Cleanup only works if someone owns it and enforces conventions.
Without that authority, the codebase is back to this state in 3 months."
```

[See full output →](examples/technical-architecture.md)
</details>

---

## Installation

```
2 minutes. No account needed beyond Claude.
```

**Step 1** — Clone the repo
```bash
git clone https://github.com/itshussainsprojects/Claude-Council-Skill.git
```

**Step 2** — Open Claude.ai → Settings → Skills → Add Skill

**Step 3** — Upload the `council/` folder

**Step 4** — Start talking. The Council triggers automatically.

> **Trigger phrases:** "Should I...", "Is this a good idea...", "Help me decide...", "Stress-test this:", "Convene the Council"

---

## What makes it different from just prompting ChatGPT?

```
┌───────────────────────┬──────────────────────┬──────────────────────┐
│                       │  Short ChatGPT Prompt │   Claude Council     │
├───────────────────────┼──────────────────────┼──────────────────────┤
│ Consistent structure  │         ✗            │         ✓            │
│ Documented biases     │         ✗            │         ✓            │
│ Real inter-persona    │         ✗            │         ✓            │
│   debate              │                      │                      │
│ Calibrated confidence │         ✗            │         ✓            │
│ Minority report       │         ✗            │         ✓            │
│ Permanent (no         │         ✗            │         ✓            │
│   re-pasting)         │                      │                      │
│ Open source /         │         ✗            │         ✓            │
│   customizable        │                      │                      │
└───────────────────────┴──────────────────────┴──────────────────────┘
```

You *could* write a 2000-word prompt to replicate this. This is that prompt — already written, tested, and free.

---

## Works best for

```
 💼 Business decisions      🏗️  Technical architecture
 💰 Job offers & salary     🎨  Creative project strategy  
 🚀 Startup ideas           📚  Educational choices
 🔀 Career pivots           ❓  Any "should I" with real stakes
```

---

## Repo structure

```
claude-council-skill/
│
├── council/                    ← Install this folder into Claude
│   ├── SKILL.md                ← Core skill logic & trigger rules
│   ├── personas/
│   │   ├── adversary.md        ← Voice, bias, blind spot, debate style
│   │   ├── strategist.md
│   │   ├── scientist.md
│   │   ├── visionary.md
│   │   ├── engineer.md
│   │   ├── philosopher.md
│   │   └── humanist.md
│   └── templates/
│       ├── debate-format.md    ← Exact banner & structure rules
│       └── verdict-format.md   ← Verdict block specification
│
├── examples/                   ← 3 full real-world outputs
│   ├── startup-decision.md
│   ├── career-change.md
│   └── technical-architecture.md
│
├── README.md
├── INSTALL.md                  ← 3 installation methods + troubleshooting
├── CONTRIBUTING.md             ← How to add new personas
└── LICENSE                     ← MIT
```

---

## Contributing

The most wanted contributions:

- **New personas** — Lawyer, Therapist, Historian, UX Researcher, Financial Planner
- **New examples** — relationship decisions, health choices, investment moves
- **Better triggers** — edge cases where the Council should or shouldn't fire

See [CONTRIBUTING.md](CONTRIBUTING.md) for the persona template and quality bar.

---

## Community

> *"The Adversary said something I had been avoiding thinking about for 6 months."*

> *"74% confidence with a specific reason. First time AI gave me something I could actually act on."*

> *"The Visionary reframe completely changed how I was thinking about my startup."*

---

<div align="center">

**If the Council helped you make a better decision — star the repo.**

It helps other people find it.

[![Star this repo](https://img.shields.io/github/stars/itshussainsprojects/Claude-Council-Skill?style=for-the-badge&color=FFD700&labelColor=1a1a2e&label=⭐%20Star%20this%20repo)](https://github.com/itshussainsprojects/Claude-Council-Skill/stargazers)

*The Council is not responsible for decisions made after consulting it.*
*The Council is responsible for making sure you've thought about them properly.*

</div>

---

## 🌐 Live Demo Site

**Try the interactive demo:** [itshussainsprojects.github.io/Claude-Council-Skill](https://itshussainsprojects.github.io/Claude-Council-Skill)

See 4 famous decisions debated live — with tabs, persona cards, and full verdicts.

---

## 📜 Famous Decisions — The Council Weighs In

What would the Council have said about the biggest decisions in business history?

| Decision | Verdict | Confidence |
|----------|---------|-----------|
| [⚡ Steve Jobs return to Apple (1997)](examples/famous-decisions/jobs-return-to-apple.md) | Take it — founding frame, not turnaround | 79% |
| [🐦 Elon Musk buy Twitter for $44B](examples/famous-decisions/musk-buy-twitter.md) | Don't — debt structure makes it near-impossible | 61% |
| [📘 Zuckerberg drop out of Harvard](examples/famous-decisions/zuckerberg-harvard-dropout.md) | Drop out — winner-take-all, speed is everything | 82% |
| [📺 Netflix pivot to streaming (2007)](examples/famous-decisions/netflix-dvd-to-streaming.md) | Build streaming, keep DVDs as runway | 76% |

> *The Adversary on Jobs returning to Apple:* "You're not being brought back because they believe in you. You're being brought back because everyone else failed."

> *The Visionary on Zuckerberg:* "You're asking whether to finish your homework before discovering fire."

> *The Philosopher on Musk/Twitter:* "One person owning the infrastructure of global public discourse has no historical precedent in a private transaction."

What famous decision should the Council analyze next? [Open an issue →](https://github.com/itshussainsprojects/Claude-Council-Skill/issues)

---

*Developed by Hussain Ali*
