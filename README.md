# Sex Differences in *PGLYRP2* Variant rs892145 in Parkinson's Disease


`GP2 ❤️ Open Science 😍`


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15799510.svg)](https://doi.org/10.5281/zenodo.16279897) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

**Last Updated:** June 2025




## Summary
This repository contains all analyses for the manuscript titled ***"Sex-stratified analysis of the potential association between PGLYRP2 rs892145 variant and Parkinson’s disease across diverse ancestral populations"***. 

---

### Data Statement 
* Results were generated using
  - GP2 data release 9 (controlled-tier access; DOI: 10.5281/zenodo.14510099
  - AMP-PD v3.0 (controlled-tier access)


## Repository Orientation
```
analyses/
├── AMPPD
│   └── 00_PGLYRP2_singlegene-analysis_AMPPD
└── GP2
    └── 00_PGLYRP2_singlegene-analysis_GP2.ipynb
```

## Notebooks Description
| **Directory** | **Notebook**                             | **Description**                                             |
|:-------------:|:----------------------------------------:|:-----------------------------------------------------------:|
| AMPPD/        | `00_PGLYRP2_singlegene-analysis_AMPPD.ipynb`                | Analyses of AMP-PD whole-genome sequencing data                |
| GP2/          | `00_PGLYRP2_singlegene-analysis_GP2.ipynb`                  | Analyses of GP2 genotyped imputed data across ancestries               |


## Data Privacy
All individual-level data have been removed, including sample IDs and identifiers. Sensitive paths have been cleared. Notebooks have been saved as `.ipynb` files for easy sharing while ensuring compliance with data privacy standards.

## Software and Tools
|Software/Tool     |Version   |Resource URL                            |RRID             | Notes                                                                                 |
|------------------|----------|----------------------------------------|-----------------|---------------------------------------------------------------------------------------|
|Python	           |3.10      |http://www.python.org/                  |RRID:SCR_008394  |pandas; numpy; forestplot; matplotlib used for general data wrangling/plotting/analysis|
|Jupyter Notebook  |4.3	      |https://jupyter.org                     |RRID:SCR_018315  |used to keep record of the analysis pipeline                                           |
|PLINK	           |1.9	      |https://www.cog-genomics.org/plink/     |RRID:SCR_001757  |used for LD calculations                                                               |
|PLINK	           |2.0       |https://www.cog-genomics.org/plink/2.0/ |RRID:SCR_001757  |used for association analysis                                                          |
|BCFTOOLS          |1.21      |https://github.com/samtools/bcftools    |RRID:SCR_005227  |used for manipulating, analyzing, and calling genetic variants                         |
|ANNOVAR	       |2019Oct24 |https://annovar.openbioinformatics.org/ |RRID:SCR_012821  |used for annotation of genetic variants                                                |
|RVTESTS           |2.1       |https://github.com/zhanxw/rvtests/      |RRID:SCR_007639  |used for burden analysis                                                               |
|R                 |4.4.2     |http://www.r-project.org/               |RRID:SCR_001905	 |used for interaction analyses                                                          |
|Inkscape          |1.4.2     |https://inkscape.app/                   |RRID:SCR_014479  |used for figure composition      
