# [NexGen] Universal Leave Logic & Calculator

> A scalable, AI-assisted leave liability engine built to replace manual calculations for 13,000+ employees across diverse contract types, exit scenarios, and calculation periods.

---

## The Problem

 The existing leave tool was limited to single-period calculations for exiting employees only. This forced the Total Rewards and HRBP teams to manually audit leave balances for all other scenarios — an estimated **80+ hours of lost productivity annually**, with significant risk of human error across complex, multi-variable calculations.

---

## The Solution

A self-service Excel-based calculator that handles the full spectrum of leave liability scenarios automatically — removing the need for manual intervention in the vast majority of cases.

### What It Covers

| Scenario | Supported |
|---|---|
| Resignation | ✅ |
| Retirement | ✅ |
| Change in Job Grade (Promotion / Regrading) | ✅ |
| Change in Leave Entitlement | ✅ |
| Transition from Full-Time to Part-Time | ✅ |

- Handles **3 simultaneous calculation periods** per case
- Covers **15+ distinct exit and leave sub-scenarios**
- Built for a workforce of **13,000+ employees** across multiple contract types

---

## How It Was Built

This project was built using an **AI-native builder approach**:

| Role | Owner |
|---|---|
| Problem definition & scoping | Irfaan (Human) |
| Business logic & calculation methodology | Irfaan (Human) |
| Formula architecture & structural design | Claude AI (Anthropic) |
| Edge case identification & test design | Irfaan (Human) |
| Formula stress-testing & validation | Irfaan + Claude AI |
| Final output verification | Irfaan (Human) |

The approach: define the problem clearly, own the logic and architecture, delegate engineering execution to AI, and rigorously validate every output before shipping.

---

## Quality Assurance

A dedicated **use case testing folder** was created to stress-test the calculator against edge cases across all supported scenarios. Key validation included:

- Multi-period calculation accuracy across overlapping entitlement windows
- Leap year handling — a legacy bug was identified and resolved to ensure mathematical accuracy in perpetuity
- Boundary condition testing for part-time proration and mid-year entitlement changes

---

## Status

🟡 **Pending company-wide rollout** — currently in final iterations in progress. Intended to become the standardised self-service tool for employees.

---

## Tools & Stack

| Tool | Purpose |
|---|---|
| Microsoft Excel | Calculator engine and user interface |
| Complex Conditional Logic | Multi-scenario branching and period calculations |
| Claude AI (Anthropic) | Formula generation, structural design, edge case testing |
| Prompt Engineering | Iterative refinement of logic, validation, and stress-testing |

---

## Skills Demonstrated

- **Business Problem Analysis** — translating a messy, manual HR process into a structured, automatable system
- **Prompt Engineering** — detailed context-setting, iterative instruction, and output validation using Claude AI
- **Logic Design** — designing calculation methodology for multi-period, multi-scenario leave liability
- **QA & Stress Testing** — building and executing a test suite to validate mathematical accuracy across edge cases
- **AI-Native Development** — using AI as the engineering layer while retaining full ownership of logic, architecture, and outcomes

---

## About the Builder

**Muhammad Irfaan Bin Abdul Rahaman**
Total Rewards Intern @ NCS (Singtel Group) | HR Professional | AI-Native Builder

- 🔗 [LinkedIn](https://www.linkedin.com/in/muhammad-irfaan-562373196)
- 🐙 [GitHub](https://github.com/byIrfaan)

> *"I am not a traditional developer. I am a domain expert who uses AI as my engineering team — speccing the problem, owning the logic, and shipping solutions that work in the real world."*

---

## Disclaimer

This project was built independently outside of work hours as a personal initiative and value-add contribution. 
