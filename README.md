# PGA CSM AI Coworker

Your AI-powered Student Success Manager assistant for the Premium Ghostwriting Academy.

## What This Is

This folder turns Claude into your CSM coworker. Open Claude in this directory and it instantly knows the PGA program, your students, your tools, and your daily workflow. It drafts assignment feedback, prepares call briefs, generates reports, tracks payments, and keeps you ahead of every student on your roster.

## Prerequisites

- Claude account with Claude Code or desktop app
- Access to: Slack, AirTable, SamCart, Fathom, Google Drive, Calendly

## Quick Start

1. **Fill out config.md** — Add your name, Calendly link, and verify URLs
2. **Set up connectors** — See [connectors.md](connectors.md) for integration setup
3. **Open Claude in this folder** — Claude becomes your CSM coworker immediately
4. **Say "morning brief"** — Get your daily rundown of students, payments, and priorities

## What Your Coworker Does

| Area | What It Handles |
|------|----------------|
| **Assignment Reviews** | Drafts personalized feedback for Modules 0-9 submissions |
| **Question Responses** | Drafts Slack replies linking to curriculum |
| **Call Prep** | Generates pre-call briefs from AirTable + Slack + Success Paths |
| **Post-Call Follow-up** | Summarizes Fathom transcripts into next steps |
| **Weekly Check-ins** | Generates personalized outreach per student's stage |
| **BOD/EOD/EOW Reports** | Auto-generates status reports from your data |
| **Payment Tracking** | Monitors failed payments, drafts escalation messages |
| **Onboarding** | Runs 6-step new student workflow |
| **Offboarding** | Progressive Wk 10-16 transition management |
| **AirTable Sync** | Updates student stages from Slack activity |

## How to Customize

- **config.md** — Update when tools, URLs, or team members change
- **training/sops/** — Drop your SOPs here as processes evolve
- **training/examples/** — Add example feedback to improve draft quality
- **training/context/** — Drop any role-specific docs (org charts, policies, etc.)
- **skills/[name]/playbook.md** — Edit when call flows or review criteria change

## Important: All Drafts Need Your Review

Your coworker drafts everything but sends nothing. Every student-facing message, feedback response, and report is queued for your approval before it goes anywhere. You stay in control.

## Getting Help

- Edit any file in this folder to change how your coworker operates
- Check [connectors.md](connectors.md) for integration troubleshooting
- Your coworker learns from what's in this folder — keep it current
