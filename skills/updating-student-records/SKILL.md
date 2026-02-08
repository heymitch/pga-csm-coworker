---
name: updating-student-records
description: Maps student activity to AirTable stage updates and flags data mismatches. Use when telling your coworker about submissions or asking it to reconcile student progress.
---

# Updating Student Records

Tell me what your students submitted or did this week. I'll tell you exactly what to update in AirTable — which students, which stages, which fields. If I have AirTable access, I'll do it directly.

## What I Need
- Student activity (submissions, calls completed, milestones hit)
- Or: "reconcile my roster" — I'll compare what I know against expected progress

## What I Produce

```
## AirTable Updates — [Date]

### Stage Advances
| Student | From | To | Reason |
|---------|------|-----|--------|
| @Sarah | Assignment 2 | Assignment 3 | Submitted EEC in #submit-assignment-3 today |
| @Marcus | Enrolled | Joined Slack | First message in private channel |

### Flags
⚠️ @Julia — AT shows Assignment 1 but submitted Assignment 3 in Slack.
   Gap detected — check if Assignment 2 was missed or automation issue.
   → Flag to Daniel/Jamie if automation problem.

⚠️ @Pat — AT shows Assignment 4 but no submission found in Slack.
   Possible: submitted via private channel or email issue.

### Notes to Add
- @David: "EEC launched 2/6. Strong outline, personality present. Watch for client landing."
- @Kim: "Week 15. Business Strategy Call scheduled 2/14. Liftoff candidate — $4.2K clients landed."

### Referral Tracking
- @Sarah referred @NewStudent → attribute to Sarah's Student Referral KPI,
  assign @NewStudent to this CSM roster, 5% UF & AR
```

## Stage Progression Rules

Students must move in order — I never skip stages:
```
Enrolled → Joined Slack → Booked OB Call → Assignment 0 → 1 → 2 → 3 → 4 (EEC!) → 5 → 6 → 7 → 8 → 9 → Offboarding/Liftoff
```

If a submission appears that skips a stage, I flag the gap instead of advancing.

## Key Rules

- **Exact timestamps** — every stage change gets a date
- **Flag stalls** — 10+ days on same stage = flagged
- **Detect mismatches** — AT and Slack should agree, if not I flag
- **Referral attribution** — I know the referral KPI rules and apply them correctly

## References

- Full stage progression and detection rules: [playbook.md](playbook.md)
- Resource manifest: [manifest.md](manifest.md)
