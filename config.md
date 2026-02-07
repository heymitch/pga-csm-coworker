# Business Configuration

> PGA-specific details so this coworker works for YOUR roster.
> Fill this out manually OR say "interview me" on first use.
> All playbooks reference these values as `{{config.variable_name}}`

---

## Status

- [ ] Configuration complete

---

## Business Details

```yaml
business_name: "Premium Ghostwriting Academy"
program_name: "PGA"
student_term: "ghost"
community_name: "PGA Community"
company_domain: "ship30for30.com"
program_length: "16 weeks"
ascension_program: "Liftoff"
```

---

## CSM Details

```yaml
csm:
  name: ""                         # Your name
  email: ""                        # your-name@ship30for30.com
  calendly_link: ""                # e.g., "https://calendly.com/katieship30"
  roster_size: ""                  # Number of active students
  team_name: ""                    # e.g., "Team Katie"
```

---

## Tools & Platforms

```yaml
tools:
  communication: "Slack"           # PGA Slack workspace
  curriculum: "Skool"              # PGA curriculum + clinic replays
  crm: "AirTable"                  # Student tracking + KPIs
  payments: "SamCart"              # Payment processing
  agreements: "PandaDoc"           # Program agreements
  scheduling: "Calendly"           # 1:1 call booking
  video_messages: "Loom"           # Welcome Looms + feedback
  call_recording: "Fathom"         # 1:1 call recordings + transcripts
  video_calls: "Zoom"             # Live calls
  success_paths: "Google Docs"     # Custom Success Paths
  community: "Skool"              # Community + curriculum
```

---

## Dashboard URLs

```yaml
urls:
  airtable_student_view: ""        # Your CSM Student View
  airtable_contracts_pending: "https://airtable.com/appsHqlnN4bM3PpG4/tblcmWKrysJwNkFKw/viwjqNtiO3rYTRQlC?blocks=hide"
  samcart_dashboard: ""            # SamCart audience tab
  skool_curriculum: "https://www.skool.com/pga/classroom"
  skool_events: "https://www.skool.com/pga/classroom/5b1740d1"
  success_path_templates: "https://drive.google.com/drive/u/0/folders/10QeUIFR_QaxVg0uTLwIqBVoOa9kz3xtY"
  failed_payments_tracker: ""      # Failed Payments Google Sheet
  sales_accelerator: "https://www.skool.com/sales-team-accelerator-30-4166/classroom/b6310c7d"
```

---

## Slack Channels

```yaml
slack:
  internal:
    success_ops: "#ghostwriting-success-ops"       # BOD reports
    success_eod: "#ghostwriting-success-eod"       # EOD reports + EOW Looms
    sales_dopamine: "#pga-sales-dopamine"           # New student alerts
    student_onboarding: "#pga-student-onboarding"   # Onboarding notifications
    failed_payments: "#pga-failed-payments"          # Payment failure alerts
    payments: "#pga-payments"                        # Payment confirmations
  assignment_channels:
    - "#introduce-yourself"
    - "#submit-assignment-0"
    - "#submit-assignment-1"
    - "#submit-assignment-2"
    - "#submit-assignment-3"
    - "#submit-assignment-4"
    - "#submit-assignment-5"
    - "#submit-assignment-6"
    - "#submit-assignment-7"
    - "#submit-assignment-8"
    - "#submit-assignment-9"
  question_channels:
    - "#ask-curriculum-questions"
    - "#ask-logistical-questions"
    - "#ask-niche-and-content-questions"
    - "#ask-tech-questions"
    - "#ask-sales-questions"
  community_channels:
    - "#check-announcements"
    - "#share-wins"
    - "#lessons-learned"
    - "#rising-ghostwriters"
    - "#social-strategy"
    - "#pga-alumni"
```

---

## Team Directory

```yaml
team:
  founders:
    - name: "Dickie"
      role: "Co-founder"
    - name: "Cole"
      role: "Co-founder, curriculum lead"
  csm_team:
    - name: "Katie"
      role: "CSM Lead, Accountability Trios"
    - name: "Andrew"
      role: "CSM, Sales Clinics"
    - name: "Daniel"
      role: "Ops, Tech Clinics, milestone messages"
  finance:
    - name: "Jamie Runion"
      role: "Operations, PandaDoc, payment cancellations"
    - name: "Chris Hanna"
      role: "Head of Finance"
      email: "chris@ship30for30.com"
  escalation_order:
    - "Katie (CSM issues)"
    - "Jamie (payment/contract issues)"
    - "Chris (financial escalation)"
    - "Daniel (tech/automation issues)"
```

---

## Program Structure

```yaml
program:
  modules: 10                      # Module 0-9
  coaching_calls:
    - type: "Onboarding Call"
      trigger: "After enrollment + agreement signed"
      length: "30 min"
    - type: "Outreach Strategy Call"
      trigger: "After Assignment 5 submitted"
      length: "20 min"
    - type: "Sales Call Review"
      trigger: "After Assignment 7 submitted"
      length: "20 min"
    - type: "Delight & Upsell Call"
      trigger: "After Assignment 8 submitted"
      length: "20 min"
    - type: "Wildcard Call"
      trigger: "As needed"
      length: "20 min"
    - type: "Business Strategy Call (Offboarding/Upsell)"
      trigger: "Week 16 or $5K clients landed"
      length: "30 min"
  kpis:
    - "Active Students"
    - "EECs Launched (goal: within 28 days)"
    - "Free Clients Landed"
    - "Paid Clients Landed"
    - "Liftoff Upsells"
    - "Student Referrals"
    - "NPS Score"
  clinics:
    monday:
      - "Meet & Greet - Katie"
      - "Tech Clinic - Daniel"
    tuesday:
      - "Sales Clinic - Andrew"
      - "Liftoff Outreach - Andrew"
    wednesday:
      - "Niche/EEC/Content Clinic - Katie"
      - "Liftoff Q&A - Cole"
    thursday:
      - "Hot Seats - Cole"
```

---

## Deposit & Payment Thresholds

```yaml
payments:
  deposit_amounts: ["$1", "$500", "$1,000"]
  deposit_followup_hours: 72
  cancellation_thresholds:
    below_50_percent: "$3,400"     # Remove from Skool + Slack
    above_50_percent: "$3,400"     # Pause payments, keep Skool, lose Slack
    above_5000: "$5,000"           # Pause payments, keep Skool + Slack, lose 1:1
  keep_skool_threshold: "$1,700"   # If paid $1700+ with cancelled future, keep Skool
  refund_policy: "PGA does not offer refunds"
```

---

## Placeholder Reference

| Placeholder | Example Value |
|-------------|---------------|
| `{{config.csm.name}}` | Katie |
| `{{config.csm.calendly_link}}` | https://calendly.com/katieship30 |
| `{{config.program_name}}` | PGA |
| `{{config.student_term}}` | ghost |
| `{{config.team.finance[0].name}}` | Jamie Runion |
| `{{config.urls.airtable_student_view}}` | https://airtable.com/... |
| `{{config.slack.assignment_channels}}` | #submit-assignment-0 through 9 |
