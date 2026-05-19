# 🎨 CodeStudio IDE

<div align="center">

![CodeStudio IDE](https://img.shields.io/badge/CodeStudio-IDE-6366f1?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Version](https://img.shields.io/badge/Version-989.34.6-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Single File](https://img.shields.io/badge/Single-HTML%20File-orange?style=for-the-badge)

**A powerful, all-in-one browser-based IDE with real-time collaboration — no installation required.**

[🚀 Live Demo](https://planetb00m.github.io/CodeStudio-IDE/CodeStudio_IDE.html) · [📖 Documentation](#features) · [🐛 Report Bug](https://github.com/asser20102040-png/CodeStudio-IDE/issues)

</div>

---

## ✨ Overview

CodeStudio IDE is a fully-featured development environment built entirely as a **single HTML file**. It supports multiple languages, real-time collaboration, voice & video huddle, an AI assistant, a community Hub, and cloud sync — all with zero installation and no backend server required.

---

## 🚀 Features

### 🖊️ Editor
- **Syntax Highlighting** — HTML, CSS, JavaScript, TypeScript, Python, Java, C/C++, Markdown, JSON, and more via Prism.js
- **Auto-complete & IntelliSense** — Smart tag, attribute, CSS property, and JS keyword suggestions as you type
- **Auto Close Brackets & Tags** — Automatically closes brackets, quotes, and HTML tags
- **Multi-language Projects** — Web (HTML/CSS/JS), JavaScript, TypeScript, Python, Java, C/C++, Markdown, and Blank
- **Custom File Manager** — Create, rename, delete, and organize files and folders inside each project
- **Split Editor** — Side-by-side view of any two files with real-time sync (`Ctrl+\`)
- **Minimap** — Visual overview panel for quick navigation in large files
- **Code Beautifier** — One-click formatting for HTML, CSS, and JS (`Ctrl+Shift+F`)
- **Find & Replace** — Full search and replace with match highlighting (`Ctrl+H`)
- **Comment Toggle** — Comment/uncomment lines instantly (`Ctrl+/`)
- **Breakpoints** — Click gutter to set/clear breakpoints with visual indicators
- **Word Count & Stats** — Live line, word, and character count in the status bar
- **Font Size Control** — Adjust editor font size with `Ctrl+=` / `Ctrl+−`
- **Word Wrap Toggle** — Toggle line wrapping on/off
- **Focus Mode** — Distraction-free full-screen editing (`F11`)

### 👁️ Preview
- **Live Preview** — Real-time HTML/CSS/JS preview as you type
- **Adjustable Preview Delay** — Control how fast the preview refreshes
- **Fullscreen Preview** — Expand preview to fill the screen
- **Responsive Breakpoints Tool** — Preview at common device widths
- **Console Panel** — View `console.log`, errors, and warnings inline with the editor

### 📁 Project Management
- **Multi-Project Workspace** — Unlimited projects saved locally in `localStorage`
- **Language Templates** — Starter files auto-generated for each project type
- **ZIP Export & Import** — Export any project as a `.zip`; import ZIP files or single HTML files
- **Google Drive Sync** — Push and pull full project workspaces to/from Google Drive
- **Auto Save** — Automatically saves on every keystroke (toggleable)
- **Diff Viewer** — Compare any two snapshots of your code side-by-side (`Ctrl+D`)

### 🤝 Live Collaboration
- **Real-time Co-editing** — Multiple users edit the same code simultaneously (powered by Yjs CRDT)
- **Live Cursors** — See every collaborator's cursor and selection in real-time
- **Public Room Browser** — Discover and join public coding rooms (powered by Firebase)
- **Private Rooms** — Password-protected rooms for your team
- **Role-based Permissions** — Host / Editor / Viewer roles with granular controls
- **Join Request System** — Host approves or denies incoming join requests
- **Follow Me Mode** — Lock all participants to the host's cursor and scroll position
- **Live Leaderboard** — Track code contributions per collaborator in real-time
- **File Presence Indicators** — See which file each collaborator is currently editing

### 🎙️ Voice & Video Huddle
- **Voice Huddle** — In-browser audio calls with no external app needed
- **Video Huddle** — Face-to-face video with collaborators
- **Screen Share** — Share your screen during a session
- **Camera & Mic Toggles** — Turn camera/microphone on or off at any time
- **Participant Count** — Live count of active huddle participants

### 💬 Communication
- **Collab Chat** — Real-time group chat during collaboration sessions
- **Direct Messages (DM)** — Private one-on-one messaging between collaborators
- **System Notifications** — Join/leave events and room status messages
- **Whiteboard** — Collaborative freehand drawing canvas with pen, marker, highlighter, eraser, shapes, and text tools — synced live across all collaborators

### 🏪 CodeStudio Hub
- **Discover Feed** — Browse projects published by the community
- **Publish Projects** — Share your project publicly with a title, description, tags, and cover image
- **Star & Comment** — Star projects you love and leave comments
- **Follow Developers** — Follow other users and see their activity in your personal feed
- **Notifications** — Get notified when someone stars, comments on, or follows you
- **Developer Profiles** — Public profile pages showing projects, followers, following, stars, and downloads

### 🎨 Themes & Customization
- **Built-in Dark Themes** — Default Dark, Dracula, Oceanic, Monokai, Midnight, Nord, Synthwave
- **Built-in Light Themes** — Light, Snow, Sakura, Latte, Mint
- **Custom Theme Engine** — Full color customization: background, sidebar, toolbar, text, accent, success, danger, warning, border, scrollbar, and all syntax token colors
- **Theme Import / Export** — Share your custom themes as `.json` files
- **Persistent Themes** — Your theme choice is saved across sessions

### 🤖 AI Assistant (Groq)
- **AI Chat Panel** — Ask the AI to write, fix, explain, or refactor your code (`Ctrl+G`)
- **Fix Selected Code** — Highlight broken code and fix it in one click (`Alt+E`)
- **Explain Selected Code** — Get a plain-English explanation of any selection
- **Multiple Models** — Choose between Llama 3.3 70B, Llama 3.1, Llama 8B, Gemma 2, and more
- **Usage Stats** — Track your AI token usage per session
- **Attach Files** — Send files directly to the AI chat for context

### 🧰 Dev Tools & Toolbox
- **Smart Snippets** — Quick-insert templates for HTML5, Flexbox, Grid, Tables, Forms, Fetch, and more
- **Libraries Panel** — One-click CDN injection for Bootstrap, Tailwind, React, Vue, jQuery, D3.js, and more
- **Responsive Breakpoints Inserter** — Auto-insert standard CSS media queries
- **Remove Comments Tool** — Strip all comments from the current file in one click
- **Code Statistics** — Total lines, words, and characters across all projects

### 👤 User Accounts
- **Google Sign-In** — One-click login via Firebase Auth
- **Profile Pictures** — Your Google avatar appears everywhere in the IDE and Hub
- **Auto Account Sync** — Projects sync to your account across devices
- **Guest Mode** — Full IDE access without signing in

### ⚙️ Settings & Productivity
- **PWA — Install as App** — Install CodeStudio as a desktop/mobile app via the browser
- **Offline Support** — All editing, preview, and local saving works without internet
- **Session Stats** — Live count of keystrokes, words typed, and time in session
- **All-time Statistics** — Cumulative coding stats dashboard
- **Learning Center** — Built-in HTML, CSS, and JS tutorials with interactive examples
- **FAQ Panel** — Searchable help covering all major features

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Vanilla HTML / CSS / JS** | Core IDE — zero frameworks |
| **Prism.js** | Syntax highlighting |
| **Yjs (CRDT)** | Real-time collaborative editing |
| **PeerJS (WebRTC)** | P2P voice, video, screen share, and data |
| **Firebase Auth** | Google Sign-In |
| **Firebase Realtime DB** | Public room discovery & Hub |
| **Google Drive API** | Cloud project storage |
| **Groq AI API** | AI code assistant |

---

## 🚀 Getting Started

### Option 1 — Use Online
```
https://planetb00m.github.io/CodeStudio-IDE/CodeStudio_IDE.html
```

### Option 2 — Run Locally
1. Download `CodeStudio_IDE.html`
2. Open it in any modern browser
3. Start coding — everything works instantly

> ⚠️ Google Sign-In, Public Rooms, and Hub features require an internet connection.

---

## 🤝 Collaboration Guide

### Hosting a Room
1. Click the **collab icon** in the sidebar
2. Click **Host a Room**
3. Set a room name, optional password, and visibility (public/private)
4. Share your **Room ID** with collaborators

### Joining a Room
1. Click the **collab icon** in the sidebar
2. Browse **Public Rooms** or paste a Room ID directly
3. Wait for the host to approve your join request

### Voice & Video Huddle
1. Click **Huddle** at the bottom of the screen
2. Choose **Voice** or **Video**
3. All room participants can join the same huddle

---

## 🎨 Theme Customization

1. Click the **theme icon** in the toolbar
2. Select a preset or click **Custom**
3. Adjust any color with the live pickers
4. Click **Export** to save your theme as a `.json` file
5. Click **Import** to load a theme file

---

## 📊 Keyboard Shortcuts

### Editor
| Shortcut | Action |
|---|---|
| `Ctrl + S` | Save / sync project |
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Ctrl + /` | Toggle comment |
| `Ctrl + H` | Find & Replace |
| `Ctrl + Shift + F` | Beautify code |
| `Ctrl + =` | Font size up |
| `Ctrl + −` | Font size down |
| `Tab` | Indent selection |
| `Shift + Tab` | Outdent selection |

### View & Layout
| Shortcut | Action |
|---|---|
| `F11` | Focus Mode |
| `Ctrl + \` | Split editor |
| `Ctrl + B` | Toggle sidebar |
| `Ctrl + T` | Toggle toolbox |
| `Ctrl + P` | Toggle preview |
| `Ctrl + R` | Refresh preview |
| `Ctrl + K` | Keyboard shortcuts |
| `Ctrl + ,` | Open settings |

### Files & Projects
| Shortcut | Action |
|---|---|
| `Ctrl + N` | New project |
| `Ctrl + O` | Open / import file |
| `Ctrl + E` | Export project |
| `Ctrl + 1` | Switch to HTML |
| `Ctrl + 2` | Switch to CSS |
| `Ctrl + 3` | Switch to JS |

### Console & AI
| Shortcut | Action |
|---|---|
| `Ctrl + \`` | Toggle console |
| `Ctrl + L` | Clear console |
| `Ctrl + Enter` | Run / refresh preview |
| `Ctrl + G` | Open AI chat |
| `Alt + E` | Fix selected code (AI) |
| `Ctrl + D` | Open Diff Viewer |

---

## 🌍 Browser Support

| Browser | Support |
|---|---|
| Chrome | ✅ Full |
| Edge | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |

---

## 📄 License

```
Copyright (c) 2025 planetb00m. All Rights Reserved.

This software and its source code are proprietary and confidential.
Unauthorized copying, distribution, modification, or use of this
software, in whole or in part, is strictly prohibited without
prior written permission from the author.
```

---

<div align="center">

Made with ❤️ by **planetb00m**

⭐ Star this repo if you find it useful!

</div>
