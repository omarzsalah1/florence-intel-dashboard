# Florence AI Navigator - Comprehensive Demo Script

**Version:** 2.0  
**Date:** February 15, 2026  
**Duration:** ~15 minutes  
**Audience:** CMOs, VP of Quality, Care Navigation Directors, CTOs  
**Demo URL:** https://florence-intel-dashboard.vercel.app/

---

## Pre-Demo Setup

Before starting the demo, ensure the following:

1. Open the demo URL in Chrome (full screen, 1920x1080 recommended)
2. Verify the dashboard loads with Jane Doe's patient chart
3. Confirm the Florence panel is visible on the right side
4. Ensure "Navigator View" toggle is checked (default)

---

## Act 1: The Problem (2 minutes)

### Narrator Talking Points

> "Today, I want to show you how NightingaleMD's Florence AI Navigator transforms the way your care team manages value-based care. We're going to follow a real patient journey, from hospital discharge through a physician visit, and show you how Florence eliminates the manual work that costs your organization time, money, and quality scores."

> "Let me introduce you to Jane Doe. She's a 68-year-old woman who was just discharged this morning from St. Joseph's Hospital after a heart attack. She has multiple chronic conditions: diabetes with an A1c of 8.9%, CKD Stage 3a, hypertension, and she's at high fall risk. She's exactly the kind of complex patient that falls through the cracks in traditional care models."

**On Screen:** Point to the athenaOne panel showing Jane's demographics, vitals, problem list, and the "Appointments Needed" section showing the TCM follow-up due in 7 days.

> "In a traditional workflow, your care navigator would spend 30-45 minutes manually reviewing the chart, calling the patient, documenting the call, scheduling follow-ups, and staging care gaps. Florence does all of this in under 5 minutes."

---

## Act 2: TCM Outreach Call (3 minutes)

### Step 1: Initiate the Engage Call

**Action:** Click the **"Engage"** button in the Florence panel.

> "Florence has already identified that Jane needs a TCM call within 24 hours of discharge. The navigator clicks 'Engage' and Florence initiates the call. Watch how the conversation unfolds."

**On Screen:** The transcript panel shows the simulated conversation between Florence and Jane. Florence verifies medications, checks for red flags, and educates the patient on weight monitoring.

### Step 2: Review the Documentation

**Action:** Click the **"Documentation"** tab.

> "While the call was happening, Florence was automatically generating a complete Care Manager's Note. This includes discharge information, medication reconciliation, vital signs, red flags assessment, and the follow-up plan. The navigator can review and edit this before filing."

**On Screen:** Scroll through the Care Manager's Note showing all sections. **Point out the Follow-Up Plan section** which includes the PCP appointment scheduled for Monday, February 18, 2026 at 10:00 AM.

> "Notice that Florence has already scheduled the PCP follow-up appointment through a 3-way call with Dr. Campbell's office. The patient selected the 10am slot. This is all documented automatically."

### Step 3: File to EHR

**Action:** Click the **"File to EHR"** button.

> "With one click, the navigator files the complete note and the appointment to athenaOne. Watch the left panel."

**On Screen:** The progress bar fills, the toast notification appears confirming the note and appointment are filed. The athenaOne Appointments section updates to show the TCM Follow-up as "Scheduled."

> "The TCM follow-up that was showing as 'Due in 7 days' is now marked as 'Scheduled' with all the details. This is real-time EHR integration."

---

## Act 3: Care Gap Intelligence (4 minutes)

### Step 4: Review Care Gaps

**Action:** Click the **"Facesheet"** tab to return to the gap view.

> "Now let's look at what makes Florence truly powerful. Florence has analyzed Jane's entire medical history, claims data, and clinical guidelines to identify 9 care gaps across four categories."

**On Screen:** Point to the gap categories: Suspect (4), Quality (3), Frailty (2).

> "These aren't just simple reminders. Florence uses clinical intelligence to identify suspect diagnoses that may be undercoded, quality measures that are overdue, and frailty indicators that affect risk adjustment."

### Step 5: Stage a Suspect Diagnosis

**Action:** Click **"Stage for MD Review"** on the "Chronic Kidney Disease Stage 3a" gap.

> "The navigator reviews each gap and stages the ones that are clinically appropriate for the physician to review. Watch what happens when I stage this CKD gap."

**On Screen:** The staging preview modal appears showing the ICD-10 code, MEAT criteria, and what will be added to athenaOne.

**Action:** Click **"Stage for MD Review"** in the modal to confirm.

> "Florence has pre-populated the MEAT criteria: Monitor, Evaluate, Assess, and Treat. This is the documentation the physician needs to support the diagnosis code. The navigator can add a prep note, and then this gets staged in athenaOne's problem list and assessment sections."

### Step 6: Stage for Future Visit

**Action:** Click **"Future Visit"** on the "Colorectal Cancer Screening" gap.

> "Not every gap needs to be addressed today. The Colorectal Cancer Screening requires bowel prep and scheduling. The navigator can defer this to a future visit."

**On Screen:** The Future Visit modal appears with reason and target visit options.

**Action:** Select "Patient needs preparation" and "Annual Wellness Visit" then click "Defer to Future Visit."

> "Florence tracks this deferral and will automatically surface it again before the Annual Wellness Visit. Nothing falls through the cracks."

### Step 7: Dismiss a Gap

**Action:** Click the checkbox on "Morbid Obesity with Obstructive Sleep Apnea" and then click **"Stage for MD Review"**. Then switch to Provider View.

> "Some gaps may not be clinically appropriate. The physician can dismiss a gap with a documented reason, which Florence tracks for audit purposes."

---

## Act 4: Physician Workflow (3 minutes)

### Step 8: Switch to Provider View

**Action:** Toggle the **"Navigator View"** checkbox to switch to Provider View.

> "Now let's see what the physician experiences. Dr. Campbell opens the Florence panel and sees only the gaps that have been staged for review. The navigator has done all the prep work."

**On Screen:** The view changes to show the staged gaps with MEAT criteria and acceptance/dismissal options.

### Step 9: Accept and Edit MEAT Criteria

> "The physician can review each staged diagnosis, edit the MEAT criteria if needed, and accept or dismiss with one click. The documentation is already 90% complete. The physician just needs to validate and sign."

### Step 10: Batch Sync to athenaOne

**Action:** Click **"Sync from athenaOne"** to show the batch sync capability.

> "All accepted diagnoses, orders, and documentation are synced to athenaOne in a single batch operation. No duplicate data entry. No missed codes."

---

## Act 5: Post-Visit Automation (3 minutes)

### Step 11: Open Post-Visit Tasks

**Action:** Click the **"Post-Visit Tasks"** button.

> "After the physician visit, the navigator has a clear task list. Florence has organized everything: confirmed diagnoses, pending orders, referrals to schedule, and patient education to send."

**On Screen:** The Post-Visit Task List showing stats (Confirmed, Pending, Dismissed, Automated) and organized task sections.

### Step 12: Automate Lab Orders

**Action:** Click **"Automate"** on the BMP Lab Order.

> "Florence can automate routine tasks. With one click, the lab order is sent to Quest Diagnostics and the patient receives an SMS with instructions. Watch the communication timeline update in real-time."

**On Screen:** The task card animates to "In Progress" then "Done." The communication timeline shows the new entry.

### Step 13: Schedule a Referral

**Action:** Click **"Schedule"** on the Nephrology Referral.

> "For referrals, Florence orchestrates a multi-step workflow. First, she texts the patient to confirm availability. Then, when the patient responds, Florence initiates a 3-way call with the specialist office."

**On Screen:** Walk through the 4-step referral scheduling workflow:
1. SMS sent to patient
2. Patient responds with availability
3. 3-way call to specialist office
4. Appointment confirmed and filed to EHR

> "The entire referral scheduling process that normally takes 3-4 phone calls and 20 minutes of navigator time is completed in under 2 minutes."

### Step 14: Send Patient Education

**Action:** Click **"Automate"** on the CKD Patient Education.

> "Florence also handles patient education. Materials are sent via the patient portal and SMS, personalized to the patient's conditions and reading level."

---

## Act 6: The ROI Story (1 minute)

### Closing Talking Points

> "Let me summarize what Florence just accomplished in this single patient encounter:"

| Metric | Traditional Workflow | With Florence |
|--------|---------------------|---------------|
| TCM Call + Documentation | 45 minutes | 5 minutes |
| Care Gap Staging | 30 minutes | 3 minutes |
| Referral Scheduling | 20 minutes | 2 minutes |
| Patient Education | 15 minutes | 30 seconds |
| **Total Navigator Time** | **110 minutes** | **~11 minutes** |

> "That's a 90% reduction in navigator time per patient. For a practice with 500 Medicare patients, that's the equivalent of recovering 2-3 full-time navigators."

> "But the real value isn't just time savings. It's the clinical outcomes: every gap is tracked, every referral is followed up, every patient gets the right care at the right time. That's how you move the needle on quality scores and shared savings."

---

## Demo Tips

1. **Pace yourself.** Let each animation complete before moving to the next step.
2. **Use the athenaOne panel** to show real-time updates as you work in Florence.
3. **Highlight the Communication Timeline** as it grows throughout the demo.
4. **If asked about integration:** "Florence integrates with athenaOne via FHIR APIs and can be configured for any EHR."
5. **If asked about AI accuracy:** "Florence uses clinical NLP and claims data analysis with physician oversight. Every recommendation is reviewed by the care team before action."

---

## Appendix: Key Demo Data Points

| Data Point | Value | Clinical Significance |
|-----------|-------|----------------------|
| Patient Age | 68 y/o Female | Medicare-eligible, CCA population |
| HbA1c | 8.9% | Uncontrolled diabetes, HCC 18/19 |
| eGFR | 42 mL/min | CKD Stage 3a, HCC 138 |
| BMI | 29.3 | Overweight, approaching obesity |
| PHQ-9 | 8 (Mild) | Depression screening completed |
| Morse Fall Scale | 55 | High fall risk, Z91.81 |
| BP | 142/88 | Elevated, needs monitoring |
| Care Gaps | 9 total | 4 suspect, 3 quality, 2 frailty |
