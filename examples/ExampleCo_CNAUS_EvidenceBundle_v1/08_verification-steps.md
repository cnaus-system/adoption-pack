# Verification Steps
**Bundle:** ExampleCo_CNAUS_EvidenceBundle_v1
**Record ID:** CNAUS-DEMO-EXAMPLECO-20260515

These steps allow any third party to independently verify the integrity and findings of this evidence bundle.

---

## Step 1 — Verify file integrity

Run SHA256 checksums on all files and compare against `07_sha256-manifest.txt`:

```bash
sha256sum 01_management-summary.md
sha256sum 02_ai-tool-register.csv
sha256sum 03_risk-control-mapping.md
sha256sum 04_evidence-checklist.md
sha256sum 05_cnaus-record.json
sha256sum 06_conformance-report.md
```

Expected hashes are listed in `07_sha256-manifest.txt`.
Any mismatch indicates the file has been modified after bundle creation.

---

## Step 2 — Verify tool register

Open `02_ai-tool-register.csv` and confirm:
- 4 tools listed
- Approval status matches `05_cnaus-record.json`
- Custom LLM Pipeline marked as "Pending Review"

---

## Step 3 — Verify conformance findings

Open `05_cnaus-record.json` and confirm:
- `conformance_result` = `PASS_WITH_FINDINGS`
- Custom LLM Pipeline has 3 findings listed
- All other tools have `conformance` = `PASS`

---

## Step 4 — Verify evidence checklist

Open `04_evidence-checklist.md` and confirm:
- 8/10 items evidenced
- 2 open items relate to Custom LLM Pipeline
- Items match findings in `06_conformance-report.md`

---

## Step 5 — Confirm scope

This bundle covers employee-facing AI tools as of 2026-05-01.
Shadow AI tools outside the register are not in scope.
