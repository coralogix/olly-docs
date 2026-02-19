---
name: Update Release Notes To Cover Missing Capabilities
overview: ""
todos:
  - id: df470f1e-88e8-4ec6-b55e-dfe77b451778
    content: Add “Also available (foundational)” appendix to Nov 2025 notes
    status: pending
  - id: d4630478-c01d-4c02-a9bd-9ed25d4c8b70
    content: Add chart types + supporting data views note to Oct 2025 notes
    status: pending
  - id: eb6c49b3-52a6-4a2a-90a0-4573f0d2fbb6
    content: Add optional provider choice + file attachments bullets with cautious wording in Nov appendix
    status: pending
---

# Update Release Notes To Cover Missing Capabilities

## Files to update

- [content/olly-release-notes-nov-2025.mdx](/Users/yael.vogel/Documents/olly-docs/content/olly-release-notes-nov-2025.mdx)
- [content/olly-release-notes-oct-2025.mdx](/Users/yael.vogel/Documents/olly-docs/content/olly-release-notes-oct-2025.mdx)

## Approach

- Add a concise “Also available” appendix to November 2025 highlighting foundational capabilities that ship with or predate current RNs but were not listed.
- Add a one-liner in October 2025 under Artifact/Insights to call out supported chart types and supporting data views.

## Edits (concise)

- November 2025: New section “Also available (foundational)” listing:
- Per‑query data source selector in chat
- Personal vs Organizational data sources and sharing (incl. Slack uses one org data source)
- Org/region selection (org switcher, region selector, auto region logic)
- Admin/Member roles and org management
- Team-level enable/disable AI toggle in Coralogix
- Optional file attachments as context (if enabled)
- Optional enterprise model providers (Gemini/Claude) in enterprise environments
- October 2025: After “Artifact Previews” or near “Prompt Templates,” add:
- Supported chart types (line, bar, pie, stacked bar, area, horizontal bar, multi‑series bar) and auto chart selection
- Supporting data views alongside answers (logs table, metrics line chart, spans Gantt, alerts triggering logs)

## Notes

- Keep phrasing high‑level; no dates or GA/preview claims unless certain. Mark provider choice and file attachments as “optional/enterprise” capabilities.