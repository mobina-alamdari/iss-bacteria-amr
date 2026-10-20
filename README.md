# Antimicrobial Resistance Genes in ISS Bacteria

**Investigating antimicrobial resistance (AMR) genes in *Enterobacter bugandensis* strains isolated from the International Space Station (ISS) and comparing them with clinical strains from Earth.**

**Status:** Work in Progress

## Research Question

Do *Enterobacter bugandensis* strains isolated from the International Space Station carry different antimicrobial resistance (AMR) genes compared with clinical strains of the same species isolated on Earth?

## Background

*Enterobacter bugandensis* is an opportunistic bacterial pathogen associated with hospital-acquired infections. Strains of this species have also been identified aboard the International Space Station (ISS), raising questions about bacterial adaptation and antimicrobial resistance in closed space environments.

Comparing ISS-associated strains with clinical isolates from Earth may help reveal differences in their antimicrobial resistance gene profiles and improve our understanding of bacterial adaptation in different environments.

## Objectives

- Collect publicly available genome assemblies of ISS-associated and clinical *E. bugandensis* strains.
- Identify antimicrobial resistance genes using established bioinformatics tools.
- Compare AMR gene profiles between ISS-associated and clinical strains.
- Visualize the results using Python.
- Discuss the findings, limitations, and potential implications.

## Methodology

1. **Genome collection:** Retrieve publicly available genome assemblies and metadata from the NCBI database.
2. **AMR gene identification:** Analyze genomes using tools such as AMRFinderPlus or the Comprehensive Antibiotic Resistance Database (CARD).
3. **Data analysis:** Organize and compare AMR gene profiles using Python and pandas.
4. **Data visualization:** Create plots using matplotlib to explore similarities and differences between the groups.
5. **Interpretation:** Summarize the findings while considering sample size, genome quality, and other limitations.

## Tools and Technologies

- Python
- pandas
- matplotlib
- NCBI genome database
- AMRFinderPlus / CARD

## Data Sources

Genome assemblies and associated metadata will be obtained from the [NCBI Assembly database](https://www.ncbi.nlm.nih.gov/datasets/genome/).

Genome accession numbers and relevant metadata will be documented as the dataset is assembled.

## Project Progress

- [ ] Identify relevant ISS-associated and clinical strains.
- [ ] Download genome assemblies and metadata.
- [ ] Identify AMR genes in each genome.
- [ ] Compare gene profiles between the two groups.
- [ ] Visualize the results.
- [ ] Document findings and limitations.

## Expected Outcome

This project aims to develop a comparative overview of antimicrobial resistance genes in ISS-associated and clinical *E. bugandensis* strains. The analysis may help identify differences in gene profiles and generate hypotheses for further investigation.

The presence of an AMR gene does not necessarily establish phenotypic antibiotic resistance. Results will therefore be interpreted cautiously, and conclusions will be limited by the available genomic data.

## Author

Mobina Alamdari
