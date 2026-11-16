# Omega Tech Service automations

Scheduled Claude tasks for the business. Each file holds the prompt a task runs.

| Task | Schedule (Pacific) | Uses | Does |
|---|---|---|---|
| [weekly-business-brief.md](weekly-business-brief.md) | Mondays 5:40 AM | QuickBooks, Jobber, Quo, Gmail | Emails the owner a one-page weekly brief. Read-only. |
| [quote-follow-up.md](quote-follow-up.md) | Weekdays 10:46 AM | Jobber, Gmail | Drafts follow-ups for quotes waiting 3+ days. Never sends to customers. |

The tasks need the QuickBooks, Jobber, Quo and Gmail connectors attached
in claude.ai (Scheduled tasks → edit task → Connectors).
