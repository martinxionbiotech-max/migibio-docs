---
title: "Analyzer Technology"
date: 2026-08-14
description: "Technical specifications, fluorescence detection principle, operation, calibration, and maintenance of the Migibio FIA680 and FIA880 immunofluorescence quantitative analyzers."
---

# Analyzer Technology

The FIA680 and FIA880 are dedicated fluorescence immunoassay analyzers that read Migibio FICT test cartridges and convert fluorescence signal into quantitative concentration results.

## How Fluorescence Detection Works

FICT (Fluorescence Immunochromatographic Technology) is instrument-read, not visually read:

```
LED excitation → fluorophore emission → photodetector → fluorescence intensity
→ standard curve → concentration
```

1. **Excitation** — an LED excites the fluorophore bound to the detection antibody at the test line.
2. **Emission** — the fluorophore emits light at a longer wavelength (Stokes shift).
3. **Detection** — a photodiode (or PMT) measures the emitted light intensity.
4. **Quantification** — intensity maps to analyte concentration via the pre-loaded standard curve.

This is fundamentally different from colloidal-gold (visual) strips: **fluorescence intensity is measured quantitatively**, giving concentration values rather than a "line present / absent" judgment.

## Analyzer Comparison

| Parameter | FIA680 | FIA880 |
|-----------|--------|--------|
| Channels | Single | Six |
| Throughput | 1 test/run | Up to 6 tests/run |
| Sample types | Serum, plasma, whole blood | Serum, plasma, whole blood |
| Excitation | LED | LED |
| Detection | Photodiode | Photodiode / PMT |
| Calibration | QR code standard curve | Cloud standard-curve sync |
| Best for | Low-volume clinics | High-volume clinics |

## Operation Overview

1. **Apply sample** to the test cartridge.
2. **Insert cartridge** into the analyzer.
3. **Read result** — concentration + qualitative flag in 3–15 min.

## Calibration & Maintenance

| Item | Frequency |
|------|-----------|
| QC cartridge verification | Daily (or per IFU) |
| Standard-curve update | Via QR code / cloud sync |
| Optical path cleaning | Weekly |
| Full calibration | Per service schedule |

## FAQ

**Do I need to build a standard curve manually?** No — curves are pre-loaded via QR code or cloud sync.

**Can I run different assays simultaneously?** On FIA880 yes (six channels, mixed assays); FIA680 is single-channel.

**What samples are accepted?** Serum, plasma, and whole blood (assay-dependent).

**Why is fluorescence better than visual (colloidal gold) reading?** Fluorescence gives quantitative concentrations (pg/ml sensitivity, CV% < 10%), while visual strips are qualitative and operator-dependent. See [Quantitative vs Qualitative](/domain-02-detection-principles/quantitative-vs-qualitative/).

*For assay performance data, see the [Data Hub](https://data.migibio.net/analyzer-comparison/).*
