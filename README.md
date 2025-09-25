# Variant Evidence Table + Prioritizer

**Goal:** Given one or more human variant IDs (rsIDs), build a tidy table that aggregates key evidence for quick interpretation and triage.

- **Inputs:** rsIDs (e.g., `rs429358`, `rs7412`)
- **Outputs:** A CSV table with variant coordinates, gene, consequence, allele frequency, clinical significance, and a simple **priority** flag.

> ⚠️ **Disclaimer:** Research/education only — not for clinical or diagnostic use.

---

## Quick start (Colab)

Open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/harita-bio/variant-evidence-annotation/blob/main/01_variant_evidence_table.ipynb)

1. Run all cells.
2. Enter rsIDs when prompted.
3. View/download the final output table.

---

## Data sources

- **Ensembl Variation REST API** — variant details & clinical significance.
- **Ensembl VEP REST API** — gene symbols, consequence terms, impact levels.
- **MyVariant.info** — gnomAD allele frequency & ClinVar annotations.

---

## Outputs

- **Notebook:** `variant_evidence_table.ipynb`
- **CSV table:** `variant_evidence_table_example.csv`

---

## Tools & Skills

Python (pandas, requests), REST API queries, data integration, variant annotation.

---

## The project and my experience in detail at

🔗 [My portfolio](https://harita-bio.github.io/#/projects/variant-evidence-annotation)
