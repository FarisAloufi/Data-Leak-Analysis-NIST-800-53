# Data Leak Analysis — NIST SP 800-53: AC-6

## 📌 Project Overview
This project analyzes a data leak at an edtech company, where an employee accidentally shared a folder of internal business documents with an external partner, who then posted it publicly. The goal was to identify what went wrong, connect it to the relevant NIST SP 800-53 control, and recommend specific control enhancements to prevent it from happening again.

## 🎯 Objectives
- Analyze the human and process factors that led to the data leak.
- Understand and summarize NIST SP 800-53's AC-6 (Least Privilege) control.
- Recommend specific control enhancements to close the security gap.
- Justify the recommendations in a way that's clear to non-technical decision makers.

## 🛠️ Skills & Concepts Demonstrated
- Incident/root-cause analysis
- NIST SP 800-53 control-level application (not just framework-level)
- Principle of least privilege
- Access review and privileged activity logging
- Translating technical controls into business-friendly recommendations

## 📋 Summary
| Section | Key Point |
|---|---|
| Issue | Forgotten folder access + accidental link oversharing led to the leak |
| Relevant control | NIST SP 800-53 AC-6 — Least Privilege |
| Recommendation 1 | AC-6(7) — Periodic review of user privileges |
| Recommendation 2 | AC-6(9) — Log use of privileged functions |
| Justification | Regular reviews and access logging would have caught the issue before it became public |

## 📂 Files in This Repository
- `Data-Leak-Analysis.pdf` — Full write-up covering the incident, control review, recommendations, and justification.

## 📎 Note
This is a training/portfolio project based on a fictional company scenario, intended to demonstrate applying a specific NIST SP 800-53 control to a real-world-style data leak incident.
