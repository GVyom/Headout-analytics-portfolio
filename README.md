# Team Performance Dashboard: VLOOKUP Automation + Google Apps Script
**Vyom | Headout Principal | UNSW MCom 2026**

## Executive Summary
**Automated 12-agent reporting** → **72% time savings** (4hrs → 1 hr 7 min weekly)

| Metric | Before | After | Improvement |
|--------|--------|-------|-------------|
| **Reporting Time** | **4 hours/week** | **1 hr 7 min** | **72% ↓** |
| Associate Case Trail | Manual | **Auto-logged** | ✅ |
| **Team Scale** | **6 agents** | **Scalable** | ✅ |

**Business Impact**: **18.7 agent workdays saved annually**

**Core Formula** (Production-grade):
```excel
=ARRAYFORMULA(IF(E2:E="", "", VLOOKUP(E2:E, Sheet1!$B$3:$Q$961, 3, FALSE)))

PROBLEM: Manual formatting of structural data as per stakeholder's requirement → 18% errors + 4hr waste
SOLUTION: VLOOKUP + ARRAYFORMULA + Apps Script audit trail  
RESULT: Single source pre-formatted data based on stakeholders + 72% efficiency

