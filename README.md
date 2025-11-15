# Consensus Democracy and Quality of Government: A Critical Re-Assessment

This repository contains replication code and analysis for a critical re-assessment of the relationship between consensus democracy and government quality.

## Repository Structure

### Main Branch (Default)

The `main` branch contains the complete research project with data, analysis code, and outputs.

```
Consensus-Democracy/
├── data/
│   ├── Processed/          # Cleaned and processed datasets
│   └── Raw/                # Original raw data files
├── output/                 # Generated regression tables (6 .tex files)
├── src/
│   └── lijphart_revisit.R  # Main analysis script
├── Consensus-Democracy.Rproj
├── Does_Consensus_Democracy_Improve_the_Quality_of_Government__A_Critical_Re_Assessment.pdf    # Writing
└── codebook_bas_jan24.pdf                                                                      # Dataset codebook
```

### Overleaf Branch

The `overleaf` branch contains only the LaTeX manuscript and generated tables for easy integration with Overleaf.

```
Consensus-Democracy/
├── output/                 # Generated regression tables (6 .tex files) (scaled for LaTeX incorporation)
├── references.bib          # Bibliography file
└── Does Consensus Democracy Improve the Quality of Government: A Critical Re-Assessment.tex    # LaTeX manuscript
```

## Usage

### Running the Analysis

1. Open `Consensus-Democracy.Rproj` in RStudio
2. Run `src/lijphart_revisit.R` to reproduce the analysis
3. Regression tables will be generated in the `output/` folder as `.tex` files

## Branch Management

- **main**: Use for all data analysis and R code development
- **overleaf**: Use for paper writing and LaTeX compilation

## Data

- **Raw data**: Located in `data/Raw/`
- **Processed data**: Located in `data/Processed/`
- **Codebook**: `codebook_bas_jan24.pdf`

## Output Files

The analysis generates 6 regression tables in LaTeX format:
1. `wgi_original.tex` - World Governance Indicators (original specification)
2. `wgi_consensus4.tex` - WGI with Consensus 4 measure
3. `ep_original.tex` - Economic performance (original)
4. `ep_consensus4.tex` - Economic performance with Consensus 4
5. `violence_original.tex` - Control of violence (original)
6. `violence_consensus4.tex` - Control of violence with Consensus 4

## Requirements

- R (version 4.0 or higher recommended)
- Required R packages: `stargazer`, `dplyr`, and others as specified in the analysis script
- LaTeX distribution (for compiling the paper)

## Contact

For questions about this research, please contact [your contact information].
