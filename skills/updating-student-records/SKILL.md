---
name: updating-student-records
description: Syncs AirTable student records from Slack activity, keeping CRM stages current as students submit assignments and progress through the program. Use daily to ensure AirTable reflects actual student progress.
---

# Updating Student Records

I keep AirTable in sync with reality so you never manually move a student through stages.

## Workflow

- [ ] Step 1: Scan #submit-assignment-* channels for new submissions
- [ ] Step 2: Match student to AirTable record
- [ ] Step 3: Advance stage (Enrolled → Joined Slack → Booked OB → Assignment 0 → ... → Assignment 9)
- [ ] Step 4: Flag mismatches (student submitted in Slack but AirTable not updated)
- [ ] Step 5: Update notes with latest activity date and context

## How I Execute

### With AirTable + Slack Access
Auto-detect submissions, match to student records, advance stages, log activity.

### Without Full Access (Fallback)
CSM reports submissions. I generate the AirTable updates needed as a checklist.

## Key Rules

- **Never skip stages** — if a student submits Assignment 3 but AirTable shows them at Assignment 1, flag the gap
- **Log the date** — every stage change gets a timestamp
- **Flag stalls to CSM** — if AirTable shows Assignment 2 but it's been 14+ days since last update, flag
- **Check both Slack and AT** — if AT shows progress but no Slack submission exists, there may be an email/automation issue (flag to Daniel/Jamie)
- **Referral tracking** — when a student refers someone, attribute in AirTable per referral KPI rules

## References

- Playbook: [playbook.md](playbook.md)
- Resource manifest: [manifest.md](manifest.md)
