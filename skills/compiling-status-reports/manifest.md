# Resource Manifest: Compiling Status Reports

## Skills Required

| Skill | Sub-skills |
|-------|-----------|
| KPI aggregation | Active student count, assignment tracking, pipeline metrics |
| Projection modeling | Velocity analysis, archetype assessment, historical comparison |
| Report formatting | BOD/EOD/EOW templates, projection narratives |

## Agents

### Sub-agents
| Agent | Role |
|-------|------|
| Data aggregator | Pulls metrics from AirTable across all views |
| Projection calculator | Analyzes trajectories, estimates milestone dates |

## Resources

### Tools (Built-in)
- File access, code execution (for KPI calculations)

### Plugins (claude.com/plugins)
| Plugin | Purpose | Install |
|--------|---------|---------|
| Slack | Post reports to ops/eod channels | [Install](https://claude.com/plugins) |

### Connectors (APIs / MCP)
| Connector | Type | Purpose | Setup |
|-----------|------|---------|-------|
| AirTable API | REST | All student data, KPIs, stages | API key |
| Slack API | MCP server | Post formatted reports | Install MCP server |

### Prompts & Playbooks
- BOD template (first month + standard)
- EOD template
- EOW Loom script template
- Projection criteria and format

## Cost Estimate

| Metric | Value |
|--------|-------|
| Tokens per execution | BOD: ~3K, EOD: ~2K, EOW: ~4K, Projections: ~5K |
| Recommended model | Haiku (BOD/EOD), Sonnet (projections/EOW) |
| Executions per month | ~52 (22 BOD + 22 EOD + 4 EOW + 4 projections) |
| Token cost / month | $4.90 |
| **Total / month** | **$4.90** |

## Compared to Manual

| | Manual | With AI | Savings |
|--|--------|---------|---------|
| Time per day | 25 min (BOD + EOD) | 0 (auto-generated) | 100% |
| Monthly hours | 10h | 0h | 10h |
| Monthly cost (at $30/hr) | $300 | $5 | $295 |
