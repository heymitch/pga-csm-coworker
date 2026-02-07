# Resource Manifest: Reviewing Assignments

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| EEC evaluation | Headline analysis, niche specificity check, formatting critique, word count validation |
| Ghostwriting pedagogy | Socratic coaching, challenge-with-a-question technique, progressive feedback |
| AI detection | ChatGPT phrase detection, voice/personality assessment |
| Curriculum mastery | Module 0-9 rubrics, FAQ references, Skool link matching |

## Agents

### Sub-agents
| Agent | Role |
|-------|------|
| Curriculum matcher | Finds relevant Skool module/lesson/FAQ links for feedback |
| Feedback drafter | Generates module-appropriate feedback using rubric |

## Resources

### Tools (Built-in)
- File access (read submission content, templates)

### Plugins (claude.com/plugins)
| Plugin | Purpose | Install |
|--------|---------|---------|
| Slack | Read #submit-assignment channels, draft feedback in thread | [Install](https://claude.com/plugins) |

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| Slack API | MCP server | Read submissions, post drafts | Install MCP server |
| Skool | REST (scrape) | Search curriculum for relevant links | API key or index file |

### Prompts & Playbooks
- Module-specific rubrics (playbook.md)
- Common copy-paste responses
- AI detection phrase list
- Cole's 1:3:1 writing structure reference

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | ~8K |
| Recommended model | Sonnet |
| Executions per month | ~80 |
| Token cost / month | $14.40 |
| Plugin costs / month | $0 |
| **Total / month** | **$14.40** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per review | 15 min | 4 min (review draft) | 73% |
| Monthly hours | 20h | 5.3h | 14.7h |
| Monthly cost (at $30/hr) | $600 | $159 + $14 | $427 |
