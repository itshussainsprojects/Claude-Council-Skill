# Drop-in README sections for v2

Paste these into README.md. Suggested placement noted per block.

---

## Block 1 — place right after the badges (announce v2)

## 🆕 v2.0 — The Council Learned New Tricks

```
NEW  ⚡ Quick Council   — 3 personas, one screen, instant sanity check
NEW  🌊 Deep Council    — two debate rounds with rebuttals & concessions
NEW  🎯 Red Team Mode   — pure attack: ranked failure modes + survival conditions
NEW  🎙 Cross-Examine   — challenge any persona after the verdict, they answer in voice
NEW  🔄 Revote          — bring new information, watch the confidence move
NEW  ⚖📜🌱 Guest Seats  — summon the Lawyer, the Historian, or the Therapist
```

---

## Block 2 — place after "The 7 Personas" section

## Modes

| Say this | You get |
|----------|---------|
| *(just ask your question)* | **Full Council** — all 7 personas, complete verdict |
| "Quick council: ..." | **Quick Council** — 3 best-fit personas, mini-verdict, one screen |
| "Deep council: ..." | **Deep Council** — opening statements + a rebuttal round; the verdict cites what moved it |
| "Red team this: ..." | **Red Team** — no balance, just ranked failure modes and the 3 conditions your plan must survive |

## Talk back to the Council

The session doesn't end at the verdict:

| Say this | What happens |
|----------|--------------|
| "Cross-examine the Adversary" | They defend their position against your challenge — and concede when you're right |
| "Revote with new info: I got 3 paying customers" | Updated verdict, old vs. new confidence, who flipped and why |
| "Summon the Lawyer" | ⚖ reviews the debate for contract/equity/liability angles |
| "Summon the Historian" | 📜 tells you who tried this before and how it ended |
| "Summon the Therapist" | 🌱 asks whether the stated question is the real question |
| "What would change your mind?" | One falsifiable condition per persona |
| "Steelman the other side" | The strongest case for the position the Council voted against |

## Guest Seats

Three specialists wait outside the chamber and enter when summoned — or automatically when the topic demands it:

| Guest | Enters when... |
|-------|----------------|
| ⚖ **The Lawyer** | equity, contracts, IP, employment terms. *"Handshakes are memories. Contracts are facts."* |
| 📜 **The Historian** | "has this been tried?" — precedents, cycles, the graveyard AND the survivors |
| 🌱 **The Therapist** | fear-driven decisions, burnout, identity. *"Is this moving toward something, or away from something?"* |

---

## Block 3 — update the repo structure tree

Add under `personas/`:
```
│   │   ├── lawyer.md      ← ⚖ guest seat
│   │   ├── historian.md   ← 📜 guest seat
│   │   └── therapist.md   ← 🌱 guest seat
```
Add under `templates/`:
```
│       └── quick-format.md    ← Quick Council compact output
```
