---
title: How to Implement CNAUS
status: Informative
conformance_scope: Non-Core
authority: CNAUS Root Authority
---

# How to Implement CNAUS (Non-Core)

## 1. Pin a CNAUS version
Select a specific CNAUS release tag `vX.Y.Z` from the canonical standard repository.

## 2. Minimal “Hello CNAUS” path
Implementation minimum for an independent implementer:
- Parse and consume `feed.json`
- Validate structural rules and `prev_hash` chain
- Validate conformance vectors (PASS/FAIL) using the provided runner or your own implementation
- Validate schema where provided (non-core)

## 3. Local verification
In the standard repo at your pinned tag:
- `make validate`

## 4. Produce a conformance claim (optional)
Use:
- `templates/CONFORMANCE_REPORT_TEMPLATE.md`

