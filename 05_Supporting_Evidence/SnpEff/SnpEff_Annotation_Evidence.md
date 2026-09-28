# SnpEff Annotation Evidence

## Purpose

This folder contains supporting evidence from the SnpEff annotation performed during Week 5.

## Source Data

The original SnpEff-annotated VCF was generated during the Galaxy workflow.

The complete annotated VCF is retained locally because its file size is too large for normal GitHub upload.

## Selected Variant Annotations

The SnpEff annotation was used to identify the predicted molecular consequences of the selected variants.

| # | Gene | HGVS Variant | Molecular Consequence | SnpEff Impact |
|---|---|---|---|---|
| 1 | PABPC3 | c.999delA (p.Phe335fs) | Frameshift | HIGH |
| 2 | UBXN8 | c.625dupT (p.L208Ffs*11 / p.Ter209fs) | Frameshift / stop-lost | HIGH |
| 3 | MCPH1 | c.2253C>G (p.Tyr751*) | Stop-gained | HIGH |
| 4 | INTS9 | c.1539C>A (p.Tyr513*) | Stop-gained | HIGH |
| 5 | DUSP4 | c.795C>A (p.Tyr265*) | Stop-gained | HIGH |
| 6 | PCM1 | c.3515C>A (p.Ser1172*) | Stop-gained | HIGH |
| 7 | CNOT7 | c.286C>G (p.Gln96Glu) | Missense | MODERATE |
| 8 | CLDN23 | c.818A>C (p.Asp273Ala) | Missense | MODERATE |
| 9 | MCPH1 | c.2226C>T (p.Ser742=) | Synonymous | LOW |
| 10 | PCM1 | c.3529+54C>T | Intron variant | MODIFIER |

## Role of SnpEff

SnpEff was used to annotate variants with information such as:

- Gene
- Transcript
- HGVS coding notation
- Protein consequence
- Molecular consequence
- Impact category
- Loss-of-function annotations where available

## Interpretation

SnpEff impact categories describe predicted molecular consequences. They should not be treated as clinical classifications.

Clinical interpretation requires additional evidence from resources such as ClinVar, gnomAD, ClinGen and established variant-classification guidelines.

## Raw VCF

The original SnpEff-annotated VCF is retained locally:

`Galaxy35-[SnpEff eff...].vcf`

The VCF was not uploaded to GitHub because its file size exceeded the normal GitHub upload limit.

> This evidence is retained for bioinformatics training and documentation and does not represent patient-specific clinical interpretation.
