# 🧠 Hermes AI — Second Brain Vault

> **Purpose:** This vault is the persistent knowledge base for Krishna Kant's work across Supercheck, Prodline, YouTube, career, and personal projects. Hermes reads, writes, and organizes Markdown notes here.

---

## 📐 Vault Structure (P.A.R.A.)

```mermaid
flowchart TD
    Inbox["📥 00-Inbox<br/>Raw research, drops, ideas"] --> Projects
    Inbox --> Areas
    Projects["📁 01-Projects<br/>Active: Supercheck, Prodline, YouTube"] --> Archive
    Areas["🗂️ 02-Areas<br/>Ongoing: SRE, Finance, Health"] --> Archive
    Resources["📚 03-Resources<br/>Templates, runbooks, references"]
    Archive["🗄️ 04-Archive<br/>Completed & old notes"]
```

| Folder | What goes in | Example |
|:---|---|:---|
| 📥 **00-Inbox** | Raw drops — research, links, quick thoughts | "K8s network policy notes", "video idea" |
| 📁 **01-Projects** | Active project notes | Supercheck roadmap, Prodline scripts |
| 🗂️ **02-Areas** | Ongoing responsibilities | SRE learnings, fitness log, finance |
| 📚 **03-Resources** | Reference material | Docker compose snippets, API docs |
| 🗄️ **04-Archive** | Completed or stale notes | Old sprint plans, deprecated notes |

---

## 🔄 Sync & Usage

```mermaid
flowchart LR
    Krishna["💬 Krishna (Telegram)"] --> Hermes["🤖 Hermes Agent"]
    Hermes --> Vault["📓 Obsidian Vault<br/>workspaces/obsidian/"]
    Vault --> Git["🌿 Git Remote"]
    Krishna --> Vault
```

| Action | How |
|:---|---|
| Hermes writes notes | Drops research, summaries, plans into appropriate folders |
| Krishna reads/edits | Directly in Obsidian app (Mac/iPhone) or via Git |
| Sync | Vault is a Git repo — push/pull to remote for cross-device |

---

## 📝 Note Standard

> All notes in this vault follow a **structured, visual, minimal-verbosity** style:
> - **Mermaid diagrams** for architecture, flows, and relationships
> - **Tables** for comparisons, specs, and structured data
> - **Task lists** for progress tracking
> - **Bullet hierarchies** over dense paragraphs
> - **Concise** — every line earns its place

---

_Last updated: 2026-07-07_
