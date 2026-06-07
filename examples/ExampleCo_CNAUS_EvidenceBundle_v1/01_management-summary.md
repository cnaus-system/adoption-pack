# Management Summary — AI Governance Evidence Review
**Organisation:** ExampleCo GmbH (fictional demonstration)
**Scope:** Employee-facing AI tools in use as of 2026-05-01
**Review Date:** 2026-05-15
**Prepared by:** CNAUS Evidence Sprint
**Bundle Version:** v1

---

## Summary

ExampleCo uses 4 AI tools across its operations. This review structured and validated the available evidence for each tool against CNAUS conformance criteria.

**Overall Result: PASS (3/4 tools fully evidenced, 1 tool with findings)**

---

## Key Findings

| Tool | Owner | Data Access | Result |
|------|-------|-------------|--------|
| ChatGPT (OpenAI) | IT Dept | Internal prompts only | PASS |
| GitHub Copilot | Engineering | Source code | PASS |
| Notion AI | Operations | Internal documents | PASS |
| Custom LLM Pipeline | Data Team | Customer data | FINDINGS |

---

## Findings — Custom LLM Pipeline

- No formal risk assessment on file
- Data retention policy not documented
- Vendor agreement does not cover AI-specific clauses

**Recommended Action:** Complete risk assessment and update vendor agreement within 30 days.

---

## Verification

All evidence files are hashed and listed in `07_sha256-manifest.txt`.
Verification steps are documented in `08_verification-steps.md`.

This bundle was produced using CNAUS registry-core v1.0.14.
