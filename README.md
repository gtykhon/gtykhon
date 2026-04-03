# Grisha Tykhonovskyi

Software & data engineer. I build AI-powered tools, automation pipelines, and data systems â€” mostly with Python, and mostly things I actually use myself.

---

## Projects

### ðŸ¤– [ai-file-agent](https://github.com/gtykhon/ai-file-agent)
Full-stack autonomous coding assistant. Natural language in â†’ real file operations out, driven by a Finite State Machine with explicit state transitions. Runs locally with Ollama, falls back to Claude. React web UI with real-time WebSocket streaming, git integration, three-tier permission system, and a two-stage code quality gate.

`Python` `FastAPI` `React` `Ollama` `Anthropic Claude` `SQLite` `WebSocket`

---

### âš¡ [simple-file-agent](https://github.com/gtykhon/simple-file-agent)
Minimal, self-contained version of the file agent â€” focused on the core architecture. Demonstrates the FSM pipeline (classify â†’ plan â†’ execute â†’ verify â†’ complete), multi-model LLM routing, and the two-stage quality gate in ~600 lines of documented Python.

`Python` `Ollama` `Anthropic Claude` `YAML`

---

### ðŸ“Š lnkdn *(private)*
Multi-source job intelligence platform. Ingests jobs from 6 sources through a 12-gate screening pipeline, scores each job using keyword matching + sentence-transformer cosine similarity, and surfaces results through 3 Streamlit dashboards. 4,156+ jobs in database, ~100/day ingestion rate.

`Python` `FastAPI` `SQLite` `sentence-transformers` `scikit-learn` `Streamlit` `Ollama`

---

### ðŸ‘ï¸ [ai-vision-agent](https://github.com/gtykhon/ai-vision-agent)
Vision-based computer control agent. Captures a screenshot, sends it to a local Ollama vision model, and optionally executes the suggested action via PyAutoGUI. Runs fully locally â€” no cloud APIs required.

`Python` `Ollama` `PyAutoGUI`

---

### ðŸ“¡ [air-traffic-monitor](https://github.com/gtykhon/air-traffic-monitor)
Self-hosted ADS-B monitoring stack. RTL-SDR receiver â†’ readsb decoder â†’ tar1090 live map, with scripts to query OpenSky and adsb.fi APIs and log aircraft within a configurable radius.

`Python` `RTL-SDR` `ADS-B` `OpenSky API`

---

## Stack

**Languages:** Python, JavaScript, SQL, VBA  
**AI/ML:** Anthropic Claude API, Ollama, sentence-transformers, scikit-learn, FastAPI  
**Data:** SQLite, SQLAlchemy, Streamlit, pandas  
**Frontend:** React, Tailwind CSS, WebSocket  
**Tools:** Git, pytest, GitHub Actions (learning)
