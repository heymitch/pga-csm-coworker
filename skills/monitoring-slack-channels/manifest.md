# Resource Manifest: Monitoring Slack Channels

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| Channel triage | Priority ordering, unread detection, response-needed flagging |
| Community engagement | Win celebration, encouragement, DM redirection |
| Student activity tracking | Inactivity detection, engagement scoring |

## Resources

### Tools (Built-in)
- File access

### Plugins (claude.com/plugins)
| Plugin | Purpose | Install |
|--------|---------|---------|
| Slack | Read 15+ channels, flag posts, draft responses | [Install](https://claude.com/plugins) |

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| Slack API | MCP server | Full channel read access | Install MCP server |

### Prompts & Playbooks
- Channel priority order (playbook.md)
- DM redirect templates
- Triage summary format

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | ~2K per scan |
| Recommended model | Haiku |
| Executions per month | ~100 |
| Token cost / month | $1.60 |
| **Total / month** | **$1.60** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per day | 35 min | 15 min (review flagged posts) | 57% |
| Monthly hours | 12.8h | 5.5h | 7.3h |
| Monthly cost (at $30/hr) | $385 | $165 + $2 | $218 |
