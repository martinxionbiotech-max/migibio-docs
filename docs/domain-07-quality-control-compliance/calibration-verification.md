---
title: "Calibration Verification & Instrument Validation"
date: 2026-08-13
description: "Calibration verification and instrument validation for the FIA680/FIA880 — confirming the analyzer reads correctly, standard curve integrity, and validation frequency."
---

# Calibration Verification & Instrument Validation

Calibration verification confirms that the analyzer — and its loaded standard curve — produces correct results. This page covers what to verify, how often, and why.

## Calibration vs Verification

| Term | Meaning |
|------|---------|
| **Calibration** | Establishing the curve (done at manufacturing; loaded via QR/cloud) |
| **Verification** | Confirming the loaded curve reads correctly on *your* instrument |

The operator does not calibrate — they **verify** that the pre-loaded curve is reading correctly.

## Verification Methods

| Method | What it confirms |
|--------|------------------|
| QC cartridge (known value) | Analyzer reads the expected control concentration |
| Control material | Curve accuracy at a defined concentration |
| Proficiency sample | Agreement with external reference |

## Verification Frequency

| Trigger | Action |
|---------|--------|
| Daily | QC cartridge verification |
| New assay lot | Verify the new lot's curve |
| Instrument service/repair | Full verification |
| Suspicion of drift | Immediate verification |

## Acceptance Criteria

| Parameter | Acceptance |
|-----------|-----------|
| QC result | Within the control's stated range |
| Curve integrity | No error on load |
| Inter-operator agreement | Consistent results across operators |

## FAQ

**Do I ever build a standard curve myself?** No — curves are pre-loaded (QR code or cloud). Your role is verification, not construction.

**What if my QC value drifts within range?** Monitor the trend; consistent drift toward the limit warrants proactive service.

*For the QC program, see [Internal QC Program](/domain-07-quality-control-compliance/internal-qc-program/).*
