# Markdown

> Learn Markdown because modern engineers document everything.

Markdown is one of the most important communication skills in:
- GitHub
- technical documentation
- READMEs
- engineering notes
- knowledge bases
- troubleshooting guides
- onboarding documentation
- startup operations

A strong engineer is not only someone who can solve problems.

A strong engineer can also:
- explain solutions clearly
- document systems professionally
- write readable technical guides
- communicate with teams asynchronously

Markdown is the industry standard for lightweight technical writing.

---

# Learning Goals

By the end of this lesson, learners should understand:

- what Markdown is
- why engineers use Markdown
- Markdown syntax
- headings
- lists
- links
- images
- code blocks
- tables
- checklists
- GitHub README formatting
- startup documentation habits
- professional engineering documentation structure

---

# What Is Markdown?

Markdown is a lightweight formatting language used to create structured text.

Markdown is commonly used in:
- GitHub repositories
- technical documentation
- internal wikis
- SaaS documentation
- developer portals
- startup knowledge bases

---

# Why Markdown Matters in Startups

Startup teams move fast.

Good documentation helps teams:
- onboard faster
- troubleshoot faster
- collaborate remotely
- reduce repeated questions
- preserve technical knowledge

Poor documentation creates:
- confusion
- repeated mistakes
- slow onboarding
- operational bottlenecks

---

# Real Startup Examples

Markdown is used for:
- README files
- deployment guides
- API docs
- incident reports
- troubleshooting notes
- architecture explanations
- onboarding checklists

---

# What a README Is

A README is usually the first file users see in a GitHub repository.

Example:
```bash
README.md
```

It explains:
- what the project does
- how to install it
- how to run it
- how to contribute
- why it exists

---

# Why Great READMEs Matter

Good READMEs:
- make projects look professional
- improve hiring visibility
- help recruiters understand your work
- help collaborators contribute
- improve portfolio quality

---

# Markdown File Extension

Markdown files use:
```bash
.md
```

Examples:
```bash
README.md
architecture.md
api.md
troubleshooting.md
```

---

# Headings

Headings organize content.

---

# Level 1 Heading

```md
# Main Title
```

Result:
# Main Title

---

# Level 2 Heading

```md
## Section Title
```

---

# Level 3 Heading

```md
### Subsection
```

---

# Best Practice

Use headings to structure documents clearly.

Good structure:
```md
# Project Title
## Overview
## Features
## Installation
## Usage
## API
## Troubleshooting
```

---

# Paragraphs

Normal text is written directly.

Example:
```md
This project automates support ticket routing.
```

---

# Bold Text

```md
**Important**
```

Result:
**Important**

---

# Italic Text

```md
*Note*
```

Result:
*Note*

---

# Strikethrough

```md
~~deprecated~~
```

Result:
~~deprecated~~

---

# Lists

---

# Bullet Lists

```md
- Monitoring
- Alerting
- Logging
```

Result:
- Monitoring
- Alerting
- Logging

---

# Numbered Lists

```md
1. Install dependencies
2. Run the application
3. Check logs
```

Result:
1. Install dependencies
2. Run the application
3. Check logs

---

# Nested Lists

```md
- Infrastructure
  - Monitoring
  - Networking
```

Result:
- Infrastructure
  - Monitoring
  - Networking

---

# Links

---

# Basic Link

```md
[GitHub](https://github.com)
```

Result:
[GitHub](https://github.com)

---

# Real Startup Usage

Documentation often links to:
- dashboards
- APIs
- repositories
- monitoring systems
- cloud consoles

---

# Images

---

# Markdown Image Syntax

```md
![Dashboard](assets/dashboard.png)
```

---

# Real Startup Examples

Images are commonly used for:
- architecture diagrams
- screenshots
- dashboards
- workflows
- monitoring panels

---

# Code Blocks

Code blocks are critical in engineering documentation.

---

# Inline Code

```md
Use `docker compose up`
```

Result:
Use `docker compose up`

---

# Multi-line Code Block

---md
```bash
docker compose up
```
## Result

```bash
docker compose up
```

---

# Syntax Highlighting

Specify language for readability.

Examples:
- `bash`
- `python`
- `json`
- `yaml`
- `javascript`

---

# Example

```python
print("Hello")
```

## Result

```python
print("Hello")
```

---

# Why Code Blocks Matter

Support engineers constantly document:
- commands
- scripts
- configs
- API examples
- troubleshooting steps

---

# Blockquotes

Useful for notes or warnings.

```md
> Important: Never expose API keys publicly.
```

## Result

> Important: Never expose API keys publicly.

---

# Horizontal Lines

```md
---
```

Creates separation sections.

---

# Tables

Tables organize structured information.

---

# Example

```md
| Tool | Purpose |
|---|---|
| Git | Version control |
| Docker | Containers |
```

## Result

| Tool | Purpose |
|---|---|
| Git | Version control |
| Docker | Containers |

---

# Why Tables Matter

Useful for:
- tool comparisons
- API documentation
- troubleshooting matrices
- feature lists

---

# Checklists

Very common in startup operations.

---

# Example

```md
- [x] Monitoring configured
- [ ] Alerts configured
- [ ] Backup verified
```

## Result

- [x] Monitoring configured
- [ ] Alerts configured
- [ ] Backup verified

---

# Real Startup Uses

Checklists help with:
- onboarding
- deployments
- incident response
- production readiness
- compliance tracking

---

# Escaping Characters

Sometimes special characters need escaping.

## Example

```md
\# Not a heading
```

---

# Markdown and GitHub

GitHub automatically renders Markdown beautifully.

This is why GitHub portfolios rely heavily on:
- structured READMEs
- markdown docs
- architecture notes
- case studies

---

# Professional README Structure

A strong GitHub README usually contains:

```md
# Project Title

## Overview

## Problem

## Solution

## Features

## Tech Stack

## Installation

## Usage

## API Examples

## Architecture

## Screenshots

## Logs

## Future Improvements

## License
```

---

# Real Startup README Example

```md
# AI Ticket Router

An AI-powered support automation platform that classifies and routes incoming tickets automatically.

## Features

- NLP classification
- Priority assignment
- Zendesk integration
- API support
```

---

# Documentation Best Practices

Good documentation should be:
- clear
- structured
- readable
- practical
- concise
- searchable

---

# Bad Documentation Example

```md
This app does stuff.
```

---

# Better Example

```md
This application monitors endpoint health across distributed startup teams and triggers alerts when thresholds are exceeded.
```

---

# Real Startup Documentation Types

| Documentation | Purpose |
|---|---|
| README | Project overview |
| API docs | Endpoint explanations |
| Runbooks | Incident response |
| SOPs | Standard procedures |
| Architecture docs | System design |
| Troubleshooting docs | Support guidance |

---

# Markdown in Knowledge Bases

Support teams heavily use Markdown in:
- Confluence
- Notion
- GitHub Wiki
- internal docs
- runbooks

---

# Real Support Engineering Example

A support engineer may document:

```md
# VPN Troubleshooting

## Symptoms

- Connection timeout
- Authentication failure

## Resolution

1. Restart VPN client
2. Verify MFA
3. Reconnect
```

---

# Markdown for Portfolio Building

Markdown helps learners:
- showcase projects
- explain architecture
- demonstrate communication skills
- look more professional to recruiters

---

# Common Beginner Mistakes

| Mistake | Better Approach |
|---|---|
| Huge text walls | Use headings |
| No code formatting | Use code blocks |
| Poor structure | Organize sections |
| No screenshots | Add visuals |
| Weak explanations | Explain business impact |

---

# Real Startup Engineering Advice

Strong engineers:
- document continuously
- write clear READMEs
- explain systems simply
- leave operational knowledge behind

Documentation is a force multiplier.

---

# Mini Exercises

---

# Exercise 1 — Create a README

Create:

```bash
README.md
```

Add:
- project title
- overview
- features

---

# Exercise 2 — Create a Table

Document tools:

| Tool | Purpose |
|---|---|
| Python | Automation |
| Git | Version control |

---

# Exercise 3 — Add Code Blocks

Document:

```bash
python app.py
```

---

# Exercise 4 — Add Checklist

```md
- [x] Install Python
- [x] Install Git
- [ ] Deploy application
```

---

# Exercise 5 — Add Screenshot Section

Create:

```md
## Screenshots
```

---

# Beginner Project Idea

## Startup Troubleshooting Knowledge Base

Create Markdown documentation for:
- VPN troubleshooting
- password resets
- Wi-Fi issues
- browser issues

Organize professionally in GitHub.

---

# Real Skills Built Here

This lesson develops:
- technical writing
- documentation habits
- communication clarity
- operational structure
- GitHub professionalism

These become critical later in:
- support engineering
- solution engineering
- DevOps
- architecture
- consulting
- technical leadership

---

# Key Takeaways

- Markdown is essential for modern engineering work
- GitHub relies heavily on Markdown
- Good documentation improves operations
- READMEs are extremely important professionally
- Engineers communicate through documentation daily
- Structured documentation reduces operational chaos

---

# Next Lesson

Continue to:

```bash
excel-google-sheets.md
```

The next lesson explains:
- version control
- repositories
- commits
- branches
- pull requests
- collaboration workflows
- professional GitHub engineering practices
