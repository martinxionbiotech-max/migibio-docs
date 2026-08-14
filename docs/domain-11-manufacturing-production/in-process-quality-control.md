---
title: "In-Process Quality Control"
date: 2026-08-14
description: "The production-side quality control gates at Migibio — incoming inspection (IQC), in-process inspection (IPQC), final QC (FQC), outgoing QC (OQC), and environmental monitoring."
---

# In-Process Quality Control

Quality is not tested *into* a product at the end — it is controlled at every stage of production. This page documents the four-layer quality-control system Migibio runs on the production line, plus the environmental controls that keep the process stable.

## The Four QC Gates

| Gate | Stage | What is checked | Action on failure |
|------|-------|-----------------|-------------------|
| **IQC** | Incoming inspection | Raw materials vs. specification | Reject / quarantine lot |
| **IPQC** | In-process inspection | Coating, conjugation, lamination, cutting | Stop line, correct, re-inspect |
| **FQC** | Final QC | Finished product vs. release spec | Quarantine, investigate, rework/reject |
| **OQC** | Outgoing QC | Packaged lot, labeling, documentation | Correct before shipment |

## IQC — Incoming Quality Control

Before any raw material enters production, it is tested against its specification:

- Antibodies — affinity and lot-consistency verification.
- Fluorescent labels — size uniformity and conjugation efficiency.
- Membranes and pads — capillary speed, pore size, background.

A raw-material lot that fails IQC is quarantined and does not reach the production line.

## IPQC — In-Process Quality Control

During production, operators and automated checks monitor each critical step:

| Process step | In-process check |
|--------------|------------------|
| Membrane coating | Line width, dispense volume, fluorescence intensity |
| Drying | Residual moisture |
| Conjugation | Conjugation ratio, unbound-label removal |
| Lamination | Alignment, dimensional inspection |
| Cutting | Strip width tolerance, edge quality |
| Assembly | Seal integrity, desiccant presence, label accuracy |

## FQC — Final Quality Control

Every finished lot is tested against the **release specification** before it can be released:

- Analytical performance (LOD, CV%, linearity) on reference material.
- Appearance and packaging integrity.
- Label and documentation accuracy (IFU, COA).

## OQC — Outgoing Quality Control

Before shipment, OQC confirms the lot is complete and correctly documented:

- Lot number matches the batch record and COA.
- Quantity, packaging, and shipping labels are correct.
- The IFU insert is present in every kit.

## Environmental Monitoring

The production environment is monitored continuously because temperature and humidity directly affect membrane and reagent stability:

| Parameter | Control | Why it matters |
|-----------|---------|----------------|
| Temperature | Controlled range | Reagent and membrane stability |
| Relative humidity | Low, via rotary dehumidification | Prevents hygroscopic degradation |
| Cleanliness | Controlled production area | Reduces contamination risk |

## Why Multi-Layer QC Matters

A single end-of-line test cannot catch every defect. The four-gate system catches problems *where they occur*, which is why Migibio lots maintain tight lot-to-lot consistency (see [Lot-to-Lot Consistency Report](https://research.migibio.net/technical-reports/lot-consistency-report/)).

## FAQ

**What is the difference between FQC and OQC?** FQC verifies the product meets its release specification; OQC verifies the lot is complete, correctly labeled, and documented for shipment.

**What happens to a lot that fails FQC?** It is quarantined and investigated. It is only released after the root cause is corrected and the lot re-tested — or it is rejected.

*For the batch release criteria, see [Batch Release & Traceability](/domain-11-manufacturing-production/batch-release-traceability/).*
