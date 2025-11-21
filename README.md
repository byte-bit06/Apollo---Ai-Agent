# Apollo – AI Desktop Application

Apollo is a desktop-grade AI assistant built with PySide6/QML and modular Python backends. It blends conversational intelligence with real automation: semantic scheduling, screen-aware help, voice control, Spotify integration, and focus tooling.
---
<img width="2109" height="1209" alt="image" src="https://github.com/user-attachments/assets/07f953c3-daac-4a9c-bb89-14f7805ac169" />

## ✨ Features

- **Calendar Dashboard**
  - Google Calendar sync with week view, drag-to-create events, and live summaries.
  - AI task reshuffling keeps `[Task]` events within deadline windows.
  - Natural-language commands such as “schedule a meeting with Mark tomorrow at 2 PM”.

- **Voice-First Assistant**
  - Wake word (“Hey Apollo”), streaming STT, and intent routing.
  - Hands-free Spotify playback, calendar actions, and study-mode toggles.

- **Screen-Aware Intelligence**
  - Continuous screen capture + OCR so Apollo can “see” the desktop context.
  - Attachments support for docs, screenshots, and images.

- **Productivity & Focus Tools**
  - Study mode blocks distracting apps/sites, monitors active windows, and exposes subtle sidebar toggles.
  - Keyboard/mouse automation hooks can execute local tasks when permitted.

- **Customizable AI Brain**
  - Gemini-powered `ai_client.py` with prompt presets (Direct & Concise, Detailed Analysis, Technical Focus, Simple Explanations).
  - Settings panel lets you edit the system prompt, fonts, and integration state (`settings.json` persistence).
  - Local-first routing: simple intents use local managers; complex reasoning goes through the LLM.

- **Polished UI**
  - PySide6/QML front end with themed sidebar, frameless window chrome, drag zone, and responsive layouts.
  - Collapsible navigation, status overlays, and a Notion-inspired dark palette—no white elements in dark mode.

---
