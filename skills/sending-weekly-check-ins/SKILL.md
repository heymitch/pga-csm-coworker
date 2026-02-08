---
name: sending-weekly-check-ins
description: Produces personalized weekly check-in messages for every student on the CSM's roster. Use Thursday or Friday to batch-generate all outreach at once.
---

# Sending Weekly Check-ins

Give me your roster (names + current modules + any notes). I write every check-in message — one per student, personalized to their stage. You review the batch and post.

## What I Need

- Student roster: name, current module/assignment, weeks in program
- Any specific flags: inactive students, upcoming milestones, recent wins, issues
- (If I have AirTable access, I pull this myself)

## What I Produce

A batch of ready-to-post messages, one per student:

```
## Weekly Check-ins — [Date]

### @[Student 1] — Module 3, Week 4
> Hey @[Student]! How's your EEC coming along? I saw your outline had some
> strong headlines — are you keeping that energy in the daily content?
> Remember Day 0 should tease the mistakes without giving them away.
> You're on track for an EEC launch this week!

### @[Student 2] — Module 5, Week 7
> Hey @[Student]! How's outreach going? How many messages have you sent
> this week? Remember — 25 per week is the target. The most successful
> ghosts in this program have a daily outreach practice. What's your
> schedule looking like?

### @[Student 3] — ⚠️ INACTIVE 9 days, Module 2, Week 5
> Hey @[Student]! Haven't seen you in the channels lately — everything okay?
> Where are you at with your EEC outline? I'd love to help you get back on
> track. What's your biggest blocker right now?

[...for every student on roster]
```

## Offboarding Integration

For students at Week 10, 12, 14, or 16, I automatically include the appropriate offboarding reminder in their check-in. You don't need to remember the timeline — I handle it. See [playbook.md](playbook.md) for exact copy.

## Rules I Follow

- **Reference their specific work** — "How's your EEC outline?" not "How's it going?"
- **Include the right offboarding language** at Wk 10/12/14/16
- **Flag inactive students** with ⚠️ — 7+ days no activity gets a stronger check-in
- **Never generic** — if the message could go to any student, I rewrite it
- **Group by urgency** — inactive/flagged students first, then by module stage

## References

- Stage-specific templates and offboarding copy: [playbook.md](playbook.md)
- Resource manifest: [manifest.md](manifest.md)
