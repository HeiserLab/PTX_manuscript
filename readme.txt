R code and output for "TNBC response to paclitaxel phenocopies interferon response which reveals cell cycle-associated resistance mechanisms" (Scientific Reports, 2025, https://doi.org/10.1038/s41598-024-82218-9 )

scRNA-seq raw data is available on GEO at: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE266934

Raw images and code related to image processing can be found on Zenodo:
	- Immunofluorescent stained HCC1143 (https://doi.org/10.5281/zenodo.11237850)
	- siRNA knockdown and live-cell quantified data (https://doi.org/10.5281/zenodo.11238552). Raw live-cell images are available upon request.
	- EdU incorporation studies (https://doi.org/10.5281/zenodo.14226249)


Files within this repository:

	- s1_scRNA-seq_processing.rmd : R code for processing scRNA-seq data
	- s2_markov_transition_estimation.rmd : R code for estimating Markov transition rates from live-cell imaging study (data: https://doi.org/10.5281/zenodo.11238552)
	- s3_figure_generation.rmd : R code for downstream analysis and figure generation
	- supplementary_information_1.pdf : contains supplemental figures referenced within the manuscript 
	- supplementary_information_2.xlsx : contains differential gene expression results for all scRNA-seq perturbation 
studies compared to time-matched vehicle control. 
	- supplementary_information_3.xlsx : contains ontology enrichment results for all scRNA-seq experiments. 
	- supplementary_information_4.xlsx : contains differential gene expression results for between ELF3-high and ELF3-low 
samples from the Metabric cohort. 
	- supplementary_information_5.xlsx : contains MsigDB GSEA results for ELF3-high and ELF3-low samples from the 
Metabric cohort. 
	- supplementary_information_6.xlsx : contains z-factor results for each siRNA experiments. 
