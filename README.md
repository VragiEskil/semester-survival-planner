# 📚 Semester Survival Planner (Track 2: Agentic Solution)

> **"One Prompt → One Goal → End-to-End Execution"**

## 🚀 Overview
The **Semester Survival Planner** is an autonomous multi-agent assistant built on Tencent WorkBuddy designed to solve a universal student pain point: decoding complex course syllabi, mapping out dense semesters, and avoiding high-stress "red-zone" weeks where multiple major deadlines collide.

---

## 🎯 The Problem & Value Proposition
* **The Problem:** University students juggle 5+ concurrent courses with messy, unstructured outlines. Manually parsing dates leads to missed deadlines and massive workload spikes.
* **The Solution:** A single master prompt ingests all course outlines, automatically parses every grading item and due date, runs an overlap clash-detection algorithm, and compiles production-ready operational files.
* **Value Saved:** Eliminates hours of administrative planning and prevents burnout during crunch weeks.

---

## ⚙️ How the Agentic Workflow Works
Instead of manual micro-prompting, the WorkBuddy agent executes an autonomous multi-step pipeline:
1. **Data Ingestion & Parsing Agent:** Reads all course outlines and extracts assignments, weights, and exam schedules.
2. **Schedule & Risk Analysis Agent:** Maps out a chronological week-by-week timeline and detects overlapping deadline clusters.
3. **Study Prep & Quiz Generator Agent:** Synthesizes weekly outcomes into high-yield summaries and custom practice questions.
4. **Publisher Agent:** Formats and outputs finalized workspace assets (`.xlsx` and `.docx`).

---

## 📂 Repository Contents
* `prompts/master_orchestrator.md`: The system instructions used to orchestrate the agent.
* `sample_data/`: The 5 sample university course outlines (`Course Briefing Slide Sem 1 2026-2027`, `EDISI SEMAK Jadual Pengajaran PBM2072 SEM 1 2026 2027`, `S1 2026-27 Course Schedule TMA3093(1)`, `TMF3963 Course Schedule                      Semester 1 2026-2027`, `TMF3973 Sem 1 2627 WEB APPLICATION DEVELOPMENT`).
* `outputs/`: Production-ready artifacts generated autonomously by WorkBuddy.

---

## 📸 Proof of WorkBuddy Execution
<img width="1657" height="945" alt="Screenshot 2026-10-11 071152" src="https://github.com/user-attachments/assets/4edf92c7-23e1-4963-b231-4981eb868704" />
<img width="1657" height="944" alt="Screenshot 2026-10-11 071855" src="https://github.com/user-attachments/assets/4cf6dc95-f757-484a-85fe-b9ca23aee1d6" />
<img width="1919" height="900" alt="Screenshot 2026-10-11 072246" src="https://github.com/user-attachments/assets/e26fb7f9-4494-40fb-8b67-24470b35345d" />
<img width="1655" height="904" alt="Screenshot 2026-10-11 072512" src="https://github.com/user-attachments/assets/9d55335b-340b-43a0-9ab5-e27e66fd556b" />
<img width="1654" height="947" alt="Screenshot 2026-10-11 072538" src="https://github.com/user-attachments/assets/129c318c-8849-4d75-b6dd-9d7204f58e7d" />

## 📊 Presentation Deck
* 📄 [View Presentation Deck on Google Drive](https://drive.google.com/file/d/1d2-HyRGQpENu2Mk60_izK5VzSkJR-sON/view?usp=sharing)





