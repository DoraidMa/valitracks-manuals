# How to Limit Scoping Specialists From Signing High-Value Quotes (Proof of Concept)

This guide explains how to configure Valitracks so that scoping specialists are restricted from approving or signing high-value project quotes. This Proof of Concept (POC) shows how value thresholds, user-role permissions, and workflow checks prevent unauthorized approvals inside the ERP system.

---

## 1. Access User Roles & Permissions
- Go to **Admin Settings → User Management**.
- Select the **Scoping Specialist** role.
- Open the **Permissions** tab.
- Review which quote-related actions are enabled (e.g., *View Quote*, *Sign Quote*, *Edit Scope*).

---

## 2. Set a Maximum Allowed Quote Value
- Navigate to **Project Offer Settings → Approval Rules**.
- Enable **“Restrict Quote Signing by Value Threshold”**.
- Set the maximum amount a scoping specialist is allowed to approve.

Example:  
If the threshold is €2,500, any quote above this amount must be signed by a PM or Team Leader.

---

## 3. Configure Automatic Escalation
When a quote exceeds the limit:

- The **Sign Quote** button is replaced with **Request Approval**.
- The quote is automatically escalated to:
  - The **Project Manager**, or
  - The **Team Leader**, or
  - A **Finance/Approval Group**

Enable:  
**“Escalate quotes above threshold to authorized approvers”**

---

## 4. How It Looks for the Scoping Specialist
After the rule is active:

- Quotes **below** the limit → “Sign Quote” button visible.
- Quotes **above** the limit → locked with a message:

  **“You are not authorized to sign quotes above this value. Please escalate.”**

- A **Request Approval** button appears.
- The system logs the attempt for auditing.

---

## 5. How It Looks for PMs / Team Leaders
PMs and TLs receive:
- A notification in **Pending Approvals**
- Quote details including value breakdown
- Buttons to **Approve**, **Reject**, or **Return for Revision**

They also see who attempted to sign it.

---

## 6. What Happens Automatically (POC Logic)
Valitracks handles:

- Enforcement of value-based restrictions  
- Role-based approval permissions  
- Auto-escalation of high-value quotes  
- Audit trail creation  
- Workflow sync with ERP and Finance modules  
- Notification and approval routing  

This ensures governance without slowing down operations.

---

## Purpose of This Simulation
This POC demonstrates how Valitracks can protect financial compliance by preventing scoping specialists from authorizing high-value quotes — ensuring that the final approval always remains with senior roles.

---

## Video Simulation
View the interactive simulation here:

🔗 **https://manuals.valitracks.io/Manuals/how-to-limit-scoping-specialist-quote-approvals**
