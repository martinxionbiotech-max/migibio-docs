---
title: "How Fluorescence Immunochromatography (FICT) Works"
date: 2026-08-13
description: "A plain-language explanation of how fluorescence immunochromatography (FICT) detects and quantifies analytes — the sandwich immunoassay, fluorophore labeling, and instrument readout."
---

# How Fluorescence Immunochromatography (FICT) Works

FICT (Fluorescence Immunochromatographic Technology) is a quantitative lateral-flow immunoassay. This page explains the mechanism in plain language — what happens inside the cartridge between sample application and result.

## The Signal Chain, Step by Step

1. **Capture antibody** is immobilized on a nitrocellulose membrane at the test (T) line.
2. **Detection antibody**, conjugated to a **fluorophore**, is dried on the conjugate pad.
3. **Sample** (serum/plasma/whole blood) is applied; capillary action carries it forward.
4. **Sandwich complex** forms: capture antibody — analyte — fluorophore-labeled detection antibody.
5. **Excitation light** excites the fluorophore at the T line.
6. **Emission** is collected by a photodetector and converted to concentration.

## The Sandwich Immunoassay

```
Capture antibody (T line)  ←  Analyte  →  Detection antibody (fluorophore)
```

The analyte is "sandwiched" between two antibodies. The more analyte present, the more fluorophore-labeled antibody binds at the T line — and the brighter the fluorescence.

## Why Fluorescence → Quantitation

| Property | Consequence |
|----------|-------------|
| Fluorescence intensity ∝ analyte concentration | Enables a numerical result |
| Wide dynamic range (3–4 logs) | Measures low and high values without dilution |
| Instrument readout (not eye) | Removes operator judgment variability |

## From Signal to Number

The analyzer:
1. Excites the T line at a specific wavelength (e.g., 365 nm).
2. Measures emitted light (e.g., 615 nm).
3. Converts intensity to concentration using the **pre-loaded standard curve**.

## FAQ

**What is the difference from a pregnancy-test-style strip?** Those are colloidal-gold and read by eye (line present/absent). FICT is fluorescence read by an instrument, giving a *number*.

**Why does FICT need a dedicated analyzer?** The fluorophore must be excited and its emission measured precisely — only a calibrated fluorometer can do this.

*For the full technical treatment, see the [Research Center white paper](https://research.migibio.net/fict-technology/fluorescence-immunochromatography/).*
