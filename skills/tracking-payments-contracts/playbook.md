# Payment & Contract Tracking Playbook

## Failed Payment SOP

### Step-by-Step Process
1. Check #pga-failed-payments in Slack for new alerts
2. Copy student email from the alert
3. Paste in SamCart → Audience tab → find last payment date
4. **If last payment date is AFTER the failed payment date** → No action needed, check off the Slack message
5. **If no payment since the failed date** → Add to Failed Payments Tracker:
   - Manual entry in Grid View (bottom row)
   - Enter email in "Email" and "Link to CRM" columns
   - Check off "Hub Login Sent" (needed to advance to next view, even if not actually sent)
6. Review "Weekly Review - Grouped by Time" view for escalation timing

### Escalation Ladder

**Slack Message 1** (Day 1):
```
Hey @[Student]! Our Finance Team contacted me to let me know your recent payments have failed. Do you need to update your card on file?

Here's a link to help you make any updates. Can you let me know when it's resolved and I'll let the team know? Thanks [Name]!
```

**Slack Message 2** (Day 3-4):
```
Hey @[Student] - bumping this message up regarding your failed payments. Do you need to update your credit card info? If so you can use the link I provided above.
```

**Email** (Day 7, cc Chris Hanna + optionally Katie):
```
Hi [Student],

I messaged you a few times in Slack regarding your failed PGA payments, so following up here via email and copying our Head of Finance, Chris.

If you need to update your card on file, here's a link to help you.

If you could let us know when this is resolved we'd greatly appreciate it. If we don't hear from you we'll need to remove you from the program and we do not offer refunds, so we'd hate to see you go and lose out!

Thanks [Student],
[CSM Name]
```

**Finance Escalation** (Day 10+):
Add Chris to student's private channel:
```
Hey @Chris adding you to @[Student]'s channel here so you can connect on next steps with payment delinquency.
```

### When Student Says They'll Pay Later
```
Hi @[Student], that works for us - thank you for confirming you will continue paying, starting on [DATE]. I want to be aware that the last payment received was [MONTH YEAR], and appreciate that you're able to resolve this moving forward.
```
This confirms the date (gives them ownership) and documents the gap.

## Contract/Agreement Monitoring

### Daily Check
1. Open AirTable "All Contracts Pending" view
2. For each unsigned agreement:
   - Check: Is student on deposit? (Deposits don't get agreements — skip)
   - Check: How many days since agreement was sent?
   - If 48+ hours unsigned → draft follow-up for student
   - If student says they need time → escalate in this order:
     1. Contact the Closer/Enrollment Advisor
     2. Contact Jamie Runion to confirm PandaDoc sent/opened

### Key Rules
- Deposit students ($1/$500/$1000) will NOT receive an agreement — they're not fully enrolled
- Students CANNOT book 1:1 Onboarding Call until agreement is signed
- Students CANNOT receive 1:1 coaching until agreement is signed
- If student books OB call without signing:
  - **Before call:** Explain the rules, reschedule after signing
  - **During call:** Ask them to find and sign it right now on the call, OR cancel if they "want more time"

## Deposit Follow-up (72-Hour Rule)
- Students on deposit for 72+ hours without full enrollment
- CSM contacts the Closer regarding student status
- Check #pga-sales-dopamine and Student AirTable View for deposit vs. payment plan info
