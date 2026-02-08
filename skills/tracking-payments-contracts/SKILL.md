---
name: tracking-payments-contracts
description: Drafts escalation messages for failed payments and flags unsigned program agreements. Use when checking #pga-failed-payments or when a student has a payment or contract issue.
---

# Tracking Payments & Contracts

Paste me the failed payment alerts or student payment data. I draft every escalation message at the right stage — Slack 1, Slack 2, Email, or Finance escalation. You review and send.

## Failed Payments

### What I Need
- Failed payment alert (paste from #pga-failed-payments or describe)
- Which escalation stage they're at (first contact? second? third?)
- Last payment date from SamCart if you have it (or I'll ask you to check)

### What I Produce

**If SamCart shows payment AFTER the failed date** → "No action needed on @[Student] — paid after alert."

**If payment is actually delinquent:**

Stage 1 — Slack message:
```
Hey @[Student]! Our Finance Team contacted me to let me know your recent
payments have failed. Do you need to update your card on file?

Here's a link to help you make any updates. Can you let me know when it's
resolved and I'll let the team know? Thanks [Name]!
```

Stage 2 — Slack follow-up (3-4 days later):
```
Hey @[Student] - bumping this message up regarding your failed payments.
Do you need to update your credit card info? If so you can use the link
I provided above.
```

Stage 3 — Email (7+ days, I draft with cc: Chris + Katie):
```
Hi [Student],

I messaged you a few times in Slack regarding your failed PGA payments...
[full email from playbook]
```

Stage 4 — Finance escalation:
```
Hey @Chris adding you to @[Student]'s channel here so you can connect
on next steps with payment delinquency.
```

I determine the right stage based on timeline and draft the correct message.

## Contract/Agreement Monitoring

### What I Need
- Your AirTable "All Contracts Pending" data (paste or I'll pull)

### What I Produce
- List of unsigned agreements with days outstanding
- Draft follow-up per student
- Escalation flags (deposit students skipped — they don't get agreements)

## Key Rules

- **Check SamCart BEFORE messaging** — student may have already paid
- **Deposit students don't get agreements** — I never flag them as unsigned
- **Students can't book OB calls or receive coaching until agreement is signed**
- **I never cancel payments** — always escalate to Jamie
- **72-hour deposit rule** — I flag students on deposit for 72+ hours

## References

- Full escalation templates and SOP: [playbook.md](playbook.md)
- Resource manifest: [manifest.md](manifest.md)
