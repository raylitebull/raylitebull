# Ray

Building software across mobile systems, applied algorithms, and autonomous AI agents.

Mostly interested in local-first architecture, mathematical modeling, and making complex systems feel simple to use.

---

## 🚀 [MacroPhase](https://github.com/MacroPhase/App)

**Local-first nutrition tracking with adaptive energy expenditure modeling, AI coaching, and agent integrations.**

[Website](https://macrophase.app) · [Source Code](https://github.com/MacroPhase/App)

A native Android application built from scratch around a custom **Kalman filter-based state-space model** that estimates energy expenditure from weight and nutrition data rather than relying on static TDEE formulas.

What started as a nutrition tracker has grown into a larger system spanning mobile, backend infrastructure, AI agents, and evaluation tooling.

**Under the hood:**

- **Adaptive expenditure engine:** Custom state-space modeling with Kalman filtering, RTS smoothing, and trend estimation to account for noisy weight measurements and changes in energy balance.
- **Local-first architecture:** Kotlin, Jetpack Compose, Room/SQLite, and reactive StateFlows. Core tracking works entirely offline, with optional cloud synchronization.
- **Nutrition tracking:** Food databases, natural-language logging, body composition history, adaptive targets, and a native Compose UI with custom animations and 3D visualizations.
- **Phase Coach:** Integrated AI assistant with access to nutrition history, progress metrics, and application tools.
- **Agent infrastructure:** Ktor-based MCP server and REST API, plus a standalone `mp` CLI for food logging, weight tracking, trend inspection, and external agent workflows.
- **Phase Tasks:** Scheduled reminders and AI-generated nutrition reviews, configurable from the app, web, or connected agents.

### 🧪 MacroBench

A custom LLM evaluation harness built with **Inspect AI** to test how reliably language and vision models interact with real nutrition-tracking workflows.

Covers tool calling, structured food logging, multimodal interpretation, multi-turn interactions, and database state verification.

Built to answer a practical question: *can an AI agent actually use the software correctly, not just describe how it would?*

**Stack:** Kotlin · Jetpack Compose · Room · Ktor · PostgreSQL · Python · MCP · Inspect AI

---

## 🛠️ Other Projects

### [Le Chonk Crafter](https://github.com/raylitebull/le-chonk-crafter)

An autonomous agent harness that lets **Mistral Large 4** play the Crafter survival benchmark through multimodal vision and iterative tool execution.

Implements persistent scratchpad memory, state diffing, deterministic replay, and long-horizon action planning.

**43.7%+ Crafter score** against a ~50% human reference.

`Python` `Multimodal AI` `Agent Harnesses`

---

## 🔭 In Development

### 🎵 Aurea Music

A cross-platform music client combining **Spotify, Tidal, Navidrome/Subsonic, and local libraries** into a single player.

Built with Flutter for desktop and mobile, with a focus on library management, source integration, and a clean listening experience.

`Flutter` `Dart` `Music APIs`

---

## Tech

**Mobile & Frontend:** Kotlin, Jetpack Compose, Flutter, Dart, TypeScript, Three.js

**Backend & Data:** Ktor, Python, PostgreSQL, Room, SQLite, REST

**AI & Algorithms:** State-Space Models, Kalman Filtering, MCP, Inspect AI, Multimodal Agents
