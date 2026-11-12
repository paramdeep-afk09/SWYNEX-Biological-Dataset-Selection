# SWYNEX Biological Dataset Selection

## Complete Genome Sequence of *Bacillus subtilis* Strain 168

### 1. Dataset Overview

For this task, a publicly available biological dataset was selected from the **NCBI Nucleotide database**. The selected dataset is the complete genome sequence of *Bacillus subtilis* subsp. *subtilis* strain 168.

*Bacillus subtilis* is a Gram-positive bacterium that is widely used as a model organism in microbiology, molecular biology, genetics, biotechnology, and microbial genomics.

### 2. Dataset Information

| Parameter | Information |
|---|---|
| Organism | *Bacillus subtilis* subsp. *subtilis* |
| Strain | 168 |
| Dataset type | Complete genome sequence |
| Database | NCBI Nucleotide |
| Accession number | NC_000964.3 |
| Sequence format | FASTA |
| Biological data type | Genomic DNA sequence |
| Source | NCBI Reference Sequence (RefSeq) |

### 3. Dataset Source

The genome sequence was obtained from the **National Center for Biotechnology Information (NCBI)** through its Nucleotide database.

**NCBI accession:** NC_000964.3

The accession identifies the complete genome record of *Bacillus subtilis* subsp. *subtilis* strain 168.

### 4. Biological Context

*Bacillus subtilis* is an important bacterial model organism used for studying bacterial growth, sporulation, gene regulation, metabolism, cellular processes, and host-microbe interactions.

The availability of its complete genome sequence provides a foundation for investigating its genetic composition and genomic organization using bioinformatics approaches.

### 5. Research Question

**How can the complete genome sequence of *Bacillus subtilis* strain 168 be used to investigate its genomic organization and identify genes of potential biological interest?**

### 6. Objective

The objective of this task is to retrieve and document the publicly available complete genome sequence of *Bacillus subtilis* strain 168 from NCBI in FASTA format and describe its potential applications in genomic and bioinformatics research.

### 7. Data Format

The selected sequence is available in **FASTA format**.

FASTA is a commonly used text-based format for representing biological sequences. A FASTA record generally contains a header beginning with the `>` symbol followed by the nucleotide sequence.

Example structure:

>sequence_identifier  
>ATCGATCGATCG...

The complete genome FASTA file included in this repository contains the nucleotide sequence corresponding to the selected *Bacillus subtilis* genome.

### 8. Potential Bioinformatics Applications

The genome sequence can potentially be used for:

- Genome annotation
- Gene identification
- Identification of coding sequences
- Comparative genomic analysis
- Sequence similarity analysis
- Identification of genes involved in metabolism
- Identification of genes associated with bacterial physiology
- Genomic organization studies
- Phylogenetic and evolutionary studies
- Development of computational biology workflows

### 9. Why This Dataset Was Selected

This dataset was selected because it represents a complete bacterial genome from a well-studied model organism and is publicly accessible through NCBI.

The availability of the genome in FASTA format also makes it suitable for subsequent computational analysis using bioinformatics tools and programming libraries such as Biopython.

### 10. Dataset File

The original genome sequence retrieved from NCBI is provided in the `data/` directory:

`Bacillus_subtilis_168_complete_genome_NC_000964.3.fasta`

### 11. Source and Reference

**Database:** National Center for Biotechnology Information (NCBI)

**Accession:** NC_000964.3

**Organism:** *Bacillus subtilis* subsp. *subtilis* strain 168

### 12. Learning Outcome

This task provided practical experience in identifying a publicly available biological dataset, locating a reference genome in the NCBI database, retrieving biological sequence data in FASTA format, and documenting its potential applications in bioinformatics and genomic research.

### 13. Repository Structure

```text
SWYNEX-Biological-Dataset-Selection/
│
├── README.md
│
├── data/
│   └── Bacillus_subtilis_168_complete_genome_NC_000964.3.fasta
│
└── screenshots/
    └── NCBI_Bacillus_subtilis_genome.png
```