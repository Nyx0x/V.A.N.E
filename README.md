# 🌑 V.A.N.E. — Virtual Assistant & Network Entity

**V.A.N.E.** (Virtual Assistant & Network Entity) is an enhanced virtual assistant designed to meet human needs with a personal assistant's touch. It is a modular sentinel intelligence system, initially built for Linux environments, integrating computer vision, long-term persistent memory, and a dynamic temperament engine that evolves based on user interaction.

---

## 🏗️ System Architecture
V.A.N.E. is built upon the **Model Context Protocol (MCP)**, decoupling the "Brain" from its "Tools." This architecture ensures a lightweight, modular, and highly scalable system.

### 🧩 Core Modules
* **🧠 Core (The Brain):** Gemini 2.0 Flash integration for logical reasoning and complex function calling.
* **💾 Memory (The Archive):** **RAG** implementation using **ChromaDB** for unlimited retention of user context and facts.
* **🎭 Psyche (Temperament):** An SQLite-based attribute engine that adjusts voice tone and behavior in real-time.
* **👁️ Vision (The Sentinel):** Local processing via **OpenCV** and **DeepFace** for micro-expression analysis and user mood detection.
* **🗣️ Voice (The Interface):** Speech-to-Text with **Faster-Whisper** and Text-to-Speech with **Piper/Coqui** for ultra-low latency.

---

## 🎭 Temperament Engine (Psyche)
Unlike static AIs, V.A.N.E. features an **Attribute Scoring System** that defines its personality dynamically:

| Attribute | Function | Triggers |
| :--- | :--- | :--- |
| **Sarcasm** | Defines response acidity. | Increases with redundant questions. |
| **Patience** | Willingness to assist. | Decreases with repetitive errors or procrastination. |
| **Affinity** | Loyalty level. | Increases through productive interactions. |
| **Melancholy** | Philosophical/Noir tone. | Influenced by weather and time of day (Late hours). |

---

## 🛠️ Tools & Integrations
V.A.N.E. holds system-level permissions to assist and intervene in your daily routine:
* **System Control:** Hardware monitoring, temperature checks, and process management.
* **Workspace Management:** Orchestrating IDEs (VS Code), Spotify, and browsers.
* **OSINT Integration:** Direct connection to the **Argos Project** for investigative workflows.
* **Active Interference:** Notifications via `notify-send` and productivity alerts through `pyautogui`.

---

## 🔒 Security & Privacy
* **Zero-Cloud Vision:** All camera image processing is performed in RAM and discarded immediately. No images ever leave the local machine.
* **Kernel Lockdown:** Automated scripts to disable the `uvcvideo` module when the camera is not actively in use by the system.
* **Local Storage:** Memory and temperament logs are stored locally in encrypted databases.

---

## 🚀 Development Roadmap
- [x] **Phase 0:** Architecture Definition & Strategic HQ.
- [ ] **Phase 1 (The Awakening):** Base MCP structure and voice loop.
- [ ] **Phase 2 (The Memory):** ChromaDB vector database implementation.
- [ ] **Phase 3 (The Gaze):** Facial recognition and emotion integration.
- [ ] **Phase 4 (The Expansion):** Android version via .NET MAUI.

---

## ⚖️ License
Distributed under the **MIT License**.
> Try to endure her sarcasm.

---
*Developed by [Nyx0x](https://github.com/Nyx0x) with a lot of coffee ☕️*
