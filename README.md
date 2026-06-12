![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![AI](https://img.shields.io/badge/AI-Microsoft%20Foundry-blue)
![Category](https://img.shields.io/badge/Category-Compliance-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Hackathon](https://img.shields.io/badge/Agents%20League-2026-purple)

███████╗██╗  ██╗ █████╗ ███╗   ███╗████████╗
██╔════╝██║  ██║██╔══██╗████╗ ████║╚══██╔══╝
███████╗███████║███████║██╔████╔██║   ██║   
╚════██║██╔══██║██╔══██║██║╚██╔╝██║   ██║   
███████║██║  ██║██║  ██║██║ ╚═╝ ██║   ██║   
╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝   ╚═╝   

SMART FORMS COMPLIANCE AGENT

📌 Overview
The Smart Forms Compliance Agent is an AI-powered assistant built using Microsoft Foundry.
It performs end-to-end compliance analysis on unstructured federal form text — all in one intelligent pass, without workflows or multi-step orchestration.

This project demonstrates how a single Foundry agent can:

Parse messy, unstructured text
Extract key fields
Validate completeness
Flag compliance risks
Recommend corrections
Produce a clean, human-readable compliance summary

🧠 Features

✔ One-pass compliance pipeline
All logic is embedded inside a single agent instruction block.

✔ Automatic field extraction
The agent identifies:
Name
Email
Address
ZIP
Date
Signature

✔ Validation engine
Flags:
Missing required fields
Invalid formats
Inconsistencies
Compliance risks

✔ Clean, readable summaries
The agent returns a polished compliance report — never JSON.

🧩 How It Works
┌──────────────────────────────┐
│        User Input            │
│  (Unstructured form text)    │
└───────────────┬──────────────┘
                │
                ▼
┌──────────────────────────────┐
│      1. Field Extraction     │
│ Extracts: name, email,       │
│ address, ZIP, date, signature│
└───────────────┬──────────────┘
                │
                ▼
┌──────────────────────────────┐
│       2. Validation          │
│ Identifies missing fields,   │
│ inconsistencies, risks       │
└───────────────┬──────────────┘
                │
                ▼
┌──────────────────────────────┐
│   3. Compliance Summary      │
│ Human-readable explanation   │
│ + recommended corrections    │
└───────────────┬──────────────┘
                │
                ▼
┌──────────────────────────────┐
│        Final Output          │
│ Clean compliance report      │
└──────────────────────────────┘

📝 Example Input
Name: John Doe, Email:, Address:, ZIP:, Date:, Signature:

✅ Example Output
Compliance Summary:

Fields Present: Name (John Doe)
Fields Missing: Email, Address, ZIP, Date, Signature
Compliance Risks: The form is missing all required fields except for the name.
Recommended Corrections: Provide a valid email, address, ZIP code, date, and signature.

📁 Project Structure
smart-forms-agent/
│
├── README.md                # Full project documentation
├── agent-instructions.txt   # Main agent logic (single-pass pipeline)
└── examples/
    ├── example-input.txt
    └── example-output.txt
    
🎯 Hackathon Context

This project was built for the Microsoft Agents League Hackathon to demonstrate:
Practical use of Microsoft Foundry
Intelligent automation for federal workflows
How a single agent can replace multi-step workflows
Real-world compliance automation

👩🏽‍💻 Author
Milka Bekele  
AI + Modern Work Engineer (in progress)
Washington, DC

