# Leadership Portfolio Redesign

## Overview

This project is a redesign of the **PDGMS Leadership Portfolio** for the **DeepThought Product Management Internship Assignment**.

The objective of this redesign was to transform the existing dashboard-style employee portfolio into a **narrative-driven career artifact** that feels more like a **career pitch deck** than an analytics dashboard.

The redesigned portfolio focuses on storytelling, information hierarchy, and employee identity while preserving complete fidelity to the underlying backend data.

---

## Problem Statement

The existing Leadership Portfolio presented employee performance as a collection of metrics and widgets with equal visual weight.

This redesign addresses the following challenge:

> **How can a data-heavy employee performance report be transformed into a story-driven portfolio that employees would proudly share with mentors, managers, and their future selves?**

---

## Design Approach

The redesign follows these principles:

* **Narrative First, Data Second**
* **Single Story-Driven Scrolling Experience**
* **Strong Information Hierarchy**
* **Career Artifact over Dashboard**
* **Progressive Disclosure**
* **Complete Data Fidelity**

The portfolio answers six questions:

1. How did I perform this month?
2. What did I deliver?
3. How did I grow?
4. What business impact did I create?
5. What challenges did I navigate?
6. Where is my career headed?

---

## Features

### Executive Summary

* Employee identity
* Monthly story
* Composite score
* Career pace
* Current and projected level

### Contribution Highlights

* Deliverable completion summary
* Knowledge contributions
* Completion metrics

### Capability Growth

* Six-axis capability scores
* Growth narratives
* Threshold indicators

### Business Impact

* KPI performance table
* Verified KPI summary

### Challenges Navigated

* Constraint overview
* Challenge categories
* Key blockers

### Career Journey

* Career trajectory timeline
* Promotion projections
* Development gap analysis

### Evidence Appendix

* Supporting evidence and portfolio metadata

---

## Tech Stack

* HTML5
* CSS3

No JavaScript or external frameworks were used.

---

## Project Structure

```text
.
├── index.html
├── style.css
├── README.md
├── screenshots/
│   └── portfolio-preview.png
└── design-rationale.pdf
```

---

## Design Decisions

### Narrative-First Layout

Each section begins with a narrative before presenting metrics. This allows readers to understand the significance of achievements before reviewing supporting data.

### Single Scrolling Experience

The portfolio uses a single-page layout to preserve storytelling continuity and create a pitch-deck-like reading experience.

### Prominent Identity

Employee identity and career signal are displayed prominently to reinforce that this is the employee's personal career artifact.

---

## Data Fidelity

All displayed values, narratives, scores, milestones, and metrics are derived directly from the provided backend data model and mock portfolio dataset.

No additional performance metrics or backend fields were invented.

---

## Submission Notes

This submission contains:

* Static HTML/CSS implementation
* Narrative-driven portfolio redesign
* Complete data preservation
* Product design rationale
* Hand-drawn wireframe (submitted separately)

---

## Author

**Krishna Mehta**

DeepThought Product Management Internship Assignment
