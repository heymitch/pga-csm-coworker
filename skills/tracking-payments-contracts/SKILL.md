---
name: tracking-payments-contracts
description: Monitors failed payments and unsigned program agreements for PGA students. Use daily to check #pga-failed-payments, cross-reference SamCart, draft escalation messages, and flag outstanding contracts.
---

# Tracking Payments & Contracts

I monitor payment failures and unsigned agreements so nothing slips through the cracks.

## Workflow — Failed Payments

- [ ] Step 1: Check #pga-failed-payments for new alerts
- [ ] Step 2: Cross-reference student email in SamCart (audience tab) — check last payment date
- [ ] Step 3: If last payment is AFTER failed date → no action, check off
- [ ] Step 4: If no payment since → add to Failed Payments Tracker
- [ ] Step 5: Determine escalation stage (Slack 1, Slack 2, Email, Finance escalation)
- [ ] Step 6: Draft appropriate message using template
- [ ] Step 7: Queue for CSM review

## Workflow — Contract Monitoring

- [ ] Step 1: Check AirTable "All Contracts Pending" view every morning
- [ ] Step 2: Identify unsigned agreements older than 48 hours
- [ ] Step 3: Cross-reference: is student on deposit (no agreement sent) or enrolled (agreement sent, not signed)?
- [ ] Step 4: Draft follow-up or escalation as appropriate
- [ ] Step 5: Flag during daily standup prep

## How I Execute

### With SamCart + AirTable + Slack Access
Auto-cross-reference payments, generate escalation drafts, update tracker.

### Without Full Access (Fallback)
Provide checklist: "Check these 3 students in SamCart, here are the draft messages for each escalation level."

## Key Rules

- **Check SamCart BEFORE messaging** — student may have already paid after the alert
- **Follow the escalation ladder** — Slack 1 → Slack 2 → Email (cc Chris + Jamie) → Add Chris to private channel
- **Deposit students don't get agreements** — don't flag them as unsigned
- **Never cancel payments yourself** — always escalate to Jamie
- **72-hour rule** — students on deposit for 72+ hours without payment plan need closer contact

## References

- Playbook: [playbook.md](playbook.md)
- Resource manifest: [manifest.md](manifest.md)
