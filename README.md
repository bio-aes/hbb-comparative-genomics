# Comparative Analysis of the HBB (Beta-Globin) Gene Across Species

## Overview

This project explores the evolutionary conservation of the **HBB (beta-globin) gene** through comparative sequence analysis across four mammalian species: humans, chimpanzees, cattle, and sheep.

Using computational biology tools, DNA and protein sequences were retrieved, analyzed, and aligned to investigate sequence identity, genetic variation, nucleotide composition, and evolutionary conservation.

## Research Question

How conserved is the HBB gene across different species, and what genetic variations can be identified through comparative DNA and protein sequence analysis?

## Species Analyzed

| Species | Scientific Name |
|---|---|
| Human | *Homo sapiens* |
| Chimpanzee | *Pan troglodytes* |
| Cattle | *Bos taurus* |
| Sheep | *Ovis aries* |

## Tools & Technologies

- **Python** — Computational sequence analysis
- **Biopython** — Sequence retrieval, manipulation, and translation
- **NCBI GenBank** — Reference sequence retrieval
- **MAFFT** — Multiple sequence alignment
- **Matplotlib** — Data visualization
- **Google Colab** — Development environment

## Methodology

1. Retrieved HBB reference sequences from NCBI.
2. Extracted coding DNA sequences (CDS).
3. Translated nucleotide sequences into amino acid sequences.
4. Performed multiple sequence alignment using MAFFT.
5. Calculated DNA and protein sequence identity.
6. Investigated conserved and variable alignment positions.
7. Analyzed GC content and codon-position nucleotide composition.
8. Visualized comparative results.

## Key Findings

**DNA Sequence Identity**
- Chimpanzee: 99.77%
- Cattle: 86.99%
- Sheep: 85.16%

**Protein Sequence Identity**
- Chimpanzee: 100.00%
- Cattle: 84.83%
- Sheep: 81.38%

**Protein Conservation**
- Conserved positions: 116
- Variable positions: 29
- Gap-containing positions: 2
- Conservation across comparable positions: 80.00%

The findings demonstrate substantial conservation of the HBB protein, particularly between humans and chimpanzees, while also revealing sequence differences across the analyzed species.

## Repository Contents

| File | Description |
|---|---|
| `HBB_Comparative_Genomics.ipynb` | Main analysis notebook |
| `hbb_sequences.fasta` | Retrieved DNA sequences |
| `hbb_alignment.fasta` | Multiple DNA sequence alignment |
| `hbb_proteins.fasta` | Translated protein sequences |
| `hbb_protein_alignment.fasta` | Multiple protein sequence alignment |

## Data Considerations

The chimpanzee sequence used in this analysis is a predicted RefSeq record (`XM_508242.5`), while the sheep sequence is a provisional RefSeq record (`NM_001097648.1`). These annotation statuses should be considered when interpreting the results.

## Project Focus

This project demonstrates the application of Python-based bioinformatics workflows to comparative genomics, sequence analysis, and the investigation of evolutionary conservation.

---

*An introductory bioinformatics project exploring evolutionary conservation through comparative sequence analysis.*
