# Assignment 01 — Product Discovery

## Objective

Before performing threat modeling or security analysis, it is essential to understand the product, its purpose, users and business workflows.

This exercise focuses on gathering foundational information about the target system. The goal is not to identify vulnerabilities but to build a clear understanding of the product and its business context.

Product understanding is a critical first step in any security review because security risks can only be evaluated within the context of business objectives, users, data flows and system functionality.


## Assignment Context

As an AI Product Security Analyst, you have been assigned to perform an initial security review of FinBot, a multi-agent AI platform used in the financial services industry.

The platform automates several business processes including vendor onboarding, invoice processing, payment operations, fraud investigation, and vendor communications.

Before conducting any security assessment, it is necessary to understand the product and document its core characteristics.


## Target System

This exercise uses **OWASP FinBot CTF** as the target application.

OWASP FinBot is an intentionally vulnerable agentic AI platform developed by the OWASP GenAI Security Project for education, security research, and hands-on learning.

The purpose of this project is not to develop or modify FinBot, but to perform a structured AI Product Security review of the platform from the perspective of an AI Product Security Analyst.

All product ownership, source code, and intellectual property belong to the OWASP GenAI Security Project and its contributors.

Project Repository:

https://github.com/GenAI-Security-Project/finbot-ctf


## Assumptions

This exercise is based solely on publicly available documentation and source code.

Any assumptions made during the analysis should be clearly documented and validated during later stages of the security review.


## Tasks

### 1. Product Purpose

Describe the primary purpose of the platform.

Consider:

* What problem does the product solve?
* Why was it built?
* What business value does it provide?


### 2. Main Users

Identify the primary user groups.

Examples may include:

* Internal employees
* Administrators
* Vendors
* Finance teams
* Compliance teams

Document each user type and their relationship to the platform.


### 3. Core Business Functions

Identify the most important business functions provided by the platform.

Examples:

* Vendor onboarding
* Invoice processing
* Payment operations
* Fraud investigation
* Vendor communications

Explain why each function is important to the business.


### 4. AI Components

Identify all AI-related components currently known.

Examples may include:

* Chat Agent
* Orchestrator Agent
* Specialized Agents
* Tool Integrations
* MCP Integrations

Document the role of each component within the platform.


### 5. Open Questions

List information that is still unknown and should be clarified before beginning a formal threat model.

Examples:

* Which LLM models are used?
* What permissions do agents have?
* Which tools can agents access?
* What sensitive data is processed?
* How are agents authenticated and authorized?


## Deliverable

Create a Product Discovery Report documenting your findings.

Suggested file:

```text
product-understanding/product-discovery-report.md
```

The report should summarize:

* Product purpose
* Users
* Business functions
* AI architecture components
* Outstanding questions

This document will serve as the foundation for future activities including:

* Architecture Review
* Asset Inventory
* Trust Boundary Analysis
* Threat Modeling
* Risk Assessment


## Learning Goals

By completing this assignment, you should be able to:

* Understand a product before performing security analysis
* Identify business-critical functionality
* Recognize AI-specific system components
* Gather information required for threat modeling
* Document assumptions and knowledge gaps
