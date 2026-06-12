![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![AI](https://img.shields.io/badge/AI-Microsoft%20Foundry-blue)
![Category](https://img.shields.io/badge/Category-Compliance-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Hackathon](https://img.shields.io/badge/Agents%20League-2026-purple)

# Smart Forms Compliance Agent

The Smart Forms Compliance Agent is an AI-powered assistant built using Microsoft Foundry.  
It performs end-to-end compliance analysis on unstructured form text in a single pass — no workflows required.

## 🚀 What It Does
Given any form text, the agent:
1. Extracts key fields (name, email, address, ZIP, date, signature)
2. Identifies missing or inconsistent fields
3. Flags compliance risks
4. Recommends corrections
5. Returns a clean, human-readable compliance summary

All logic is contained inside one powerful agent instruction block.

## 🧠 How It Works
The agent follows a strict internal pipeline:

### 1. Field Extraction
- Parses unstructured text
- Normalizes fields
- Fills missing fields with empty values

### 2. Validation
- Detects missing required fields
- Checks for invalid formats
- Identifies compliance risks

### 3. Summary Generation
- Produces a clear, concise compliance report
- No JSON is exposed to the user
- No follow-up questions unless necessary

## 🛠 Example Input
Name: John Doe, Email:, Address:, ZIP:, Date:, Signature:
Compliance Summary:
Fields Present: Name (John Doe)
Fields Missing: Email, Address, ZIP, Date, Signature
Compliance Risks: The form is missing all required fields except for the name.
Recommended Corrections: Provide a valid email, address, ZIP code, date, and signature.
