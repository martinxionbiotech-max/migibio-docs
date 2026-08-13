---
title: "Calibration & Standard Curve Management"
date: 2026-08-13
description: "How Migibio FIA680/FIA880 analyzers manage calibration and standard curves — QR code, cloud sync, QC verification, and why pre-loaded curves reduce operator error."
---

# Calibration & Standard Curve Management

Calibration is what turns a raw fluorescence signal into a meaningful concentration. This page explains how the FIA680/FIA880 manage standard curves — and why the operator never builds one manually.

## Why Pre-Loaded Curves Matter

A standard curve maps fluorescence intensity to analyte concentration. Manually constructing curves is the single largest source of inter-operator variability in quantitative testing. Migibio removes this by **pre-loading** validated curves.

| Curve method | How it works | Operator effort |
|--------------|--------------|-----------------|
| QR code (FIA680) | Scan code → curve loads | Scan only |
| Cloud sync (FIA880) | Curve pushed automatically | None |
| Manual construction | Operator builds curve | High (error-prone) |

## The Calibration Chain

```
Assay lot → validated standard curve → QR code / cloud → analyzer → result
```

Each production lot is validated against a standard curve during manufacturing; that curve is then delivered to the analyzer via QR code or cloud sync.

## QC Verification

Even with pre-loaded curves, routine QC confirms the system is reading correctly:

| QC step | Frequency | Purpose |
|---------|-----------|---------|
| QC cartridge | Daily | Verify curve integrity |
| Lot-change verification | Per new lot | Confirm new curve loads |
| Full calibration | Per service schedule | Instrument-level check |

## What This Means for Results

- **No manual curve errors** — the operator cannot mis-enter a curve.
- **Lot-specific accuracy** — each lot uses its own validated curve.
- **Consistency across operators** — two operators get the same result from the same sample.

## FAQ

**Do I need to recalibrate between lots?** When you receive a new assay lot, load the new lot's curve (QR scan or cloud). No manual recalibration is required.

**How do I know the curve is valid?** Daily QC cartridge verification confirms the analyzer reads the expected control value.

*For maintenance schedules, see the [FIA680](/domain-01-analyzer-technology/fia680-guide/) and [FIA880](/domain-01-analyzer-technology/fia880-guide/) guides.*
