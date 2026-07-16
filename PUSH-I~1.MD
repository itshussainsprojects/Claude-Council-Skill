# How to publish v2

New/updated files in this folder (paths mirror your repo):
- claude-council-skill/council/SKILL.md            (REPLACES existing)
- claude-council-skill/council/personas/lawyer.md    (new)
- claude-council-skill/council/personas/historian.md (new)
- claude-council-skill/council/personas/therapist.md (new)
- claude-council-skill/council/templates/quick-format.md (new)
- CHANGELOG.md (new, put at repo root)
- README-NEW-SECTIONS.md (paste blocks into your README.md, don't commit this file)

Commands (from your local clone):
```bash
# copy the files in, then:
git checkout -b v2-council-upgrade
git add -A
git commit -m "v2.0: modes (quick/deep/red-team), cross-examination, revote, guest personas (Lawyer, Historian, Therapist)"
git push -u origin v2-council-upgrade
# open a PR, or push straight to main if you prefer
```

Commits will be attributed to whatever identity is set in your git config
(`git config user.name` / `git config user.email`) — set it to your own account.
