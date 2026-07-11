# Local Folder File Explorer

A single-file, browser-based file explorer for viewing local folders. No install, no server — just open `index.html` in your browser.

## Features

- **Open a local folder** using the File System Access API (no upload, files never leave your machine)
- **Tree or List view** — toggle the sidebar between a nested folder tree and a flat, searchable file list
- **Tabs** — open multiple files at once, close one/others/all, cycle with `Ctrl+Tab`
- **Preview / Code toggle** — view HTML/text files rendered, or as syntax-highlighted code (Monaco Editor)
- **Search** — instantly filter files by name (`/` to focus)
- **Zoom & fullscreen** for the preview pane
- **Resizable sidebar**
- **Highlighting** for 150+ languages (Monaco Editor)

## Requirements

- Chrome or Edge (or another browser supporting the [File System Access API](https://developer.mozilla.org/en-US/docs/Web/API/File_System_Access_API))
- An internet connection on first load (Tailwind, DaisyUI, and Monaco Editor are loaded from CDN)

## Usage

1. Open `index.html` in your browser.
2. Click **Open Folder** and pick a directory.
3. Click any file in the sidebar to open it in a new tab.
4. Switch between **Tree** / **List** view using the toggle above the file list.

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `/` | Focus search |
| `↑` / `↓` | Navigate files |
| `F` | Toggle fullscreen |
| `Ctrl/Cmd + W` | Close active tab |
| `Ctrl + Tab` | Next tab (`Shift` for previous) |
| `Esc` | Exit search |

## Notes

- All file access is local — the app never sends your files anywhere.
- Everything lives in one `index.html` file, so it's easy to copy or share.