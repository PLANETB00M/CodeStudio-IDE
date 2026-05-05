# 🎨 CodeStudio IDE

<div align="center">

![CodeStudio IDE](https://img.shields.io/badge/CodeStudio-IDE-6366f1?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Version](https://img.shields.io/badge/Version-956.28.1-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Single File](https://img.shields.io/badge/Single-HTML%20File-orange?style=for-the-badge)

**A powerful, all-in-one browser-based IDE with real-time collaboration — no installation required.**

[🚀 Live Demo](https://planetb00m.github.io/CodeStudio-IDE/CodeStudio_IDE.html) · [📖 Documentation](#features) · [🐛 Report Bug](https://github.com/asser20102040-png/CodeStudio-IDE/issues)

</div>

---

## ✨ Overview

CodeStudio IDE is a fully-featured web development environment built entirely as a **single HTML file**. It delivers a rich coding experience with real-time collaboration, voice & video huddle, AI-powered tools, and cloud sync — all without any installation or backend server.

---

## 🚀 Features

### 🖊️ Editor
- **Syntax Highlighting** — HTML, CSS, and JavaScript with full color coding
- **Auto-complete & IntelliSense** — Smart suggestions as you type
- **Auto Close Brackets & Tags** — Automatically closes brackets and HTML tags
- **Multi-tab Editing** — Switch between HTML, CSS, and JS files instantly
- **Font Size Control** — Adjustable editor font size
- **Word Wrap Toggle** — Toggle line wrapping on/off
- **Code Folding** — Collapse and expand code blocks
- **Mini Map** — Navigate large files with ease
- **Error Detection** — Real-time error highlighting in the gutter
- **Find & Replace** — Powerful search and replace tool
- **Keyboard Shortcuts** — Full set of VS Code-like shortcuts

### 👁️ Preview
- **Live Preview** — Real-time HTML/CSS/JS preview as you type
- **Split / Full / Desktop modes** — Multiple layout options
- **Adjustable Preview Delay** — Control how fast the preview updates
- **Console Output** — View JavaScript logs and errors inline

### 📁 Project Management
- **Multi-Project Workspace** — Manage multiple projects simultaneously
- **File Manager** — Create, rename, delete files and folders
- **ZIP Export** — Export your entire project as a ZIP file
- **Import Projects** — Import ZIP files directly into the IDE
- **Google Drive Sync** — Save and load projects from Google Drive
- **Auto Save** — Automatic project saving to localStorage

### 🤝 Live Collaboration
- **Real-time Co-editing** — Multiple users edit the same code simultaneously (powered by Yjs CRDT)
- **Live Cursors** — See your collaborators' cursors in real-time
- **Public Room Browser** — Discover and join public coding rooms (powered by Firebase)
- **Private Rooms** — Password-protected rooms for your team
- **Role-based Permissions** — Host / Editor / Viewer roles with granular controls
- **Join Request System** — Host approves or denies join requests
- **Follow Me Mode** — Collaborators follow the host's cursor and scroll position
- **Live Leaderboard** — Track who's contributing the most code in real-time
- **File Presence Indicators** — See which file each collaborator is editing

### 🎙️ Voice & Video Huddle
- **Voice Huddle** — Crystal-clear audio calls directly in the IDE
- **Video Huddle** — Face-to-face video calls with your collaborators
- **Screen Share** — Share your screen during a session
- **Camera Toggle** — Turn camera on/off anytime
- **Mic Toggle** — Mute/unmute with one click
- **Participant Count** — Live count of huddle participants

### 💬 Communication
- **Collab Chat** — Real-time group chat during collaboration sessions
- **Direct Messages (DM)** — Private one-on-one messaging between collaborators
- **System Notifications** — Join/leave notifications and system messages
- **Reaction Support** — Express yourself during sessions

### 🎨 Themes & Customization
- **Built-in Themes** — Dark, Light, Monokai, Dracula, Nord, Solarized, and more
- **Custom Theme Engine** — Full color customization with live preview
  - Background, Surface, Toolbar colors
  - Text, Dim Text colors
  - Accent, Success, Danger, Warning colors
  - Border, Scrollbar colors
  - Syntax highlighting colors (Keywords, Strings, Functions, etc.)
- **Theme Import/Export** — Share your custom themes
- **Persistent Themes** — Your theme is saved and restored automatically

### 🤖 AI Tools
- **AI Code Analysis** — Powered by Qroq AI to review and suggest improvements
- **Smart Snippets** — Quick-insert common HTML, CSS, and JS patterns
- **Libraries Panel** — One-click CDN library injection (Bootstrap, Tailwind, React, Vue, etc.)

### 👤 User Accounts
- **Google Sign-In** — One-click login with your Google account (powered by Firebase Auth)
- **Profile Pictures** — Your Google profile photo appears everywhere in the IDE
- **Persistent Identity** — Your name and avatar sync across all devices
- **Guest Mode** — Use the IDE without signing in

### 🎓 Learning Center
- **Built-in Tutorials** — HTML, CSS, JavaScript learning resources
- **Quick Reference** — Cheat sheets for common patterns
- **Interactive Examples** — Learn by doing

### ⚡ Productivity
- **Snippet Toolbar** — Quick-insert HTML5, DIV, BUTTON, TABLE, FLEX, GRID, FETCH templates
- **Command Shortcuts** — Ctrl+S to save, Ctrl+Z to undo, and more
- **Session Stats** — Track words typed, time spent, and lines written
- **All-time Statistics** — Long-term coding stats dashboard

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Vanilla HTML/CSS/JS** | Core IDE — zero frameworks |
| **Yjs (CRDT)** | Real-time collaborative editing |
| **PeerJS (WebRTC)** | P2P voice, video, and data |
| **Firebase Auth** | Google Sign-In |
| **Firebase Realtime DB** | Public room discovery |
| **Google Drive API** | Cloud project storage |
| **Claude AI API** | AI code analysis |

---

## 🚀 Getting Started

### Option 1 — Use Online
Visit the live demo directly:
```
https://asser20102040-png.github.io/CodeStudio-IDE/CodeStudio_IDE.html
```

### Option 2 — Run Locally
1. Download `CodeStudio_IDE.html`
2. Open it in any modern browser
3. Start coding!

> ⚠️ Note: Google Sign-In and Public Rooms require an internet connection.

---

## 🤝 Collaboration Guide

### Hosting a Room
1. Click the **collab icon** in the sidebar
2. Click **Host a Room**
3. Set a room name, optional password, and visibility
4. Share your **Room ID** with collaborators

### Joining a Room
1. Click the **collab icon** in the sidebar
2. Click **Browse Public Rooms** or enter a Room ID directly
3. Wait for the host to approve your request

### Voice & Video
1. Click **Huddle** at the bottom of the screen
2. Choose **Voice** or **Video**
3. All participants in the room can join the huddle

---

## 🎨 Theme Customization

1. Click the **theme icon** in the toolbar
2. Select a preset theme or click **Custom**
3. Adjust any color using the color pickers
4. Click **Export** to save your theme as a file
5. Click **Import** to load a theme file

---

## 📊 Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + S` | Save project |
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Ctrl + /` | Toggle comment |
| `Ctrl + F` | Find & Replace |
| `Ctrl + D` | Duplicate line |
| `Tab` | Indent |
| `Shift + Tab` | Outdent |

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

Made with ❤️ by **asser20102040**

⭐ Star this repo if you find it useful!

</div>
