# 🏗️ Strukture

**The Professional Suite for Architectural Visualization & File Documentation**

Strukture is an advanced, client-side utility designed for software architects and developers.  
It transforms conceptual project hierarchies into documentation-grade ASCII trees, physical folder structures, and high-resolution visuals.

[Open the Application](https://strukture.ableproman.hu) • [Source Code](https://github.com/ableproman/strukture/index.html)

---

## 🚀 The Vision

In modern software development, clarity is currency. Manually typing out file hierarchies for GitHub READMEs, technical blogs, or onboarding wikis is a repetitive, error-prone task that scales poorly.

Strukture eliminates this friction. It provides a real-time, bidirectional environment where you can type a structure, refactor it with AI, validate its logic, and export it into five different professional formats instantly.

---

## ✨ Enterprise-Grade Features

### 🪄 The "Magic Three" Refactor Engine

One click to perfection. Our internal engine handles the heavy lifting of directory hygiene:

- **Auto-Sort**  
  Alphabetically organizes your files and folders. Context-aware, ensuring comments and annotations (`//`) stay pinned to the correct line.

- **Fix Indent**  
  Detects inconsistent spacing and standardizes the entire tree to a perfect 2-space hierarchical format.

- **Auto-Slash**  
  Analyzes logic to identify folders vs. files, ensuring all directories end with the standard `/` suffix.

---

### 🤖 Gemini AI Architect (BYOK)

Bring your own Google Gemini API key to unlock a built-in architectural consultant:

- **AI Architect**  
  Prompt with a concept (e.g. *"A scalable AWS Lambda microservice using TypeScript and Clean Architecture"*) and get a full boilerplate structure in seconds.

- **AI Audit**  
  Run a professional review on your current tree. The AI identifies missing standard files (like `.env.example` or `LICENSE`) and suggests structural optimizations.

---

### 🛠️ The Bootstrapper (Physical Exports)

We go beyond simple text visualization. Use Strukture to actually start your project:

- 📁 **ZIP Bootstrapper**  
  Download a physical archive containing the empty directory structure you designed. Unzip and start coding immediately.

- 💻 **CLI Command Generator**  
  Generates a single, optimized shell command for Bash/Zsh or PowerShell to recreate the tree on your local disk using `mkdir` and `touch`.

---

### 🖼️ Documentation-Ready Visuals

- **High-Res PNG**  
  Capture your tree as a polished image for social media, Jira tickets, or pitch decks.

- **Vector SVG**  
  Export lossless vector graphics for technical blogs and high-quality web embedding.

- **Mermaid.js Support**  
  Convert your tree into Mermaid diagram code for live rendering in supported Markdown viewers.

---

### 🔍 Validation & Navigation

- **Real-Time Guardrails**  
  Alerts you if a file is mistakenly used as a parent directory or if naming conflicts occur within the same scope.

- **Live Search**  
  Efficiently filter through massive hierarchies with a lightning-fast search bar that maintains structural context.

- **Interactive Breadcrumbs**  
  Click through the breadcrumb trail to instantly jump your cursor to a specific file or folder in the editor.

- **Reverse Parser**  
  Paste an existing ASCII tree from a legacy document to revive it into editable source code.

---

### 🎨 Design & Experience

- **Multi-Style Connector Logic**  
  Switch between Round, Modern, Classic, or Minimal ASCII styles to match your project's branding.

- **PWA-Ready**  
  Fully responsive interface optimized for desktop precision and mobile speed.

- **Browser Persistence**  
  All projects are saved locally in IndexedDB. No cloud account required.

---

## 💻 Local Development

Strukture is built to be *forever-green* — no frameworks, no build steps, no dependencies.

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/strukture.git

# 2. Open index.html
# That's it. Pure speed.
