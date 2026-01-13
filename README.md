**Vyom | Headout Principal | UNSW MCom 2026**

## Executive Summary
**Automated 6-agent reporting** → **72% time savings** (4hrs → 1hr 7min daily)

| Metric | Before | After | Improvement |
|--------|--------|-------|-------------|
| **Reporting Time** | **4 hours/day** | **1hr 7min** | **72% ↓** |
| Audit Trail | Manual | **Auto-logged** | ✅ |
| **Team Scale** | **6 agents** | **Scalable** | ✅ |

**Business Impact**: **2.88 hours/day saved × 250 workdays = 720 agent hours annually** (~**AUD 10K** labor cost)

## Problem → Solution → Result
PROBLEM: Manual data formatting → 4hr daily waste on re-formatting as per stakeholders need
SOLUTION: VLOOKUP + ARRAYFORMULA + Apps Script audit trail
RESULT: Single source automated formatting → 72% efficiency gain

## Structural Workflow
Raw Data (Sheet1) → VLOOKUP Automation → Executive Dashboard → Google Drive Audit

## Technical Implementation
![App Script P1](https://github.com/GVyom/Headout-analytics-portfolio/blob/VLOOKUP-Dashboard-%7C-72%25-efficiency-improvement/App%20Script%20P1.jpg)
![App Script P2](https://github.com/GVyom/Headout-analytics-portfolio/blob/VLOOKUP-Dashboard-%7C-72%25-efficiency-improvement/App%20script%20P2.png)
![Individual Case Tracking + Case count on week basis](https://github.com/GVyom/Headout-analytics-portfolio/blob/VLOOKUP-Dashboard-%7C-72%25-efficiency-improvement/Individual%20Case%20Tracking%20%2B%20Case%20count%20on%20weekly%20basis.png)
![Mail Merge required format](https://github.com/GVyom/Headout-analytics-portfolio/blob/VLOOKUP-Dashboard-%7C-72%25-efficiency-improvement/Mail%20Merge%20tool%20required%20format.jpg)
![Standard Structural Data Pull](https://github.com/GVyom/Headout-analytics-portfolio/blob/VLOOKUP-Dashboard-%7C-72%25-efficiency-improvement/Standard%20Structural%20Data%20Pull.jpg)
![Vendor Required Format](https://github.com/GVyom/Headout-analytics-portfolio/blob/VLOOKUP-Dashboard-%7C-72%25-efficiency-improvement/Vendor%20required%20format.jpg)

**Core Formula** (Production-grade):
```excel
=ARRAYFORMULA(IF(E2:E="", "", VLOOKUP(E2:E, Sheet1!$B$3:$Q$961, 3, FALSE)))

