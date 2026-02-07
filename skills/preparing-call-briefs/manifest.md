# Resource Manifest: Preparing Call Briefs

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| Data aggregation | Multi-source pull (AirTable, Slack, Google Drive, Fathom) |
| Call agenda creation | Call-type-specific agendas, talking point generation |
| Transcript summarization | Fathom transcript extraction, key point identification |
| Student profile synthesis | Enrollment status, agreement status, progress tracking |

## Agents

### Sub-agents
| Agent | Role |
|-------|------|
| Data puller | Aggregates student data from AT + Slack + Success Path |
| Brief formatter | Structures data into call-type-specific brief |
| Transcript summarizer | Extracts key points from Fathom recordings |

## Resources

### Tools (Built-in)
- File access

### Plugins (claude.com/plugins)
| Plugin | Purpose | Install |
|--------|---------|---------|
| Google Docs | Access Custom Success Path documents | [Install](https://claude.com/plugins) |

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| AirTable API | REST | Student status, enrollment, stage | API key |
| Slack API | MCP server | Recent activity, submissions | Install MCP server |
| Google Drive API | REST | Custom Success Path access | OAuth |
| Fathom API | REST | Call transcript retrieval | API key |
| Calendly API | REST | Upcoming call schedule | API key |

### Prompts & Playbooks
- Call flow templates per type (playbook.md)
- 4-week action plan template
- Post-call follow-up template

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | ~5K (pre-call), ~4K (post-call) |
| Recommended model | Sonnet |
| Executions per month | ~32 (16 pre + 16 post) |
| Token cost / month | $5.18 |
| **Total / month** | **$5.18** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per brief | 15 min prep + 10 min follow-up | 0 (auto-generated) | 100% |
| Monthly hours | 6.7h | 0h | 6.7h |
| Monthly cost (at $30/hr) | $200 | $5 | $195 |
