# Smart Forms Compliance Agent 
A multi-step reasoning agent built with Microsoft Foundry to automate Smart form validation, compliance checks, and correction recommendations.

## 🧠 Overview  
The Smart Forms Compliance Agent analyzes any government form text and performs a structured, multi-step review:

1. Extracts fields  
2. Validates completeness and consistency  
3. Identifies compliance risks  
4. Recommends corrections  
5. Generates a final compliance summary  

This agent is designed for modernization, reducing manual review time and improving accuracy.

## 🚀 Features  
- Multi-step reasoning workflow  
- JSON-based structured extraction  
- Automated compliance validation  
- Correction recommendations  
- Human-readable compliance summary  
- Built entirely in Microsoft Foundry (no code required)

## 🏗 Architecture  
**Workflow:**  
Start → ExtractFields → ValidateFields → RecommendFixes → SummarizeCompliance

**Agent:**  
Smart-Forms-Compliance-Agent (Reasoning Agent)

**Workflow Type:**  
Sequential Workflow App

## 📦 How It Works  
Users submit form text.  
The workflow processes it step-by-step and returns a final compliance report.

## 📄 Example Input  
Applicant Name: John Doe
Date of Birth:
Address: 123 Main St

## 📄 Example Output  
Status: Needs Fixes
Missing required field: Date of Birth
Recommended correction: Provide valid date in MM/DD/YYYY format
Next steps: Update missing fields and resubmit


## 🏆 Hackathon Track  
Reasoning Agents – Microsoft Foundry

## 👩‍💻 Author  
Milka Bekele  
SharePoint & Power Platform Consultant  
Washington, DC  

