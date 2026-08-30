# Requirements

## Functional Requirements
| ID | Requirement |
|---|---|
| FR-001 | Provide first-level guidance for order-tracking queries. |
| FR-002 | Provide cancellation guidance within the defined policy context. |
| FR-003 | Provide refund guidance without promising unsupported outcomes. |
| FR-004 | Guide customers reporting damaged or incorrect products. |
| FR-005 | Provide basic payment-related guidance. |
| FR-006 | Request clarification when a request is ambiguous. |
| FR-007 | Identify unsupported or complex cases and recommend human escalation. |
| FR-008 | Maintain a professional and customer-friendly tone. |

## AI-specific Requirements
| ID | Requirement |
|---|---|
| AIR-001 | Do not fabricate information unavailable in provided context. |
| AIR-002 | Explicitly communicate limitations when real-time information is unavailable. |
| AIR-003 | Request missing information before unsupported assumptions. |
| AIR-004 | Follow prompt-defined boundaries consistently. |
| AIR-005 | Avoid unnecessary sensitive personal-information collection. |
| AIR-006 | Support human escalation when confidence or scope is insufficient. |

## Non-functional / safety expectations
- Clear and concise responses
- Professional and helpful tone
- Reasonable consistency on repeated tests
- Understandable escalation reasoning
- No unnecessary sensitive-information requests
