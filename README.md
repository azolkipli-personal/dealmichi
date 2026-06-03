# BerKanban PWA 🗂️

Fully offline Kanban board for deal pipeline management. Runs on Android, tablet, desktop — no server needed.

## Install on Android

1. Open **`index.html`** in Chrome
2. Tap the menu ⋮ → **Add to Home Screen**
3. BerKanban appears as an app with its own icon

Once installed, works fully offline.

## Usage

| Action | How |
|--------|-----|
| **Add deal** | Tap ＋ New Deal |
| **Edit deal** | Tap any card |
| **Move between columns** | Drag & drop (desktop) or double-tap (mobile cycles through statuses) |
| **Search** | Type in search bar |
| **Export backup** | Tap 📤 Export → saves `.json` |
| **Import backup** | Tap 📥 Import → select `.json` file |
| **Toggle theme** | Tap 🌓 |

## Columns

- 🔄 **Active** — deals in progress
- 📈 **Closing** — near closure
- ✅ **Won** — closed won
- ❌ **Lost** — closed lost

## Data

All data stored locally in your browser's IndexedDB. Export regularly for backup.

## Development

No build tools needed. Just serve with any static server:

```bash
python3 -m http.server 8080
# or
npx serve .
```
