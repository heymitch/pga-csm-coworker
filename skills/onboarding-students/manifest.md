# Resource Manifest: Onboarding Students

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| Workflow management | 6-step checklist tracking, deadline monitoring |
| Student intake | Deposit detection, agreement monitoring, stage tracking |
| Welcome scripting | Loom talking points generation, personalized intro drafts |

## Resources

### Tools (Built-in)
- File access

### Plugins (claude.com/plugins)
| Plugin | Purpose | Install |
|--------|---------|---------|
| Slack | Monitor #pga-sales-dopamine, #pga-student-onboarding | [Install](https://claude.com/plugins) |

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| AirTable API | REST | Student status, enrollment, agreement | API key |
| Slack API | MCP server | Detect new students, track notifications | Install MCP server |
| Calendly API | REST | Verify OB call booking | API key |

### Prompts & Playbooks
- 6-step onboarding checklist (playbook.md)
- Welcome Loom script template
- Deposit vs. enrollment rules
- Agreement escalation path

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | ~5K per new student |
| Recommended model | Sonnet |
| Executions per month | ~8 |
| Token cost / month | $1.44 |
| **Total / month** | **$1.44** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per student | 30 min | 15 min (Loom still manual) | 50% |
| Monthly hours | 4h | 2h | 2h |
| Monthly cost (at $30/hr) | $120 | $60 + $1 | $59 |
