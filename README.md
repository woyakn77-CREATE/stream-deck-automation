# One-Button Desk: Stream Deck Automation System

**Live:** https://woyakn77-create.github.io/stream-deck-automation/ · [Back to portfolio](https://woyakn77-create.github.io/Portfolio/)

A 15-key Stream Deck set up as the front panel for daily work. Repeat tasks across Excel, email, screen capture and AI tools are each one labeled button. The rule: everything has a button, and nothing depends on remembering a shortcut.

## Pages
| Page | What's on it |
|---|---|
| Home | Same on every profile: save-and-close, quick capture, live network status, AI-ready keys |
| Excel QA | One-press PASS / FAIL / REVIEW / VOID status macros with color, timestamp and audit log |
| Email | Triage flags (today, tomorrow, waiting, cleared, archive) and view controls |
| Capture | Six screen-capture presets: region, full screen, scrolling, video, text grab, panorama |
| AI | Ten prompt templates (five for Claude, five for Copilot) typed by AutoHotkey |

## Behind the buttons
- **Excel VBA framework:** every macro validates the selection, acts, logs to a hidden sheet and gives feedback.
- **AutoHotkey v2:** system-wide prompt templates and save-and-close.
- **Power Automate:** button-triggered flows on a lookup table instead of nested switches.
- **Icon generator:** Python + Pillow, 160 icons in 15 packs, rendered at 4x and downscaled.
- **MCP:** Claude connected to the deck through Elgato's MCP server, so AI-ready keys can be triggered in plain language.
- **Hotkey conflict audit:** all 26 Ctrl+Shift+letter combinations rated for conflict risk before rollout.

Keys marked "planned" on the page are designed but not built yet. Layouts and labels are generic.

## Files
`index.html`: interactive demo, one self-contained file.
