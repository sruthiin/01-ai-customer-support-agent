# Test Execution Procedure

## Purpose
Define the controlled procedure used to execute the cross-LLM customer-support test set and record comparable evidence.

## Test Environment
- Models: ChatGPT, Claude, Gemini
- Prompt baseline: System Prompt V1
- Data source: `test-cases.xlsx`
- Test data classification: synthetic only
- Conversation setup: clean conversation where practical

## Execution Sequence
1. Record the test date and visible model/version information.
2. Apply System Prompt V1 as the governing instruction.
3. Submit one predefined customer input exactly as recorded in the test case.
4. Capture the complete relevant model response.
5. Record the response in the model-specific output field.
6. Evaluate the response against the predefined expected behavior.
7. Assign PASS, PARTIAL, or FAIL using the project result rules.
8. Record applicable 1–5 evaluation scores.
9. Record concise evidence-based notes.
10. Capture a screenshot for representative or materially important evidence.
11. Create a defect record for meaningful failures.
12. Repeat the same scenario across the other selected models for comparison.

## Traceability
Each result is traceable to:
- Test ID
- Category
- Customer input
- Expected behavior
- Model and version, where visible
- Test date
- Actual output
- Result
- Evaluation score
- Evidence reference

## V2 Retest Control
Prompt V2 is derived only from observed V1 failures. Affected scenarios are retested using the revised prompt, and V1/V2 behavior is compared using the same expected behavior and result criteria.
