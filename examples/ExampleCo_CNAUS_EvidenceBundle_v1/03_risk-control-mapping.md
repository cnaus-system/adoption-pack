# Risk & Control Mapping
**Organisation:** ExampleCo GmbH (fictional demonstration)
**Scope:** Employee-facing AI tools
**Date:** 2026-05-15

---

## Risk Categories Assessed

| Risk | Description | Controls in Place | Status |
|------|-------------|-------------------|--------|
| Data leakage | Sensitive data sent to external AI providers | Usage policy, approved tool list, training | PASS |
| Unauthorised use | Employees using unapproved AI tools | Approved tool register, IT monitoring | PASS |
| Vendor risk | AI vendor changes terms, data handling, or access | Vendor review process, annual review | PASS |
| Model output risk | AI output used without human review | Human-in-the-loop policy | PASS |
| PII processing | Customer data processed by AI without legal basis | DPA review, data minimisation | FINDINGS |

---

## Findings — PII Processing (Custom LLM Pipeline)

**Risk:** Customer PII processed without completed data protection assessment.

**Control Gap:** No Data Protection Impact Assessment (DPIA) on file. Vendor DPA does not cover AI processing.

**Recommended Control:** Complete DPIA, update vendor DPA, implement data minimisation before next production run.

---

## Control Evidence References

- Usage policy: referenced in `04_evidence-checklist.md`
- Vendor agreements: referenced in `04_evidence-checklist.md`
- Approval records: `02_ai-tool-register.csv`
