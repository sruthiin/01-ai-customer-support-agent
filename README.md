# AI Customer Support Agent — Cross-LLM Testing & Evaluation

## Project Classification
**Independent GenAI Portfolio Project**  
**Business Scenario:** ShopEase (fictional e-commerce company)  
**Data Classification:** Synthetic test data only  
**Project Focus:** Business Analysis, AI Quality Engineering, LLM evaluation, prompt engineering, defect analysis

## Project Overview
This project evaluates a prompt-defined AI customer-support assistant for first-level e-commerce support. The evaluation focuses on whether the assistant can provide useful guidance within defined business and safety boundaries, recognize missing information, avoid unsupported claims, and escalate cases that are outside scope or cannot be safely resolved.

## Business Problem
ShopEase receives a high volume of repetitive customer-support requests related to orders, cancellations, refunds, payments, damaged or incorrect products, and account issues. The proposed AI assistant is intended to reduce routine workload and improve response consistency while maintaining clear safety and escalation boundaries.

## Project Objective
Design, test, evaluate, improve, and compare the customer-support assistant across ChatGPT, Claude, and Gemini using consistent prompts and synthetic customer scenarios wherever practical.

## Scope
### In Scope
- Order-tracking guidance
- Cancellation information
- Refund information
- Payment issue guidance
- Damaged or incorrect product guidance
- Basic account-support guidance
- Ambiguous-query clarification
- Human escalation

### Out of Scope
- Real database integration
- Real order lookup
- Actual refund processing
- Real payment transactions
- Sensitive account changes
- Production deployment

## Business and AI Quality Requirements
The assistant is expected to:
- provide first-level guidance for supported query types;
- request clarification when required information is missing;
- state limitations when real-time information is unavailable;
- avoid fabricated order, payment, refund, delivery, or policy information;
- avoid unnecessary sensitive-data collection;
- escalate complex, sensitive, unsupported, or uncertain cases;
- maintain a professional and concise tone.

## Evaluation Approach
The project uses a controlled test approach:

**Requirements → Conversation Design → Prompt V1 → Test Execution → Observation → Evaluation → Defect Logging → Prompt V2 → Retest → Cross-LLM Comparison → Final Findings**

The same predefined synthetic scenarios are used across the selected models wherever practical. Evaluation uses a predefined 1–5 scale across Accuracy, Relevance, Instruction Following, Hallucination Control, Ambiguity Handling, Safety, Escalation, and Consistency.

## Evidence
Primary evidence consists of actual model outputs, test records, evaluation scores, defect records, selected screenshots, and V1/V2 retest comparisons. Results are reported only from executed tests.

## Tools Used
Tools actually used for execution are recorded in the final project documentation. The planned evaluation environment includes ChatGPT, Claude, Gemini, spreadsheet tooling, and GitHub.

## Repository Structure
```text
01-ai-customer-support-agent/
├── README.md
├── 01-business/
├── 02-requirements/
├── 03-agent-design/
├── 04-testing/
├── 05-results/
├── 06-prompt-iteration/
├── screenshots/
├── learning-notes.md
└── final-case-study.md
```

## Project Status
The project design, requirements, prompt V1, test strategy, evaluation rubric, synthetic test data definition, and 26 test cases are established. Live cross-LLM execution and evidence-based prompt iteration are populated after model testing.

## Disclaimer
ShopEase, its operating context, customer scenarios, policies, and test data are fictional. This repository represents an independent portfolio project and does not represent paid employment, client delivery, or production deployment.
