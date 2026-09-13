<p align="center">
  <img src="https://i.ibb.co/Kc3dBBZv/a2555b9b-3169-4fdb-b7e1-fdceedecaf6b.png" width="120" height="120" alt="منصة البكالوريا السورية الذكية Logo" />
</p>

<h1 align="center">منصة البكالوريا السورية الذكية<br><sub>Syrian Baccalaureate Platform</sub></h1>

<p align="center">
  <strong>An enterprise-grade, Arabic-first educational ecosystem and AI-powered study companion built specifically for Syrian General Secondary Certificate (Baccalaureate) students.</strong>
</p>

<p align="center">
  <a href="https://baccalaureate.code-elta6ur.sy/"><img src="https://img.shields.io/badge/Live_Platform-baccalaureate.code--elta6ur.sy-4f46e5?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Platform" /></a>
  <a href="https://www.appcreator24.com/app4181134-v7nscz"><img src="https://img.shields.io/badge/Android_App-Download_APK-059669?style=for-the-badge&logo=android&logoColor=white" alt="Mobile App" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-%5E8.2-777bb4?style=flat-square&logo=php&logoColor=white" alt="PHP Version" />
  <img src="https://img.shields.io/badge/Laravel-12.x-ff2d20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel 12" />
  <img src="https://img.shields.io/badge/TailwindCSS-3.x-38bdf8?style=flat-square&logo=tailwindcss&logoColor=white" alt="TailwindCSS" />
  <img src="https://img.shields.io/badge/Vite-7.x-646cff?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Database-SQLite%20%7C%20MySQL-003b57?style=flat-square&logo=sqlite&logoColor=white" alt="Database" />
  <img src="https://img.shields.io/badge/AI_Engine-Gemini%203.1%20%7C%20Groq%20LLaMA%203.3-8b5cf6?style=flat-square&logo=openai&logoColor=white" alt="AI Engine" />
  <img src="https://img.shields.io/badge/PWA-Ready%20%26%20Offline%20Mode-f59e0b?style=flat-square&logo=pwa&logoColor=white" alt="PWA Ready" />
  <img src="https://img.shields.io/badge/UI-Arabic--First%20%2F%20RTL-10b981?style=flat-square" alt="RTL Support" />
  <img src="https://img.shields.io/badge/License-Proprietary%20%2F%20All%20Rights%20Reserved-gray?style=flat-square" alt="License" />
</p>

---

## 📑 Table of Contents

- [Overview & Mission](#-overview--mission)
- [Core Features](#-core-features)
- [Educational System & Curriculum Structure](#-educational-system--curriculum-structure)
- [Artificial Intelligence & RAG Architecture](#-artificial-intelligence--rag-architecture)
- [Student Journey & Pedagogical Experience](#-student-journey--pedagogical-experience)
- [Admin Panel & Curriculum Quality Control](#-admin-panel--curriculum-quality-control)
- [System Architecture & Design Patterns](#-system-architecture--design-patterns)
- [Tech Stack](#-tech-stack)
- [Project Directory Structure](#-project-directory-structure)
- [Prerequisites & System Requirements](#-prerequisites--system-requirements)
- [Local Installation & Quickstart](#-local-installation--quickstart)
- [Environment Configuration](#-environment-configuration)
- [Database & Seeded Datasets](#-database--seeded-datasets)
- [Scheduled Tasks & Automation](#-scheduled-tasks--automation)
- [Progressive Web App & Mobile Application](#-progressive-web-app--mobile-application)
- [Security Hardening & Protection](#-security-hardening--protection)
- [Production Deployment](#-production-deployment)
- [Automated Testing & Quality Assurance](#-automated-testing--quality-assurance)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [Roadmap](#-roadmap)
- [License](#-license)
- [Author & Credits](#-author--credits)

---

## 🎯 Overview & Mission

**Syrian Baccalaureate Platform (منصة البكالوريا السورية الذكية)** is an academic web application designed specifically for Syrian 12th-grade secondary school students preparing for their national ministerial examinations (*Al-Shahada Al-Thanawiyya Al-Amma*).

### The Challenge
Baccalaureate students in Syria historically grapple with fragmented study resources:
- Ministry textbooks scattered across disparate PDF portals.
- Past ministerial exam sessions and correction rubrics (*Salalem Al-Tashih*) difficult to find and categorize.
- Commercial tutoring requiring prohibitive expenses during challenging economic realities.
- Unfocused study routines lacking personalized diagnostic feedback or systematic revision schedules.

### The Solution
Developed under the **كود التطور (Code El-Ta6ur)** initiative, this platform unites the entire baccalaureate journey into a single platform:
1. **Curriculum-Grounded**: Every lesson, formula, and question corresponds to the official Syrian Ministry of Education curriculum.
2. **Arabic-First & RTL Native**: Engineered from the ground up for right-to-left Arabic typography, scientific terminology, and Syrian mathematical conventions.
3. **AI Study Companion**: An anti-hallucinating AI tutor powered by **Retrieval-Augmented Generation (RAG)**, grounded exclusively in Syrian ministerial textbooks and scoring rubrics.
4. **Active Learning & Spaced Repetition**: Combines continuous quiz diagnostics, automatic mistake logging ("دفتر الأخطاء الذكي"), and flashcards driven by the **SuperMemo SM-2** algorithm.

---

## 🚀 Core Features

### 1. Curriculum Hub & Lesson Viewer
- Organized dual-branch support: **Scientific Branch (`الفرع العلمي`)** and **Literary Branch (`الفرع الأدبي`)**.
- Modular hierarchy: **Branch → Subject → Unit → Lesson → Topics**.
- Comprehensive lesson view incorporating:
  - Official lesson summary and key concepts.
  - Mathematical formulas and physical laws in symbolic notation with international SI units.
  - Common exam pitfalls and traps (*الفخاخ الامتحانية*).
  - Curated educational video lectures.
  - Linked question bank items with instant scoring rubrics.
  - Interactive flashcards.
  - Direct references to official Ministry textbooks.

### 2. Comprehensive Question Bank & Past Ministerial Exams
- Over **2,630 verified ministerial and bank questions** categorized by subject, unit, lesson, difficulty (`easy`, `medium`, `hard`), and exam year.
- **Past Ministerial Exam Archive (`دورات امتحانية`)**:
  - Filterable by academic year and exam session (*الدورة الأولى* / *الدورة الثانية*).
  - Two operating modes:
    - **Study Mode**: Questions accompanied by official answer keys and step-by-step scoring scales.
    - **Timed Exam Simulator**: Exact ministerial exam simulation featuring a 120-minute countdown timer and comprehensive grading.

### 3. Interactive Quiz Engine & Student Progress Tracking
- On-demand custom quizzes per lesson or subject.
- Automated score calculation, percentage accuracy, and time-tracking.
- Dynamic lesson mastery algorithm:
  $$\text{Mastery Score} = \min\left(100, (\text{Accuracy} \times 0.8) + \text{Attempt Weight}\right)$$
- Progress states: `not_started`, `in_progress`, `completed`, and `mastered` (at $\ge 85\%$ mastery).

### 4. Smart Mistake Notebook ("دفتر الأخطاء الذكي")
- Every incorrectly answered question across quizzes and timed exams is automatically captured into the student's personal mistake notebook.
- Students can re-attempt failed questions. Correct answers mark mistakes as mastered and award confidence points.
- Failed re-attempts schedule spaced follow-up review sessions (+2 days).

### 5. Spaced Repetition Flashcards (SuperMemo SM-2)
- Subject-based flashcard decks for definitions, laws, dates, and concepts.
- Full implementation of the **SuperMemo SM-2** spaced repetition algorithm:
  - Student rates recall quality from $0$ (complete blackout) to $5$ (perfect recall).
  - Dynamically recalculates repetition intervals, repetitions count, and the Easiness Factor ($EF \ge 1.3$).
  - Automates daily review decks so memories consolidate before forgetting occurs.

### 6. Study Planner, Exam Countdown & Focus Sessions
- Automatic personalized study schedule calculated from the student's daily study hours and remaining days until the national exam.
- Integrated focus session timer (Pomodoro-style) that logs actual study duration and awards gamification points.
- One-click overdue task rescheduling: automatically re-allocates missed tasks into future daily blocks.

### 7. Official Ministry Textbooks Reader & Downloader
- Direct access to **16 official ministry textbooks**.
- Integrated in-browser PDF reader.
- Verified downloads sourced directly from official Syrian Ministry of Education / NCED servers.

### 8. Normalized Arabic Search Engine
- Full-text multi-entity search spanning Subjects, Lessons, Books, Questions, and Videos.
- Custom Arabic text normalizer:
  - Strips Arabic diacritics (*Tashkeel*).
  - Normalizes Alef variants (`إ`, `أ`, `آ` $\rightarrow$ `ا`).
  - Normalizes Taa Marbuta and Haa (`ة` $\rightarrow$ `ه`).
  - Normalizes Yaa and Alef Maksura (`ى`, `ي` $\rightarrow$ `ي`).
  - Strips the Arabic definite article (`ال`) for enhanced fuzzy keyword discovery.

### 9. Gamification, Points & Leaderboard
- Point rewards for completing study tasks, taking quizzes, mastering notebook mistakes, and engaging in focus sessions.
- Daily study streak tracker (`streak_days`) rewarding consistent habit formation.
- Public Student Leaderboard (*لوحة الشرف*) displaying top performers and current student rank.

---

## 📚 Educational System & Curriculum Structure

The platform implements an academic hierarchy strictly aligned with the official Syrian General Secondary Education regulations.

```
Curriculum Hierarchy
│
├── الفرع العلمي (Scientific Branch)
│   ├── الرياضيات (Mathematics - Parts 1 & 2)
│   ├── الفيزياء (Physics)
│   ├── الكيمياء (Chemistry)
│   ├── علم الأحياء (Biology)
│   ├── اللغة العربية (Arabic Language)
│   ├── اللغة الإنكليزية (English)
│   └── اللغة الفرنسية (French)
│
└── الفرع الأدبي (Literary Branch - 7 Subjects / 2600 Marks)
    ├── اللغة العربية (Arabic Language - 550 Marks)
    ├── الفلسفة والعلوم الإنسانية (Philosophy - 400 Marks)
    ├── التاريخ (History - 300 Marks)
    ├── الجغرافيا (Geography - 300 Marks - 6 Units / 11 Lessons)
    ├── اللغة الإنكليزية (English - 400 Marks)
    ├── اللغة الفرنسية (French - 350 Marks)
    └── الجغرافيا / الثقافة الدينية (Religious Education - 300 Marks)
```

> [!NOTE]
> **Curriculum Integrity Note**: In strict adherence to recent Syrian Ministry of Education curriculum reforms, *National Education (التربية الوطنية)* has been completely purged from the system. The Literary Branch structure is calibrated to 7 subjects totaling 2,600 marks, verified through automated feature audit suites (`ProductionAuditTest`).

### Content Unit Composition
Each **Lesson** (`Lesson` model) is a rich composite object containing:
- `summary`: High-yield ministerial summary.
- `key_concepts`: Foundational concepts and scientific definitions.
- `formulas`: Equations, scientific laws, and boundary conditions.
- `common_mistakes`: Examination traps and frequent student errors.
- `topics`: Chronological textbook section breakdown.
- `questions`: Bank questions with four options, explanations, and official scoring rubrics.
- `videos`: Approved educational YouTube lectures.
- `flashcards`: Active recall flashcard pairs.
- `sources`: Textbook page references.

---

## 🧠 Artificial Intelligence & RAG Architecture

The platform embeds an AI layer designed specifically for Syrian secondary education, engineered to prevent hallucinations and strictly enforce syllabus boundaries.

```
                              ┌──────────────────────────────────────────────┐
                              │            Student HTTP Request              │
                              │     (Chat / Solver / Summary / Quiz)         │
                              └──────────────────────┬───────────────────────┘
                                                     │
                                                     ▼
                              ┌──────────────────────────────────────────────┐
                              │                 AiManager                    │
                              │  - Rate Limiting (20 req/min, 200 req/day)   │
                              │  - Response Caching (Cache::remember)        │
                              │  - Transaction Logging (ai_logs audit)       │
                              └──────────────┬───────────────────────────────┘
                                             │
                                             ▼
                              ┌──────────────────────────────────────────────┐
                              │                 RagService                   │
                              │  - Syrian Curriculum Grounding               │
                              │  - Exam Rubrics & Sample Ministerial Qs      │
                              │  - Student Knowledge & Mistake Context       │
                              │  - Pedagogical Mode Directives               │
                              │  - Anti-Prompt Injection & Sanitization      │
                              └──────────────┬───────────────────────────────┘
                                             │
                       ┌─────────────────────┴─────────────────────┐
                       ▼                                           ▼
         ┌───────────────────────────┐               ┌───────────────────────────┐
         │      GeminiProvider       │  Failover     │       GroqProvider        │
         │  (Google Gemini 3.1 Flash)│ ────────────> │  (Groq LLaMA 3.3 70B)     │
         │   Multimodal & Vision     │   (Spike/429) │   Ultra-Fast Fallback     │
         └─────────────┬─────────────┘               └─────────────┬─────────────┘
                       │                                           │
                       └─────────────────────┬─────────────────────┘
                                             ▼
                              ┌──────────────────────────────────────────────┐
                              │              OcrSpaceService                 │
                              │  Arabic OCR Fallback for Image Parsing       │
                              └──────────────────────────────────────────────┘
```

### 1. Dual-Provider Failover Architecture
Managed by `App\Services\AI\AiManager`:
- **Primary Provider**: **Google Gemini** (`gemini-3.1-flash-lite`) utilized for fast chat completions, structured extraction, and native multimodal image problem solving.
- **Fallback Provider**: **Groq** (`llama-3.3-70b-versatile` text, `llama-3.2-11b-vision-preview` vision) providing sub-second failover when Gemini reaches quota limits or experiences API spikes.
- **OpenRouter Compatible**: Pre-configured for open-source model routing (`meta-llama/llama-3.3-70b-instruct:free`).
- **OCR Engine**: `OcrSpaceService` provides Arabic OCR extraction for low-contrast question photos before language model analysis.

### 2. Retrieval-Augmented Generation (RAG)
Managed by `App\Services\AI\RagService`:
Before calling an AI provider, the service compiles an augmented context:
- **Curriculum Grounding**: Branch name, subject, unit, and lesson title.
- **Academic Knowledge**: Approved lesson summary, official formula sheets, key concepts, and common ministerial traps.
- **Ministerial Exam Rubrics**: Previous Syrian exam questions with their official answer rubrics (*سلالم التصحيح*).
- **Personalized Student State**: Total unmastered mistakes the student has in this lesson, progress status, and completion rate, allowing the AI to address known student weaknesses.

### 3. Multimodal & Text Question Solver
- **Image Solver (`/solver`)**: Students upload photos or screenshots of homework or exam problems (supports JPEG, PNG, WebP up to 8MB). The AI reads the problem and generates a Syrian ministerial solution format:
  1. **📋 المعطيات (Given parameters)**: Transcribed with immediate conversion into international SI units.
  2. **🎯 المطلوب (Required objectives)**: Explicit statement of requirements.
  3. **📐 القوانين والعلاقات (Approved laws)**: Symbolic mathematical formulas from ministry textbooks.
  4. **🔢 خطوات التعويض والحل (Step-by-step arithmetic)**: Explicit algebraic steps.
  5. **🏁 النتيجة والواحدة (Final answer & SI units)**: Highlighted final value with units.
  6. **💡 تنبيهات وفخاخ امتحانية (Exam traps & rubrics)**: Warnings regarding marks lost in grading.
- **Text Solver**: Direct input solver following the same structured ministerial output standard.

### 4. Specialized Pedagogical Modes
The AI Teacher (`/tutor`) adapts its teaching persona using 12 pedagogical modes:
| Mode | Arabic Name | Pedagogical Purpose |
| :--- | :--- | :--- |
| `tutor` | الشرح المنهجي | Balanced, textbook-aligned explanation |
| `simpler` | الشرح المبسط | Everyday analogies and intuitive concepts |
| `beginner` | المبتدئ من الصفر | Step-by-step primer assuming no prior knowledge |
| `help_solve` | المساعدة في الحل | Educational scaffolding: hints and guiding questions without immediate final answers |
| `ask_me` | النمط التفاعلي | AI queries the student and evaluates their response |
| `quiz_me` | اختبار سريع | Generates a 4-option ministerial MCQ and withholds the answer until the student responds |
| `example` | أمثلة تطبيقية | Fully worked numerical problem matching Syrian ministerial style |
| `summarize` | التلخيص السريع | High-yield summary with quick-reference formulas |
| `flashcards` | بطاقات الحفظ | High-yield definition pairs for memorization |
| `exam_review` | المراجعة الامتحانية | Focus on recurring ministerial questions and grading rubrics |
| `key_points` | النقاط الجوهرية | The 5 essential items necessary to prevent lost marks |
| `common_mistakes` | كشف الفخاخ | Common pitfalls and exam traps |

### 5. Automated AI Content Generators
- **AI Summary Generator**: Summarizes any lesson with 7-day server caching.
- **AI Flashcard Generator**: Analyzes lesson text and creates interactive flashcards automatically inserted into the student's study deck.
- **AI Quiz Generator**: Generates 5 high-yield Syrian-style MCQs with distractor explanations and instantiates an active Quiz session on the fly.
- **Intelligent Recommendations**: Analyzes student error patterns, identifies weak lessons ($<75\%$ accuracy), and schedules spaced review sessions.

### 6. Guardrails & Audit Logging
- **Anti-Prompt Injection**: Incoming prompts are sanitized via `RagService::sanitizeInput` (stripping non-printable control characters, truncating excessive inputs, and prepending strict instructions forbidding persona drift outside Syrian academics).
- **Rate Limiting**: Monitored via Cache keys (default: 20 requests/minute, 200 requests/day per student/IP).
- **Audit Logging**: Every AI interaction logs tokens consumed, latency in milliseconds, model name, provider, status, and IP address into the `ai_logs` table.

---

## 🧭 Student Journey & Pedagogical Experience

```
 [1. Onboarding] ──> Select Branch (Scientific / Literary)
         │           Set Exam Date & Daily Target Hours
         ▼
 [2. Dashboard]  ──> Real-Time Exam Countdown, Daily Tasks,
         │           Subject Mastery %, AI Recommendation Widgets
         ▼
 [3. Study Hub]  ──> Select Subject & Lesson ──> Read Formulas & Notes,
         │                                       Watch Video Lectures
         ▼
 [4. Practice]   ──> Take Lesson Quiz or Past Ministerial Exam
         │
         ├── Score < 85% ──> Incorrect answers routed to [Mistake Notebook]
         │                   AI Suggests targeted lesson revision
         │
         └── Score >= 85% ──> Lesson marked as [Mastered]
                             Earn Confidence & Gamification Points
         ▼
 [5. Review]     ──> SuperMemo SM-2 Flashcards (Spaced Repetition)
         │           Re-attempt pending notebook mistakes
         ▼
 [6. AI Tutor]   ──> Ask interactive questions or solve problem photos
```

---

## 🛠️ Admin Panel & Curriculum Quality Control

The administration suite (`/admin`) provides diagnostic tools to safeguard curriculum completeness and system performance.

- **AI Health Monitoring (`/admin/ai`)**:
  - Real-time success rate, average latency (ms), and failure tracking.
  - Distribution breakdown by feature and provider.
  - Live Diagnostic Ping button: sends an end-to-end test query to verify API connectivity.
- **Curriculum Data Quality & Matrix (`/admin/quality`)**:
  - Automatic detection of orphaned lessons, units, or questions.
  - Identification of incomplete questions (missing correct answers or options).
  - Coverage gap audit (units lacking lessons, lessons lacking summaries).
  - **Content Depth Score (0 - 100)**: Evaluates question density, video density, flashcard coverage, exam question ratio, and official source references.
  - Automated detection of deficient lessons ($0$ questions or $0$ videos).
- **Curriculum Management**:
  - Full CRUD operations for Subjects, Units, Lessons, and Bank Questions.

---

## 🏗️ System Architecture & Design Patterns

The codebase is built on Laravel 12 following decoupled architectural patterns:

```
┌────────────────────────────────────────────────────────────────────────┐
│                        Presentation Layer                              │
│  Blade Templates, TailwindCSS, Alpine.js, Responsive Mobile Navigation │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│                    Routing & Middleware Pipeline                       │
│  web.php, SecurityHeadersMiddleware, EnsureOnboardingIsComplete, Auth  │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│                        Controller Layer                                │
│  Curriculum, Quiz, Mistake, Flashcard, StudyPlan, AiTutor, Solver      │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│                    Service & Abstraction Layer                         │
│  AiProviderInterface ──> AiManager (Strategy & Fallback)               │
│  RagService (Curriculum Context), YouTubeService (Video Discovery)     │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│                      Eloquent Data Models (ORM)                        │
│  Branch, Subject, Unit, Lesson, Question, Quiz, Mistake, Flashcard...  │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
┌───────────────────────────────────▼────────────────────────────────────┐
│                       Database & Storage Layer                         │
│  SQLite (Default / Zero-Config) or MySQL / MariaDB                     │
└────────────────────────────────────────────────────────────────────────┘
```

### Design Patterns Used
1. **Strategy Pattern**: `AiProviderInterface` enables plug-and-play AI providers (`GeminiProvider`, `GroqProvider`).
2. **Manager / Failover Pattern**: `AiManager` wraps providers in a resilient execution chain with automatic failover on API exceptions.
3. **Repository / Query Scopes**: Branch isolation is enforced throughout all controllers using relation scopes.
4. **Service-Oriented Context Building**: `RagService` decouples prompt construction and Syrian curriculum compliance from HTTP controllers.

---

## 💻 Tech Stack

| Layer | Technology | Version / Details |
| :--- | :--- | :--- |
| **Backend Framework** | [Laravel](https://laravel.com/) | `12.0.x` |
| **Runtime Language** | [PHP](https://www.php.net/) | `^8.2` (Compatible with PHP 8.2 & 8.3) |
| **Admin Panel** | Custom Blade Admin + [Filament](https://filamentphp.com/) | `^3.2` |
| **Frontend Styling** | [TailwindCSS](https://tailwindcss.com/) & `@tailwindcss/forms` | `3.1+` / PostCSS / Autoprefixer |
| **Reactive Client** | [Alpine.js](https://alpinejs.dev/) | `^3.4.2` |
| **HTTP Client** | [Axios](https://axios-http.com/) | `^1.11.0` |
| **Asset Bundler** | [Vite](https://vitejs.dev/) | `^7.0.7` |
| **Database** | [SQLite](https://www.sqlite.org/) (Default) / [MySQL](https://www.mysql.com/) | Preloaded `database.sqlite` (9.4 MB) |
| **Primary AI Provider** | [Google Gemini](https://ai.google.dev/) | `gemini-3.1-flash-lite` |
| **Fallback AI Provider**| [Groq Cloud](https://groq.com/) | `llama-3.3-70b-versatile` & `llama-3.2-11b-vision-preview` |
| **OCR Service** | [OCR.space](https://ocr.space/) | Arabic Engine (`ara`) |
| **Video Integration** | [YouTube Data API v3](https://developers.google.com/youtube/v3) | Automated educational video discovery |
| **PWA & Offline** | Service Worker + Web App Manifest | Native offline fallback page |
| **Web Server Compatibility** | LiteSpeed / Apache / Nginx | Root and public `.htaccess` security rules |

---

## 📁 Project Directory Structure

```
منصة البكالوريا السورية الذكية/
├── app/
│   ├── Console/
│   │   └── Commands/
│   │       ├── DiscoverVideosCommand.php   # YouTube video discovery automation
│   │       └── SyncBooksCommand.php        # Ministry textbooks sync
│   ├── Http/
│   │   ├── Controllers/
│   │   │   ├── Admin/                      # Admin controllers (Dashboard, Quality, AI Health)
│   │   │   ├── Auth/                       # Laravel Breeze authentication
│   │   │   ├── AiToolsController.php       # Summaries, Flashcards, AI Quizzes, Recommendations
│   │   │   ├── AiTutorController.php       # Interactive AI Teacher with RAG grounding
│   │   │   ├── BookController.php          # Ministry textbook downloads and in-browser reader
│   │   │   ├── CurriculumController.php    # Branches, Subjects, Units, Lessons
│   │   │   ├── DashboardController.php     # Student dashboard, exam countdown, daily tasks
│   │   │   ├── FlashcardController.php     # SuperMemo SM-2 spaced repetition flashcards
│   │   │   ├── GamificationController.php  # Points, study streaks, public leaderboard
│   │   │   ├── ImageSolverController.php   # Multimodal and text exam problem solver
│   │   │   ├── MistakeController.php       # Mistake notebook ("دفتر الأخطاء الذكي")
│   │   │   ├── OnboardingController.php    # Student branch selection & study targets
│   │   │   ├── PastExamController.php      # Ministerial exam sessions & 120min exam simulator
│   │   │   ├── QuestionBankController.php  # Question bank with filters & scoring rubrics
│   │   │   ├── QuizController.php          # Lesson quizzes, scoring, and mastery calculation
│   │   │   ├── SearchController.php        # Multi-entity normalized Arabic search
│   │   │   ├── StudyPlanController.php     # Personalized schedule & Pomodoro focus timer
│   │   │   └── VideoLibraryController.php  # Educational video playlists
│   │   └── Middleware/
│   │       ├── AdminMiddleware.php         # Gate for role=admin
│   │       ├── EnsureOnboardingIsComplete  # Redirects to onboarding if branch is null
│   │       └── SecurityHeadersMiddleware   # Production security headers
│   ├── Models/                             # 26 Eloquent Models (User, Lesson, Quiz, Mistake...)
│   ├── Providers/
│   │   └── AiServiceProvider.php           # AI Manager, Providers, and RAG bindings
│   └── Services/
│       ├── AI/
│       │   ├── AiManager.php               # AI Provider manager with automatic failover
│       │   ├── AiProviderInterface.php     # Abstract AI contract
│       │   ├── GeminiProvider.php          # Google Gemini implementation
│       │   ├── GroqProvider.php            # Groq Cloud implementation
│       │   ├── OcrSpaceService.php         # Arabic OCR parsing
│       │   └── RagService.php              # Syrian curriculum RAG context & guardrails
│       └── YouTubeService.php              # YouTube API search & video ingestion
├── bootstrap/
│   └── app.php                             # Laravel 12 application bootstrap
├── config/                                 # Configuration files (services.php, database.php...)
├── database/
│   ├── database.sqlite                     # Preloaded database (2,630+ questions, 15 subjects)
│   ├── migrations/                         # 18 structured database migrations
│   └── seeders/                            # Curriculum seeders for Scientific & Literary branches
├── public/
│   ├── favicon.svg                         # Vector favicon
│   ├── logo.svg                            # Official platform SVG logo
│   ├── manifest.json                       # Progressive Web App manifest
│   ├── sw.js                               # PWA Service Worker for offline asset caching
│   └── index.php                           # Application entry point
├── resources/
│   ├── css/                                # Tailwind styling tokens
│   ├── js/                                 # Alpine.js & Axios client scripts
│   └── views/                              # Arabic RTL Blade templates
├── routes/
│   ├── auth.php                            # Authentication routes
│   ├── console.php                         # Scheduled artisan tasks
│   └── web.php                             # All platform HTTP routes
└── tests/
    └── Feature/
        ├── AdminTest.php                   # Admin access & health tests
        ├── AiFeaturesTest.php              # AI Summaries & Flashcard generator tests
        ├── AiTutorTest.php                 # AI Teacher chat & RAG tests
        ├── CurriculumFlowTest.php          # Student branch & curriculum navigation tests
        ├── ImageSolverTest.php             # Vision solver tests
        └── ProductionAuditTest.php         # End-to-end production audit test suite
```

---

## ⚙️ Prerequisites & System Requirements

Ensure your environment satisfies the following requirements:
- **PHP**: `8.2.0` or higher (`8.3` recommended).
  - Required PHP Extensions: `pdo_sqlite`, `sqlite3`, `curl`, `mbstring`, `fileinfo`, `openssl`, `tokenizer`, `xml`.
  - (Optional for MySQL): `pdo_mysql`.
- **Composer**: `2.x`
- **Node.js**: `18.x` or `20.x` & **npm**: `9.x` or `10.x`
- **Web Server**: Apache, LiteSpeed, or Nginx.

---

## 🚀 Local Installation & Quickstart

Follow these steps to clone, configure, and run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/code-elta6ur/syrian-baccalaureate-platform.git
cd syrian-baccalaureate-platform
```

### 2. Install Dependencies
```bash
composer install
npm install
```

### 3. Configure Environment
```bash
cp .env.example .env
php artisan key:generate
```

### 4. Database Setup
The repository includes a ready-to-use preloaded database containing complete curriculum data.

**Option A: Use the Preloaded SQLite Database (Recommended)**
```bash
# Ensure the SQLite database file exists and is writable
touch database/database.sqlite
# Run any pending migrations
php artisan migrate
```

**Option B: Fresh Migration & Seeders**
If you wish to rebuild the database from scratch:
```bash
php artisan migrate:fresh --seed
```

### 5. Build Assets & Create Storage Link
```bash
npm run build
php artisan storage:link
```

### 6. Start the Development Server
You can launch the full development environment with hot-reloading using the configured composer script:
```bash
composer run dev
```
Or start the servers individually:
```bash
# Terminal 1: Laravel Backend
php artisan serve

# Terminal 2: Vite Asset Server
npm run dev
```

Visit the application at: `http://localhost:8000`

---

## 🔐 Environment Configuration

Key configuration parameters defined in `.env`:

| Variable | Required | Default | Description |
| :--- | :---: | :--- | :--- |
| `APP_NAME` | **Yes** | `منصة البكالوريا السورية الذكية` | Application name |
| `APP_ENV` | **Yes** | `local` | Environment (`local`, `production`) |
| `APP_KEY` | **Yes** | `[Generated]` | Application encryption key |
| `APP_DEBUG` | **Yes** | `true` | Debug mode (`false` in production) |
| `APP_URL` | **Yes** | `http://localhost:8000` | Canonical application URL |
| `APP_LOCALE` | **Yes** | `ar` | Primary locale (Arabic) |
| `DB_CONNECTION` | **Yes** | `sqlite` | Database driver (`sqlite` or `mysql`) |
| `DB_DATABASE` | Optional | `database/database.sqlite` | Path for SQLite or MySQL database name |
| `AI_DEFAULT_PROVIDER`| **Yes** | `gemini` | Primary AI engine (`gemini`, `groq`) |
| `AI_FALLBACK_PROVIDER`| **Yes** | `groq` | Failover AI engine (`groq`) |
| `GEMINI_API_KEY` | **Yes** | — | Google AI Studio API Key |
| `GEMINI_MODEL` | No | `gemini-3.1-flash-lite` | Gemini model version |
| `GROQ_API_KEY` | Optional | — | Groq Cloud API Key for ultra-fast failover |
| `GROQ_MODEL` | No | `llama-3.3-70b-versatile` | Groq text model version |
| `GROQ_VISION_MODEL` | No | `llama-3.2-11b-vision-preview` | Groq multimodal vision model |
| `OCR_SPACE_API_KEY` | No | `helloworld` | Free engine key for Arabic OCR image parsing |
| `YOUTUBE_API_KEY` | Optional | — | Google API key for automated video discovery |
| `AI_MAX_TOKENS` | No | `2048` | Maximum token limit per AI response |
| `AI_TEMPERATURE` | No | `0.4` | Determinism temperature for academic accuracy |
| `AI_RATE_LIMIT_PER_MINUTE` | No | `20` | Maximum AI requests per minute per user/IP |
| `AI_RATE_LIMIT_PER_DAY` | No | `200` | Maximum AI requests per day per user/IP |
| `AI_CACHE_TTL` | No | `86400` | Cache duration (in seconds) for summaries |

> [!IMPORTANT]
> Never commit your production `.env` file or real API keys to any public git repository. Use `.env.example` as a clean template.

---

## 🗄️ Database & Seeded Datasets

The platform includes a pre-populated SQLite database (`database/database.sqlite` ~9.4 MB) containing:
- **15 Complete Subjects**: Across both Scientific and Literary branches.
- **127 Lessons**: Fully categorized with summaries, formulas, and common exam errors.
- **2,630+ Questions**: Official ministerial examination questions from past sessions alongside bank exercises with complete grading rubrics.
- **16 Official Ministry Textbooks**: Matched with direct download and reading links.
- **Default Seeded Accounts**:
  - **Administrator**: `admin@bac-platform.sy` (configured in `AdminSeeder.php`) / `password`
  - **Sample Student**: Created upon registration or via test factories.

### Database Seeders Reference
- `BranchSeeder`: Sets up Scientific and Literary branches.
- `ScientificCurriculumSeeder` & `ScientificCurriculumExpansionSeeder`: Scientific syllabus.
- `LiteraryCurriculumSeeder` & `LiteraryCurriculumExpansionSeeder`: Literary syllabus (7 subjects).
- `MinisterialExamsQuestionSeeder`: Past ministerial exams archive.
- `ComprehensiveCurriculumBankSeeder` & `MultiFormulationBankSeeder`: Bank questions with explanations.
- `FlashcardsSeeder`: SuperMemo active recall cards.
- `OfficialBooksSeeder`: Textbooks directory.
- `CuratedVideosSeeder`: Educational video playlists.

---

## ⏰ Scheduled Tasks & Automation

The platform utilizes the **Laravel Task Scheduler** (`routes/console.php`) for maintenance tasks:

```php
// Synchronize official textbooks weekly every Friday at 03:00 AM
Schedule::command('books:sync')->weeklyOn(5, '03:00');

// Discover new educational video lectures daily at 02:00 AM
Schedule::command('videos:discover')->dailyAt('02:00');
```

### Production Cron Setup
On your production Linux / cPanel / Hostinger server, configure a single cron entry:
```bash
* * * * * cd /path-to-your-project && php artisan schedule:run >> /dev/null 2>&1
```

---

## 📱 Progressive Web App & Mobile Application

### 1. Progressive Web App (PWA)
The web application is PWA-enabled:
- **Manifest (`/manifest.json`)**: Configures standalone app appearance, theme color (`#4f46e5`), background (`#0f172a`), portrait orientation, and maskable icons.
- **Service Worker (`/sw.js`)**:
  - Precaches essential navigation routes (`/`, `/offline`, `/manifest.json`).
  - Implements runtime caching for static assets (CSS, JS, fonts, SVGs, images).
  - Provides a dedicated offline fallback page (`/offline`) whenever network connectivity drops.

### 2. Android Mobile Application
Students can install the platform directly on Android devices via the published mobile package:
- **Direct APK Download**: [https://www.appcreator24.com/app4181134-v7nscz](https://www.appcreator24.com/app4181134-v7nscz)
- Built as an optimized mobile client providing hardware back-button support, fullscreen viewport scaling, and push notification readiness.

---

## 🛡️ Security Hardening & Protection

1. **Strict Multi-Tenant Student Isolation**:
   - Every quiz, mistake record, flashcard review, and study plan is scoped to `user_id`.
   - Cross-user data access triggers `403 Forbidden` or `404 Not Found` (enforced via feature tests).
2. **Security Headers (`SecurityHeadersMiddleware`)**:
   - `X-Frame-Options: SAMEORIGIN` (prevents clickjacking).
   - `X-Content-Type-Options: nosniff` (prevents MIME-type sniffing).
   - `X-XSS-Protection: 1; mode=block`.
   - `Referrer-Policy: strict-origin-when-cross-origin`.
   - `Permissions-Policy: camera=(), microphone=(), geolocation=()`.
3. **Web Server Hardening (`.htaccess`)**:
   - Blocks direct HTTP access to `.env`, `.git`, SQLite database files, composer files, and artisan.
   - Redirects all incoming traffic to `public/index.php`.
4. **AI Abuse Protection**:
   - Cache-backed rate limiting per student and IP address.
   - Input sanitization removing non-printable control characters.
   - Strict system prompt guardrails against prompt injection and role manipulation.

---

## 🚢 Production Deployment

The project is pre-packaged for fast deployment on shared hosting (e.g., **Hostinger**, cPanel) or virtual private servers (VPS).

### Hostinger / LiteSpeed / Apache Quick Deployment
1. Upload the pre-built deployment archive (`hostinger_deploy.zip` or `baccalaureate_clean.zip`) to `public_html`.
2. Extract files directly into `public_html`.
3. Ensure hidden files are visible and rename `env.hostinger.example` to `.env` (or configure your own `.env`).
4. Set `APP_ENV=production`, `APP_DEBUG=false`, and set `APP_URL` to your production domain:
   ```env
   APP_URL=https://baccalaureate.code-elta6ur.sy
   ```
5. Verify folder permissions (`755` for directories, `644` for files, and write permissions for `storage/`, `bootstrap/cache/`, and `database/`).
6. Ensure PHP version is set to **PHP 8.2** or **PHP 8.3** with the extensions `pdo_sqlite`, `sqlite3`, `curl`, `mbstring`, `fileinfo`, and `openssl` enabled.
7. Optimize Laravel for production:
   ```bash
   php artisan config:cache
   php artisan route:cache
   php artisan view:cache
   ```

*(For detailed step-by-step instructions, see the dedicated [HOSTINGER_DEPLOY_GUIDE.md](file:///d:/my%20projects/منصة%20البكالوريا%20السورية%20الذكية/HOSTINGER_DEPLOY_GUIDE.md)).*

---

## 🧪 Automated Testing & Quality Assurance

The codebase includes automated test suites covering curriculum integrity, multi-user isolation, security headers, and AI services:

```bash
# Run the entire test suite
php artisan test

# Run the comprehensive production audit suite
php artisan test tests/Feature/ProductionAuditTest.php

# Run AI and RAG specific feature tests
php artisan test tests/Feature/AiTutorTest.php
php artisan test tests/Feature/AiFeaturesTest.php
php artisan test tests/Feature/ImageSolverTest.php
```

### Test Coverage Highlights
- `ProductionAuditTest`:
  - Validates complete purge of National Education from all subjects and questions.
  - Confirms Literary Branch has exactly 7 subjects totaling 2,600 marks.
  - Verifies Geography has 6 units, 11 lessons, and high question density.
  - Executes full end-to-end student flow: Onboarding $\rightarrow$ Dashboard $\rightarrow$ Lesson $\rightarrow$ Quiz $\rightarrow$ Mistake Notebook $\rightarrow$ Resolution $\rightarrow$ AI Tutor.
  - Enforces cross-user data isolation.
  - Verifies presence of security headers and absence of debug files.
  - Verifies PWA manifest, service worker, dynamic sitemap, and offline routes.
  - Verifies AI input sanitization and anti-prompt-injection guardrails.

---

## 📸 Screenshots

*(Visual documentation of key platform interfaces. Replace paths below with your repository screenshots once captured).*

| Student Dashboard | Interactive Lesson View |
| :---: | :---: |
| ![Dashboard Preview](public/logo.svg) | ![Lesson Preview](public/logo.svg) |
| *Personalized exam countdown & daily tasks* | *Curriculum notes, formulas & ministerial questions* |

| AI Question Solver | Smart Mistake Notebook |
| :---: | :---: |
| ![Solver Preview](public/logo.svg) | ![Mistakes Preview](public/logo.svg) |
| *Step-by-step ministerial solution with SI units* | *Automated error tracking & mastery re-tests* |

---

## 🤝 Contributing

Contributions to improve curriculum coverage, add new ministerial question papers, or optimize AI prompts are welcome.

1. **Fork the Repository**
2. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/curriculum-expansion
   ```
3. **Implement Changes & Maintain Style**:
   - Adhere to PSR-12 coding standards (`composer run test`).
   - Add feature tests for any new endpoints or controllers.
4. **Commit Changes**:
   ```bash
   git commit -m "Add: official ministerial exam session 2024 for Physics"
   ```
5. **Push to Your Branch**:
   ```bash
   git push origin feature/curriculum-expansion
   ```
6. **Open a Pull Request** with a detailed explanation of changes.

---

## 🗺️ Roadmap

- [x] Full Syrian General Secondary Curriculum (Scientific & Literary branches).
- [x] Complete purge of National Education and calibration of Literary branch to 2,600 marks.
- [x] Dual AI Provider architecture with automatic failover (Gemini + Groq).
- [x] Curriculum-grounded Retrieval-Augmented Generation (RAG).
- [x] Multimodal image problem solver with ministerial SI unit formatting.
- [x] Interactive Quiz Engine and dynamic lesson mastery scores.
- [x] Automated Mistake Notebook ("دفتر الأخطاء الذكي").
- [x] Spaced Repetition Flashcards using SuperMemo SM-2.
- [x] PWA offline fallback and published Android APK.
- [ ] Direct voice questions for the AI Teacher.
- [ ] PDF export for personalized mistake notebooks and flashcard decks.
- [ ] Collaborative study rooms and peer challenge quizzes.

---

## 📄 License

The code, curriculum structure, and digital assets of this platform are proprietary software developed for the Syrian Baccalaureate Platform under **كود التطور (Code El-Ta6ur)**. All rights are reserved.

*(For licensing inquiries or institutional partnerships, please reach out via the official contact channels below).*

---

## 👥 Author & Credits

- **Platform Name**: منصة البكالوريا السورية الذكية (Syrian Baccalaureate Platform)
- **Brand & Organization**: **كود التطور (Code El-Ta6ur)**
- **Official Web Platform**: [https://baccalaureate.code-elta6ur.sy/](https://baccalaureate.code-elta6ur.sy/)
- **Mobile Application**: [AppCreator24 Android APK](https://www.appcreator24.com/app4181134-v7nscz)
- **Contact & Support**: [https://baccalaureate.code-elta6ur.sy/contact](https://baccalaureate.code-elta6ur.sy/contact)

<p align="center">
  <sub>Made with dedication for every Syrian student striving for academic excellence. 🇸🇾🎓</sub>
</p>
