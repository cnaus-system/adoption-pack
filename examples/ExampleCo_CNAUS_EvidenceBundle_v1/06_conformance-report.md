# Conformance-Style Report
**Organisation:** ExampleCo GmbH (fictional demonstration)
**Record ID:** CNAUS-DEMO-EXAMPLECO-20260515
**CNAUS Version:** registry-core v1.0.14
**Date:** 2026-05-15

---

## Result: PASS WITH FINDINGS

3 of 4 AI tools fully evidenced and conformant.
1 tool (Custom LLM Pipeline) has open findings requiring remediation.

---

## Per-Tool Results

### ChatGPT (OpenAI) — PASS
- Approval on file ✓
- Usage policy signed ✓
- Vendor agreement reviewed ✓
- Risk assessment complete ✓
- No PII involved ✓

### GitHub Copilot — PASS
- Approval on file ✓
- Restricted to internal repos ✓
- Vendor agreement reviewed ✓
- Risk assessment complete ✓
- No PII involved ✓

### Notion AI — PASS
- Approval on file ✓
- Internal use only ✓
- Vendor agreement reviewed ✓
- Risk assessment complete ✓
- No PII involved ✓

### Custom LLM Pipeline — FINDINGS
- Approval: PENDING ✗
- Risk assessment: INCOMPLETE ✗
- DPIA: MISSING ✗
- Vendor DPA: DOES NOT COVER AI PROCESSING ✗
- PII involved: YES — requires immediate remediation

---

## Scope & Limitations

This review covers employee-facing AI tools as of 2026-05-01.
Shadow AI tools not included in the register are outside scope.
This report does not constitute legal certification or regulatory approval.

---

## Reproducibility

All findings can be independently reproduced using `08_verification-steps.md`.
File integrity can be verified using `07_sha256-manifest.txt`.
