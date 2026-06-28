# PRONTA – Sales & Service Brain

## Project Report

---

## Project Overview

**PRONTA – Sales & Service Brain** is an AI-powered business automation system built using **n8n**. The project automates customer interactions by intelligently handling sales inquiries, generating quotations, and managing customer complaints. It integrates Large Language Models (LLMs) with workflow automation to reduce manual work, improve response time, and provide a consistent customer experience.

The system is designed as a collection of independent workflows that work together to automate the complete customer support and sales process.

---

# Objectives

The primary objectives of this project are:

* Automate customer inquiry processing.
* Classify customer messages using Artificial Intelligence.
* Generate professional quotations automatically.
* Create and manage complaint tickets.
* Reduce manual effort for support and sales teams.
* Improve response accuracy and consistency.
* Demonstrate the capabilities of AI-powered workflow automation using n8n.

---

# Technology Stack

| Component           | Technology               |
| ------------------- | ------------------------ |
| Workflow Automation | n8n                      |
| AI Model            | OpenAI / Claude (LLM)    |
| Communication       | WhatsApp, Discord        |
| Data Storage        | Google Sheets / Database |
| APIs                | HTTP Request APIs        |
| Version Control     | Git & GitHub             |

---

# System Architecture

The project consists of three major workflows:

1. Inquiry Classifier
2. Quotation Generator
3. Complaint Ticket System

Each workflow operates independently while contributing to the overall Sales & Service Brain.

---

# Workflow 1 – Inquiry Classifier

## Purpose

The Inquiry Classifier automatically analyzes incoming customer messages and determines the type of inquiry.

## Process

1. Receive customer message.
2. Send the message to the AI model.
3. Classify the inquiry into predefined categories.
4. Route the inquiry to the appropriate workflow.
5. Store the result for future processing.

## Categories

* Sales Inquiry
* Complaint
* Product Information
* General Inquiry
* High Priority
* Critical Priority

## Benefits

* Eliminates manual message sorting.
* Faster customer response.
* Improved workflow routing.
* Better customer experience.

---

# Workflow 2 – Quotation Generator

## Purpose

The Quotation Generator creates professional quotations automatically based on customer requirements.

## Process

1. Receive quotation request.
2. Extract required information.
3. Generate quotation using AI.
4. Format the quotation.
5. Deliver the quotation to the customer.
6. Save quotation records.

## Features

* AI-generated quotations.
* Professional formatting.
* Automated delivery.
* Reduced manual effort.
* Consistent pricing presentation.

---

# Workflow 3 – Complaint Ticket System

## Purpose

The Complaint Ticket System manages customer complaints automatically from submission to notification.

## Process

1. Receive complaint.
2. Analyze complaint using AI.
3. Determine priority level.
4. Generate unique ticket ID.
5. Store complaint details.
6. Notify support team.
7. Send confirmation to customer.

## Priority Levels

* Low
* Medium
* High
* Critical

## Notifications

High and Critical priority complaints trigger instant notifications through:

* Discord
* WhatsApp

This ensures urgent issues receive immediate attention from the support team.

---

# AI Integration

Artificial Intelligence is used throughout the project for:

* Natural language understanding
* Intent classification
* Information extraction
* Quotation generation
* Complaint analysis
* Priority detection
* Response generation

The AI enables the workflows to process customer requests intelligently without requiring predefined keyword matching.

---

# Key Features

* AI-powered automation
* Intelligent inquiry classification
* Automatic quotation generation
* Complaint ticket management
* Priority detection
* Real-time notifications
* Modular workflow design
* Easy scalability
* Reduced manual workload

---

# Project Benefits

## Business Benefits

* Faster response time
* Improved customer satisfaction
* Reduced operational costs
* Better support management
* Increased productivity

## Technical Benefits

* Modular architecture
* Easy maintenance
* Workflow scalability
* API integration
* AI-assisted decision making

---

# Future Enhancements

Potential improvements include:

* CRM integration
* Email automation
* Voice assistant support
* Analytics dashboard
* Customer feedback analysis
* Multi-language support
* Knowledge base integration
* Automated follow-up messages

---

# Conclusion

PRONTA – Sales & Service Brain demonstrates how Artificial Intelligence and workflow automation can transform customer service and sales operations. By combining n8n workflows with Large Language Models, the project automates repetitive business processes, improves operational efficiency, and delivers faster, more accurate customer interactions. Its modular architecture allows for future expansion, making it a scalable solution for modern businesses.

---

## Repository Structure

```text
PRONTA-Sales-Service-Brain/
│
├── workflows/
│   ├── inquiry-classifier.json
│   ├── quotation-generator.json
│   └── complaint-ticket-system.json
│
├── docs/
│   └── report.md
│
├── images/
│
├── README.md
└── LICENSE
```
