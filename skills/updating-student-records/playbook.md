# Student Records Playbook

## AirTable Stage Progression

Students move through these stages in order:

```
Enrolled
  → Joined Slack
    → Booked Onboarding Call
      → Completed Assignment 0
        → Completed Assignment 1
          → Completed Assignment 2
            → Completed Assignment 3
              → Completed Assignment 4 (EEC Launched!)
                → Completed Assignment 5
                  → Completed Assignment 6
                    → Completed Assignment 7
                      → Completed Assignment 8
                        → Completed Assignment 9
                          → Offboarding / Liftoff
```

## Detection Rules

### From Slack Activity
| Slack Event | AirTable Update |
|------------|----------------|
| Student posts in any channel | Confirm "Joined Slack" if not already |
| Student posts in #submit-assignment-X | Advance to "Completed Assignment X" |
| Student books Calendly call | Update to "Booked Onboarding Call" (if first call) |
| Student inactive 14+ days | Flag for CSM attention |

### From AirTable
| AirTable Event | Action |
|---------------|--------|
| Stage hasn't changed in 10+ days | Flag student as potentially stuck |
| Assignment submitted in Slack but AT not updated | Possible automation issue → flag to Daniel/Jamie |
| Student shows progress in AT but no Slack submissions | Possible email/form issue → investigate |

## Update Process

1. **Scan assignment channels** daily for new submissions
2. **Match student to AirTable record** by name
3. **Verify current stage** — don't skip stages (if AT shows Assignment 1 but they submitted Assignment 3, flag the gap)
4. **Advance stage** and log timestamp
5. **Add notes** with context (what they submitted, any notable feedback)

## Fields to Update

| Field | When to Update |
|-------|---------------|
| Current Stage | Every assignment submission |
| Last Activity Date | Any Slack activity |
| Notes | After calls, notable interactions, flags |
| NPS Score | After Week 8 survey |
| Referrals | When student refers someone new |
| Liftoff Candidate | When $5K clients landed or approaching Week 16 |

## Referral Tracking

### Student Referral (student refers someone to PGA)
- Attributed to CSM's Student Referral KPI
- CSM gets referred student as their dedicated 1:1
- CSM gets 5% of referred student's UF & AR payments

### CSM Personal Referral (CSM's own network)
- NOT attributed to Student Referral KPI
- CSM gets that student as their dedicated 1:1
- CSM gets 5% of UF & AR payments AND 15% referral commission on cash collected

## AirTable Views Used

| View | Purpose |
|------|---------|
| CSM Student View | Your personal roster with all student data |
| All Contracts Pending | Unsigned agreements needing follow-up |
| CSM Deals View | Payment and financial status |
| Failed Payments Tracker | Weekly Review - Grouped by Time |
