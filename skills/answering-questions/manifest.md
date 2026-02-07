# Resource Manifest: Answering Questions

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| Curriculum mastery | Module content mapping, FAQ knowledge, Skool search |
| Socratic coaching | Challenge-with-a-question, don't give direct answers |
| Channel routing | Identify correct channel for each question type |

## Resources

### Tools (Built-in)
- File access

### Plugins (claude.com/plugins)
| Plugin | Purpose | Install |
|--------|---------|---------|
| Slack | Read #ask-* channels, draft responses | [Install](https://claude.com/plugins) |

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| Slack API | MCP server | Read questions, draft responses | Install MCP server |
| Skool | REST | Search curriculum for answer links | API key or index |

### Prompts & Playbooks
- Channel-specific response guides (playbook.md)
- DM redirect template
- Common copy-paste responses

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | ~3K |
| Recommended model | Sonnet |
| Executions per month | ~200 |
| Token cost / month | $10.80 |
| **Total / month** | **$10.80** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per response | 5 min | 1.5 min (review draft) | 70% |
| Monthly hours | 16.7h | 5h | 11.7h |
| Monthly cost (at $30/hr) | $500 | $150 + $11 | $339 |
