# Project 2 – Support Ticket Automation

## Overview
This project showcases an end-to-end **support and operations automation system** designed to handle customer service requests in a structured, scalable way.

Instead of treating tools in isolation, the system connects customer requests directly to operational execution with defined SLAs and escalation paths.

---

## What the System Does
- Customers submit service requests through a support portal
- Requests are converted into support tickets
- Tickets automatically become operational tasks
- SLAs are tracked from first contact to task completion
- Escalations occur automatically when deadlines are missed

---

## System Layers
The design is structured into **three layers**:

### 1. Frontend Layer (Customer Support)
- Customer-facing support portal using a service desk widget
- Ticket categorization by service type, priority, and support method
- First response and resolution SLAs with automated escalation

### 2. Automation & Integration Layer
- Webhooks trigger workflows instantly when tickets are created
- Automation creates operational tasks and assigns correct pipelines
- Priority and SLA timelines are mapped automatically

### 3. Operations & Execution Layer
- Tasks are executed by engineers and technicians
- Separate operational SLAs govern execution timelines
- Supervisors maintain visibility through alerts and status updates

---

## SLA & Escalation Logic
- Frontend SLAs ensure timely customer response
- Backend SLAs ensure timely task execution
- Breaches trigger escalations, notifications, and status changes

---

## Tools Used
- Service Desk Platform
- Automation & Webhooks
- Workflow Orchestration
- Project & SLA Management

---

## Demo Links
- Evidence & Walkthrough:  
  https://nnabueze014-cell.github.io/portfolio/Projects/Project%202%20-%20Support%20Ticket%20Automation/evidence.html

- Support Portal Demo:  
  https://nnabueze014-cell.github.io/SteviewGlobal-support-demo/

---

## Key Takeaway
This project marks a shift from learning tools individually to **designing real-world operational systems**.

🚀 More improvements coming.
