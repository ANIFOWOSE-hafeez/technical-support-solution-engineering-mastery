# Hardware Basics

> Understand the physical components of a computer so you can troubleshoot real-world IT issues in startup environments.

In Technical Support and Solution Engineering roles, hardware issues are very common.

You will often hear users say things like:
- “My laptop is slow”
- “My system is overheating”
- “It won’t turn on”
- “My screen is black”
- “My keyboard is not working”

To solve these issues properly, you must understand hardware.

---

# Learning Goals

By the end of this lesson, learners should understand:

- what computer hardware is
- major hardware components
- how hardware affects performance
- common hardware failures
- how to diagnose hardware issues
- startup device environments (laptops, servers, cloud machines)
- basic hardware troubleshooting workflow

---

# What Is Hardware?

Hardware refers to the physical parts of a computer system.

Unlike software (which is code), hardware is tangible.

Examples:
- CPU
- RAM
- Hard drive / SSD
- Motherboard
- Keyboard
- Mouse
- Monitor
- Battery

---

# Hardware in Startup Environments

In startups, hardware is everywhere:
- employee laptops
- office devices
- cloud servers (virtual hardware)
- networking equipment
- backup systems

Even cloud systems depend on physical hardware in data centers.

---

# Main Hardware Components

---

# 1. CPU (Processor)

## What It Does

The CPU processes instructions and runs programs.

It is responsible for:
- executing commands
- running applications
- processing data

---

## Startup Example

A developer runs:
```bash
npm start
```

The CPU handles:
- compiling code
- running processes
- managing system operations

---

## Common CPU Problems

| Issue | Effect |
|---|---|
| Overheating | System slows or shuts down |
| High usage | Lagging system |
| Old CPU | Slow performance |

---

# 2. RAM (Memory)

## What It Does

RAM stores temporary data while applications are running.

---

## Startup Example

A user opens:
- Chrome (20 tabs)
- Slack
- Zoom
- VS Code

RAM gets heavily used.

---

## RAM Problems

| Issue | Effect |
|---|---|
| Low RAM | Freezing |
| Memory leak | System slowdown |
| Too many apps | Performance drop |

---

# 3. Storage (HDD / SSD)

## What It Does

Storage permanently saves:
- files
- applications
- system data

---

## Types

| Type | Speed |
|---|---|
| HDD | Slow |
| SSD | Fast |
| NVMe SSD | Very fast |

---

## Startup Example

A support engineer investigates:

> “My laptop takes 5 minutes to boot.”

Possible cause:
- slow HDD
- full disk
- failing storage drive

---

# Storage Problems

| Issue | Effect |
|---|---|
| Full disk | System crashes |
| Slow disk | Long loading times |
| Corruption | Missing files |

---

# 4. Motherboard

## What It Does

The motherboard connects all components:
- CPU
- RAM
- storage
- ports
- peripherals

It is the communication hub of the system.

---

# 5. GPU (Graphics Processing Unit)

## What It Does

Handles:
- graphics
- video rendering
- visual processing

---

## Startup Usage

Important for:
- design teams
- AI/ML workloads
- video conferencing
- dashboards

---

# 6. Power Supply (Battery / PSU)

## What It Does

Provides power to all hardware components.

---

## Common Issues

| Issue | Effect |
|---|---|
| Faulty battery | Random shutdowns |
| Power failure | No boot |
| Voltage issues | System instability |

---

# 7. Network Hardware (NIC / Wi-Fi Adapter)

## What It Does

Connects your system to:
- Wi-Fi
- Ethernet
- internet services

---

## Startup Example

User reports:
> “No internet connection”

Possible hardware cause:
- disabled Wi-Fi adapter
- faulty NIC
- damaged router connection

---

# Input Devices

Devices used to send data into the computer:
- keyboard
- mouse
- microphone
- webcam

---

# Output Devices

Devices that display or output information:
- monitor
- speakers
- printer

---

# Hardware vs Software Issues

One of the most important support skills is distinguishing between hardware and software problems.

---

# Example Scenario

User says:
> “My laptop is very slow.”

Possible causes:

| Hardware | Software |
|---|---|
| Low RAM | Too many browser tabs |
| Failing SSD | Malware |
| Overheating CPU | Background apps |

Support engineers must diagnose correctly.

---

# Hardware Troubleshooting Method

Follow this structured approach:

---

## Step 1: Identify Symptoms

Ask:
- What exactly is not working?
- When did it start?
- Is it constant or random?

---

## Step 2: Check Power

- Is the device on?
- Is battery working?
- Any charging issues?

---

## Step 3: Check External Devices

- keyboard
- mouse
- monitor
- cables

---

## Step 4: Check Performance

Look for:
- CPU usage
- RAM usage
- disk usage

---

## Step 5: Inspect Hardware Behavior

- overheating
- fan noise
- unusual sounds
- slow boot

---

## Step 6: Isolate the Problem

Determine:
- component failure
- peripheral issue
- system-wide issue

---

# Common Hardware Issues in Startups

---

# 1. Overheating Systems

Caused by:
- dust buildup
- heavy CPU usage
- poor ventilation

---

# 2. Slow Laptops

Caused by:
- low RAM
- HDD storage
- background processes

---

# 3. Random Shutdowns

Caused by:
- battery failure
- overheating
- power issues

---

# 4. Peripheral Failures

Caused by:
- driver issues
- damaged cables
- faulty ports

---

# Startup Reality

In startups:
- employees work remotely
- devices are heavily used
- laptops run multiple SaaS tools
- systems stay on for long hours

Hardware problems are frequent.

---

# Hardware Lifecycle in Companies

1. Procurement (buy laptop)
2. Setup (install OS/software)
3. Deployment (assign to employee)
4. Usage (daily operations)
5. Maintenance (updates, repairs)
6. Replacement (end of life)

---

# Device Management in Startups

IT support engineers often handle:
- onboarding laptops
- replacing hardware
- fixing device issues
- tracking assets

---

# Basic Hardware Tools

Support engineers may use:
- diagnostic tools
- system monitors
- hardware test software
- BIOS/UEFI settings
- remote support tools

---

# BIOS / UEFI

## What It Is

Firmware that starts before the operating system.

Used for:
- hardware checks
- boot configuration
- system settings

---

# Why It Matters

Hardware issues often begin here:
- boot failures
- disk not detected
- memory errors

---

# Performance Monitoring Tools

---

# Windows

- Task Manager
- Device Manager

---

# Linux

```bash
top
htop
lshw
```

---

# Startup Support Example

A user complains:
> “My laptop freezes during Zoom calls.”

Investigation:
- CPU at 100%
- RAM usage maxed
- overheating detected

Root cause:
hardware + performance bottleneck

---

# Hardware Safety Best Practices

- avoid overheating
- keep devices updated
- avoid physical damage
- clean hardware periodically
- use proper charging practices

---

# Real Skills Built Here

This lesson develops:
- hardware awareness
- troubleshooting discipline
- system observation skills
- root cause thinking

---

# Key Takeaways

- Hardware is the physical foundation of computing
- Performance problems often start with hardware
- Support engineers must isolate hardware vs software issues
- Startup environments depend heavily on reliable devices
- Structured troubleshooting is critical

---

# Next Lesson

Continue to:

```bash
troubleshooting-method.md
```

Next you will learn:
- how real IT engineers solve problems step-by-step
- structured debugging frameworks used in startups
- incident resolution thinking
