# Hermes Prompt Templates

> Useful prompt templates for common workflows with Hermes.

---

## 🐛 Bug Investigation

```markdown
Investigate this bug in [repo path]:

**Issue:** [link or description]
**Expected:** [what should happen]
**Actual:** [what's happening]
**Branch:** [current branch]

Inspect the repo, root-cause analysis first, then propose a fix plan.
Do not create branches or make changes without approval.
```

## 📝 Content Draft

```markdown
Draft a [type: script/post/email] about [topic].
Target audience: [describe].
Style: [practical/professional/casual].
Include: [specific elements].
Format: Markdown with tables and diagrams where helpful.
```

## 🏗️ Architecture Review

```markdown
Review this architecture: [describe or link].
Focus on: [reliability/scalability/security/cost].
Identify: top 3 risks and recommendations.
Format: Table with risk → impact → recommendation.
```

---

## 📋 Markdown Style Guide

| Element | When to use |
|:---|---|
| **Mermaid flowcharts** | Architecture, processes, decision trees |
| **Mermaid sequence diagrams** | API flows, handoffs, auth flows |
| **Tables** | Comparisons, specs, structured data, status |
| **Task lists** (`- [ ]`) | Progress tracking, todos |
| **Bullet hierarchies** | Over dense paragraphs |
| **Collapsible details** | Optional deep-dive content |
| **Code blocks** | Commands, configs, snippets |
