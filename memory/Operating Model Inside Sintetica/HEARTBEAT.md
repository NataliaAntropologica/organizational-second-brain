# Heartbeat Monitor Checklist

<!-- Loaded by heartbeat.py to drive each monitoring cycle.
     Update this file when Sintética's monitoring priorities change. -->

## Every 30 Minutes (Active Hours 7 AM–10 PM COT, Mon–Fri)

- Check for new or modified `.md` files in `sources/` via git log
- Identify which domains have new activity
- If new entry in `sources/trends/` or `sources/future-signals/`:
  → Search `sources/hypotheses/` for related hypotheses
  → If match found: note evidence accumulating for or against that hypothesis
- If new entry in `sources/decisions/`:
  → Check if it connects to any active hypothesis in `strategic_memory.md`
- If any hypothesis has 5+ supporting signals: propose a synthesis brief draft

## Morning Briefing (8 AM COT, Mon–Fri)

- Review `memory/strategic_memory.md` for active projects and open questions
- List domains with new activity since yesterday
- Flag decisions older than 90 days with no recorded outcome
- Highlight the most active hypothesis this week
- Identify any `drafts/active/` files older than 48 hours without review

## Weekly Synthesis (Sunday 6 PM COT)

- Review all daily logs from `memory/daily/` for the past week
- Detect new patterns: same theme appearing in 3+ separate domain entries
- Update confidence signals on active hypotheses
- Propose `memory/strategic_memory.md` updates: new patterns, remove resolved items
- Generate a "Weekly Strategic Pulse" draft in `drafts/active/`

## Weekly Rhythm Check (Monday 9 AM COT)

- Check `memory/STRATEGIC_HABITS.md` pillars — which triggered last week?
- For untriggered pillars: suggest one specific action based on active projects in `strategic_memory.md`
- Friday 5 PM: if all 5 pillars triggered this week → draft a Weekly Pulse
