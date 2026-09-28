
# Week 5 — 10-Variant Clinical Annotation

## Purpose

This table documents the annotation of 10 selected variants from the SnpEff-annotated VCF. The information combines molecular annotation with clinical and population database evidence where available.

> Note: Database classifications are reported as annotations/evidence and are not interpreted as patient-specific clinical diagnoses.

| # | Gene | HGVS Variant | Transcript | Molecular Consequence | ClinVar Classification | Review Status | gnomAD Frequency | Disease Association | Evidence Notes | Conflicting Evidence | Interpretation Limitation |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | PABPC3 | c.999delA (p.Phe335fs) | NM_030979.2 | Frameshift | To be checked | To be checked | To be checked | To be checked | SnpEff: HIGH impact; LOF annotation present | To be checked | Molecular impact prediction does not establish clinical pathogenicity |
| 2 | UBXN8 | c.625dupT (p.Ter209fs / p.L208Ffs*11) | NM_005671.4 | Frameshift / stop-lost | To be checked | To be checked | To be checked | To be checked | SnpEff: HIGH impact; LOF annotation present | To be checked | Molecular impact prediction does not establish clinical pathogenicity |
| 3 | MCPH1 | c.2253C>G (p.Tyr751*) | NM_024596.5 | Stop-gained | No exact ClinVar record found | Not applicable | Variant not found in gnomAD v4.1.1 | Microcephaly 1, primary, autosomal recessive | Stop-gained variant; MCPH1 has an established loss-of-function disease mechanism; population variant not observed in gnomAD | No exact ClinVar record identified | Absence from databases does not independently establish pathogenicity |
| 4 | INTS9 | c.1539C>A (p.Tyr513*) | NM_001363038.2 | Stop-gained | To be checked | To be checked | To be checked | To be checked | SnpEff: HIGH impact; LOF/NMD annotation present | To be checked | Molecular annotation alone is insufficient for clinical classification |
| 5 | DUSP4 | c.795C>A (p.Tyr265*) | NM_001394.7 | Stop-gained | To be checked | To be checked | To be checked | To be checked | SnpEff: HIGH impact | To be checked | Molecular consequence does not by itself establish disease association |
| 6 | PCM1 | c.3515C>A (p.Ser1172*) | NM_001352632.2 | Stop-gained | To be checked | To be checked | To be checked | To be checked | SnpEff: HIGH impact | To be checked | Clinical significance requires independent evidence |
| 7 | CNOT7 | c.286C>G (p.Gln96Glu) | NM_001322093.2 | Missense | No exact ClinVar record found | Not applicable | To be checked | To be checked | SnpEff: MODERATE impact; missense variant | No exact ClinVar record identified | Computational/molecular annotation alone does not establish clinical significance |
| 8 | CLDN23 | c.818A>C (p.Asp273Ala) | NM_194284.3 | Missense | No exact ClinVar record found | Not applicable | To be checked | To be checked | SnpEff: MODERATE impact; missense variant | No exact ClinVar record identified | Clinical significance requires additional evidence |
| 9 | MCPH1 | c.2226C>T (p.Ser742=) | NM_024596.5 | Synonymous | Benign | 2-star aggregate review | 0.39666 | Microcephaly 1, primary, autosomal recessive | ClinVar Variation ID 158844; 11 submissions contributed; common population allele | No major conflicting classification identified in the reviewed ClinVar record | Database classification may not apply to every possible clinical context |
| 10 | PCM1 | c.3529+54C>T | NM_001352632.2 | Intron variant | No exact ClinVar record found | Not applicable | To be checked | To be checked | SnpEff: MODIFIER impact; intronic variant | No exact ClinVar record identified | Intronic annotation alone does not establish clinical significance |

## Interpretation Notes

- SnpEff impact categories such as HIGH, MODERATE, LOW and MODIFIER describe predicted molecular consequences and should not be treated as clinical classifications.
- ClinVar provides submitted clinical interpretations and their review status.
- gnomAD provides population frequency information.
- Absence of an exact variant from a database should be recorded as "variant not found" rather than automatically treating the allele frequency as 0%.
- Variant interpretation requires evidence from multiple sources and should follow an established classification framework such as ACGS.
- This training exercise is for bioinformatics and variant-interpretation learning and is not a clinical diagnostic assessment.
