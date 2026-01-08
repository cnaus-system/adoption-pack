---
title: CNAUS Adoption Pack — Definition of Done Checklist
status: Informative
scope: Non-Core
---

# Definition of Done (DoD) — Conformance/Evidence Sprint

## A) Required Deliverables (must all be present)
- [ ] Conformance Report produced (filled, not a blank template)
- [ ] Evidence Bundle delivered as a folder/zip with stable structure
- [ ] Evidence Bundle includes hashes (sha256) for all included files
- [ ] Verification Steps included and reproducible by a third party

## B) Minimum Checks (PASS/FAIL)
The report MUST clearly state:
- [ ] What was checked (explicit checklist)
- [ ] What inputs were used (explicit list)
- [ ] PASS/FAIL outcome and rationale
- [ ] Any deviations or exceptions (explicit)

## C) Reproducibility
- [ ] A third party can follow `VERIFICATION_STEPS.md` and obtain the same validation results
- [ ] All referenced files exist at the referenced paths inside the evidence bundle
- [ ] No “TBD”, “...” or placeholder sections remain in the delivered report

## D) Constraints
- [ ] Scope boundaries are written (tenant, systems, environments)
- [ ] Out-of-scope items are written
- [ ] Any redactions are documented

