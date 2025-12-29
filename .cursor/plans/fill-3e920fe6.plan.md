<!-- 3e920fe6-3f26-430a-a0cf-4b22df8f0d21 159d1f1b-b66f-4671-a541-0c50e809d49b -->
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

### To-dos

- [ ] Add “Also available (foundational)” appendix to Nov 2025 notes
- [ ] Add chart types + supporting data views note to Oct 2025 notes
- [ ] Add optional provider choice + file attachments bullets with cautious wording in Nov appendix