# Installation Guide

## Prerequisites

- A Claude account at [claude.ai](https://claude.ai) (any plan — Free, Pro, or Team)
- The Skills feature enabled (Settings → Skills → toggle on)

---

## Method 1: Upload the skill folder (recommended)

This method installs all 7 persona files and templates so the Council has full depth.

1. Clone or download this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/claude-council-skill.git
   ```

2. Navigate to [claude.ai](https://claude.ai) → click your profile icon → **Settings**

3. Select **Skills** from the left sidebar

4. Click **Add Skill** or the **+** button

5. Upload the entire `council/` folder

6. Claude will confirm the skill is active

7. Start a new conversation and try: *"Should I quit my job and start a business?"*

---

## Method 2: Manual copy-paste

If you want the minimal install (SKILL.md only, without full persona depth):

1. Open [`council/SKILL.md`](council/SKILL.md) in this repository

2. Copy the entire contents

3. In Claude.ai → Settings → Skills → **New Skill**

4. Paste the contents and save

**Note:** Without the persona files, the Council will still work, but persona voices will be less precisely calibrated. Method 1 is strongly recommended.

---

## Method 3: Claude Code

If you use Claude Code:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/claude-council-skill.git

# Copy to your Claude skills directory
cp -r claude-council-skill/council ~/.claude/skills/council
```

---

## Verifying it works

Start a new Claude conversation and send:

> "Convene the Council. I'm deciding whether to freelance full-time or stay employed."

You should see the Council banner appear with all 7 personas and a structured verdict.

---

## Troubleshooting

**The Council isn't triggering automatically**

Try an explicit trigger: *"Convene the Council on this decision:"* followed by your question. If that doesn't work, verify the skill is enabled in Settings → Skills.

**The output looks like a normal Claude response, not the Council format**

The skill may not have loaded the persona files. Try Method 1 (full folder upload) instead of Method 2.

**The personas sound similar to each other**

This can happen if Claude doesn't have access to the individual persona files. Ensure the full `council/` folder was uploaded, not just `SKILL.md`.

---

## Uninstalling

Settings → Skills → find "council" → click the trash icon or toggle off.
