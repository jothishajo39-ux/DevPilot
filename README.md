# 🚀 DevPilot — AI Developer Productivity Assistant

Five tools your workflow needs. One place to run them.

DevPilot reviews your code, writes your docs, explains your errors, maps your repo, and drafts your commit messages — without switching tabs.

🔗 **Live Demo:** [jothishajo39-ux.github.io/DevPilot](https://jothishajo39-ux.github.io/DevPilot/)

## 💡 Problem
Developers lose time moving between separate tools for code review, documentation, debugging, onboarding, and commit messages. DevPilot puts all five behind one input box.

## 🚀 Features

| Tool | What it does |
|---|---|
| 🔍 **Code Review** | Flags bugs, security issues, and bad practices with plain-language explanations and fixes |
| 📝 **Documentation** | Generates a README-style overview, docstrings, and a usage example from raw code |
| 🐛 **Debug** | Takes an error message + code, returns root cause and a corrected snippet |
| 🗺️ **Repo Navigator** | Points new contributors to the right file for a given codebase question |
| ✅ **Commit Generator** | Turns a diff into a conventional commit message and a short PR description |

## ⚙️ How It Works
1. Pick a tool — review, docs, debug, navigate, or commit
2. Paste your input (or click "Try sample" for a ready example)
3. Run it — DevPilot returns a structured, judge-friendly result
4. Reuse the output — copy the fix, docs, or commit message straight into your repo

## 🛠️ Tech Stack
- HTML, CSS, JavaScript (static frontend)
- Backend-ready — designed to connect to Claude/OpenAI API via a Node/Flask endpoint

## 📌 Note
This is a static demo build — results shown are pre-written examples, not live model output. To make it fully functional, wire the `run()` function to a backend endpoint that calls the Claude or OpenAI API with the DevPilot system prompt.

## 🏆 Built For
Hackathon demo — static frontend, backend-ready

## ⚙️ Installation
```bash
git clone https://github.com/jothishajo39-ux/DevPilot.git
cd DevPilot
```
Open `index.html` in your browser.

## 👤 Author
Jothisha
