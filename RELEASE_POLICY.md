---
title: CNAUS Adoption Pack Release Policy
status: Informative
scope: Non-Core
---

# CNAUS Adoption Pack Release Policy (Non-Core)

## 1. Canonical Source
The canonical source for the CNAUS Adoption Pack is this repository’s `main` branch and its immutable, annotated git tags.

## 2. Releases and Immutability
- A release MUST be represented by an annotated git tag (e.g., `v0.1.0`).
- Tags are immutable references. Published tags MUST NOT be moved or rewritten.
- Corrections after a release MUST be shipped as a new tag.

## 3. Versioning
This repository follows Semantic Versioning.
- During early adoption the major version may remain `0` (e.g., `0.x.y`).
- PATCH (`0.x.y` → `0.x.(y+1)`): wording fixes, template clarifications, examples, added guidance that does not change intended deliverables.
- MINOR (`0.x.y` → `0.(x+1).0`): new templates, new optional sections, expanded walkthroughs.
- MAJOR (`0.x.y` → `1.0.0`): stable, procurement-ready pack with consistent templates and no “structural churn”.

## 4. What this Pack is (and is not)
- This pack is implementation and review guidance for adopting the CNAUS Core Standard.
- This pack is NOT the CNAUS Core Standard and MUST NOT introduce new normative requirements for the Core Standard.

## 5. Release Contents
A release MUST contain:
- Clear scope statement (`SCOPE.md`)
- Review guidance (`HOW_TO_REVIEW.md`)
- Implementation guidance (`HOW_TO_IMPLEMENT.md`)
- Templates (intake, SOW, DoD, report templates)
- At least one end-to-end walkthrough in `examples/`
- `CHANGELOG.md`

