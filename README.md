<div align="center">

![Header](https://capsule-render.vercel.app/api?type=venom&color=0:0D1117,50:1F6FEB,100:A371F7&height=260&section=header&text=AWAB%20HAMMAD&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=I%20don't%20just%20write%20code.%20I%20build%20systems%20that%20think,%20remember%20and%20verify.&descSize=18&descAlignY=60)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&color=58A6FF&center=true&vCenter=true&width=720&lines=Rust+%E2%9A%99%EF%B8%8F+Flutter+%F0%9F%93%B1+Python+%F0%9F%90%8D+%E2%80%94+one+mind%2C+three+universes;Building+AI+agents+that+ship+verified+code+%F0%9F%A4%96;Local-first.+Private+by+design.+Zero+telemetry.+%F0%9F%94%92;Code+is+poetry+written+for+machines+%E2%9C%A8)](https://github.com/B-max12)

<br>

<a href="https://github.com/B-max12"><img src="https://img.shields.io/badge/GitHub-B--max12-0D1117?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/awab-hammad-128aa4300"><img src="https://img.shields.io/badge/LinkedIn-Awab_Hammad-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:awabbhammad8@gmail.com"><img src="https://img.shields.io/badge/Email-Say_Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://awab.lovable.app"><img src="https://img.shields.io/badge/Portfolio-Visit-FF5722?style=for-the-badge&logo=todoist&logoColor=white"/></a>

<br><br>

<img src="https://count.getloli.com/get/@:B-max12?theme=original-new" alt="views"/>

</div>

---

## 🧬 `whoami`

```rust
struct Awab {
    handle:     &'static str,   // "B-max12"
    builds:     [&'static str; 3],
    obsessions: Vec<&'static str>,
    philosophy: &'static str,
}

const AWAB: Awab = Awab {
    handle: "B-max12",
    builds: ["Dear Diary", "AURELIS", "FORGEX"],
    obsessions: vec!["local-first", "verification", "privacy by architecture", "details nobody notices"],
    philosophy: "Code is poetry written for machines ✨",
};
```

> **Three projects. Three different worlds.**
> A diary that remembers you, a download manager that respects you, and an AI engineering team that checks its own work.

---

## 🚀 Flagship Projects

<table>
<tr>
<td align="center" width="33%">
<h3>📖 Dear Diary</h3>
<sub><b>Your Vintage Journal</b></sub><br><br>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
<img src="https://img.shields.io/badge/AI-RAG-A371F7?style=flat-square"/>
<br><br>
<a href="#-dear-diary">Jump to details ↓</a>
</td>
<td align="center" width="33%">
<h3>⬇️ AURELIS</h3>
<sub><b>Downloads, refined.</b></sub><br><br>
<img src="https://img.shields.io/badge/Tauri_2-24C8DB?style=flat-square&logo=tauri&logoColor=white"/>
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
<br><br>
<a href="#%EF%B8%8F-aurelis">Jump to details ↓</a>
</td>
<td align="center" width="33%">
<h3>🔨 FORGEX</h3>
<sub><b>Plan. Build. Refine. Verify.</b></sub><br><br>
<img src="https://img.shields.io/badge/Python_3.12-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Agents-Multi-FF6B6B?style=flat-square"/>
<img src="https://img.shields.io/badge/Tests-~360-brightgreen?style=flat-square"/>
<br><br>
<a href="#-forgex">Jump to details ↓</a>
</td>
</tr>
</table>

---

## 📖 Dear Diary

### *A private, offline-first diary that turns daily journaling into an intelligent memory system.*

Write on a vintage notebook with ruled lines, paper themes and ink colors, then let an AI layer help you *remember* your own life, without ever betraying your privacy.

<table>
<tr>
<td width="50%" valign="top">

#### ✍️ The Writing Experience
- Rich-text entries on a **vintage notebook UI**
- Paper themes, ruled lines, custom ink colors
- Photos as compact **inline blocks**
- **Voice notes** with playback
- Monthly calendar with entry activity and moods

#### 🌅 Daily Life Tools
- Mood tracking and custom categories
- Routine task management with **streaks**
- Daily reflections: philosopher quotes, puzzles, Quran verses with verified translations
- Statistics dashboard: writing patterns, streaks, mood distribution

</td>
<td width="50%" valign="top">

#### 🧠 The AI Layer
- **Semantic search** across every entry
- Diary analysis with caching
- A chatbot that answers **with entry citations**
- **Anti-hallucination** guardrails
- Explicit **user confirmation** before any edit or deletion

#### 🔐 Privacy First
- Private *Letters to God* are **encrypted separately**
- Excluded from all AI, search and statistics
- **App Lock** with PIN protection
- Offline-first: your device is the source of truth

</td>
</tr>
</table>

```mermaid
flowchart LR
    A[📱 Flutter UI<br/>Android · iOS · Web · Windows] --> B[(SQLite + Drift<br/>offline-first truth)]
    B <-->|pull / push engine| C[☁️ Supabase<br/>Postgres · Auth · Storage · RLS]
    B --> D{{🧠 AI Layer<br/>OpenAI · Gemini<br/>Embeddings + RAG}}
    D -->|cited answers only| A
    B -.->|conflict detected| E[⚖️ Conflict Resolution UI]
    F[🔒 Letters to God<br/>encrypted] -. never indexed .-x D
```

<p>
<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/Riverpod-State-00B4AB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SQLite-Drift-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
<img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
</p>

---

## ⬇️ AURELIS

### *"Downloads, refined."*

A **production-grade, local-first download manager** for Windows, macOS and Linux, built from scratch across **thirteen verified phases**.

```text
┌──────────────────────────────────────────────────────────────┐
│  🖥️  React + TypeScript + Vite  (Tailwind · Radix · Zustand)  │
│        every IPC payload validated: Zod ⇄ typed Rust errors   │
├──────────────────────────────────────────────────────────────┤
│  🦀  Tauri 2  →  Rust core  (tokio · reqwest)                 │
│   ├─ segmented multi-connection transfers                     │
│   ├─ byte-accurate cross-restart resume                       │
│   ├─ bounded retry + backoff                                  │
│   ├─ token-bucket throttling                                  │
│   └─ checksum verification                                    │
├──────────────────────────────────────────────────────────────┤
│  🗄️  SQLite via SQLx  ·  immutable migrations                 │
└──────────────────────────────────────────────────────────────┘
```

<details>
<summary><b>⚡ Feature highlights (click to expand)</b></summary>

<br>

| Area | What it does |
|---|---|
| **Queues** | Durable queues, priorities, drag ordering, daily schedule windows |
| **Resolvers** | Analyzes direct files, HTML pages, HLS and clear DASH, with a real **format picker** |
| **Browsers** | Chrome / Edge / Firefox integration over **authenticated native messaging** with a dedicated host binary |
| **OS citizenship** | System notifications, live tray, real statistics |
| **Accessibility** | Virtualized lists, full keyboard and screen-reader support |
| **Quality gate** | One-command release gate (Vitest, `cargo test`, `clippy`) + three-OS CI producing installers |

</details>

> 🛡️ **Privacy is architectural.** No account. No cloud. No telemetry.
> Protected content (encrypted HLS, DRM DASH) is **refused, never bypassed.**

<p>
<img src="https://img.shields.io/badge/Tauri_2-24C8DB?style=for-the-badge&logo=tauri&logoColor=white"/>
<img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"/>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
</p>

---

## 🔨 FORGEX

### *Plan. Build. Refine. Verify.*

A **CLI-first autonomous AI software engineering runtime**. Not a chatbot. Not a code generator. A *team* of specialized agents working on a real repository, with receipts.

```mermaid
flowchart TD
    U([👤 Your request]) --> A[🏛️ Architect<br/>analyzes repo · verifies deps on<br/>PyPI / npm / crates.io / Go proxy]
    A -->|dependency-ordered plan| B[🔧 Builder<br/>implements task by task]
    B --> E[🧐 Expert Coder<br/>reviews every diff + impact analysis]
    E --> V[✅ Deterministic Harness<br/>tests · build · lint]
    V -->|pass| S[🛡️ Supervisor<br/>audits and issues verdict]
    V -->|fail| R[🔁 Repair Loop<br/>capped by max_iterations]
    R --> B
    S --> D([🚀 Verified result])
    G[(🌿 Git checkpoints<br/>every rollback reversible)] -.- B
    G -.- R
```

```console
$ forgex build "add OAuth login to my API"
 ◆ Architect   plan ready · 7 tasks · deps verified against PyPI
 ◆ Builder     task 1/7 ... done
 ◆ Expert      diff reviewed · impact: low
 ◆ Harness     pytest ✔  ruff ✔  mypy ✔
 ◆ Supervisor  verdict: APPROVED
```

<table>
<tr>
<td width="50%" valign="top">

#### 🧩 Engineering Guarantees
- **Permission-gated** tools
- **Git checkpoints**, every rollback reversible
- Repair loop is **never infinite**
- Interrupts are safe, runs are **resumable**
- Optional **hardened Docker sandbox**

</td>
<td width="50%" valign="top">

#### 🔌 Model Layer
- OpenAI-compatible, Groq and local servers
- Capability-aware routing, retries, fallback
- **Multi-model ensemble review**
- Pydantic v2 structured outputs everywhere
- JSON / plain modes on every command

</td>
</tr>
</table>

<p>
<img src="https://img.shields.io/badge/Python_3.12+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/asyncio-Concurrent-FFD43B?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pydantic_v2-E92063?style=for-the-badge&logo=pydantic&logoColor=white"/>
<img src="https://img.shields.io/badge/Typer-Rich-009688?style=for-the-badge"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/pytest-~360_tests-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/>
</p>

---

## ⚔️ Side by Side

| | 📖 Dear Diary | ⬇️ AURELIS | 🔨 FORGEX |
|---|---|---|---|
| **Domain** | Personal memory + AI | Desktop networking | AI engineering |
| **Core language** | Dart / Flutter | Rust + TypeScript | Python |
| **Data layer** | SQLite + Supabase | SQLite (SQLx) | SQLite + JSON state |
| **Philosophy** | *Remember, privately* | *Local-first, no telemetry* | *Never trust. Verify.* |
| **Platforms** | Android · iOS · Web · Windows | Windows · macOS · Linux | Any CLI environment |
| **Trust model** | Encrypted + AI-excluded secrets | Refuses DRM, never bypasses | Permission-gated + checkpointed |

---

## 🛠️ Tech Arsenal

<div align="center">

<img src="https://skillicons.dev/icons?i=dart,flutter,rust,tauri,react,ts,py,cpp,qt&theme=dark"/>
<br>
<img src="https://skillicons.dev/icons?i=sqlite,postgres,supabase,tailwind,vite,docker,git,github,linux,vscode&theme=dark"/>

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api?username=B-max12&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9"/>
<img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=B-max12&layout=compact&langs_count=10&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9"/>

<img src="https://github-readme-streak-stats-nine-azure.vercel.app/?user=B-max12&theme=tokyonight&hide_border=true&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=FF6B6B&currStreakLabel=58A6FF"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=B-max12&theme=react-dark&hide_border=true&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FF6B6B"/>

</div>

---

## 🎯 Current Focus

```yaml
🔭 building:      Dear Diary · AURELIS · FORGEX
🌱 learning:      multi-agent systems, Rust async internals, RAG that doesn't hallucinate
👯 collaborating: open source, AI tooling, local-first software
💬 ask me about:  Flutter, Rust/Tauri, agent runtimes, offline-first sync
⚡ fun fact:      I'll happily spend hours perfecting one animation
```

---

<div align="center">

### 💬 Got a wild idea? Let's build it.

<a href="mailto:awabbhammad8@gmail.com"><img src="https://img.shields.io/badge/📫_awabbhammad8@gmail.com-D14836?style=for-the-badge"/></a>
<a href="https://awab.lovable.app"><img src="https://img.shields.io/badge/🌐_awab.lovable.app-FF5722?style=for-the-badge"/></a>
<a href="https://www.linkedin.com/in/awab-hammad-128aa4300"><img src="https://img.shields.io/badge/💼_LinkedIn-0077B5?style=for-the-badge"/></a>

<br><br>

⭐ *If any of these projects impressed you, drop a star. It fuels the next build.*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:A371F7,50:1F6FEB,100:0D1117&height=120&section=footer)

</div>
