# Payroll AI Copilot

## Overview
This project demonstrates a controlled Payroll AI Copilot built using
prompt-based GenAI principles. The system is designed to assist HR teams
and employees with payroll-related queries while ensuring safety,
privacy, and legal compliance.

⚠️ This is NOT an open chatbot. It is a constrained AI assistant.

---

## Key Features
- Context-aware payroll responses
- Role-based prompt handling (HR vs Employee)
- Legal and ethical deduction explanations
- Hallucination prevention using topic validation
- Automatic redaction of sensitive data

---

## Architecture
User Query  
→ Role Detection  
→ Context Loader (Payroll Policy)  
→ Prompt Controller  
→ Rule-based Response Engine  
→ Safety & Redaction Layer  

---

## Technologies Used
- Python
- Google Colab
- Prompt Engineering (Rule-based)
- Regex for data redaction

---

## Safety & Privacy Strategy
- AI is restricted to payroll topics only
- Out-of-scope queries are rejected safely
- Aadhaar and phone numbers are redacted
- No personal data storage or learning

---

## Sample Queries
- Why is PF deducted?
- Is ESI applicable?
- Why did tax increase?
- Is bonus taxable?

---

## Failure Scenarios & Mitigation
| Scenario | Risk | Mitigation |
|-------|------|------------|
Wrong tax advice | Legal risk | Static rule-based logic |
Sensitive data leak | Privacy breach | Redaction layer |
Hallucination | Misinformation | Topic validation |
Policy change | Outdated info | Config-based update |

---

## Conclusion
This Payroll AI Copilot demonstrates how GenAI can be safely used
in high-risk domains like payroll without hallucinations or
privacy violations.
