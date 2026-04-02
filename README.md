# Emotional Intelligence Assessment — HUM1002

A minimal, professional Emotional Intelligence (EQ) assessment website built as a **single-file static application**.

The assessment measures workplace emotional intelligence across **5 dimensions**, followed by **case-based evaluation and written responses**, and generates **visual score analysis**.

---

## Features

- 25 Core EI Questions (Likert Scale)
- 5 Emotional Intelligence Dimensions
  - Self-Awareness  
  - Self-Regulation  
  - Motivation  
  - Empathy  
  - Social Skills
- Case Study Based Decision Questions
- Effectiveness Statements
- Written Response Section
- Automatic Scoring
- Pie Chart & Bar Chart Visualization
- Minimal, Professional UI
- Single File — No Backend Required

---

## Scoring

### Part 1 — Core EI

- 25 questions  
- Each scored 1–5  
- Total Score: **0–125**

#### Score Bands

| Score | Interpretation |
|------|---------------|
| 100–125 | High Emotional Intelligence |
| 63–99 | Moderate Emotional Intelligence |
| 25–62 | Low Emotional Intelligence |

Each dimension is scored independently (out of 25).

---

### Part 2 — Workplace Effectiveness

Includes:

- Case Study Questions  
- Effectiveness Statements  
- Written Responses  

Written responses are scored using a **word-count based heuristic**.  
No external APIs or AI services are used.

---

## Charts

The results page includes:

- Doughnut Chart — Score distribution across dimensions  
- Bar Chart — Your score vs assumed average  

Charts are generated using **Chart.js (CDN)**.

---

## Tech Stack

- HTML  
- CSS  
- Vanilla JavaScript  
- Chart.js (CDN)

No frameworks  
No backend  
No build step

---

## File Structure

Single-file project:

All UI, logic, scoring, and charts are contained in this file.

---
