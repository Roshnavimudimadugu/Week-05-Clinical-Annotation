# Week 5 — 10-Variant Clinical Annotation

## Purpose

This table documents the annotation of 10 selected variants from the SnpEff-annotated VCF. The information combines molecular annotation with clinical and population database evidence where available.

> Note: Database classifications are reported as annotations/evidence and are not interpreted as patient-specific clinical diagnoses.

| # | Gene | HGVS Variant | Transcript | Molecular Consequence | ClinVar Classification | Review Status | gnomAD Frequency | Disease Association | Evidence Notes | Conflicting Evidence | Interpretation Limitation |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | PABPC3 | c.999delA (p.Phe335fs) | NM_030979.2 | Frameshift | No exact ClinVar record identified | Not applicable | No exact gnomAD record identified | No established disease association identified in the reviewed ClinGen sources | SnpEff: HIGH; LOF annotation 1.00 | No exact ClinVar record identified | Molecular impact alone does not establish clinical pathogenicity |
| 2 | UBXN8 | c.625dupT (p.L208Ffs*11 / p.Ter209fs) | NM_005671.4 | Frameshift / stop-lost | No exact ClinVar record identified | Not applicable | No exact gnomAD record identified | No established ClinGen gene-disease validity association identified | SnpEff: HIGH; LOF annotation 1.00; MANE Select transcript | No exact ClinVar record identified | Predicted loss of function does not by itself establish disease causality |
| 3 | MCPH1 | c.2253C>G (p.Tyr751*) | NM_024596.5 | Stop-gained | No exact ClinVar record found | Not applicable | Variant not found in gnomAD v4.1.1 | Microcephaly 1, primary, autosomal recessive | Stop-gained; MCPH1 has Definitive gene-disease validity and an established loss-of-function mechanism; PVS1 Very Strong considered based on transcript/NMD evidence | No exact ClinVar record identified | Absence from ClinVar/gnomAD does not independently establish pathogenicity |
| 4 | INTS9 | c.1539C>A (p.Tyr513*) | NM_001363038.2 | Stop-gained | No exact ClinVar record identified | Not applicable | No exact gnomAD record identified | No established disease association identified in the reviewed ClinGen sources | SnpEff: HIGH; LOF/NMD annotation 0.80 | No exact ClinVar record identified | Molecular annotation alone is insufficient for clinical classification |
| 5 | DUSP4 | c.795C>A (p.Tyr265*) | NM_001394.7 | Stop-gained | No exact ClinVar record identified | Not applicable | No exact gnomAD record identified | No established ClinGen gene-disease validity association identified | SnpEff: HIGH; stop-gained consequence | No exact ClinVar record identified | Molecular consequence alone does not establish a disease association |
| 6 | PCM1 | c.3515C>A (p.Ser1172*) | NM_001352632.2 | Stop-gained | No exact ClinVar record identified | Not applicable | No exact gnomAD record identified | No established disease association identified in the reviewed ClinGen sources | SnpEff: HIGH; LOF/NMD annotation 0.91 | No exact ClinVar record identified | Clinical significance requires independent clinical/genetic evidence |
| 7 | CNOT7 | c.286C>G (p.Gln96Glu) | NM_001322093.2 | Missense | No exact ClinVar record found | Not applicable | No exact gnomAD record identified | No established ClinGen gene-disease validity association identified | SnpEff: MODERATE; missense consequence | No exact ClinVar record identified | Computational/molecular annotation alone does not establish clinical significance |
| 8 | CLDN23 | c.818A>C (p.Asp273Ala) | NM_194284.3 | Missense | No exact ClinVar record found | Not applicable | No exact gnomAD record identified | No established ClinGen gene-disease validity association identified | SnpEff: MODERATE; missense consequence; NM_194284.3 is MANE Select | No exact ClinVar record identified | Clinical significance requires additional evidence |
| 9 | MCPH1 | c.2226C>T (p.Ser742=) | NM_024596.5 | Synonymous | Benign | 2-star aggregate review | 0.39666 | Microcephaly 1, primary, autosomal recessive | ClinVar Variation ID 158844; 11 submissions contributed; common population allele | No major conflicting classification identified in the reviewed ClinVar record | Database classification is variant-specific and does not automatically apply to other variants |
| 10 | PCM1 | c.3529+54C>T | NM_001352632.2 | Intron variant | No exact ClinVar record found | Not applicable | No exact gnomAD record identified | No established disease association identified in the reviewed ClinGen sources | SnpEff: MODIFIER; intronic variant | No exact ClinVar record identified | Intronic annotation alone does not establish clinical significance |

## Interpretation Notes

- SnpEff impact categories such as HIGH, MODERATE, LOW and MODIFIER describe predicted molecular consequences and should not be treated as clinical classifications.
- ClinVar provides submitted clinical interpretations and their review status.
- gnomAD provides population frequency information.
- Absence of an exact variant from a database should be recorded as "variant not found" rather than automatically treating the allele frequency as 0%.
- Variant interpretation requires evidence from multiple sources and should follow an established classification framework such as ACGS.
- This training exercise is for bioinformatics and variant-interpretation learning and is not a clinical diagnostic assessment.
