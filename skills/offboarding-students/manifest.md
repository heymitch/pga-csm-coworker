# Resource Manifest: Offboarding Students

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| Timeline management | Week milestone tracking, progressive reminder scheduling |
| Upsell awareness | Liftoff eligibility detection, $5K threshold monitoring |
| Cancellation policy | Payment threshold rules, refund policy enforcement |
| De-escalation | Coaching responses for unhappy students |

## Resources

### Tools (Built-in)
- File access

### Plugins (claude.com/plugins)
| Plugin | Purpose | Install |
|--------|---------|---------|
| Slack | Draft offboarding messages in private channels | [Install](https://claude.com/plugins) |

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| AirTable API | REST | Enrollment dates, payment totals, stage | API key |
| Slack API | MCP server | Private channel messaging | Install MCP server |

### Prompts & Playbooks
- Week-by-week offboarding timeline (playbook.md)
- Business Strategy Call agenda
- Cancellation response templates
- Payment threshold decision tree

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | ~3K per student |
| Recommended model | Sonnet |
| Executions per month | ~6 |
| Token cost / month | $0.32 |
| **Total / month** | **$0.32** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per student | 2h (over weeks) | 45 min (review auto-reminders) | 63% |
| Monthly hours | 3h | 1.1h | 1.9h |
| Monthly cost (at $30/hr) | $90 | $33 + $0.32 | $57 |
