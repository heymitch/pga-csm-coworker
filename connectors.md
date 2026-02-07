# Connectors & Integrations

> Required and recommended integrations for your PGA CSM AI coworker.
> Set up required integrations before first use for full functionality.

---

## Required Integrations

| Integration | Type | Purpose | Setup |
|------------|------|---------|-------|
| Slack API | MCP Server | Read all PGA channels, draft messages, monitor activity | [Install](https://claude.com/connectors) |
| AirTable API | REST API | Student CRM, stage tracking, KPIs, contract status | [Install](https://claude.com/connectors) |
| SamCart API | REST API | Payment verification, failed payment cross-reference | [Install](https://claude.com/connectors) |
| Fathom API | REST API | Retrieve 1:1 call transcripts for post-call follow-ups | [Install](https://claude.com/connectors) |

---

## Recommended Integrations

| Integration | Type | Purpose | Setup |
|------------|------|---------|-------|
| Google Drive API | REST API | Access Custom Success Path templates | [Install](https://claude.com/plugins) |
| Calendly API | REST API | See upcoming 1:1 calls for prep scheduling | [Install](https://claude.com/connectors) |
| Loom API | REST API | Auto-post Welcome Loom links to private channels | [Install](https://claude.com/plugins) |
| PandaDoc API | REST API | Check agreement signature status directly | [Install](https://claude.com/connectors) |

---

## Marketplace Links

- **Plugins:** https://claude.com/plugins
- **Connectors:** https://claude.com/connectors
- **MCP Servers:** https://github.com/modelcontextprotocol/servers

---

## Setup Instructions

### First-Time Setup

1. Install the Slack MCP server — this is the #1 priority, enables 80% of functionality
2. Configure AirTable API key — enables student tracking and reporting
3. Add SamCart API credentials — enables payment monitoring
4. Connect Fathom API — enables automatic post-call summaries
5. Tell your coworker "check integrations" to verify everything works

### Without Integrations (Fallback Mode)

Your coworker still works without connectors — it just produces checklists and drafts instead of pulling live data:
- **No Slack:** Drafts messages for you to copy-paste
- **No AirTable:** Asks you to look up student status manually
- **No SamCart:** Asks you to cross-reference payments manually
- **No Fathom:** Asks you to paste call notes or transcript

### When Your Coworker Asks for Access

- **"I need Slack access to pull channel data"** → Install the Slack MCP server
- **"I can't reach AirTable"** → Check API key in environment variables
- **If setup isn't possible right now** → Coworker falls back to checklists

---

## Integration Status

| Integration | Status | Last Verified |
|------------|--------|--------------|
| Slack API | Not Set Up | - |
| AirTable API | Not Set Up | - |
| SamCart API | Not Set Up | - |
| Fathom API | Not Set Up | - |
| Google Drive API | Not Set Up | - |
| Calendly API | Not Set Up | - |
