# Team Performance Dashboard: VLOOKUP Automation + Google Apps Script
**Vyom | Headout Principal | UNSW MCom 2026**

## Executive Summary
**Automated 6-agent reporting** → **72% time savings** (4hrs → 1hr 7min daily)

| Metric | Before | After | Improvement |
|--------|--------|-------|-------------|
| **Reporting Time** | **4 hours/day** | **1hr 7min** | **72% ↓** |
| Audit Trail | Manual | **Auto-logged** | ✅ |
| **Team Scale** | **6 agents** | **Scalable** | ✅ |

**Business Impact**: **2.88 hours/day saved × 250 workdays = 720 agent days annually** (~**AUD 10K** labor cost)

## Problem → Solution → Result
PROBLEM: Manual data formatting → 4hr daily waste on re-formatting as per stakeholders need
SOLUTION: VLOOKUP + ARRAYFORMULA + Apps Script audit trail
RESULT: Single source automated formatting → 72% efficiency gain

## Structural Workflow
Raw Data (Sheet1) → VLOOKUP Automation → Executive Dashboard → Google Drive Audit

## Technical Implementation
**Core Formula** (Production-grade):
```excel
=ARRAYFORMULA(IF(E2:E="", "", VLOOKUP(E2:E, Sheet1!$B$3:$Q$961, 3, FALSE)))

