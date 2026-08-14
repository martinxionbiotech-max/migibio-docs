---
title: "FIA680 Analyzer: Complete Operation Guide"
date: 2026-08-14
description: "Complete operation guide for the Migibio FIA680 single-channel fluorescence immunoassay analyzer — specifications, detection principle, workflow, sample requirements, data management, maintenance, and troubleshooting."
---

# FIA680 Analyzer: Complete Operation Guide

The **FIA680** is Migibio's single-channel fluorescence immunoassay analyzer — designed for low- to medium-volume veterinary clinics that need quantitative POCT results without the footprint or cost of a multi-channel system.

## Key Specifications

| Parameter | FIA680 |
|-----------|--------|
| Detection method | Fluorescence immunochromatography (FICT), quantitative |
| Channels | Single |
| Throughput | 1 test / run |
| Sample types | Serum, plasma, whole blood |
| Excitation source | LED |
| Detector | Photodiode |
| Calibration | Pre-loaded standard curve (QR code) |
| Result time | 3–15 min (assay-dependent) |
| Output | Concentration + qualitative flag |
| Data management | Result storage, print, export |
| Connectivity | USB (LIS/export via supported interface) |

## Detection Principle

The FIA680 quantifies fluorescence from the test cartridge:

1. **Excitation** — an LED illuminates the test line at the fluorophore's excitation wavelength.
2. **Emission** — the bound fluorescent label emits light at a longer wavelength.
3. **Detection** — a photodiode measures the emitted fluorescence intensity.
4. **Quantification** — the instrument converts fluorescence intensity to analyte concentration via the pre-loaded standard curve.

Because the readout is fluorescence intensity (not visual line darkness), results are quantitative and reproducible — the basis for CV% below 10%.

## Operation Workflow

1. **Collect sample** — serum, plasma, or whole blood per the assay IFU.
2. **Apply sample** to the test cartridge at the indicated volume.
3. **Insert cartridge** into the FIA680 sample well.
4. **Scan the QR code** (or select the assay) to load the standard curve.
5. **Read result** — the analyzer displays concentration + a qualitative flag.

## Sample Requirements

| Consideration | Guidance |
|---------------|----------|
| Sample type | Serum, plasma, or whole blood (assay-dependent) |
| Hemolysis | Avoid grossly hemolyzed samples — may affect optical readout |
| Lipemia | Avoid grossly lipemic samples for optical assays |
| Bubbles | Remove air bubbles before applying sample |
| Volume | Use the exact volume stated in the IFU |
| Freshness | Test promptly; refer to IFU for stability limits |

## Data Management & Connectivity

- **Result storage** — the analyzer retains recent test records for audit and review.
- **Printing** — results can be printed for the patient record.
- **Export** — records export via USB for integration with practice records.
- **Traceability** — each result is linked to the assay lot and standard curve used.

## When to Choose the FIA680

- **Low-volume clinics** running a handful of tests per day.
- **Startup / mobile practices** where a compact, single-channel unit is sufficient.
- **Cost-sensitive procurement** — single-channel hardware has a lower entry cost.

## Maintenance Schedule

| Item | Frequency | Purpose |
|------|-----------|---------|
| QC cartridge verification | Daily (or per IFU) | Confirm the analyzer reads the expected control value |
| Optical path / window cleaning | Weekly | Prevent dust from degrading signal |
| Standard-curve update | Via QR code (per assay lot) | Ensure the correct curve is loaded |
| Full calibration / service | Per service schedule | Manufacturer service |

## Troubleshooting

| Symptom | Likely cause | Action |
|---------|--------------|--------|
| No result | Cartridge not fully seated | Re-insert cartridge |
| Error code | Insufficient sample volume | Repeat with a fresh cartridge |
| Drifting results | Dirty optical window | Clean the optical path |
| Failed QC | QC cartridge expired or mishandled | Use a fresh QC cartridge |
| Curve load error | QR code unreadable / wrong assay | Re-scan; confirm assay selection |
| High background | Sample interference (hemolysis/lipemia) | Re-collect or clarify sample |

## FAQ

**Can the FIA680 run mixed assays?** No — it is single-channel. For mixed simultaneous assays, use the [FIA880](/domain-01-analyzer-technology/fia880-guide/).

**Do I need to build a standard curve manually?** No — curves are pre-loaded via QR code; the operator never manually constructs one.

**What is the difference between FIA680 and FIA880?** FIA680 is single-channel (one test at a time); FIA880 has six channels for parallel runs. See [Analyzer Technology](/domain-01-analyzer-technology/).

*For a side-by-side comparison, see [Analyzer Technology](/domain-01-analyzer-technology/). For structured benchmarks, see the [Data Hub](https://data.migibio.net/analyzer-comparison/).*
