# How to Prepare a Detailed Workflow (Full Guide)

This document provides a complete, step-by-step guide on how to create, structure, and finalize a **Detailed Workflow** inside Valitracks.  
A detailed workflow is the backbone of any linguistic-validation (LV) project. It aligns tasks, roles, deadlines, automation logic, and pricing structures, ensuring that all teams operate under a unified process.

---

## 📌 1. Overview

A **Detailed Workflow** consists of:
- A sequence of LV steps (translation, reconciliation, cognitive debriefing, proofreading, etc.)
- Assigned roles and permissions
- Deadlines and durations per task
- Pricing rules (if connected to external or internal pricing cards)
- Automation triggers (notifications, dependencies)
- Upload/download requirements
- Quality-control steps
- Optional branching or conditions

This guide explains how to prepare the full workflow so that it is ready to be used in real projects or in a POC setup.

---

## 📌 2. Prerequisites

Before creating a detailed workflow, ensure the following:

1. **Company structure is set**  
   - Team Leaders created  
   - Project Managers assigned  
   - Other users created or imported

2. **Languages and locations** have been added (source, target, locales).

3. **Pricing cards** (if used) are completed.

4. You have **Team Leader permissions** (required for workflow creation).

---

## 📌 3. Starting a New Workflow

1. Navigate to:  
   **Company Owner / Team Leader → Workflows → New Workflow**

2. Enter the required metadata:
   - Workflow name  
   - Description
   - Category (LV, Translation-Only, Hybrid, etc.)
   - Visibility (internal, external, or global)

3. Choose whether the workflow will be:
   - **Simple** (straight linear)
   - **Advanced** (with branching, conditional steps, or complex dependencies)

---

## 📌 4. Adding Steps to the Workflow

Each workflow contains multiple predefined or custom steps. To add a step:

1. Click **“Add Step”**
2. Choose a step type:
   - Translation
   - Back Translation
   - Reconciliation
   - Proofreading
   - Cognitive Debriefing
   - Review/Approval
   - Import/Export
   - Custom step

3. Define parameters for each step:
   - **Step title**
   - **Assigned role** (PM, Clinician, Interviewer, Reviewer, etc.)
   - **Estimated duration**
   - **Dependencies** (Steps that must be completed before this step starts)
   - **Input/output files** required
   - **Quality checks** (where applicable)

---

## 📌 5. Configuring Automation

Each step can have automation settings:

- **Notifications**  
  Triggered when:
  - A step starts  
  - A step ends  
  - A file is uploaded  
  - A due date is near or overdue

- **Auto-assignment**  
  Automatically assigns the next step to the correct user role based on project structure.

- **Conditional routing**  
  Optional advanced logic allowing:
  - Additional QC steps only if errors > threshold  
  - Branching depending on language or project type

---

## 📌 6. Mapping Pricing (Optional)

If external or internal pricing cards exist, they can be attached.

1. Select **“Attach Pricing Card”**
2. Choose:
   - Simple Pricing  
   - External Client Pricing  
   - Internal Cost Card  
3. The system automatically maps:
   - Per service pricing  
   - Language/location-specific adjustments  
   - Volume-based or tiered rates  

Prices can be:
- Locked to the workflow  
- Variable depending on the client offer  

---

## 📌 7. Finalizing the Workflow

Before publishing the workflow:

### ✔ Review structure
Ensure:
- All steps are in logical order  
- Durations are realistic  
- No step is missing a role  
- Dependencies are consistent  
- Notifications are configured  

### ✔ Confirm permissions
Check that:
- Team Leaders have full visibility  
- PMs have operational visibility  
- Other users see only assigned steps  

### ✔ Publish
Click **Publish Workflow** to activate it.

Once published:
- It can be used in real projects  
- It can be duplicated for future workflows  
- It becomes available in “Simple Project Offer” connections (if desired)

---

## 📌 8. Using the Workflow in a Project

When creating a new project:
1. Select **Use Existing Workflow**
2. Choose your detailed workflow
3. The system auto-generates:
   - Tasks  
   - Schedules  
   - User assignments  
   - Pricing (if attached)

This ensures consistent delivery and eliminates manual setup.

---

## 📌 9. Best Practices

- Keep steps granular for maximum clarity  
- Use clear naming conventions  
- Attach pricing only when finalized  
- Test the workflow using a demo project before real deployment  
- Duplicate successful workflows for new client types  
- Update workflows centrally so changes propagate organization-wide  

---

## 📌 10. Support & Feedback

If you need help configuring complex workflows, conditional branches, or multi-team structures, contact:

**Valitracks Support**  
support@valitracks.com  
  
Or message your assigned implementation manager.

---

**© Valitracks — Workflow Preparation Guide (Full Version)**

