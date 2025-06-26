# Workflow-Automation-App-ForceCom
## 🛠️ Equipment Maintenance Tracker on Force.com
This repository documents the design and implementation of a low-code Equipment Maintenance Tracker application built on the Salesforce Force.com platform. The project was created as part of a university coursework to demonstrate workflow automation, data integrity, and role-based access control in a SaaS environment.

## 🔍 Project Overview
This Force.com-based SaaS application helps IT teams or organisations manage their equipment and maintenance schedules more efficiently. It leverages Force.com's low-code environment to deliver features like:
- Object and field modeling
- Validation rules for data integrity
- Profile-based security configuration
- Role hierarchy and object-level/tab-level access control
- Automated workflows (email, task, and time-based triggers)

## 📦 Core Components
- Objects:
  - Asset: Represents physical equipment.
  - Maintenance Request: Tracks request and status of maintenance.
  - Technician: The person responsible for maintenance tasks.
- Validation Rules:
  - Prevent scheduling during inactive periods.
  - Disallow future maintenance request dates.
  - Match technician email patterns.
  - Ensure a technician is assigned based on status.
- Profiles & Access Control:
  - Profiles: Requester, Technician, Supervisor, Administrator
  - Custom tab/object visibility & editability
  - Organisation-wide defaults
- Workflow Automation:
  - Email: Notify technician on request, notify completion.
  - Task: Auto-create follow-up tasks for supervisors.
  - Time-based: Alert for delayed status updates.

## 📈 Outcome
Through configuration of five automated workflows and comprehensive security settings, the application ensures timely and secure handling of maintenance operations. The project validates key principles in low-code SaaS design and Force.com-based implementation.

