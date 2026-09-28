# Week 5 — Why Variant Interpretation Is Evidence-Based and Not Guesswork

## Purpose

Variant interpretation is an evidence-based process. A genetic variant should not be classified as pathogenic, likely pathogenic, uncertain significance, likely benign or benign from a single database result, computational prediction or molecular consequence alone.

The ACGS 2024 guidelines describe the use of defined evidence criteria and different levels of evidence for clinical variant classification. The evidence must be considered in relation to the relevant disease and inheritance pattern.

## Why Multiple Sources of Evidence Are Needed

A variant can have a predicted molecular consequence without necessarily being disease-causing. For example, a stop-gained or frameshift variant may have a potentially damaging molecular effect, but its clinical significance depends on additional information such as:

- The disease associated with the gene
- The inheritance pattern
- The known disease mechanism
- The relevant transcript
- Population frequency
- Clinical observations
- Functional evidence
- Segregation or family evidence
- Previous clinical classifications
- Appropriate variant-classification criteria

Therefore, molecular annotation is only one part of the interpretation process.

## Role of Different Databases and Resources

### SnpEff

SnpEff predicts the molecular consequence and annotation impact of a variant.

Examples include:

- HIGH
- MODERATE
- LOW
- MODIFIER
- stop-gained
- frameshift
- missense
- synonymous
- intron variant

These predictions describe the expected molecular consequence and should not be treated as clinical classifications.

### ClinVar

ClinVar collects submitted interpretations of the clinical significance of genetic variants.

ClinVar can provide information such as:

- Clinical classification
- Number of submissions
- Review status
- Associated condition
- Variant identifiers
- Conflicting interpretations

A ClinVar classification should be considered together with its review status and the evidence supporting the interpretation.

### gnomAD

gnomAD provides population variation and allele-frequency information.

Population frequency can help determine whether a variant is compatible with the expected frequency of a disease-causing allele.

However, absence of a variant from gnomAD does not by itself prove that the variant is pathogenic.

### ClinGen

ClinGen provides expert-curated information about gene-disease relationships and the clinical relevance of genes and variants.

Gene-disease validity is important because the significance of a variant depends partly on whether the gene is established as being associated with the relevant disease.

### ACGS

The Association for Clinical Genomic Science provides UK best-practice guidance for clinical genomic variant classification.

The ACGS 2024 guidelines describe how ACMG/AMP evidence criteria should be applied and integrated for clinical variant interpretation.

## Example From This Week's Analysis

The MCPH1 variant:

`NM_024596.5:c.2253C>G (p.Tyr751*)`

was annotated by SnpEff as a stop-gained variant with HIGH impact.

However, the SnpEff result alone was not used to classify the variant.

Additional evidence was considered:

1. MCPH1 has an established gene-disease relationship for primary microcephaly with autosomal recessive inheritance.
2. The established disease mechanism involves loss of function.
3. The variant introduces a premature termination codon.
4. The relevant transcript was considered.
5. Population information was checked using gnomAD.
6. ClinVar was searched for an exact variant-level clinical record.
7. The ACGS/ClinGen approach to loss-of-function evidence was considered.

This demonstrates why variant interpretation requires integration of multiple types of evidence.

## Importance of Evidence Strength

Evidence is not simply counted as "present" or "absent". Different evidence criteria have different strengths.

Examples include:

- PVS1 — Very Strong
- PS — Strong
- PM — Moderate
- PP — Supporting
- Benign evidence categories such as BA1 and BS

The appropriate evidence strength depends on the characteristics of the variant, gene, disease and available supporting information.

For example, PVS1 is intended for predicted loss-of-function variants in genes where loss of function is an established disease mechanism. Additional considerations such as transcript relevance and the likelihood of nonsense-mediated decay are important.

## Conflicting Evidence

Evidence can sometimes support different interpretations.

For example:

- A variant may have a damaging molecular consequence but also occur at a population frequency that is too high for a severe rare disease.
- Different ClinVar submitters may provide different classifications.
- Computational predictions may disagree.
- Functional or clinical evidence may provide information that changes the interpretation.

Conflicting evidence should therefore be documented rather than ignored.

## Why "Rare" Does Not Automatically Mean "Pathogenic"

A rare variant is not automatically a disease-causing variant.

Similarly:

- Not found in gnomAD does not automatically mean pathogenic.
- HIGH impact in SnpEff does not automatically mean pathogenic.
- A VUS is not equivalent to likely pathogenic.
- A computational prediction is not equivalent to experimental evidence.
- A single ClinVar submission should not automatically be treated as definitive evidence.

The evidence must be evaluated in the context of the gene, disease and inheritance pattern.

## Key Principles

1. Variant interpretation is evidence-based.
2. Molecular consequence and clinical significance are different concepts.
3. Multiple independent evidence sources should be considered.
4. Gene-disease validity is important when interpreting a variant.
5. Population frequency provides important supporting information.
6. ClinVar classifications should be considered together with their review status and supporting evidence.
7. Absence from a database should not automatically be interpreted as pathogenicity.
8. Evidence strength must be appropriate to the type of evidence available.
9. Conflicting evidence should be documented and considered.
10. Variant classification should follow an established framework such as ACMG/AMP with relevant ACGS and ClinGen guidance.

## Conclusion

Clinical variant interpretation is not a process of guessing whether a variant looks harmful. It is a structured process in which different sources of evidence are evaluated and integrated according to established guidelines.

The same molecular consequence can have different clinical significance in different genes or diseases. Therefore, reliable interpretation requires consideration of molecular annotation, population data, clinical databases, gene-disease relationships and other relevant evidence together.

> This document summarises concepts learned during Week 5 clinical genomics training and is intended for bioinformatics and educational purposes. It is not a patient-specific clinical interpretation.
