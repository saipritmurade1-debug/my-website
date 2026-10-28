# StudyOS | Unified Academic Copilot & Retention Engine

> **Problem Solved:** *"The Academic Fragmentation & 'Cram-and-Dump' Cycle"* — eliminating scattered dead-zones, cognitive overload, and passive 11th-hour cramming by converting raw course syllabi into an intelligent, prioritized daily flight plan.

---

## 🚀 Website Overview & Live Demo

The website code is fully self-contained in [index.html](file:///C:/Users/JSPMUNI-SL-I-32/.gemini/antigravity/scratch/study-os-web/index.html).

You can open this file in any web browser (Chrome, Edge, Firefox, Safari) immediately without needing to run `npm install` or configure a database server.

---

## 🛠️ The 5 Core Modules of the Website

### 1. Daily Flight Plan (Command Center)
* **Study Debt Index:** Measures how many hours behind the student is from their optimal study curve so they never get hit with sudden surprises before midterms.
* **Prioritized Micro-Study Sessions:** Calculates daily study tasks ranked by upcoming exam weight (e.g., 35% midterm) and forgetting curves.
* **Deadlines Radar:** Real-time visibility on labs, quizzes, and exams color-coded by grade impact.

### 2. Smart Syllabus Ingestion (AI Extractor)
* Drag-and-drop course PDFs, slide decks, or syllabus URLs.
* Uses document extraction to detect:
  * Grade distribution formulas (e.g., Midterms 30%, Quizzes 20%, Finals 50%).
  * Milestones and assignment due dates.
  * Chapter learning objectives.

### 3. Active Recall & Quiz Studio
* Replaces passive re-reading with **3D Interactive Spaced-Repetition Flashcards** (Leitner system).
* **AI Mock Exam Generator:** Generates exam-style multiple-choice questions grounded directly in lecture slides with immediate feedback and citations.

### 4. Course Knowledge Vault
* Centralized hub organizing enrolled subjects (`CS 301`, `MATH 220`, `AI 402`).
* Tracks syllabus coverage percentage, target grades, and active question banks.

### 5. Deep Focus Chamber (Pomodoro Integration)
* Integrated 25-minute focus timer that logs completed sprints directly to syllabus tasks to reduce study debt in real time.

---

## 💻 Recommended Tech Stack for Production

If you wish to scale this prototype into a full-scale web application:

* **Frontend:** Next.js (React 19), Tailwind CSS, Lucide Icons, Framer Motion
* **Backend:** FastAPI (Python) or Node.js / Express
* **Document Parsing & AI:** LangChain / LlamaIndex + Gemini 1.5 Pro / Flash (for PDF parsing, table extraction, and flashcard generation)
* **Database & Vector Store:** PostgreSQL (Supabase) + pgvector (for semantic search across lecture notes)
* **Integrations:** Canvas LMS API, Google Classroom API, Moodle LTI
