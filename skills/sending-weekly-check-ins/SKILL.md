---
name: sending-weekly-check-ins
description: Generates personalized weekly proactive check-in messages for each student on the CSM's roster. Use every Thursday or Friday to batch-generate outreach messages based on each student's program stage and activity.
---

# Sending Weekly Check-ins

I generate personalized check-in messages for every student on your roster so you approve a batch instead of writing 18 messages from scratch.

## Workflow

- [ ] Step 1: Pull full roster from AirTable with current stage per student
- [ ] Step 2: Check each student's Slack activity (last message, last submission)
- [ ] Step 3: Identify program milestone approaching (assignment due, call eligible, offboarding timeline)
- [ ] Step 4: Draft personalized check-in per student (3-5 sentences)
- [ ] Step 5: Batch all drafts for CSM review
- [ ] Step 6: CSM approves/edits → posts to private channels

## How I Execute

### With Slack + AirTable Access
Auto-pull roster, activity data, and stage. Generate all check-ins in one batch. Present as a table: Student | Stage | Days Since Last Activity | Draft Message.

### Without Full Access (Fallback)
Ask CSM to paste roster status. Generate messages based on provided stage info.

## Key Rules

- **Personalize to their stage** — early students get assignment nudges, mid-stage get outreach encouragement, late-stage get offboarding awareness
- **Reference their specific work** — "How's your EEC outline coming?" not "How's it going?"
- **Include offboarding reminders at Wk 10, 12, 14, 16** — use offboarding copy from playbook
- **Flag inactive students** — 7+ days no Slack activity gets a stronger check-in
- **Never generic** — if the message could be sent to any student, it's not good enough

## References

- Playbook: [playbook.md](playbook.md)
- Resource manifest: [manifest.md](manifest.md)
