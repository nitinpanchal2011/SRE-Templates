# SRE Templates

This repository contains reusable templates and documents for Site Reliability Engineering (SRE) practices.  
It is designed as a companion to my blog series *Enterprise SRE Playbook* and *From Principles to Practice: SRE Execution Series*.  
Readers, recruiters, and practitioners can use these templates directly or adapt them for their own organizations.

---

## 📂 Repository Structure
- **postmortems/**  
  Templates for writing blameless postmortems, including incident summary, timeline, root cause analysis, lessons learned, and action items.

- **incident-command/**  
  Templates for structuring incident response roles (Incident Commander, Communications Lead, Operations Lead, Scribe).

- **error-budgets/**  
  Dashboards and governance templates for managing error budgets across multiple services.

---

## 📝 How to Use
1. Browse to the relevant folder (e.g., `postmortems/`).  
2. Open the template file (`.md`) and copy it into your own documentation system (Confluence, Google Docs, Wiki, etc.).  
3. Fill in the placeholders with incident-specific details.  
4. Refresh and update templates periodically to keep them operational.

---

## 🔗 Related Blog Series
- [Enterprise SRE Playbook – Foundations, Frameworks & Transformation Insights](https://yourbloglink.com/foundations)  
- [From Principles to Practice: SRE Execution Series](https://yourbloglink.com/execution-series)

---

## 📌 Notes
- All templates are **blameless** by design — they focus on systems and processes, not individuals.  
- Contributions and suggestions are welcome via pull requests.  
- Future additions will include templates for **SLO dashboards**, **release readiness checklists**, and **capacity planning**.

---

# Incident Response Templates

This folder contains practical templates to support Site Reliability Engineering (SRE) incident response workflows.  
Each template is designed to be lightweight, actionable, and easy to integrate into your team’s runbooks or tooling.

---

## 📋 ICS Role Assignment Checklist
**File:** `ics-role-checklist.md`

The Incident Command System (ICS) provides structure and clarity during outages.  
This checklist helps teams quickly assign roles, track handoffs, and document responsibilities during live incidents.

### Roles Covered
- Incident Commander (IC)
- Communications Lead
- Operations Lead
- Scribe/Recorder

### Usage
1. Assign roles within minutes of declaring an incident.
2. Use the handoff checklist when rotating ICs or shifting responsibilities.
3. Capture all role assignments and timelines for the postmortem.
4. Link the completed checklist to your postmortem template for continuity.

---

## 🔗 Related Templates
- [Blameless Postmortem Template](../postmortems/postmortem-template.md)  
Use this after the incident to document timeline, causes, and action items.

---

## ✅ Best Practices
- Keep templates in a central, searchable repository (e.g., Confluence, GitHub, internal wiki).
- Refresh quarterly to align with evolving systems and team structures.
- Tie follow-up actions into your backlog or sprint board to ensure improvements are tracked.

---

*These templates are part of the broader SRE Execution Series: Incident Response & Operations.*


## 👤 Author
Created by **Nitin Panchal**  
Senior Leadership | Program Governance | SRE Transformation

