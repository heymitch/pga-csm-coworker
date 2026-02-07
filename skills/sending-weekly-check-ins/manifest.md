# Resource Manifest: Sending Weekly Check-ins

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| Student progress analysis | Stage detection, activity scoring, milestone awareness |
| Motivational messaging | Stage-appropriate tone, personalization |
| Offboarding awareness | Wk 10/12/14/16 reminder integration |

## Resources

### Tools (Built-in)
- File access

### Plugins (claude.com/plugins)
| Plugin | Purpose | Install |
|--------|---------|---------|
| Slack | Post check-ins to private channels | [Install](https://claude.com/plugins) |

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| AirTable API | REST | Pull roster with current stages | API key |
| Slack API | MCP server | Check last activity, post messages | Install MCP server |

### Prompts & Playbooks
- Stage-specific message templates (playbook.md)
- Offboarding reminder copy (Wk 10/12/14/16)
- Inactive student escalation template

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | ~3K per student |
| Recommended model | Haiku |
| Executions per month | ~72 (18 students x 4 weeks) |
| Token cost / month | $1.73 |
| **Total / month** | **$1.73** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per batch | 90 min (18 students x 5 min) | 15 min (review batch) | 83% |
| Monthly hours | 6h | 1h | 5h |
| Monthly cost (at $30/hr) | $180 | $30 + $2 | $148 |
