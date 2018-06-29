# miRNA_Diff_Expression_Analysis
Cancer related miRNA Differential Expression Analysis on Data Queried from GDC Data Portal.


This repository contains the code used in the summer of 2018 for a research project at Denison Univeristy. The goal of the project was to find a miRNA that has a large impact on Cancer development. miRNA-seq data was gathered from the GDC Data Portal API. Files pertaining to the acquisition of data can be found in the API folder.

The data was then aggregated, and converted into a proper format for differential expression analysis. Also, normalized (counts per million) expression values were averaged for each miRNA in the cancer types of interest. Files pertaining to differential expression analysis and average expression aggregation can be found in the Analysis folder. 

The resulting data was then created into a excel workbook for exploring and filtering miRNA. Files pertaining to the data acquired and created can be found in the Data folder.
