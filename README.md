AI Agent – Opportunity & Document Automation
Overview

This agent automates the creation and preparation of sales opportunities in Dynamics 365.
It reduces manual work by enriching data, structuring SharePoint folders, and generating customer-specific documents.

What it does

Given an inbound request (e.g. RFP), the agent will:

Resolve or create the Account and Contacts
Enrich the Account with public and financial data
Discover additional relevant Contacts
Create or update an Opportunity
Prepare a structured SharePoint workspace
Generate customer-specific documents (PowerPoint offer + Word agreement)
Save document links back to the Opportunity
Tools used (MCP)

The agent is connected to the following tools via Model Context Protocol:

Microsoft Dataverse (CRM data: Accounts, Contacts, Opportunities)
Work IQ SharePoint (document storage and folder structure)
Work IQ Teams (Teams / SharePoint workspace context)
Work IQ Word (agreement document generation)
Work IQ Copilot (general reasoning and orchestration)
Key capabilities
No duplicate record creation
Proactive data enrichment (not just input-based)
Template-based document generation with case-specific content
Automated SharePoint folder structure
End-to-end flow from request → ready-to-work Opportunity
How it works (simplified)
Understand input
Resolve customer context
Create/update Opportunity
Prepare SharePoint workspace
Generate tailored documents
Save everything back to CRM
Result

A ready-to-use Opportunity with:

structured data
enriched context
linked documents
prepared workspace

👉 All repetitive groundwork completed automatically.

Notes
Requires valid SharePoint location
Documents are finalized before saving (no post-editing step)
Contact creation requires email
