# Assignment 01 — Product Discovery

## Objective

Before performing threat modeling or security analysis, it is essential to understand the product, its purpose, users, and business workflows.

This exercise focuses on gathering foundational information about the target system. The goal is not to identify vulnerabilities but to build a clear understanding of the product and its business context.

## Scenario

You are an AI Product Security Analyst assigned to review FinBot, a multi-agent AI platform used in the financial services industry.

The platform automates several business processes including vendor onboarding, invoice processing, payment operations, fraud investigation, and vendor communications.

Before conducting any security assessment, you must first understand the product and document its core characteristics.

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

Produce a Product Discovery Report that summarizes:

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
