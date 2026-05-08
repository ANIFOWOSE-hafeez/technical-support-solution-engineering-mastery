# 01-beginner-foundations

# Beginner Foundations

> Build the technical mindset, habits, and foundational knowledge required to become a strong Technical Support Engineer or Solution Engineer.

---

# Module Goal

This module is designed to transform complete beginners into technically confident learners capable of:

- understanding how computers and systems work
- troubleshooting basic technical problems
- using command line tools
- documenting technical work professionally
- thinking logically through technical problems
- building the habits required for production environments

This is the foundation for everything else in the repository.

---

# Why This Module Matters

Most support engineers fail because they:
- memorize commands without understanding systems
- panic during troubleshooting
- cannot explain technical problems clearly
- cannot document work properly
- lack structured thinking

This module focuses heavily on:
- systems thinking
- troubleshooting logic
- communication
- documentation
- foundational technical confidence

---

# Learning Strategy

Each topic in this module should be studied in this order:

1. Understand the concept  
2. Learn the real-world purpose  
3. Practice hands-on  
4. Break something safely  
5. Troubleshoot it  
6. Document what happened  

---

# Topics To Master

---

# 1. Computer Fundamentals

## Goal

Understand what a computer actually is and how systems interact internally.

---

# Core Concepts

## What Is a Computer?

A computer is a machine that:
- receives input
- processes data
- stores information
- produces output

---

# Main Components

## CPU (Central Processing Unit)

The CPU:
- executes instructions
- processes calculations
- controls operations

### Important Concepts
- cores
- threads
- clock speed
- cache
- architecture

### Real Startup Relevance
High CPU usage can:
- slow applications
- crash services
- affect customer experience

Support engineers often investigate:
- CPU spikes
- runaway processes
- overloaded systems

---

## RAM (Memory)

RAM stores temporary active data.

### Important Concepts
- volatile memory
- memory allocation
- swapping
- memory leaks

### Real Startup Relevance
Insufficient RAM can:
- freeze systems
- crash applications
- slow browsers
- affect virtualization

---

## Storage

### HDD
- mechanical
- slower
- cheaper

### SSD
- faster
- modern standard
- better startup performance

### NVMe SSD
- extremely fast
- common in cloud and production systems

---

# Input Devices

Examples:
- keyboard
- mouse
- scanner
- microphone

---

# Output Devices

Examples:
- monitor
- printer
- speakers

---

# Operating System

The operating system manages:
- hardware
- memory
- processes
- files
- applications

Examples:
- Windows
- Linux
- macOS

---

# Real Startup Thinking

A support engineer must understand:
- where failures happen
- what component is responsible
- how system resources affect applications

---

# Beginner Exercises

## Exercise 1
Open Task Manager and identify:
- CPU usage
- RAM usage
- disk usage

---

## Exercise 2
Research:
- difference between RAM and storage
- SSD vs HDD
- CPU cores vs threads

---

# Skills To Gain

- understanding hardware bottlenecks
- identifying performance problems
- understanding system resource usage

---

# 2. Operating Systems Basics

## Goal

Understand how operating systems work and why support engineers rely heavily on them.

---

# What Is an Operating System?

An OS acts as the bridge between:
- hardware
- software
- users

---

# Main Operating Systems

| OS | Common Usage |
|---|---|
| Windows | Enterprise desktops |
| Linux | Servers, cloud, DevOps |
| macOS | Development, design |

---

# Critical Concepts

## Processes

A process is:
- a running program

Examples:
- browser
- Zoom
- VS Code

Support engineers often:
- kill frozen processes
- investigate runaway applications

---

## Services

Background applications that run automatically.

Examples:
- databases
- web servers
- VPN services

---

## File Permissions

Permissions determine:
- who can read
- who can write
- who can execute files

---

# Real Startup Relevance

Production outages often involve:
- failed services
- permission issues
- broken processes
- OS resource exhaustion

---

# Beginner Labs

## Windows
Learn:
- Task Manager
- Event Viewer
- Services
- Device Manager

---

## Linux
Learn:
- terminal basics
- systemctl
- ps
- top
- htop

---

# 3. File Systems and Folders

## Goal

Understand how data is organized inside systems.

---

# Important Concepts

## Files
Contain:
- data
- code
- logs
- configurations

---

## Directories/Folders
Organize files.

---

# Common File Types

| Extension | Meaning |
|---|---|
| .txt | text |
| .log | logs |
| .json | API data |
| .yaml | configs |
| .py | Python |
| .sh | shell script |

---

# Critical Startup Relevance

Support engineers constantly work with:
- logs
- config files
- backups
- scripts
- documentation

---

# Folder Structure Thinking

Good engineers organize systems clearly.

Bad structure causes:
- confusion
- deployment issues
- operational mistakes

---

# Beginner Practice

Create:
```bash
support-lab/
├── logs/
├── scripts/
├── docs/
├── configs/
└── backups/
```

---

# 4. Hardware Basics

## Goal

Understand physical infrastructure and endpoint devices.

---

# Core Hardware

## Motherboard
Connects components.

---

## Network Interface Card (NIC)
Enables networking.

---

## GPU
Handles graphics processing.

---

## Power Supply
Provides electricity.

---

# Common Hardware Problems

| Problem | Possible Cause |
|---|---|
| Slow PC | low RAM |
| Random shutdowns | overheating |
| No internet | NIC failure |
| No display | GPU issue |

---

# Support Mindset

Do not guess.

Always:
1. isolate variables
2. test assumptions
3. verify symptoms

---

# 5. Troubleshooting Method

## Goal

Develop structured problem-solving skills.

---

# Golden Rule

Never troubleshoot randomly.

---

# Professional Troubleshooting Flow

## Step 1 — Identify the Problem

Questions:
- what changed?
- when did it start?
- who is affected?
- can it be reproduced?

---

## Step 2 — Gather Evidence

Check:
- logs
- screenshots
- metrics
- error messages

---

## Step 3 — Form Hypotheses

Possible causes:
- DNS
- permissions
- service outage
- expired token
- bad deployment

---

## Step 4 — Test Safely

Change ONE thing at a time.

---

## Step 5 — Verify the Fix

Confirm:
- issue resolved
- no side effects

---

## Step 6 — Document Everything

Always record:
- root cause
- fix
- prevention steps

---

# Real Startup Relevance

Good troubleshooting saves:
- downtime
- revenue
- customer trust

---

# 6. Networking Basics

## Goal

Understand how devices communicate.

---

# Core Concepts

## IP Address

Unique identifier for devices.

Example:
```bash
192.168.1.10
```

---

## Router

Directs traffic between networks.

---

## Switch

Connects local devices.

---

## DNS

Converts:
```bash
google.com
```

into:
```bash
142.250.x.x
```

---

## VPN

Secure encrypted connection.

---

# Important Support Skills

Learn:
- ping
- tracert/traceroute
- nslookup
- ipconfig
- ifconfig

---

# Real Startup Relevance

Most support incidents involve:
- DNS
- connectivity
- VPNs
- firewalls
- routing

---

# 7. Internet Protocols

## Goal

Understand the rules systems use to communicate.

---

# Core Protocols

| Protocol | Purpose |
|---|---|
| HTTP | web traffic |
| HTTPS | secure web traffic |
| TCP | reliable communication |
| UDP | fast communication |
| DNS | domain resolution |
| SSH | secure remote access |
| SMTP | email sending |

---

# Real Startup Thinking

Support engineers constantly troubleshoot:
- SSL failures
- API connectivity
- DNS propagation
- blocked ports

---

# 8. Command Line Basics

## Goal

Become comfortable operating systems without GUIs.

---

# Why Command Line Matters

Production systems often:
- have no GUI
- run remotely
- require automation

---

# Essential Commands

## Windows
```powershell
dir
cd
mkdir
copy
move
ping
ipconfig
tasklist
```

---

## Linux
```bash
ls
cd
mkdir
cp
mv
pwd
cat
grep
chmod
curl
```

---

# Startup Reality

Strong command line skills dramatically improve:
- troubleshooting speed
- automation capability
- cloud operations

---

# 9. Basic Scripting Logic

## Goal

Learn how automation thinking works.

---

# Core Concepts

- variables
- conditions
- loops
- functions
- input/output

---

# Example Logic

```python
if vpn_status == "down":
    restart_service()
```

---

# Real Startup Relevance

Support engineers automate:
- onboarding
- password resets
- monitoring
- backups
- reporting

---

# 10. Basic Python

## Goal

Use Python for support automation.

---

# Why Python?

Python is:
- beginner friendly
- automation focused
- API friendly
- widely used in startups

---

# Important Skills

Learn:
- variables
- loops
- functions
- file handling
- APIs
- requests library

---

# Starter Projects

- password generator
- disk usage checker
- log parser
- simple API client

---

# 11. Basic JavaScript

## Goal

Understand frontend logic and browser scripting.

---

# Learn

- variables
- functions
- DOM basics
- fetch API
- browser console

---

# Why This Matters

Support engineers troubleshoot:
- web apps
- browser errors
- frontend integrations
- authentication issues

---

# 12. Git and GitHub

## Goal

Learn version control and portfolio publishing.

---

# Important Concepts

- repositories
- commits
- branches
- pull requests
- markdown
- README files

---

# Real Startup Relevance

Engineering teams use Git daily.

---

# 13. Markdown

## Goal

Document professionally.

---

# Learn

- headings
- lists
- tables
- code blocks
- images
- links

---

# Why It Matters

Documentation quality affects:
- onboarding
- troubleshooting
- scalability

---

# 14. Excel / Google Sheets

## Goal

Handle operational data efficiently.

---

# Learn

- filtering
- sorting
- formulas
- pivot tables
- reporting

---

# Startup Relevance

Support teams track:
- incidents
- assets
- tickets
- SLAs

---

# 15. Ticketing Systems Basics

## Goal

Understand support operations.

---

# Important Concepts

- tickets
- SLAs
- escalation
- priority
- severity

---

# Common Tools

- Zendesk
- Jira
- Freshdesk
- ServiceNow

---

# 16. Professional Communication

## Goal

Communicate clearly under pressure.

---

# Learn

- concise writing
- active listening
- escalation language
- status updates
- technical explanation

---

# Real Startup Reality

Poor communication creates:
- confusion
- escalations
- customer frustration

---

# 17. Basic Cybersecurity Hygiene

## Learn

- MFA
- phishing awareness
- password security
- least privilege
- secure browsing

---

# 18. Basic Cloud Concepts

## Learn

- servers
- virtual machines
- containers
- cloud regions
- scalability

---

# 19. Basic API Concepts

## Learn

- requests
- responses
- JSON
- authentication
- endpoints

---

# 20. Time Management

## Learn

- prioritization
- ticket management
- focus systems
- interruption handling

---

# 21. Active Listening

## Learn

- clarifying questions
- issue confirmation
- empathy without assumptions

---

# 22. Problem Decomposition

## Learn

Break large issues into:
- smaller systems
- smaller tests
- isolated variables

---

# 23. Professional Email Writing

## Learn

- clarity
- structure
- concise updates
- customer-friendly explanations

---

# 24. Presentation Basics

## Learn

- demos
- architecture walkthroughs
- explaining systems visually

---

# Beginner Projects

---

# 1. Personal IT Troubleshooting Notebook

Document:
- issues
- causes
- fixes
- lessons learned

---

# 2. GitHub Profile Setup

Create:
- profile README
- pinned repositories
- project screenshots

---

# 3. Basic Command Line Practice Repo

Build:
- file management examples
- networking commands
- scripts

---

# 4. Simple Python Utility Script

Ideas:
- disk checker
- password generator
- file organizer

---

# 5. Basic Documentation Project

Write:
- setup guides
- troubleshooting guides
- FAQ documents

---

# Final Beginner Goal

By the end of this section, learners should:
- think more systematically
- troubleshoot more confidently
- document more professionally
- understand technical environments better
- be ready for real support engineering workflows

---

# Next Module

Continue to:

```bash
02-core-it-support/
```

The next module introduces:
- real-world support workflows
- troubleshooting production issues
- ticket triage
- escalation systems
- monitoring
- identity management
- operational thinking
