# Automation Portfolio

### Hands-On n8n Workflows, Integrations & AI-Assisted Business Solutions

Welcome to my automation portfolio.

I build practical workflow automation solutions designed to reduce repetitive tasks, connect business applications, organize data, and improve day-to-day processes. My current focus is **n8n workflow automation, API integrations, webhooks, Google Workspace, and AI/LLM-powered workflows**.

This portfolio showcases projects I have built while developing my skills in workflow automation and AI-assisted solutions.

---

## 🚀 Featured Projects

### 1. CRM Lead Management Automation

**n8n · Google Sheets · Forms · Gmail · Webhooks**

An automated lead management workflow that captures potential leads, checks for existing records, generates unique Lead IDs for new leads, updates the CRM, and sends notifications.

**Key concepts demonstrated:**

* Form-triggered workflows
* Google Sheets integration
* Duplicate lead detection
* Conditional branching
* Dynamic Lead ID generation
* Automated email notifications
* Data updates and record management

**[View Project →](#)**

---

### 2. Payment Tracking Automation

**n8n · Gmail · Google Sheets**

An automation that processes payment notification emails and records relevant payment information in a structured spreadsheet.

**Key concepts demonstrated:**

* Email-triggered automation
* Email data extraction
* Data transformation
* Google Sheets integration
* Automated record updates

**[View Project →](#)**

---

### 3. Employee Leave Management Automation

**n8n · Forms · Google Sheets · Slack**

A workflow designed to streamline employee leave requests by collecting submission data, determining leave status, updating records, calculating remaining leave, and notifying the appropriate team members.

**Key concepts demonstrated:**

* Form automation
* Conditional logic
* Data validation
* Leave balance calculations
* Spreadsheet updates
* Automated team notifications

**[View Project →](#)**

---

### 4. Employee Availability Heatmap Dashboard

**n8n · Forms · Google Sheets · Data Processing**

A workflow that collects employee availability information and transforms the submitted data into a visual availability dashboard.

**Key concepts demonstrated:**

* Form data collection
* Time and date processing
* Data transformation
* Spreadsheet automation
* Dashboard generation
* Availability visualization

**[View Project →](#)**

---

### 5. Multi-Source Email Funnel & Application Tracking System

**n8n · Gmail · Email Processing · Data Classification · Google Sheets · Link/Security Analysis**

A centralized email automation workflow designed to collect messages from multiple email sources and funnel them into a single tracking system.

The workflow is being developed to organize job applications, identify job offers and recruitment-related messages, and flag potentially suspicious emails or links for further review.

Rather than manually monitoring multiple inboxes, the workflow provides a centralized process for receiving, categorizing, and tracking incoming messages.

**Key concepts demonstrated:**

* Multi-source email ingestion
* Email forwarding and routing
* Automated email classification
* Job application tracking
* Job offer identification
* Phishing and suspicious-link detection
* Email content processing
* Data extraction
* Google Sheets/database tracking
* Conditional workflow branching
* Automated notifications
* Centralized email monitoring

**Planned workflow:**

```text
    Multiple Email Sources
            ↓
       Email Collection
            ↓
          n8n
            ↓
     ┌──────┼──────────┐
     ↓      ↓          ↓
    Job    Offer    Suspicious
           /Recruiter  Email
     ↓      ↓          ↓
     └──────┼──────────┘
            ↓
     Classification
            ↓
     ┌───────────────┐
     │               │
     ↓               ↓
    Tracking       Security
    Database       Review
     │               │
     └───────┬───────┘
             ↓
       Notifications /
       Follow-up Actions
```

**Example information that can be tracked:**

| Field         | Purpose                                         |
| ------------- | ----------------------------------------------- |
| Sender        | Identify the company/recruiter                  |
| Subject       | Categorize the message                          |
| Date Received | Track communication timeline                    |
| Company       | Associate the message with an employer          |
| Position      | Identify the job role                           |
| Email Type    | Application, rejection, offer, recruiter, etc.  |
| Status        | New, reviewing, applied, interview, offer, etc. |
| Links         | Extract relevant URLs for review                |
| Risk Flag     | Identify potentially suspicious messages        |
| Notes         | Add additional information                      |

**Security considerations:**

The workflow is designed to assist with identifying potentially suspicious emails and links. It does not automatically assume that an email is malicious. Suspicious messages can instead be flagged for manual review before any link is opened or action is taken.

**What I'm learning through this project:**

* Processing emails from multiple sources
* Building classification logic
* Extracting structured information from unstructured email content
* Designing workflows around real-world data
* Handling potentially unsafe links and messages
* Building centralized tracking systems
* Creating automation with human review points

**Project Status:** 🚧 In Development

**[View Project →](#)**


---

## 🛠️ Technologies & Tools

### Workflow Automation

* n8n
* Webhooks
* Workflow triggers
* Conditional logic
* Data transformation
* Scheduled workflows

### Integrations & APIs

* REST APIs
* Google Workspace APIs
* Gmail
* Google Sheets
* Google Calendar
* Google Drive
* Discord

### AI & LLM

* Large Language Models (LLMs)
* Prompt Engineering
* AI-assisted workflows
* AI Agent concepts

### Development & Infrastructure

* Docker
* Self-hosted n8n
* JSON
* JavaScript expressions

---

## 📚 What I'm Currently Developing

My current learning path is focused on progressing from individual workflows toward more complete automation systems.

### Current Focus

* Advanced n8n workflow design
* REST API integrations
* Webhooks
* Authentication and OAuth
* Data transformation
* Error handling
* AI/LLM integrations
* AI agents
* Docker-based deployments
* Production-oriented workflow design

---

## 💡 My Approach to Automation

I focus on building automation around real business processes rather than isolated technical demonstrations.

My typical approach is:

**Identify the repetitive process**

↓

**Understand the data and systems involved**

↓

**Design the workflow**

↓

**Connect the required applications/APIs**

↓

**Add validation and conditional logic**

↓

**Automate notifications and updates**

↓

**Test and improve the workflow**

The goal is to create workflows that are practical, understandable, and maintainable.

---

## 📂 Portfolio Philosophy

These projects are hands-on demonstrations of my developing automation skills.

I believe a portfolio should show not only **what tools were used**, but also:

* What problem the automation addresses
* How the workflow works
* Why specific tools were selected
* How data moves between systems
* What challenges were encountered
* What was learned during development

Where possible, each project includes workflow files, screenshots, documentation, and example data.

> **Note:** Portfolio projects use demonstration data and credentials are never included in the repositories.

---

## 📈 Learning Journey

I am currently building my experience in **AI and workflow automation**, with a particular focus on n8n and practical business automation.

My background also includes extensive experience in **transcription, proofreading, data-related work, and working with structured information**, which has helped me develop strong attention to detail and familiarity with process-driven work.

I am now combining that experience with automation technologies to build solutions that reduce repetitive manual work and improve business workflows.

---

## 📫 Connect With Me

**LinkedIn:** [Your LinkedIn Profile](#)

**Email:** [Your Email](#)

**GitHub:** [Your GitHub Profile](#)

---

### ⭐ Thanks for visiting

I'm continuously adding new projects and improving existing workflows as I expand my knowledge of automation, APIs, AI, and workflow engineering.
