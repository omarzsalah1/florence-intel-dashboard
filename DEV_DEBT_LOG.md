# Florence Intel Dashboard - Dev Debt Log

**Last Updated:** February 15, 2026

## Status Legend
- **CRITICAL** — Must fix before demo recording
- **HIGH** — Should fix before production rollout
- **MEDIUM** — Nice to have, can be done post-launch
- **LOW** — Future enhancement

---

## RESOLVED ISSUES

| # | Issue | Status | Date Fixed |
|---|-------|--------|------------|
| 1 | Sync button not working (syntax error in script block) | Resolved | 02/15/2026 |
| 2 | `<style>` tag inside `<script>` block breaking gaps rendering | Resolved | 02/15/2026 |
| 3 | `addSyncButton()` function never called | Resolved | 02/15/2026 |
| 4 | Patient name: Neil Campbell changed to Jane Doe | Resolved | 02/15/2026 |
| 5 | Gender: Male changed to Female throughout | Resolved | 02/15/2026 |
| 6 | TCM call script: Generic CCM changed to Heart attack discharge | Resolved | 02/15/2026 |
| 7 | Note format: SOAP note changed to Care Manager's Note | Resolved | 02/15/2026 |
| 8 | Text contrast: White on white changed to Dark on light | Resolved | 02/15/2026 |
| 9 | File to EHR: Now files note AND schedules appointment | Resolved | 02/15/2026 |
| 10 | Dismissal modal: Duplicate rendering bug | Resolved | 02/15/2026 |
| 11 | Morbid Obesity gap: Updated to BMI 36 + sleep apnea | Resolved | 02/15/2026 |
| 12 | Depression gap: PHQ-9 updated to 8 (mild) for dismissal | Resolved | 02/15/2026 |
| 13 | Button text: "R: Convene" changed to "Convene" | Resolved | 02/15/2026 |
| 14 | Care Manager's Note: Not scrollable, now scrollable | Resolved | 02/15/2026 |
| 16 | Physician MEAT criteria editing | Resolved | 02/15/2026 |
| 17 | Navigator Task List View | Resolved | 02/15/2026 |
| 18 | Florence Referral Scheduling UI | Resolved | 02/15/2026 |
| 19 | Patient Communication Log | Resolved | 02/15/2026 |
| 20 | COOP Population Health Gap Import Indicator | Resolved | 02/15/2026 |
| 21 | Quality gap "Stage for Future Visit" option | Resolved | 02/15/2026 |
| 31 | Patient avatar update: "NC" changed to "JD" | Resolved | 02/15/2026 |

**Total Resolved: 21 items**

---

## OPEN DEV DEBT

### CRITICAL — Must Fix Before Demo Recording

| # | Issue | Description | Status |
|---|-------|-------------|--------|
| 15 | Care Manager's Note visible on athenaOne side | When "File to EHR" is clicked, the note should appear as a filed document on the athenaOne (left) side, not just the celebration animation | Resolved 02/15/2026 |

### HIGH — Should Fix Before Production Rollout

| # | Issue | Description | Est. Effort |
|---|-------|-------------|-------------|
| 22 | Real-time sync indicator | Visual notification when physician signs note (bell icon, toast, etc.) | Resolved 02/15/2026 |
| 23 | Referral order write-back to athenaOne | When Florence schedules a referral, it should appear in the Referrals section | Resolved 02/15/2026 |
| 24 | Open/Closed gaps tracking in Log tab | Show all gaps with current status (open, staged, accepted, dismissed, documented) | Resolved 02/15/2026 |
| 25 | Dismissal analytics dashboard | Track dismissal patterns by gap type, show "Your feedback improved X recommendations" | Resolved 02/15/2026 |
| 26 | Medications list needs updating | Current meds (Lisinopril 20mg, Metformin 1000mg) don't match post-MI discharge meds | Resolved 02/15/2026 |
| 27 | HPI needs updating for post-MI scenario | Current HPI describes annual wellness visit, should reflect post-discharge context | Resolved 02/15/2026 |

### MEDIUM — Nice to Have

| # | Issue | Description | Est. Effort |
|---|-------|-------------|-------------|
| 28 | Florence panel tab redesign | Optimize Facesheet/Transcript/Documentation/Log tabs for information density | Resolved 02/15/2026 |
| 29 | Bulk gap staging | Select multiple gaps and stage them all at once | Resolved 02/15/2026 |
| 30 | Call progress indicator | Show "Florence is speaking..." animation during call | 1 hour |
| 32 | ROI summary at end of encounter | Show "This encounter captured $X in HCC value" | 2 hours |

### LOW — Future Enhancement

| # | Issue | Description | Est. Effort |
|---|-------|-------------|-------------|
| 33 | Multi-language support | Florence conversations in Spanish, Mandarin, etc. | 8 hours |
| 34 | Voice recording playback | Play actual audio of Florence calls | 6 hours |
| 35 | Real-time EHR integration | Connect to actual athenaOne API | 40 hours |
| 36 | AI model feedback loop | Use dismissal reasons to retrain gap detection model | 20 hours |

---

## SUMMARY

**Resolved:** 30 items  
**Open Critical:** 0 items  
**Open High:** 0 items  
**Open Medium:** 2 items  
**Open Low:** 4 items  
**Total Open:** 6 items  

---

## CHANGELOG

- **2026-02-15:** Initial dev debt log created
- **2026-02-15:** Fixed items 1-14 (Phase 1 core fixes)
- **2026-02-15:** Completed items 16-19, 21 (Phase 2 and Phase 3 features)
- **2026-02-15:** Created DEMO_SCRIPT.md and SALES_ENABLEMENT.md
- **2026-02-15:** Fixed note scrollability (item 14)
- **2026-02-15:** Florence automation (lab scheduling, patient education) implemented
- **2026-02-15:** Added File to EHR celebration animation with 2-step WOW moments
- **2026-02-15:** Added "Run Demo" button for post-encounter follow-through automation
- **2026-02-15:** Fixed Convene button SVG icon to prevent visual confusion
- **2026-02-15:** Added COOP badge to all gap cards (item 20 resolved)
- **2026-02-15:** Fixed patient avatar from "NC" to "JD" (item 31 resolved)
- **2026-02-15:** Created CHECKLIST_VERIFICATION_REPORT.md
- **2026-02-15:** Created ANNOTATED_SCREENSHOT_GUIDE.md
- **2026-02-15:** Created DIAGRAM_UPDATE_BRIEF.md for CCA Lifecycle v9.7
- **2026-02-15:** Deployed all changes to https://florence-intel-dashboard.vercel.app/
- **2026-02-15:** **CRITICAL FIXES COMPLETE** - Resolved items #15, #22, #23, #26, #27 (5 fixes, 8 hours effort)
- **2026-02-15:** Care Manager's Note now files to athenaOne Assessment & Plan section
- **2026-02-15:** Real-time sync indicator (bell + toast notifications) working
- **2026-02-15:** Referral write-back to athenaOne Referrals section working
- **2026-02-15:** Medications and HPI updated for post-MI discharge scenario
- **2026-02-15:** **DEMO IS NOW READY FOR RECORDING**
- **2026-02-15:** **TECH DEBT FIXES #24, #25, #28 COMPLETE** - Resolved 3 items (11 hours effort)
- **2026-02-15:** Gap Status Tracker added to Analytics tab (renamed from Log tab)
- **2026-02-15:** Dismissal Analytics Dashboard added with impact counter and charts
- **2026-02-15:** Florence panel tabs redesigned with icons (Overview, Transcript, Documentation, Analytics)
- **2026-02-15:** All tabs now have icons, tooltips, and improved hover/active states
- **2026-02-15:** **BULK GAP STAGING COMPLETE** - Resolved item #29 (3 hours effort)
- **2026-02-15:** Checkboxes on gap cards, floating "Stage Selected (X)" button, bulk staging modal with collapsible MEAT criteria
- **2026-02-15:** Batch staging to athenaOne with proper attribution and sync notifications
- **2026-02-15:** All 5 tests passed - feature is production-ready
