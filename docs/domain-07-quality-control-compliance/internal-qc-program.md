---
title: "Building an Internal QC Program for POCT"
date: 2026-08-13
description: "How to build an internal quality control program for veterinary POCT — daily QC cartridge verification, documentation, and error handling."
---

# Building an Internal QC Program for POCT

A rigorous internal QC program is what separates trustworthy POCT results from unverified numbers. This page explains how to build one around the Migibio FIA680/FIA880 platform.

## Why Internal QC Matters

Quantitative results are only as good as the system producing them. Internal QC catches drift **before** it affects a patient result — not after.

## The Daily QC Routine

| Step | Frequency | Purpose |
|------|-----------|---------|
| QC cartridge verification | Daily | Confirm the analyzer reads the expected control value |
| Lot-change verification | Per new lot | Confirm the new curve loads correctly |
| Documentation | Every run | Audit trail |

## Document Everything

A QC log should record:

- Date, operator, analyzer.
- QC cartridge lot + result.
- Any deviation and corrective action.

> **If it is not documented, it did not happen** — a principle that holds for accreditation and for defending a result.

## Handling QC Failures

| Situation | Action |
|-----------|--------|
| QC result out of range | Do not run patient samples; troubleshoot |
| Repeated failure | Clean optical path; contact support |
| New lot fails | Verify curve loaded; check lot integrity |

## The QC Hierarchy

```
Daily QC → Lot verification → External proficiency → Accreditation
```

Internal QC is the foundation; external proficiency (EQA) validates it against other laboratories.

## FAQ

**How often should I run QC?** Daily (or per IFU), plus at each lot change. Higher-risk settings may warrant more frequent QC.

**What do I do if QC fails?** Stop patient testing, troubleshoot (clean/verify), and document the corrective action.

*For the compliance framework, see [Quality Control & Compliance](/domain-07-quality-control-compliance/).*
