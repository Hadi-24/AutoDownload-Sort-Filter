# AutoDownload-Filter-Sort: Genomic Variant Curation Tool

This tool automates the process of downloading, parsing, filtering, and sorting variant data (e.g., from ClinVar) for genomic and bioinformatics research. This helps simplify large-scale variant curation by focusing on key clinical attributes such as pathogenicity and variant type (SNPs, SVs).

## Features

- Automated download of ClinVar VCF/TSV data
- Filtering based on:
  - Clinical significance (Pathogenic, Likely Pathogenic)
  - Variant type (SNPs, SVs)
- Output of cleaned, curated files for downstream analysis
- Easily customizable: supports modular edits and flexible logic for specific research needs

## File Structure
AutoDownload-Filter-Sort/
- data/ # Stores raw and processed files
- scripts/ # Main Python or R scripts
- output/ # Filtered, sorted result files
- README.md # This file
- requirements.txt # Dependencies

