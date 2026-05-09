# Basic Python

> Learn Python from a real Technical Support and Solution Engineering perspective.

Python is one of the most important languages in:
- technical support automation
- cloud operations
- scripting
- APIs
- monitoring
- DevOps
- cybersecurity
- AI workflows
- startup infrastructure

Modern startups heavily rely on Python because it is:
- easy to read
- fast to develop with
- automation-friendly
- powerful for integrations
- widely used in cloud environments

This lesson focuses on practical Python for:
- support engineers
- solution engineers
- automation engineers
- startup operations teams

---

# Learning Goals

By the end of this lesson, learners should understand:

- what Python is
- how Python runs
- variables
- data types
- conditions
- loops
- functions
- files
- error handling
- APIs
- automation basics
- real support engineering use cases

---

# What Is Python?

Python is a programming language used to:
- automate repetitive work
- build APIs
- process data
- interact with cloud systems
- create monitoring tools
- integrate platforms

---

# Why Python Is Important for Startup Engineers

Python is used everywhere in startups for:
- automation
- integrations
- backend systems
- internal tooling
- monitoring
- AI systems
- SaaS operations

---

# Real Startup Examples

Python can:
- auto-route support tickets
- monitor endpoint health
- reset passwords automatically
- connect Slack alerts
- analyze logs
- automate onboarding
- generate reports
- call APIs

---

# Installing Python

---

# Verify Installation

Open terminal:

Windows:
```powershell
python --version
```

Linux/macOS:
```bash
python3 --version
```

Expected output:
```bash
Python 3.x.x
```

---

# Running Python

---

# Interactive Mode

Start Python:

```bash
python
```

or:

```bash
python3
```

Example:
```python
print("Hello World")
```

---

# Running Python Files

Create:
```bash
app.py
```

Run:
```bash
python app.py
```

---

# Your First Python Program

Create:
```python
print("Welcome to Technical Support Engineering")
```

---

# What `print()` Does

`print()` outputs information to the screen.

Example:
```python
print("Monitoring started")
```

Real startup systems often print:
- logs
- alerts
- statuses
- debugging info

---

# Variables

Variables store information.

---

# Example

```python
username = "hafeez"
ticket_count = 42
system_online = True
```

---

# Real Startup Example

```python
server_name = "support-api-01"
cpu_usage = 92
alert_active = True
```

---

# Naming Rules

Good variable names:
```python
ticket_priority
api_response
user_email
```

Bad variable names:
```python
x
a1
thing
```

---

# Data Types

---

# String

Text data.

```python
name = "Support Team"
```

---

# Integer

Whole numbers.

```python
ticket_count = 120
```

---

# Float

Decimal numbers.

```python
cpu_usage = 92.5
```

---

# Boolean

True/False values.

```python
server_online = True
```

---

# List

Stores multiple values.

```python
servers = ["api-1", "db-1", "cache-1"]
```

---

# Dictionary

Stores key-value data.

```python
ticket = {
    "user": "alice",
    "priority": "high",
    "status": "open"
}
```

---

# Why Dictionaries Matter

APIs heavily use JSON-like structures.

Example:
```json
{
  "priority": "high"
}
```

Python dictionaries are foundational for:
- APIs
- automation
- integrations

---

# Comments

Comments explain code.

```python
# Check CPU usage
```

---

# Why Comments Matter

Support engineers must document:
- automation logic
- troubleshooting steps
- scripts
- workflows

---

# Input

Python can accept user input.

Example:
```python
name = input("Enter your name: ")
print(name)
```

---

# Real Startup Example

```python
ticket_id = input("Enter ticket ID: ")
```

---

# Conditions

Conditions allow decision-making.

---

# Example

```python
cpu_usage = 95

if cpu_usage > 90:
    print("High CPU alert")
```

---

# Real Startup Example

```python
if disk_usage > 85:
    print("Disk almost full")
```

---

# Comparison Operators

| Operator | Meaning |
|---|---|
| `==` | Equal |
| `!=` | Not equal |
| `>` | Greater than |
| `<` | Less than |
| `>=` | Greater or equal |
| `<=` | Less or equal |

---

# Multiple Conditions

```python
if cpu_usage > 90 and memory_usage > 80:
    print("Critical alert")
```

---

# Loops

Loops repeat tasks.

Automation depends heavily on loops.

---

# Example

```python
for server in servers:
    print(server)
```

---

# Real Startup Example

Check multiple endpoints:
```python
servers = ["api", "db", "auth"]

for server in servers:
    print(f"Checking {server}")
```

---

# While Loop

```python
count = 0

while count < 5:
    print(count)
    count += 1
```

---

# Functions

Functions organize reusable code.

---

# Example

```python
def greet():
    print("Welcome")
```

Run:
```python
greet()
```

---

# Real Startup Example

```python
def check_server_status(server_name):
    print(f"Checking {server_name}")
```

---

# Parameters

```python
def greet(name):
    print(f"Hello {name}")
```

---

# Return Values

```python
def add(a, b):
    return a + b
```

---

# Why Functions Matter

Production systems require:
- reusable logic
- clean code
- maintainable automation

---

# Error Handling

Systems fail constantly.

Good engineers handle failures gracefully.

---

# Example

```python
try:
    number = int(input("Enter number: "))
except:
    print("Invalid input")
```

---

# Real Startup Example

```python
try:
    api_response = requests.get(url)
except:
    print("API unreachable")
```

---

# Reading Files

---

# Example

```python
with open("notes.txt", "r") as file:
    content = file.read()

print(content)
```

---

# Writing Files

```python
with open("log.txt", "w") as file:
    file.write("System online")
```

---

# Real Startup Use Cases

Python scripts commonly:
- analyze logs
- generate reports
- save monitoring data
- create backups

---

# Installing Packages

Python packages extend functionality.

---

# pip

Install packages:
```bash
pip install requests
```

---

# Important Beginner Packages

| Package | Purpose |
|---|---|
| requests | APIs |
| pandas | Data analysis |
| flask | Web apps |
| fastapi | APIs |
| rich | Better terminal output |

---

# APIs in Python

Python interacts heavily with APIs.

---

# Example

```python
import requests

response = requests.get("https://api.github.com")

print(response.status_code)
```

---

# Real Startup Example

A support automation script may:
- call Zendesk API
- create tickets
- send Slack alerts
- fetch monitoring data

---

# JSON Handling

Most APIs use JSON.

---

# Example

```python
import json

data = {
    "status": "online"
}

print(json.dumps(data))
```

---

# Real Startup Automation Example

```python
ticket = {
    "user": "alice",
    "priority": "high"
}
```

---

# Logging

Professional systems use logs.

---

# Basic Logging Example

```python
import logging

logging.basicConfig(level=logging.INFO)

logging.info("Monitoring started")
```

---

# Why Logging Matters

Production systems need:
- audit trails
- debugging visibility
- monitoring
- incident investigation

---

# Real Support Engineering Scripts

Python can automate:

| Automation | Example |
|---|---|
| Monitoring | CPU checks |
| Alerting | Slack alerts |
| Reporting | Ticket reports |
| Integrations | Zendesk APIs |
| Backups | File archiving |
| Onboarding | Account creation |

---

# Beginner Script Example

---

# CPU Alert Script

```python
cpu_usage = 95

if cpu_usage > 90:
    print("Critical CPU alert")
else:
    print("CPU normal")
```

---

# Beginner Monitoring Example

```python
servers = ["api", "db", "auth"]

for server in servers:
    print(f"{server} is online")
```

---

# Startup Engineering Mindset

Good engineers write scripts that are:
- readable
- reusable
- documented
- reliable
- simple
- maintainable

---

# Common Beginner Mistakes

| Mistake | Better Approach |
|---|---|
| Hardcoding everything | Use variables |
| No error handling | Use try/except |
| Messy scripts | Use functions |
| No comments | Document logic |
| Huge files | Organize code cleanly |

---

# Real Startup Engineering Advice

In real startup environments:
- automation saves time
- scripts reduce manual work
- APIs connect systems
- Python becomes a force multiplier

Small scripts can save:
- hours daily
- operational costs
- support workload

---

# Mini Exercises

---

# Exercise 1 — Greeting Script

Create:
```python
name = input("Enter your name: ")
print(f"Welcome {name}")
```

---

# Exercise 2 — CPU Alert

```python
cpu_usage = 92

if cpu_usage > 90:
    print("Critical alert")
```

---

# Exercise 3 — Server Loop

```python
servers = ["api", "db", "auth"]

for server in servers:
    print(server)
```

---

# Exercise 4 — File Writer

Write:
```python
System operational
```

into:
```bash
status.txt
```

---

# Exercise 5 — API Request

Install:
```bash
pip install requests
```

Fetch:
```python
https://api.github.com
```

---

# Beginner Project Idea

## Startup Support Health Checker

Build a script that:
- checks server names
- prints statuses
- logs results
- saves output to file

---

# Real Skills Built Here

This lesson develops:
- automation thinking
- scripting confidence
- debugging habits
- API understanding
- operational logic

These become foundational later for:
- DevOps
- cloud engineering
- support automation
- solution engineering
- AI workflows

---

# Key Takeaways

- Python is one of the most valuable startup engineering languages
- Automation reduces repetitive work
- APIs are critical in modern support systems
- Logging and error handling matter heavily
- Clean code improves maintainability
- Small scripts can create massive operational impact

---

# Next Lesson

Continue to:

```bash
basic-javascript.md
```

The next lesson explains:
- JavaScript fundamentals
- browser scripting
- frontend logic
- APIs in JavaScript
- modern SaaS environments
- support dashboard behavior
