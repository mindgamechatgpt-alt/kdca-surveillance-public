# KDCA Public Verified Surveillance Data

This repository is reserved for **public, aggregate disease-surveillance statistics** verified against official Korea Disease Control and Prevention Agency (KDCA) publications.

- Version: v1.0 (repository initialization)
- Last updated: 2026-11-27
- Owner: mindgamechatgpt-alt
- Official source: https://dportal.kdca.go.kr/pot/bbs/BD_selectBbsList.do?q_bbsSn=1010&q_clsfNo=2
- Intended public data file: `latest.json` (not published yet)
- Private data, API tokens, personal notes, and dashboard backup files are **not** stored here.

## Publication policy

No statistical values are published until source consistency, previous-week corrections, and authorization to publish are verified. An absent `latest.json` means **no verified public feed is available**; it must not be interpreted as zero cases or zero patients.

The private collection and validation workflow is developed separately. The dashboard must continue using its existing embedded statistics when the public feed is unavailable.

This README is informational only; creating it does **not** authorize automated publishing, approve revisions, or change the production dashboard.

## Data interpretation

If published, the JSON will identify the source publication date, surveillance week, units, provenance, and revision history. The COVID-19 hospital admissions count and influenza-like-illness rate use **different denominators** and must not be combined or compared directly.
