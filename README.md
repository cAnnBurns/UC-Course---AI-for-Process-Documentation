# UC-Course---AI-for-Process-Documentation
# Daily Teaching Task Prioritization and Execution — SOP Documentation Repository

## Project Purpose

This repository contains a version-controlled documentation workflow for a classroom-teacher process: **prioritizing and completing daily instructional, communication, and operational tasks within fragmented work periods** while maintaining required obligations such as positive communication home, grading, planning, and lab readiness. :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

The repository is organized to support:
- clear separation of **source files** and **exports**
- reproducible documentation updates
- prompt logging for AI-assisted drafting/refinement
- QA and change tracking

---

## Process Overview

**Process Name:** Daily Teaching Task Prioritization and Execution :contentReference[oaicite:4]{index=4}

### Start Trigger
The process begins during the **initial 15-minute morning work period**, when tasks, deadlines, and constraints are reviewed. :contentReference[oaicite:5]{index=5}

### End State
The process ends at the conclusion of the school day after required tasks are completed, deferred/scheduled, and the classroom is reset for the next day. :contentReference[oaicite:6]{index=6}

---

## Time Constraints and Context

Daily work time occurs in fragmented blocks:
- **15 minutes** in the morning
- **30 minutes** during student study hall
- **30 minutes** during lunch
- **45 minutes** during plan period
- **20 minutes** at the end of the day (high interruption risk) :contentReference[oaicite:7]{index=7} :contentReference[oaicite:8]{index=8}

The final 20-minute block is primarily used for classroom reset tasks. :contentReference[oaicite:9]{index=9}

---

## Stakeholders

- Classroom teacher (process owner)
- Students
- Parents/guardians
- Fellow teachers
- School administrators
- School district (documentation/compliance) :contentReference[oaicite:10]{index=10} :contentReference[oaicite:11]{index=11}

---

## Systems and Tools (Examples Referenced in Process)

The attached scope/SOP documents reference tools and systems such as:
- Gmail (email communication)
- Google Classroom
- Snorkl
- ProgressBook
- Google Calendar
- SP26 Parent Communication spreadsheet
- Positive Communication Home form (Hub)
- Abre (student referrals)
- Lesson Summary Document
- Snorkl scoring rubric
- Wish List spreadsheet for lab supply needs :contentReference[oaicite:12]{index=12} :contentReference[oaicite:13]{index=13}

The SOP also documents an important access constraint: required systems are accessed via the classroom teacher’s laptop credentials / device access, and the full task list is not suitable for a substitute teacher. :contentReference[oaicite:14]{index=14}

---

## Key Requirements Captured in the Scope

The scope document identifies ongoing requirements including:
- one positive communication home daily (student identified after behavior occurs)
- district-level and personal documentation for positive communication
- weekly grading updates
- weekly lab supply review and tracking
- maintaining a clean classroom environment :contentReference[oaicite:15]{index=15}

---

## What’s Included in This Repository

This repository is intended to include the following artifact types:

- **Scope statement** (process boundaries, stakeholders, tools, inputs/outputs, requirements, exceptions)
- **SOP drafts and final SOP** (step-by-step procedure)
- **Diagram sources** (Mermaid / draw.io / BPMN source files)
- **Diagram exports** (PNG/PDF)
- **Prompt log** (AI prompt history and outputs)
- **QA notes/checklists** (quality review of SOP wording/structure)
- **Change log** (versioned revisions)

---

## Repository Structure

> Update folder/file names if your actual repo uses different names.

```text
daily-task-prioritization-sop/
├── README.md
├── inputs/
│   ├── scope/
│   │   └── Daily Task Prioritzation Scope.docx
│   └── sop/
│       └── Daily Task Prioritzation SOP.docx
├── scope/
│   └── scope_statement.md
├── sop/
│   ├── sources/
│   │   ├── sop_v0.md
│   │   ├── sop_v1.md
│   │   └── final_sop.md
│   └── exports/
│       └── final_sop.pdf
├── diagrams/
│   ├── sources/
│   │   ├── process_flow.mmd
│   │   ├── process_flow.drawio
│   │   └── process_flow.bpmn
│   └── exports/
│       ├── process_flow.png
│       └── process_flow.pdf
├── prompts/
│   ├── prompt_log.md
│   ├── qa_prompt_log.md
│   └── prompt_*.txt
├── qa/
│   └── sop_qa_checklist.md
├── changes/
│   └── change_log.md
└── exports/
    └── submission_bundle/
