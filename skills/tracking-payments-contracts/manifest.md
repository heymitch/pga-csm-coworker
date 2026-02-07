# Resource Manifest: Tracking Payments & Contracts

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| Payment delinquency tracking | SamCart cross-reference, timeline tracking, escalation staging |
| Contract compliance | Agreement status monitoring, deposit classification |
| Escalation routing | Message ladder (Slack 1 → Slack 2 → Email → Finance) |

## Resources

### Tools (Built-in)
- File access

### Plugins (claude.com/plugins)
| Plugin | Purpose | Install |
|--------|---------|---------|
| Slack | Read #pga-failed-payments, draft escalation messages | [Install](https://claude.com/plugins) |

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| AirTable API | REST | Contracts Pending view, CSM Deals view | API key |
| SamCart API | REST | Audience tab — verify last payment date | API key |
| Slack API | MCP server | Read payment alerts, draft messages | Install MCP server |

### Prompts & Playbooks
- Failed payment message templates (Slack 1, 2, Email)
- Escalation criteria and timeline
- Deposit threshold rules (72-hour, $1700/$3400/$5000)
- Contract follow-up templates

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | ~2K per student check |
| Recommended model | Haiku (routine), Sonnet (escalation decisions) |
| Executions per month | ~60 |
| Token cost / month | $1.44 |
| **Total / month** | **$1.44** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per day | 20 min | 5 min (review escalations) | 75% |
| Monthly hours | 7.3h | 1.8h | 5.5h |
| Monthly cost (at $30/hr) | $220 | $55 + $1 | $164 |
