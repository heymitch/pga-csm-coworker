# Resource Manifest: Updating Student Records

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| CRM management | Stage progression rules, timestamp logging |
| Activity detection | Slack submission parsing, stage matching |
| Anomaly detection | Gap identification, stall flagging, email/automation issue detection |

## Resources

### Tools (Built-in)
- File access, code execution (sync scripts)

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| AirTable API | REST | Read/write student records, advance stages | API key |
| Slack API | MCP server | Detect assignment submissions | Install MCP server |

### Prompts & Playbooks
- Stage progression rules (playbook.md)
- Detection rules (Slack event → AirTable update mapping)
- Referral attribution rules

### Scripts
| Script | Purpose |
|--------|---------|
| Slack-to-AirTable sync | Detect submissions, match students, advance stages |

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | ~1K per update |
| Recommended model | Haiku |
| Executions per month | ~100 |
| Token cost / month | $0.80 |
| **Total / month** | **$0.80** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per day | 20 min | 0 (auto-sync) | 100% |
| Monthly hours | 7.3h | 0h | 7.3h |
| Monthly cost (at $30/hr) | $220 | $0.80 | $219 |
