---
name: onboarding-students
description: Manages the 6-step new student onboarding workflow for PGA. Use when a new student notification appears in #pga-sales-dopamine or #pga-student-onboarding.
---

# Onboarding Students

I run the 6-step onboarding checklist for every new student so nothing gets missed.

## Workflow

- [ ] Step 1: Detect new student alert in #pga-sales-dopamine
- [ ] Step 2: Track #pga-student-onboarding for: Slack joined, private channel created, CSM assigned, Success Path created
- [ ] Step 3: Generate Welcome Loom script (personalized intro + evergreen steps)
- [ ] Step 4: Check deposit vs. full enrollment status — flag if deposit >72 hours
- [ ] Step 5: Check Program Agreement status — flag if unsigned
- [ ] Step 6: Monitor AirTable for stage progression (Enrolled → Joined Slack → Booked OB → Assignment 0)

## How I Execute

### With Slack + AirTable Access
Auto-detect new students, pull enrollment data, generate Loom scripts, track progress through stages, alert if student stalls.

### Without Full Access (Fallback)
Provide onboarding checklist with student name, prompt CSM for each step completion.

## Key Rules

- **Welcome Loom within 3 hours** — before the Accountability Trio auto-message fires at 6 hours
- **Batch Looms if 3+ new students** — don't break workflow for each one individually
- **Drop camera emoji on #pga-sales-dopamine** once Loom is sent
- **Deposit students can't book 1:1 OB Call** — flag and inform if they try
- **Agreement must be signed before 1:1 coaching begins** — no exceptions
- **Watch for rare cases** — some enrollments come through #pga-payments instead of #pga-sales-dopamine

## References

- Playbook: [playbook.md](playbook.md)
- Resource manifest: [manifest.md](manifest.md)
