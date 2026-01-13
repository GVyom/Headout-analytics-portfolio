# Ticket Cancellation Root Cause Analysis
**Vyom | Headout Principal | UNSW MCom 2026**

## Executive Summary
**Identified venue closure pattern** behind ticket cancellations → **Eliminated stakeholder escalations** + **Proactive guest resolution**

**Before**: Random cancellations → Multi-level escalations → Bad reviews  
**After**: Confirmed slot closures → Reservations team ownership → Positive guest experience

## Problem
High-volume ticket purchases using pseudo-emails → **Venue cancellation emails missed** → Guests impacted → **Escalations to senior stakeholders** → Bad reviews risk


## Root Cause Analysis
**Data Flow**:
- Mapped ALL escalations → Extracted exact date/time slots
- Looker → Pulled FULL booking dataset for those dates
- Excel → Matched individual emails with impacted slots
- Verified → ALL bookings for specific slots were cancelled


**Key Insight**: What appeared "random" = **Confirmed venue slot closures**

## Solution → Process Redesign
✅ Passed ownership to Reservations (first-contact team)
✅ Systematic email monitoring + proactive refund/reschedule
✅ Eliminated senior stakeholder escalations
✅ Guests assisted immediately vs escalation wait


## Business Impact
- ZERO stakeholder escalations (cross-functional fire-drills eliminated)
- Bad reviews prevented
- Positive guest experience via proactive resolution
- Reservations team empowered with clear process ownership


## Technical Execution
Looker: Full booking dataset extraction (date-specific)
Excel:
- UNIQUE function → Slot identification
- Pivot tables → Email-slot matching
- Verification → 100% slot cancellation confirmation
- Process: Stakeholder → Reservations ownership transfer

## Key Learnings
✅ Root cause via systematic data matching > Assumptions
✅ First-contact ownership > Stakeholder escalations
✅ Proactive resolution > Reactive firefighting
✅ Pseudo-email workflows need systematic monitoring


## Visual Proof
![Senior-stakeholders-recognition P2](https://github.com/GVyom/Headout-analytics-portfolio/blob/Ticket-Cancellation-Root-Cause-Analysis/senior-stakeholder-kudos%20P2.png)
![Seniro-stakeholders-recognition P1](https://github.com/GVyom/Headout-analytics-portfolio/blob/Ticket-Cancellation-Root-Cause-Analysis/senior-stakeholder-kudos.png)
![Excel-Data-Comparison-from 200+ bookings](https://github.com/GVyom/Headout-analytics-portfolio/blob/Ticket-Cancellation-Root-Cause-Analysis/Escalations%20Vs%20Valid%20bookings%20on%20the%20time%20slot.png)


