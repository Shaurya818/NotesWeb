<div align="center">

# SNAI Study Dashboard

**Learn, practise and revise the whole SNAI course in one interactive app.**

28 modules · 192 flashcards · 235 quiz questions · CPU scheduling & chmod calculators · hands-on labs
Single HTML file. Zero dependencies. No build step.

[**▶ Live demo**](https://snainotes.vercel.app/)

![Stack](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20vanilla%20JS-2453D6?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-0-13835A?style=flat-square)
![Build step](https://img.shields.io/badge/build%20step-none-5745D6?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square)

[Overview](#overview) · [Features](#features) · [Syllabus](#syllabus-coverage) · [Getting started](#getting-started) · [How it works](#how-it-works) · [Adding content](#adding-or-editing-content) · [Roadmap](#roadmap)

</div>

<!--
## Screenshots

Add 3–4 screenshots to docs/screenshots/, then uncomment this block.

| Dashboard | Module notes | CPU scheduling calculator |
|---|---|---|
| ![Dashboard](docs/screenshots/dashboard.png) | ![Module](docs/screenshots/module.png) | ![Scheduler](docs/screenshots/scheduler.png) |
-->

## Overview

SNAI Study Dashboard turns the SNAI course slides and lecture PDFs into a single interactive study app for first-year B.Tech CSE students. Instead of re-reading slides before an exam, you can learn each topic in plain English, drill it with flashcards and quizzes, run the scheduling and permission calculations yourself, and see exactly which topics are still weak.

It covers 28 modules, from "what is a computer?" through operating systems, CPU scheduling, the terminal, Git and GitHub, up to networking.

## Features

### Learn

- **28 modules in 5 parts.** Each module has a plain-English explanation, an analogy, key concepts, terms, worked examples, commands, an exam-focus list, common traps, memory tricks and quick-revise points.
- **No made-up content.** Anything the source slides don't cover is flagged as *"Not provided in the source material"* instead of being guessed.
- **Global search** across modules, concepts, terms, exam points, traps, commands, operators, flashcards and quiz questions.
- **Terminal reference.** 40 commands in 9 categories with syntax, examples, flags and explanations, filterable by category.
- **Interactive explainers** for OS layers, GUI vs CLI vs API, hardware, Windows vs macOS vs Linux, and types of computers.

### Practise

- **Flashcards.** 192 cards (147 concept, 45 command): flip, shuffle, filter by part or card type, and self-rate.
- **Quiz mode.** 20-question runs filtered by part and difficulty, with instant feedback and explanations, plus a targeted quiz built from the questions you got wrong.
- **Exam mode.** A 50-question mock exam (20 easy, 20 medium, 10 hard) with a per-module breakdown and a history of your last 10 attempts.
- **235 questions in 6 formats.** Multiple choice (113), scenario-based (45), fill-in-the-blank (26), true/false (23), CPU-scheduling problems (18) and command questions (10), split 94 easy / 90 medium / 51 hard.
- **Command Match.** A memory-card game: pair 8 terminal commands with their meanings in as few moves as possible. Your best score is saved.
- **Last-minute revision.** One page with the key definitions, formulas, commands, terminal symbols, exam traps, memory tricks and frequently confused pairs.

### Calculate and experiment

- **CPU scheduling calculator.** FCFS, SJF (non-preemptive), Priority (higher- or lower-number-first, with optional aging) and Round Robin (custom time quantum). Add processes with arrival and burst times and get a Gantt chart, a per-process completion / turnaround / waiting-time table, and the averages.
- **chmod calculator.** Click the read/write/execute grid or type an octal like `754` and see the matching symbolic permissions with a plain-English explanation.
- **Process and PCB lab.** Create processes, inspect their PCBs, trigger context switches and kill processes.
- **Memory lab.** Play with 8 RAM page frames and see how virtual memory works.

### Track your progress

- **Dashboard.** Progress per part, an adjustable daily study goal, study analytics, accuracy by difficulty, recent answer accuracy, a "Topics to Revise" list built from your mistakes, and a suggestion for what to study next.
- **Gamification.** XP and levels (100 XP per level), answer streaks, 12 achievements (from "First Step" to "Syllabus Slayer" for finishing all 28 modules), confetti and optional sound effects.
- **Saved automatically** in your browser's `localStorage`. No account, no server, no tracking.

### Built to be pleasant to use

- Light and dark themes (follows your system, with a manual toggle)
- Responsive layout with a collapsible sidebar on small screens
- Keyboard shortcuts (below), ARIA roles and visible focus outlines
- Reduced-motion friendly: CSS animations and transitions switch off with the OS setting
- Micro-interactions: 3D card tilt, spotlight glow, floating particles, scroll reveal, magnetic buttons and button ripples

### Keyboard shortcuts

| Where | Key | Action |
|---|---|---|
| Quiz / Exam | `1`–`4` | Pick an answer option |
| Quiz / Exam | `Enter` | Submit a fill-in or numeric answer |
| Flashcards | `←` / `→` | Previous / next card |
| Flashcards | `Space` / `Enter` | Flip the card |
| Flashcards | `1` / `2` | Self-rate the card |
| Anywhere | `Esc` | Close the mobile sidebar |

## Syllabus coverage

| Part | Modules | Focus | Source |
|---|---|---|---|
| 1 | 1–9 | Computer fundamentals, hardware and software, operating systems, processes, GUI vs CLI, the terminal | SNAI_1C_1 |
| 2 | 10–17 | CPU scheduling (FCFS, SJF, Priority, Round Robin), PCB and context switching, memory management, advanced terminal use | SNAI_1C_2 |
| 3 | 18–22 | Types of computers, CLI / GUI / API, Windows vs macOS vs Linux, full CLI reference, process-control commands | SNAI_1C_3 |
| 4 | 23–26 | Filesystem and permissions, number systems and encoding, compiled vs interpreted, Git | Lectures 5–9 (supplementary) |
| 5 | 27–28 | GitHub and remotes, networks and the internet | Lectures 10–11 |

<details>
<summary>Full module list</summary>

1. What even is a computer?
2. Hardware
3. Software
4. The Operating System
5. OS Architecture & Device Management
6. Process Management
7. GUI vs CLI
8. The Terminal
9. Files, Packages & Flags
10. Scheduling: FCFS
11. Scheduling: Shortest Job First
12. Scheduling: Priority
13. Scheduling: Round Robin
14. PCB & Context Switching
15. Real Terminal Toolkit
16. Memory Management
17. Terminal: Multi-Command & Multi-Process
18. Types of Computers
19. CLI, GUI & API — The Three Interfaces
20. Windows vs macOS vs Linux
21. Full CLI Reference
22. ps vs ps aux, kill vs kill -9
23. The Filesystem, Permissions & PATH
24. Number Representation & Data Encoding
25. How Software Runs: Compiled vs Interpreted
26. Version Control with Git
27. GitHub & Remote Repositories
28. The Network & the Internet

</details>

## Getting started

### Use it online

Open the live demo: **https://snai-study-dashboard.vercel.app**

### Run it locally

```bash
git clone https://github.com/YOUR-USERNAME/snai-study-dashboard.git
cd snai-study-dashboard
```

Then open `index.html` in any modern browser. No install, no build.

If you prefer a local server:

```bash
python -m http.server 8000
# open http://localhost:8000
```

> Progress is stored per browser and per site address, so the live site, `localhost` and a local file each keep their own progress.

### Deploy your own copy

- **GitHub Pages:** Settings → Pages → *Deploy from a branch* → `main` / `(root)`.
- **Vercel or Netlify:** import the repo, leave the build command empty and serve the root folder. Nothing else is needed.

## How it works

The whole app lives in one file, `index.html` (about 5,200 lines, ~420 KB): styles, course content and logic.

- **Vanilla JavaScript.** No framework, bundler or npm packages.
- **Hash router.** Every screen is a `#/route`, so pages are deep-linkable and work on any static host with zero server config.
- **Content as data.** Modules, flashcards, questions and commands are plain JavaScript arrays and objects, rendered by `view*()` functions.
- **State.** One object persisted to `localStorage` under `snai-study-v1` (completed modules, flashcard ratings, quiz and exam results, XP, badges, theme, daily goal).
- **Theming.** CSS custom properties; light/dark from `prefers-color-scheme` with a `data-theme` override.
- **Sound.** Optional effects generated with the Web Audio API, so there are no audio files.
- **Network.** The only external request is Google Fonts (Bricolage Grotesque, Figtree, JetBrains Mono), with system-font fallbacks.

### Where things live in `index.html`

| Name | What it holds |
|---|---|
| `MODULES` | The 28 module notes |
| `FLASH` | The 192 flashcards |
| `QUESTIONS` | The 235 quiz and exam questions |
| `COMMANDS`, `OPERATORS`, `DRILLS` | Terminal reference data |
| `schedFCFS`, `schedSJF`, `schedPriority`, `schedRR` | Scheduling engines behind the calculator |
| `view*()` | One renderer per screen |
| `route()` | The hash router |
| `S` and `saveState()` | Persisted progress |

<details>
<summary>Deep links</summary>

| Route | Screen |
|---|---|
| `#/` | Dashboard |
| `#/module/<n>` | Module notes (1–28) |
| `#/sched` | CPU scheduling calculator |
| `#/chmod` | chmod calculator |
| `#/terminal` | Terminal reference |
| `#/process` | Process and PCB lab |
| `#/memory` | Memory lab |
| `#/interfaces`, `#/hardware`, `#/compare`, `#/computers` | Explainers |
| `#/flashcards`, `#/quiz`, `#/exam` | Practice |
| `#/play` | Command Match game |
| `#/revision` | Last-minute revision |
| `#/search/<query>` | Global search |

</details>

## Adding or editing content

All course content is plain JavaScript data in `index.html`, so adding material needs no tooling.

**Add a flashcard.** In the `FLASH` section call `F(module, tag, question, answer)`. Use tag `"c"` for a concept card and `"k"` for a command card.

```js
F(10, "c", "What is the convoy effect in FCFS?", "Short jobs wait behind one long job, so the average waiting time goes up.");
```

**Add a quiz question.** In the `QUESTIONS` section call `M(module, difficulty, question, options, explanation)`. Difficulty is `"e"`, `"m"` or `"h"`. Put the correct option first; the app shuffles the order every time.

```js
M(12, "m",
  "What problem does aging solve in priority scheduling?",
  ["Starvation of low-priority processes", "Context-switch overhead", "Deadlock between processes"],
  "Aging slowly raises the priority of a process the longer it waits.");
```

Other helpers: `T` (true/false), `B` (fill in the blank), `S` (scenario), `C` (command) and `P` / `PM` (CPU-scheduling). Copy an existing entry of that type as a template.

**Content rules.** The course slides are the source of truth: keep their terminology, keep explanations beginner-friendly, and mark anything the source doesn't cover as *"Not provided in the source material"*.

## Roadmap

- [ ] Export / import progress as a JSON file to move between devices
- [ ] Installable PWA with offline support
- [ ] Spaced-repetition scheduling for flashcards
- [ ] Unit tests for the scheduling engines

## Contributing

Corrections and improvements to notes, questions and flashcards are welcome. Open an issue or a pull request and follow the content rules above.

## Disclaimer

This is an unofficial, student-made study aid. It is not affiliated with or endorsed by the course instructors or the university, and it doesn't replace the lectures or the official material. Double-check anything important against the official slides.

## Author

Built by **Shaurya**, B.Tech CSE (AI/ML) student at Newton School of Technology, Bangalore.
GitHub:((https://github.com/Shaurya818))
