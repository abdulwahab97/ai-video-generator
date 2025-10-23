# 🎬 AI Video Generator

Conversational AI platform that turns natural-language ideas into fully generated videos — powered by FastAPI, OpenAI, and FFmpeg.

---

## 🚀 Overview

**AI Video Generator** is a conversational platform where users can chat with an AI agent to brainstorm, script, and instantly generate video content.  
It bridges creativity and automation — combining **LLMs** for ideation with **FFmpeg** pipelines for real-time video synthesis.

**Core goal:** empower marketers, educators, and creators to go from *idea → video* in a single chat flow.

---

## 🧠 Key Features

- **Chat-based ideation** — Users converse with an AI to co-create video ideas and scene breakdowns  
- **Automatic video rendering** — Scenes are stitched using FFmpeg from selected assets  
- **Segment-level editing** — Modify, reorder, or regenerate individual scenes on the fly  
- **Real-time collaboration** — Built-in WebSocket layer for multi-user editing sessions  
- **Future Roadmap:**  
  - YouTube auto-upload integration  
  - Ad campaign and analytics dashboard  
  - Multilingual content generation

---

## 🏗️ Tech Stack

| Layer | Tools / Frameworks |
|-------|--------------------|
| **Backend** | FastAPI, OpenAI API, Celery |
| **Frontend** | React (Next.js planned) |
| **Media Processing** | FFmpeg |
| **Database** | PostgreSQL |
| **Deployment** | Docker, Railway (or AWS/GCP ready) |

---

## 🧩 Architecture Snapshot

User → Chat Interface → LangChain Pipeline → Video Segment Generator → FFmpeg Renderer → Output Preview

---

## 🎥 Demo

> [Watch the live demo](https://drive.google.com/file/d/1KXpaHQLeq0IA5panG_2vsKjr7sE6Hg-x/view?usp=drive_link)


---

## 🧑‍💼 Role & Contributions

**Role:** Product Manager  
- Defined product vision and MVP milestones  
- Collaborated with backend and AI engineers to design chat-to-video pipeline  
- Validated architecture (FastAPI + FFmpeg + OpenAI integration)  
- Managed end-to-end delivery from user story to demo-ready prototype  

---

## 📈 Impact

- Reduced video generation time from minutes to **< 20 seconds**  
- Introduced a reusable prompt-to-media pipeline architecture  
- Laid groundwork for future integrations (YouTube API, analytics dashboards)

---

## 🧰 Installation (For Developers)

```bash
git clone https://github.com/abdulwahab97/ai-video-generator.git
cd ai-video-generator
pip install -r requirements.txt
uvicorn video_generator_ai.asgi:application --reload
