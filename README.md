# 📝 SignBridge — Hackathon Blog Post

A fully self-contained HTML blog written by **Anurag Sharma** (SIRT Bhopal) for the **Vision Possible Hackathon** by Stream, documenting the 72-hour journey of building *SignBridge* — a real-time ASL sign language interpreter powered by Vision Agents.

---

## About This Blog

This is a single-file editorial-style blog post (`anurag-visionagent-blog.html`) written as a competition entry for the [$500 blog prize](https://visionagents.ai) offered as part of the Vision Possible Hackathon. It covers the full build story of SignBridge — the motivation, the architecture, the 72-hour timeline, results, and lessons learned — in a human, narrative style.

---

## How to View

Just open the file in any modern browser — no build step, no server, no dependencies.

```bash
open anurag-visionagent-blog.html
# or on Windows
start anurag-visionagent-blog.html
```

All fonts are loaded from Google Fonts (internet connection required for typography).

---

## What's Inside

| Section | Description |
|---|---|
| **Hero** | Title, author byline, and 3 key stats (latency, accuracy, build time) |
| **The Beginning** | The human story — why SignBridge exists |
| **The Framework** | What Vision Agents is and why it was chosen |
| **Build Timeline** | Day-by-day breakdown of the 72-hour hackathon |
| **How It Works** | Architecture walkthrough — YOLO → Gemini → TTS pipeline in plain English |
| **Results** | Metrics dashboard, per-sign accuracy bar charts, latency optimization chart |
| **Comparison Table** | SignBridge vs alternative approaches |
| **5 Lessons** | Key learnings about real-time multimodal AI |
| **What's Next** | Roadmap — ISL support, word-level prediction, bidirectional bridge |
| **Closing** | The moment Rohit heard "Hello" |

---

## Design Highlights

- **Editorial aesthetic** — Playfair Display serif headlines, DM Sans body, cream paper background with noise texture
- **Dark hero section** — subtle grid lines and key project stats
- **SVG architecture diagrams** — inline pipeline visuals, no external images needed
- **Charts** — bar charts for per-sign accuracy, line chart for latency optimization over 72 hours
- **Fully responsive** — readable on mobile and desktop
- **Zero dependencies** — one `.html` file, completely self-contained

---

## Files

```
anurag-visionagent-blog.html   ← the entire blog, single file
README.md                      ← this file
```

---

## Hackathon Context

**Event:** Vision Possible Hackathon — Blog Prize  
**Prize:** $500 for best build story around Vision Agents by Stream  
**Author:** Anurag Sharma · CS Undergrad · SIRT Bhopal  
**Project covered:** SignBridge — real-time ASL interpreter  
**Tags:** `#VisionPossible` `#VisionAgents` `#BuildInPublic` `#Accessibility`

---

## Built With

- Pure HTML + CSS — no frameworks
- [Google Fonts](https://fonts.google.com) — Playfair Display, DM Sans
- Inline SVG for all diagrams and charts
- [Vision Agents by Stream](https://visionagents.ai) — the framework the blog is written about
