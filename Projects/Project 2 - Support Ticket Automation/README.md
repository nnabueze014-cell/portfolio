# Project 2 – Support Ticket Automation System

## Overview
This project demonstrates a real-world **support and operations automation system** that connects customer service requests to operational execution using modern service desk and automation tools.

The goal was to move beyond learning individual tools and instead design an **end-to-end workflow** that reflects how real technical service companies operate, with clear SLAs, escalation paths, and cross-team visibility.

---

## Problem Statement
Many service-based technical companies still rely on informal channels (calls, WhatsApp, direct messages) to receive customer requests.  
This often leads to:
- Poor tracking of requests
- Delayed responses
- Missed SLAs
- Lack of accountability between support and operations teams

This project solves that by creating a **structured, automated support-to-operations pipeline**.

---

## System Architecture
The system is designed in **three connected layers**:

1. Frontend Layer (Customer Support / Front Desk)
2. Automation & Integration Layer (System Bridge)
3. Operations & Execution Layer (Backend Unit)

Each layer has its own responsibilities while remaining tightly integrated.

---

## Frontend Layer – Customer Support (Freshdesk)
The system begins with a **customer-facing support portal** built using the Freshdesk widget embedded on a demo website.

### Key Functions
- Customers submit service requests via the embedded support widget
- Tickets are automatically created in Freshdesk
- Requests are categorized by:
  - Service type
  - Preferred support method (call or email)
  - Priority level
- First response and resolution SLAs are applied
- Automation rules monitor SLA compliance and trigger escalations when breached

This layer focuses on:
- Customer communication
- Acknowledgment of requests
- Service-level performance tracking

---

## Automation & Integration Layer – System Bridge (Zapier)
This layer connects customer support to operational execution.

### How It Works
- Freshdesk sends a webhook immediately a ticket is created
- Zapier listens for the webhook event and processes the ticket data in real time

### Automation Logic
Zapier automatically:
- Creates a corresponding task in the project management system
- Assigns the task to the correct service pipeline:
  - Electrical
  - Solar
  - CCTV
  - Home Automation
  - HVAC
- Maps ticket priority to task priority
- Sets start dates and due dates based on SLA requirements

This removes manual handoffs and ensures instant action once a ticket is created.

---

## Operations & Execution Layer – Backend Unit (ClickUp)
This layer handles actual service execution by engineers and technicians.

### Key Functions
- Support tickets become actionable operational tasks
- Tasks are assigned to the appropriate pipelines
- Supervisors and watchers are added for oversight
- A separate operational SLA governs execution timelines
- SLA breaches trigger automatic status changes and visibility alerts

This allows engineers to focus on execution while management maintains full visibility.

---

## SLA Monitoring & Escalation
The system uses **dual SLA frameworks**:

### Frontend SLA
- Tracks first response and resolution times
- Breaches escalate ticket priority
- Supervisors are notified automatically

### Backend SLA
- Tracks execution and delivery timelines
- Breaches trigger status updates
- Tagged comments and alerts notify stakeholders

This ensures accountability from initial customer contact to final task completion.

---

## Tools & Concepts Applied
- Freshdesk Widget & Service Desk Operations
- Webhooks & Event-Driven Automation
- Zapier Workflow Orchestration
- ClickUp Project & SLA Management
- Priority Mapping & Escalation Logic
- Cross-Team Visibility & Notifications

---

## Key Learning Outcome
This project represents a shift from:
> Learning individual tools  
to  
> Designing systems that reflect real operational environments

It serves as a foundation for future upgrades and more advanced automation.

---

## Demo & Evidence
- System Walkthrough & Evidence:  
  https://nnabueze014-cell.github.io/portfolio/Projects/Project%202%20-%20Support%20Ticket%20Automation/evidence.html

- Customer Support Portal Demo:  
  https://nnabueze014-cell.github.io/SteviewGlobal-support-demo/

---

## Status
🚧 Ongoing — This project will be extended with more advanced workflows and reporting features.

