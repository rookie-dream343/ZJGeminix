<div align="center">
  <img src="public/icon-128.png" alt="logo"/>
  <h1>GeminiX</h1>
  <h3>Make Your Gemini Experience Truly Yours ✨</h3>
  <p>
    Navigate conversations with an elegant timeline, organize chats with folders, and build your own prompt vault.<br>
    <b>It's the missing power-up for Google Gemini.</b>
  </p>
</div>

---

## ✨ Features

### 🌌 Core (Gemini & AI Studio)

- **📂 Folder Organization**: Organize chats into a two-level folder hierarchy with drag-and-drop support.
  - **Gemini**: Supports **Account Isolation Mode** and **Custom Folder Colors**.
- **💡 Prompt Vault**: Save and reuse prompts across Gemini, AI Studio, and custom websites.
- **☁️ Cloud Sync**: Sync folders and prompts to Google Drive.
- **📐 Formula Copy**: One-click copy for LaTeX and MathML (Word) source codes.

### ✨ Gemini Exclusive

- **📍 Timeline Navigation**: Visual nodes to jump between messages, star key moments, and manage conversation branches.
- **💾 Chat Export**: Export conversations to JSON, Markdown, or PDF with images included.
- **🧜‍♀️ Mermaid Rendering**: Auto-render flowcharts, sequence diagrams, and other Mermaid charts.
- **📝 Markdown Rendering Fix**: Automatically fix broken bold syntax caused by Gemini's injected HTML elements.
- **🍌 NanoBanana**: Lossless watermark removal for Gemini-generated images.
- **🔬 Deep Research**: Extract thinking processes and research links from Deep Research sessions.
- **🛠️ Power Tools**:
  - **Batch Delete**: Bulk delete conversations.
  - **Quote Reply**: Reply with context by selecting text.
  - **Tab Title Sync**: Auto-sync browser tab titles.
  - **Prevent Auto Scroll**: Intercepts unwanted jumping behavior when hitting enter to send a new prompt.
  - **Input Collapse**: Auto-expandable input area for more reading space.
  - **Default Model**: Set your favorite model as default.
  - **Hide Recent Items**: Hide "Recent" list in the sidebar to reduce distraction.

---

## 📥 Installation

> ⚠️ Note: Prompt Manager is the only feature that supports Gemini for Enterprise.

For **manual installation**, please follow these steps:

### Chrome / Edge / Brave / Opera

1. Clone or download this repository
2. Run `pnpm run build:chrome` (or use the pre-built `dist_chrome` folder)
3. Open your browser and navigate to `chrome://extensions/`
4. Enable "Developer mode" in the top right
5. Click "Load unpacked" and select the `dist_chrome` folder

### Firefox

1. Clone or download this repository
2. Run `pnpm run build:firefox` (or use the pre-built `dist_firefox` folder)
3. Open Firefox and navigate to `about:debugging#/runtime/this-firefox`
4. Click "Load Temporary Add-on" and select `manifest.json` from the `dist_firefox` folder

---

## 🛠️ Development

```bash
# Install dependencies
pnpm install

# Development mode (with auto-reload)
pnpm run dev:chrome   # Chrome & Chromium browsers
pnpm run dev:firefox  # Firefox

# Production builds
pnpm run build:chrome   # Chrome
pnpm run build:firefox  # Firefox
pnpm run build:all      # All browsers
```

---

## 📄 License

GPLv3 License © 2026
