# DAVID (Database for Annotation, Visualization and Integrated Discovery)

## Overview

DAVID (Database for Annotation, Visualization and Integrated Discovery) is a widely used bioinformatics resource for the functional interpretation of large gene or protein lists.

It integrates multiple biological databases to identify enriched biological functions, molecular pathways, disease associations, and functional classifications.

In this project, DAVID was used to perform functional enrichment analysis of the identified common target genes.

---

# Objectives

The analyses performed using DAVID include:

- Gene Ontology (GO) Biological Process
- Gene Ontology (GO) Molecular Function
- Gene Ontology (GO) Cellular Component
- KEGG Pathway Enrichment
- Disease Association (OMIM)
- Functional Annotation Clustering

---

# Folder Structure

```
DAVID/
│
├── GO Biological Process/
├── GO Molecular Function/
├── GO Cellular Component/
├── KEGG Pathway/
├── Disease Association/
├── Functional Annotation Clustering/
└── README.md
```

---

# Analyses Included

## 1. GO Biological Process (BP)

Identifies significantly enriched biological processes associated with the submitted genes.

**Folder:**

`GO Biological Process`

---

## 2. GO Molecular Function (MF)

Determines the molecular activities performed by proteins encoded by the submitted genes.

**Folder:**

`GO Molecular Function`

---

## 3. GO Cellular Component (CC)

Identifies the cellular locations where the proteins are primarily active.

**Folder:**

`GO Cellular Component`

---

## 4. KEGG Pathway Analysis

Maps the submitted genes to biological pathways from the Kyoto Encyclopedia of Genes and Genomes (KEGG).

**Folder:**

`KEGG Pathway`

---

## 5. Disease Association

Associates the submitted genes with known human diseases using the OMIM database.

**Folder:**

`Disease Association`

---

## 6. Functional Annotation Clustering

Groups similar annotation terms into biologically meaningful clusters and assigns enrichment scores to facilitate interpretation.

**Folder:**

`Functional Annotation Clustering`

---

# Software

- DAVID Functional Annotation Tool
- Database for Annotation, Visualization and Integrated Discovery (DAVID)
- Species: *Homo sapiens*

---

# Output Files

Each analysis folder contains:

- Result screenshots
- Exported CSV files
- Exported Excel files
- Step-by-step workflow
- Explanation of the generated results

---

# References

Huang DW, Sherman BT, Lempicki RA. Systematic and integrative analysis of large gene lists using DAVID Bioinformatics Resources. *Nature Protocols*. 2009;4(1):44–57.

Huang DW, Sherman BT, Lempicki RA. Bioinformatics enrichment tools: paths toward the comprehensive functional analysis of large gene lists. *Nucleic Acids Research*. 2009;37(1):1–13.
