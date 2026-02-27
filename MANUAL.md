# The Florence Product Bible: Vision, Philosophy, and Manual

**Author:** Manus AI
**Version:** 1.0
**Date:** February 27, 2026

---

## Introduction: The Co-Pilot for Care Management

Florence is not an automation tool. It is a **co-pilot**, designed to work alongside a human care manager, amplifying their clinical judgment and freeing them from the administrative burdens that distract from patient care. Our vision is to create a seamless, intelligent partnership between human and machine, where Florence handles the rote, the routine, and the data-heavy lifting, so the care manager can focus on what they do best: building relationships, making complex clinical decisions, and providing empathetic, human-centered care.

This manual is not just a list of features. It is a bible that explains the **why** behind every design decision — the clinical philosophy that guides Florence’s development. We believe that by understanding the vision, you can more effectively partner with Florence to deliver extraordinary care.

> The goal is not to replace the care manager, but to empower them. Florence is a tool to help you attend to the patient on the call, not just record it. We are not only recording the call but also listening for clues of anything that Florence can do for you.

---

## Chapter 1: The Florence Interface — Your Command Center

The Florence AI Navigator is a Chrome extension that lives alongside your Electronic Health Record (EHR). It is organized into four primary tabs, each designed to support a key aspect of the care management workflow.

### 1.1 The Gaps Tab: Proactive Care, Realized

The Gaps tab is the heart of Florence’s proactive care engine. It moves beyond reactive sick-care to a model where we are constantly, automatically identifying opportunities to improve a patient’s health and prevent future crises. This is not just about closing quality measures; it is about fundamentally changing the care paradigm.

**The Philosophy:** A care gap is not a checkbox to be ticked. It is a window into a patient’s health, a signal that something needs attention. By surfacing these gaps automatically, Florence allows the care manager to see the full clinical picture at a glance, connecting disparate data points into a coherent narrative.

**Key Features:**

| Feature | Description & Clinical Rationale |
|---|---|
| **Gap Cards** | Each card represents a single care gap, from annual wellness visit reminders to suspected chronic conditions. The card provides a concise summary of the gap, its priority, and the supporting evidence. This allows the care manager to quickly triage and prioritize their work. |
| **Recapture vs. Suspect Gaps** | Florence distinguishes between **recapture** gaps (known conditions that need annual reassessment) and **suspect** gaps (potential new conditions flagged by the AI based on labs, vitals, or other data). This helps the care manager differentiate between routine follow-up and new diagnostic workups. |
| **Staging for MD Review** | With one click, a care manager can "stage" a gap for physician review. This is a critical workflow that respects the clinical hierarchy. Florence prepares a concise summary of the gap, the evidence, and a suggested action plan, but the final clinical decision always rests with the physician. This streamlines the process without overstepping clinical boundaries. |
| **Gap Status Tracker** | This sub-tab provides a high-level overview of all open, staged, and closed gaps for the patient. It allows the care manager to track progress and ensure nothing falls through the cracks. |

### 1.2 The Outreach Tab: Intelligent, Empathetic Communication

The Outreach tab is where Florence’s communication capabilities come to life. It is designed to make patient outreach more efficient, effective, and empathetic.

**The Philosophy:** Patient communication should be personal, timely, and relevant. Rote, repetitive calls burn out care managers and annoy patients. Florence automates the routine aspects of outreach, freeing the care manager to handle complex conversations that require a human touch.

**Key Features:**

| Feature | Description & Clinical Rationale |
|---|---|
| **Engage, Convene, Check-In** | Florence offers three distinct outreach workflows: **Engage** (a fully automated, scripted call for post-discharge follow-up), **Convene** (a three-way call where Florence brings the patient and care manager together and then listens in the background), and **Check-In** (an automated SMS-based wellness check). This allows the care manager to choose the right tool for the job, from low-touch check-ins to high-touch, human-led conversations. |
| **Live Transcript & Clinical Flagging** | During any call, Florence provides a real-time transcript. More importantly, it is actively **listening for clinical clues**. If a patient mentions "chest pain" or "feeling dizzy," Florence will surface a **Clinical Flag** alert directly in the transcript. This allows the care manager to react in the moment, without having to manually scan for keywords. |
| **Workflow Suggestion Engine** | Going a step further, Florence also listens for opportunities to help. If a patient says, "I can’t afford my medication," Florence will surface a **Workflow Suggestion** card with an "Accept" button to launch a Medication Assistance workflow. This is the core of the co-pilot vision: Florence identifies a need and proposes a solution, but the care manager makes the final call. |


### 1.3 The Workflows Tab: Automating the Administrative Burden

The Workflows tab is the engine room of Florence, where multi-step administrative processes are automated from end to end.

**The Philosophy:** Care management is plagued by administrative tasks that are critical but time-consuming: referral coordination, DME orders, prior authorizations. These tasks are perfect for automation. By handling the back-and-forth communication and status tracking, Florence frees the care manager to operate at the top of their license.

**Key Features:**

| Feature | Description & Clinical Rationale |
|---|---|
| **Active Workflows List** | This provides a real-time view of all in-progress workflows, showing the current step, progress, and any roadblocks. It allows the care manager to see the status of all delegated tasks at a glance. |
| **Workflow Catalog** | The catalog contains a library of pre-built workflows for common administrative tasks (e.g., Specialist Referral, Home Health Coordination, DME Order). The care manager can launch any workflow manually from the catalog. |
| **Workflow Steps & Progress** | Each workflow is broken down into clear, logical steps. As Florence completes each step (e.g., "Submit referral to preferred agency," "Confirm agency acceptance"), the workflow updates in real time, providing full transparency. |

### 1.4 The Tasks Tab: The Intelligent To-Do List

The Tasks tab is more than a simple to-do list. It is an intelligent, self-populating list of action items that are automatically deduced from patient conversations, incoming data, and active workflows.

**The Philosophy:** A care manager should never have to manually create a to-do list after a patient call. The act of listening should automatically generate the necessary actions. The Tasks tab is the manifestation of this philosophy.

**Key Features:**

| Feature | Description & Clinical Rationale |
|---|---|
| **AI-Deduction from Calls** | During a Convene call, as the care manager and patient talk, Florence listens for action items. When the care manager says, "I will send you a pulse oximeter," Florence automatically adds "Order home pulse oximetry monitoring" to the Tasks list. This is the magic of the co-pilot at work. |
| **Pending Review** | Tasks deduced from a call or surfaced as a workflow suggestion are initially marked as **Pending Review**. This gives the care manager full control to **Accept**, **Defer**, or **Dismiss** the task, ensuring that Florence’s suggestions are always validated by clinical judgment. |
| **Task-Workflow Linkage** | When a task is part of a larger workflow (e.g., "Coordinate home oxygen delivery" is a task within the DME Coordination workflow), the task is explicitly linked to its parent workflow. This provides a clear line of sight from a single action item to the broader clinical process. |
| **Task Origins** | Each task is tagged with its origin: **AI-deduced**, **workflow-generated**, or **manual-entry**. This helps the care manager understand where the task came from and why it exists. |

---

## Chapter 2: The Three Outreach Modalities

Florence provides three distinct outreach modalities, each tailored to a specific clinical scenario. Choosing the right modality is key to efficient and effective care management.

### 2.1 Engage: The Automated Post-Discharge Call

**When to Use:** For routine, scripted follow-up, such as the initial post-discharge call after a hospital stay.

**How it Works:** The Engage workflow is a fully automated, voice-based call. Florence follows a pre-defined script to check on the patient, review medications, ask about red-flag symptoms, and even schedule the first PCP follow-up appointment by conferencing in the clinic’s front desk. The care manager does not need to be on the call.

**Clinical Rationale:** The first 72 hours post-discharge are a critical window to prevent readmission. However, these calls are often repetitive and can be handled effectively by an AI. By automating the Engage call, Florence ensures that every discharged patient receives a timely, thorough follow-up, freeing the care manager to focus on higher-risk patients who need a human-led conversation.

### 2.2 Convene: The Human-Led, AI-Assisted Conversation

**When to Use:** For complex, nuanced conversations that require clinical judgment, empathy, and relationship-building.

**How it Works:** The Convene workflow is a three-way call. Florence initiates the call, brings the patient and care manager together, and then transitions to a listening mode. As the care manager and patient talk, Florence listens in the background, providing real-time transcription, surfacing clinical flags, suggesting relevant workflows, and automatically deducing action items for the Tasks list.

**Clinical Rationale:** This is the core of the human-machine partnership. The care manager leads the conversation, leveraging their clinical skills and empathetic connection with the patient. Florence acts as a hyper-efficient scribe and assistant, handling all the documentation and administrative follow-up in the background. This allows the care manager to be fully present in the conversation, knowing that Florence is capturing every detail.

### 2.3 Check-In: The Asynchronous SMS Wellness Check

**When to Use:** For quick, low-touch check-ins on stable patients, such as monthly CCM check-ins or post-visit follow-ups.

**How it Works:** The Check-In workflow is a fully automated, SMS-based conversation. Florence sends a series of questions to the patient (e.g., "How are you feeling today?", "Have you taken your medications?") and collects their responses. If a patient reports a concerning symptom or asks for help, Florence can escalate the conversation to the care manager.

**Clinical Rationale:** Not every patient needs a full phone call every month. The SMS Check-In provides a lightweight way to maintain contact, monitor key metrics (like blood sugar or symptoms), and surface potential issues before they become crises. This allows the care manager to efficiently monitor a large panel of patients, triaging their attention to those who need it most.


---

## Chapter 3: The Intelligence Layer — How Florence Listens and Thinks

Florence's intelligence is not a black box. It is a transparent, rule-based system designed to be predictable, auditable, and clinically sound. This chapter explains exactly how Florence detects clinical flags and surfaces workflow suggestions during a live call.

### 3.1 Clinical Flag Detection

**The Problem It Solves:** During a patient call, a care manager is simultaneously listening, thinking, and talking. It is easy to miss a subtle clinical cue — a passing mention of dizziness, a comment about not eating well. These cues can be early warning signs of a serious deterioration. Florence's Clinical Flag engine is designed to catch what a human might miss in the moment.

**How It Works:** Florence maintains a library of clinical keyword patterns, organized by severity. Every patient utterance is scanned against this library in real time. When a match is found, Florence surfaces an inline alert directly in the transcript, with a severity badge (CRITICAL, HIGH, or MEDIUM) and two action buttons: **Add to Note** and **Dismiss**.

The current Clinical Flag library covers the following categories:

| Category | Severity | Example Keywords |
|---|---|---|
| Chest Pain | CRITICAL | "chest pain," "chest pressure," "chest tightness" |
| Mental Health Crisis | CRITICAL | "hopeless," "don't want to go on," "suicide" |
| Shortness of Breath | HIGH | "short of breath," "can't breathe," "hard to breathe" |
| Dizziness / Lightheadedness | HIGH | "dizzy," "lightheaded," "feel faint" |
| Fall or Fall Risk | HIGH | "fell," "fall," "tripped," "stumbled" |
| Edema / Swelling | HIGH | "swelling," "legs are swollen," "ankles swollen" |
| Possible Infection / Fever | HIGH | "fever," "chills," "infection," "wound drainage" |
| Medication Request / Running Out | MEDIUM | "running out," "out of meds," "need a refill" |
| Cognitive Concern | MEDIUM | "confused," "memory," "forgetful" |
| Nutrition / GI Concern | MEDIUM | "not eating," "no appetite," "nausea," "vomiting" |

**The "Add to Note" Action:** When the care manager clicks "Add to Note," Florence automatically inserts a structured "Patient-Reported Concerns" section into the care manager's note, pre-populated with the flagged concern. This ensures that the clinical observation is documented without interrupting the flow of the conversation.

**The Design Philosophy:** Florence surfaces the flag and then gets out of the way. The care manager decides what to do with it. The alert is not a pop-up that demands immediate attention; it is a persistent, non-blocking card in the transcript that the care manager can address when they are ready.

### 3.2 Workflow Suggestion Engine

**The Problem It Solves:** A patient mentions they are having trouble getting food. A care manager might note this mentally, intend to follow up, and then forget in the chaos of the post-call administrative work. Florence's Workflow Suggestion engine is designed to convert these fleeting moments of clinical insight into concrete, actionable workflow suggestions — in real time, before the moment is lost.

**How It Works:** Alongside the Clinical Flag scanner, Florence runs a second, parallel scan for workflow trigger keywords. When a match is found, Florence surfaces a **Florence Suggestion** card in the transcript. This card is visually distinct from a Clinical Flag — it is styled in Florence's signature teal-and-navy color scheme, signaling a proactive suggestion rather than a clinical alert.

The Suggestion card displays:
- The name of the suggested workflow
- A brief, plain-language rationale (e.g., "Patient reported difficulty getting food — Feed Assistance Workflow may help")
- Three action buttons: **Accept**, **Defer**, and **Dismiss**

The current Workflow Trigger library covers the following scenarios:

| Patient Concern | Suggested Workflow |
|---|---|
| Home oxygen / breathing equipment | DME Order & Delivery Coordination |
| Help at home / personal care | Home Health Start-of-Care Coordination |
| Medication confusion / pharmacy | Medication Adherence Intervention |
| Specialist appointment / referral | Specialist Referral Coordination |
| Food / nutrition / meal delivery | Patient Education Delivery |
| Depression / mental health | Specialist Referral Coordination (Behavioral Health) |
| Lab results / blood work | Lab Order & Results Follow-Up |
| Insurance denial / prior auth | Prior Authorization Request |

**The Three Actions Explained:**

The three-button design reflects a core design principle: Florence proposes, the care manager disposes.

- **Accept:** The care manager agrees that this workflow is needed right now. Florence immediately creates a new task in the Tasks list (status: `pending`) and adds the workflow to the Active Workflows list. The workflow is ready to execute.
- **Defer:** The care manager acknowledges the suggestion but wants to review it after the call. Florence creates a task in the Tasks list with a `pending_review` status. This item will appear at the top of the Tasks list after the call, clearly marked for post-call review.
- **Dismiss:** The care manager determines that the suggestion is not applicable. Florence removes the card and logs the dismissal to the Activity log for auditability.

**Why Not Automate It?** This is the most important design decision in the Workflow Suggestion engine. Florence could, in theory, automatically start a workflow the moment it detects a trigger keyword. We chose not to do this for a fundamental reason: **not everything said in a call is an actionable request**. A patient might mention food in passing, or in the context of a story that has nothing to do with a need for meal assistance. The care manager is the only one who can determine context and intent. Florence provides the signal; the care manager provides the judgment.

---

## Chapter 4: The Workflows and Tasks System — A Unified Model

The relationship between Workflows and Tasks is one of the most important architectural decisions in Florence. Understanding it is key to using the system effectively.

### 4.1 The Conceptual Model

Florence uses a clear, hierarchical model:

- A **Workflow** is a multi-step, automated process for a specific clinical or administrative goal (e.g., coordinating a home health referral from submission to first visit confirmation).
- A **Task** is a single, discrete action item that may or may not be part of a workflow.
- A **Workflow** can own multiple **Tasks** (e.g., the Home Health workflow generates tasks for "Submit referral," "Confirm agency acceptance," "Notify patient").
- A **Task** can trigger a **Workflow** (e.g., the task "Initiate home health aide referral," deduced from a Convene call, triggers the Home Health Start-of-Care Coordination workflow).
- Some **Tasks** are standalone and are not connected to any workflow (e.g., "Review latest lab results," added manually by the care manager).

This model is reflected in the data structure of every task and workflow in Florence. Every task has a `workflow_id` field (which is `null` for standalone tasks) and every workflow has a `triggered_by_task` field (which is `null` for workflows started manually or by an ADT notification).

### 4.2 Task Origins

Florence tracks the origin of every task, providing full auditability:

| Origin | Description |
|---|---|
| `ai-deduced` | The task was automatically identified by Florence from a patient conversation during a Convene call. |
| `workflow-generated` | The task was created as a step in a larger workflow (e.g., a step in the Post-Discharge TCM workflow). |
| `manual-entry` | The task was manually created by the care manager. |
| `suggestion-accepted` | The task was created when the care manager accepted a Florence Workflow Suggestion during a call. |

### 4.3 Task Statuses

Tasks move through a defined lifecycle:

| Status | Meaning |
|---|---|
| `pending_review` | The task has been suggested by Florence (either deduced from a call or surfaced as a workflow suggestion) and is awaiting CM review. These tasks appear at the top of the Tasks list with an amber "PENDING REVIEW" badge. |
| `pending` | The task has been accepted by the CM and is in the queue, but work has not yet started. |
| `in-progress` | The task is actively being worked on. |
| `completed` | The task is done. |

### 4.4 The Workflow Catalog

The Workflow Catalog is a library of 10 pre-built workflows that can be launched manually by the care manager at any time. These workflows cover the most common administrative processes in care management:

| Workflow ID | Name |
|---|---|
| WF-100 | Annual Wellness Visit (AWV) Prep |
| WF-101 | Chronic Care Management (CCM) Monthly Check-In |
| WF-102 | Transitional Care Management (TCM) |
| WF-103 | Specialist Referral Coordination |
| WF-104 | Lab Order & Results Follow-Up |
| WF-105 | Home Health Start-of-Care Coordination |
| WF-106 | DME Order & Delivery Coordination |
| WF-107 | Medication Adherence Intervention |
| WF-108 | Patient Education Delivery |
| WF-109 | Prior Authorization Request |

---

## Chapter 5: The Activity Log — The Audit Trail

The Activity Log is Florence's memory. It is a chronological, timestamped record of every action taken during a session, providing a complete audit trail for documentation, compliance, and quality review.

**The Philosophy:** In care management, documentation is not just a bureaucratic requirement. It is a clinical and legal record of the care provided. The Activity Log ensures that every action — every call made, every task created, every gap staged, every clinical flag detected — is automatically captured without requiring the care manager to manually document it.

### 5.1 What Gets Logged

Every significant event in Florence is automatically logged to the Activity Log:

- **Session Start:** When Florence connects to the EHR at the beginning of a session.
- **Workflow Events:** When an Engage, Convene, or Check-In workflow is started and completed.
- **Clinical Flags:** When Florence detects a clinical flag during a call (e.g., "Patient reported: Chest Pain — flagged for documentation").
- **Workflow Suggestions:** When a workflow suggestion is accepted, deferred, or dismissed.
- **Gap Actions:** When a gap is staged for MD review, unstaged, or deferred.
- **EHR Filing:** When a care manager's note is filed to the EHR.

### 5.2 Care Manager Attribution

Every log entry generated by a care manager action is attributed to the care manager by name and credentials (e.g., "by Sarah Martinez, RN, CCM"). This is critical for accountability and for distinguishing between actions taken by the care manager and actions taken autonomously by Florence.

System-generated events (e.g., "Session Start," "Florence connected to athenaOne") are not attributed to the care manager, as they are automated actions.

### 5.3 The Filter

The Activity Log includes a filter dropdown that allows the care manager to filter the log by event type (e.g., "Outreach," "Clinical Flags," "Gap Actions"). This makes it easy to find specific events in a long session.

---

## Chapter 6: The Gap Staging System — Bridging Care Management and the Physician

The Gap Staging system is Florence's most powerful feature for improving clinical documentation and risk adjustment. It is the bridge between the care manager's proactive identification of care gaps and the physician's clinical decision-making.

### 6.1 What is a Care Gap?

A care gap is a discrepancy between the care a patient is receiving and the care they should be receiving, based on clinical guidelines, their medical history, and their current health status. Florence identifies two types of care gaps:

- **Recapture Gaps:** These are known, previously diagnosed conditions that need to be re-documented in the current year to ensure accurate risk adjustment and quality measure reporting. For example, a patient with a known history of hypertension needs to have that condition documented in every annual visit.
- **Suspect Gaps:** These are potential new conditions that Florence has identified based on the patient's data (labs, vitals, medications, etc.) but that have not yet been formally diagnosed. For example, if a patient's eGFR has been declining over three years and is now in the 45-59 range, Florence will flag a "Suspect: Chronic Kidney Disease Stage 3a" gap.

### 6.2 The Staging Workflow

The staging workflow is designed to be fast, transparent, and clinically rigorous:

1. **Review:** The care manager reviews the gap card, including the supporting evidence, clinical rationale, and suggested documentation.
2. **Stage:** With one click, the care manager stages the gap for MD review. Florence prepares a structured staging package that includes the ICD-10 code, the supporting evidence, the MEAT criteria (Monitor, Evaluate, Assess, Treat), and a suggested order set (labs, referrals, prescriptions).
3. **MD Review:** The staged gap appears in the physician's workflow in the EHR (athenaOne), where they can review the evidence and either accept, modify, or reject the staging.
4. **Documentation:** If accepted, Florence automatically adds the condition to the Problem List, the Assessment & Plan section, and generates the appropriate orders.

### 6.3 MEAT Criteria

Every staged gap includes a pre-populated MEAT criteria section:

- **Monitor:** What data is being tracked (e.g., "Last BP: 142/88 mmHg").
- **Evaluate:** What the patient reports (e.g., "Patient reports stable blood pressure control on current medications").
- **Assess:** The clinical assessment (e.g., "Controlled on current regimen. Linked to diabetic CKD").
- **Treat:** The treatment plan (e.g., "Continue Lisinopril 20mg daily. Recheck BP in 3 months").

MEAT criteria are the gold standard for documenting chronic conditions in a way that satisfies both clinical and coding requirements. By pre-populating them, Florence dramatically reduces the documentation burden on the physician.

### 6.4 Bulk Staging

For patients with multiple open gaps, Florence offers a **Bulk Staging** feature that allows the care manager to review and stage multiple gaps at once. Each gap can be individually reviewed and approved before the bulk staging is confirmed.

---

## Chapter 7: The EHR Integration — Filing to athenaOne

Florence is built to work within the existing clinical workflow, not to replace it. The EHR integration is designed to be seamless, automatic, and transparent.

### 7.1 Filing the Care Manager's Note

After any Engage or Convene call, Florence generates a structured **Care Manager's Note** that captures the key clinical information from the call. With one click on the "File to EHR" button, Florence automatically:

1. Adds the note to the **Assessment & Plan** section of the patient's chart in athenaOne.
2. Includes the care manager's name and credentials, the date and time of the call, and a structured summary of the clinical findings.
3. Logs the filing action to the Activity Log.

**Why This Matters:** Documentation is often the last thing a care manager does, and it is often done from memory, hours after the call. This leads to incomplete, inaccurate documentation. By generating the note in real time during the call and making it one click to file, Florence ensures that documentation is complete, accurate, and timely.

### 7.2 The Staged Gap Integration

When a gap is staged, Florence writes directly to the athenaOne chart, adding the condition to the Problem List and generating the appropriate orders. This is a direct, real-time integration that eliminates the manual data entry that would otherwise be required.

---

## Chapter 8: The Patient — Jane Doe

The Florence demo is built around a single patient: **Jane Doe, 68-year-old female, HIGH RISK, CCM-enrolled**. Jane's clinical profile is designed to illustrate the full range of Florence's capabilities.

Jane was recently discharged from St. Joseph's Hospital after an acute myocardial infarction (heart attack). She has multiple comorbidities, including Type 2 Diabetes with Diabetic CKD, Chronic Kidney Disease Stage 3a, Essential Hypertension, and Major Depressive Disorder. She is on a complex medication regimen and has several open care gaps.

Jane's story is the thread that runs through every feature of Florence. The Engage call is her post-discharge follow-up. The Convene call is her care manager checking in on her recovery. The care gaps are her real, documented clinical needs. The workflow suggestions are triggered by her real concerns about home oxygen, medication confusion, and difficulty with daily activities.

By grounding the demo in a realistic, complex patient, Florence demonstrates its value in the most challenging care management scenarios — the ones where the stakes are highest and the need for intelligent assistance is greatest.

---

## Appendix A: Glossary

| Term | Definition |
|---|---|
| **ADT Notification** | Admit, Discharge, Transfer notification — an automated alert sent by a hospital when a patient is admitted, discharged, or transferred. Florence uses ADT notifications to trigger post-discharge workflows. |
| **AWV** | Annual Wellness Visit — a Medicare preventive care visit that includes a comprehensive health risk assessment and care plan. |
| **CCM** | Chronic Care Management — a Medicare program that provides ongoing care management services to patients with two or more chronic conditions. |
| **MEAT Criteria** | Monitor, Evaluate, Assess, Treat — a documentation framework for chronic conditions that demonstrates active management and supports risk adjustment. |
| **HCC** | Hierarchical Condition Category — a risk adjustment model used by Medicare to predict future healthcare costs based on a patient's diagnoses. |
| **TCM** | Transitional Care Management — a Medicare program that provides care coordination services to patients transitioning from a hospital or skilled nursing facility to the community. |
| **DME** | Durable Medical Equipment — medical equipment prescribed for home use, such as oxygen concentrators, wheelchairs, and hospital beds. |
| **eGFR** | Estimated Glomerular Filtration Rate — a measure of kidney function. An eGFR of 45-59 indicates CKD Stage 3a. |
| **ICD-10** | International Classification of Diseases, 10th Revision — the standard diagnostic coding system used in the United States. |
| **Prior Authorization (PA)** | A requirement by a health insurance plan that a physician obtain approval before prescribing a specific medication or ordering a specific service. |

---

## Appendix B: Workflow Catalog Reference

| Workflow ID | Name | Description |
|---|---|---|
| WF-100 | Annual Wellness Visit (AWV) Prep | Pre-visit chart review, gap identification, and patient outreach for AWV. |
| WF-101 | Chronic Care Management (CCM) Monthly Check-In | Monthly touchpoint for CCM-enrolled patients with care plan review. |
| WF-102 | Transitional Care Management (TCM) | Post-discharge outreach, med reconciliation, and PCP follow-up scheduling. |
| WF-103 | Specialist Referral Coordination | End-to-end referral: submit, confirm, notify patient, and follow up. |
| WF-104 | Lab Order & Results Follow-Up | Order labs, track completion, and flag abnormal results for provider. |
| WF-105 | Home Health Start-of-Care Coordination | Referral submission, agency acceptance, and first visit confirmation. |
| WF-106 | DME Order & Delivery Coordination | Verify order, contact supplier, schedule delivery, confirm with patient. |
| WF-107 | Medication Adherence Intervention | Identify non-adherence, patient outreach, and pharmacy coordination. |
| WF-108 | Patient Education Delivery | Select materials, deliver via portal/SMS, and confirm receipt. |
| WF-109 | Prior Authorization Request | Submit PA, track status, appeal if denied, notify provider and patient. |

---

*This document is a living product bible and will be updated as Florence evolves. For questions, feedback, or contributions, please contact the NightingaleMD product team.*
