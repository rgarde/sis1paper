# sis1paper

Title of Dataset:

Transcriptional regulation of Sis1 promotes fitness but not feedback in the heat shock response   						
---

##Give a brief summary of dataset contents, contextualized in experimental procedures and results.

Fig 1B: Reanalysis of Triandafillou et al. 2020. Described in Methods: RNA-seq Analysis. 
Fig 1E: HS Time Course conducted with or without rapamycin 10 ug/mL (fold change) for 3 biological replicates as described in Methods:Translation Inhibition Assay (Rapamycin Pre-treatment) 
Fig 2B: log2(fold change) in HSE-YFP reporter after Sis1-AA as described in Methods: Anchor-Away Assay.
Fig 2F: HS Time Course Varying Temperature as described in Methods: HSE-YFP reporter heat shock assays.
Fig 2D: Wild Type Noise (log2 fold change in HSE-YFP reporter) as described in Methods: HSE-YFP reporter heat shock assays.
Fig 3EF: Pulse experiments, subjecting cells to challenging heat stress regimes and measuring HSE-YFP reporter (log2 fold change). 4 different cell lines were tested on 4 different days
3 biological replicates of each cell line each time.
Fig 3E) 1 30 min Pulse: First 30 minutes at 39°C followed by the recovery at 30°C for the rest of the 4 hour time course
Fig 3F) 2x Pulse 30_120_30: First 30 minutes at 39°C followed by recovery at 30°C for 120 minutes, then another 30 minutes at 39 C, followed by recovery at 30°C for the rest of the 4 hour time course
Fig S2E) 2 HR Pulse: 2 HR heat shock at 39°C followed recovery at  30°C  for the rest of the 4 hour time course
Fig S2F) 2x Pulse 30_15_30: First 30 minutes at 39°C followed by recovery at 30°C for 15 minutes, then another 30 minutes at 39°C, followed by recovery at 30°C for the rest of the 4 hour time course
Fig 3D: 4 HR HS Time course of Sis1 induction mutant (fold change in HSE-YFP reporter) as described in Methods: HSE-YFP reporter heat shock assays and Flow Cytometry.
Fig 4C: Total total Halo intensity in single cells over heat shock time course as described in Methods: Halo-Tagging and Fig 4A. The image quantification script is included in this repository. 
Values with asterisks were excluded to avoid cluttering the graph. 
Fig 4D: Halo Intensity Ratio (nucleolar ring/total cell) quantified for single cells, using the image quantification script included in this repository. Values with asterisks were excluded to avoid cluttering the graph. 
Fig 4F: M2 values calculated as Hsf1 - Chaperone Colocalization Coefficients (% chaperone colocalized with Hsf1) using the image quantification script included in this repository. Asterisk indicates values were excluded because the chaperone intensity for that cell was 0 or the nuclear membrane went out of the plane of focus.  
Fig 5A: Liquid culture density (OD600) measurements during HS, 2% glucose as described in Methods: Heat Shock Quantitative Growth Assay. Asterisk indicates first reading was excluded from the graph because cells were not well-mixed yet. First 240 minutes at 30°C (blue) before switching to heat shock (orange, 37°C). 
Fig 5B: Liquid culture density (OD600) measurements during HS, as described in Methods: Glucose Starvation Quantitative Growth Assay.				
Fig 5C: Pab1-mKate foci quantified after growth in 2% glucose media or starvation media (2% EtOH glycerol) as described in Methods: Glucose Starvation Quantitative Growth Assay.  	Fig S1: RT PCR of HSE-YFP as described in Methods: RNA quantification and analysis.
Fig S2A: Log2(fold change mscarlet) quantified as described in Methods: HSE-YFP reporter heat shock assays and Flow Cytometry.  	 
Fig S2B,D: Barcharts of target gene expression and Hsf1 activity in the cell lines developed in this study. 1600 Cell Line is the daily control cell line. 1615 cell line is labeled as WT in the published bar graphs.
Fig S2EF : see description of Fig 3EF above.
Fig S3A: Control growth experiment: 2% glucose media (YPD) all details described in Heat Shock Quantitative Growth Assay except that cells were grown at 30°C throughout the assay (i.e. non-stress conditions). 
Fig S3B: Quantitative Growth Assay as described in Methods: Glucose Starvation Quantitative Growth Assay. One biological replicate of 1701 (with asterisks) was excluded because it failed to grow. 

## Description of the data and file structure

Data in this upload are organized based on the figure they appear in, in the publication: Induction of Sis1 promotes fitness but not feedback in the heat shock response
doi: https://doi.org/10.1101/2022.04.27.489698

## Sharing/Access information

##Links to other publicly accessible locations of the data:
N/a

##Other sources:
Raw Data used in the reanalysis in Fig 1B was derived from data from:								
Triandafillou, C. G., Katanski, C. D., Dinner, A. R. and Drummond, D. A. (2020). Transient intracellular acidification regulates the core transcriptional heat shock response. eLife 9,.   						
## Code/Software
The image quantification scripts used to derive the quantification in Figure 4C,D,E,F are .ijm scripts that can be opened, edited and run in the open source software: Fiji (is just ImageJ) v1.54. 
