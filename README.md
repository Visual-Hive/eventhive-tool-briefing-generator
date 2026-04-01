# EventHive: Briefing Generator

> Generate professional briefing documents for clients, crew, speakers, sponsors, and exhibitors — automatically populated with live data from your other EventHive tools.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Part of EventHive](https://img.shields.io/badge/Part%20of-EventHive-orange)](https://eventhive.io)

![Screenshot](thumbnail.png)

## Quick Start

### Browser Mode (no install)

1. Download the [latest release](../../releases/latest) or clone this repo
2. Open `tool.html` in any modern browser
3. Start using it — data saves automatically in your browser's localStorage

### Also Available on EventHive

This tool is available on [EventHive](https://eventhive.io) — the free platform for event professionals. On EventHive, your data syncs across devices, integrates with your other tools, and includes AI assistance from Erleah.

---

## Features

- Audience presets (Client, Crew, Speaker, Sponsor, Exhibitor)
- Auto-populates sections from linked EventHive tools
- Select and reorder sections with drag-and-drop
- Live preview before export
- Export to PDF or printable HTML
- Works offline with localStorage data

---

## Customising This Tool

This tool was built using AI-assisted development ("vibe coding").
To customise it for your needs:

1. **Fork this repo** (click the Fork button above)
2. **Clone your fork** locally
3. **Read the [AI Coding Docs](https://github.com/Visual-Hive/ai-coding-docs)** — our methodology for building tools like this with AI
4. **Open in your AI editor** (Claude Code, Cursor, Copilot, etc.)
   - The `.clinerules` file gives your AI assistant context about this tool
   - For Claude Code: run `claude` and the rules load automatically
5. **Modify, test, deploy** — it's just HTML, CSS, and vanilla JS

> **Tip:** The `manifest.json` file defines the configuration schema.
> If you add new configurable options, update it so your tool works with the EventHive platform's config editor.

---

## Data Storage

| Mode | Where | Persistence |
|------|-------|-------------|
| Browser | localStorage (`eventhive_event_{eventSlug}_briefing`) | Until browser data cleared |
| EventHive | Cloud database (PostgreSQL) | Synced across devices |

This tool reads data from [Speaker Programme Manager](https://github.com/Visual-Hive/eventhive-tool-speaker-programme). Ensure the hub tool has data for best results.

---

## Related Tools

- [Speaker Programme Manager](https://github.com/Visual-Hive/eventhive-tool-speaker-programme) — reads speaker profiles for crew briefs
- [Sponsor Deliverables Tracker](https://github.com/Visual-Hive/eventhive-tool-sponsor-deliverables) — reads sponsor info for sponsor briefs
- [Exhibitor Manager](https://github.com/Visual-Hive/eventhive-tool-exhibitor-manager) — reads exhibitor info for exhibitor briefs
- [Event Ops Task & Supplier Tracker](https://github.com/Visual-Hive/eventhive-tool-ops-tracker) — reads supplier info for crew briefs

---

## Contributing

PRs welcome! Please read the [Contributing Guide](https://github.com/Visual-Hive/eventhive-tools/blob/main/CONTRIBUTING.md) first.

---

## License

MIT — free to use, modify, and distribute.

Built by [Visual Hive](https://visualhive.io) as part of the [EventHive](https://eventhive.io) open-source toolkit.
