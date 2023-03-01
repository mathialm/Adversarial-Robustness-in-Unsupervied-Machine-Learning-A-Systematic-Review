# Adversarial-Robustness-in-Unsupervied-Machine-Learning-A-Systematic-Review
Repository for accessing all relevant work documents for reproducibility and transparency


## ./SLR
"Initial search" refers to the documents containing the reference information from IEEE, ACM, arXiv and Scopus, saved as .bib files. These was imported into EndNote to automatically remove duplicates, and conduct the first round of filtration

./SLR/"Snowballing X" is snowballing round X, with "bw_snow_initial.txt" and "fw_snow_initial.txt" being .bib files to be imported into EndNote, as in the initial round.

### ./SLR/"Literature Review.xlsx"
The file "Literature Review.xlsx" is the main working document for the SLR, and contains all rounds of filtration except round 1 (which was done in EndNote, resulting list is available in this document in "round 2")

This file also contains the quality assessment for each round, validation round by Jingyue Li on a random selection of papers, and a Kappa analysis to determine if the QA was done properly.

## ./Thematic Analysis
The thematic analysis was conducted using ATLAS.ti (https://atlasti.com/)

For storage purposes, the thematic analysis files are stored in the "Literature_Review.zip.00X" X=[1-6] files in ./"Thematic Analysis". Extract these together to get the proper files.

The file "thematic_analysis.atlproj22" is the ATLAS.ti project file for the analysis, and should contain all codes, documents and such

The file "thematic_analysis.qdpx" is the project file as a QDA-XML standard. Because of limitations between the functionality of ATLAS.ti and the standard, some aspects of the thematic analysis would only be accessible in ATLAS.ti, with the limitations of the export described in "thematic_analysis_cross_platform_problems.txt"

## ./MISC
The file "Defenses_Attacks_effectiveness.pdf" contains the summary of each document containing codes from the groups "Defenses" and "Attack Types". The document contains the summary of the proported effectiveness of a defensive measure against a specific attack.
