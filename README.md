<div align="center">

# 🧫 Stan & Scoot Labs

**An AI-assisted playbook for taking app ideas from concept to launch.**

![Cursor](https://img.shields.io/badge/Cursor-AI%20Rules-000000?logo=cursor&logoColor=white)
![Prompts](https://img.shields.io/badge/Prompt-Library-10A37F?logo=openai&logoColor=white)
![Status](https://img.shields.io/badge/status-scaffold-lightgrey)

</div>

---

## 💡 What it is

A shared studio workspace with a repeatable process, prompt templates and Cursor rules, so each new app idea follows the same path: **validate → build → land → launch**.

> 🚧 **Status:** The structure is in place, and the playbook content is being written.

## 🔄 The workflow

```mermaid
flowchart LR
    I["💡 Idea"] --> V["🔍 Market validation<br/>prompts/market-validation.md"]
    V -->|"worth it?"| B["🛠️ Build the app<br/>prompts/build-app.md"]
    V -->|"no"| X["🗑️ Park it"]
    B --> L["🌐 Landing page<br/>prompts/create-landing-page.md"]
    L --> P["🚀 Launch plan<br/>prompts/launch-plan.md"]
    R["📏 Cursor rules<br/>.cursor/rules"] -.->|"guides AI at every step"| B
    R -.-> L
```

## 📂 Structure

```
00_START_HERE/
  HOW_THIS_WORKS.md        How the studio process works
  PROJECT_WORKFLOW.md      Step-by-step project lifecycle
  AI_PROMPT_TEMPLATES.md   Reusable prompt patterns
  CURSOR_RULES.md          How the AI coding rules are used
prompts/
  market-validation.md     Research demand & competition
  build-app.md             Build the MVP with AI
  create-landing-page.md   Generate the marketing page
  launch-plan.md           Go-to-market checklist
.cursor/rules/
  project-rules.mdc        Shared rules for Cursor
```

## 🔗 Related

- [App Validation System](https://github.com/scootero/App-Validation-System): the automated version of the validation step (n8n, Vercel and Meta ads)

---

<div align="center">

Built by **[Scott Oliver](https://github.com/scootero)**

</div>
