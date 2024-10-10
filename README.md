

This README.md file was created by César Bertinetti on 2024-Oct-10 and is associated with the Bertinetti, César et al. 2024. Data from:Robust sensory traits across light habitats: Visual signals but not receptors vary in centrarchids inhabiting distinct photic environments

The repository contains the datasets and the R Markdown script with step-by-step comments on the different analyses used to generate the results associated with the study: XXXX
 

GENERAL INFORMATION

1. Title of Dataset: Robust sensory traits across light habitats: Visual signals but not receptors vary in centrarchids inhabiting distinct photic environments


2. Author Information
	A. First Author
		Name: César Bertinetti
		Institution: University of Notre Dame, Dpt. Biology
		Address: 299 Galvin Life Science Center, Notre Dame, IN, 46556, US
		Email: cbertine@nd.edu

	B. Correspond Author 
		Name: Julián Torres-Dowdall
		Institution: University of Notre Dame, Dpt. Biology
		Address: 216 Galvin Life Science Center, Notre Dame, IN, 46556, US
		Email: torresdowdall@nd.edu

3. Date of data collection: Summer 2022

4. Geographic location of data collection: 

Fish were collected using fyke nets or rod and reel angling from two temperate lakes located in northern Wisconsin, USA between June and August 2022 (Table S1). The two lakes are about 45 km and not connected by any water drainage. A total of 66 specimens from six species of Centrarchidae were collected from either a clear water lake, Big Arbor Vitae (BAV; 45.924001, -89.639012), or a dark water lake, Cranberry Lake (CY; 45.887512, - 89.169695). The following species were collected from each site: black crappie, Pomoxis nigromaculatus (BAV, n = 4; CY, n = 3); rock bass, Ambloplites rupestris (BAV, n = 7; CY, n = 7); bluegill sunfish, Lepomis macrochirus (BAV, n = 9; CY, n = 9), pumpkinseed, Lepomis gibbosus (BAV, n = 10; CY, n = 7); largemouth bass, Micropterus nigricans (BAV, n = 5; CY, n = 3), and smallmouth bass, Micropterus dolomieu (BAV, n = 1; CY, n = 1). 


5. Information about funding sources that supported the collection of the data: This work was mainly supported by start-up funding allocated to J.T.D by University of Notre Dame.


SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: CC0
2. Recommended citation for this dataset:



DATA & FILE OVERVIEW

1. File List: 

- Lightdata.zip; contains all irradiance measurements for each location. Absolute irradiance (mW/cm²/nm) and normalized irradiance for all depths in each site. "Photic factors.csv" contains the summary photic parameters generated from the raw data.

- Protein sequences.zip; contains the protein sequences alignments for opsin gene in paml format and the phylogenetic tree used to test signatures of molecular evolution using EasyCodeML.

- Morphology.csv; contains metadata and morphological data associated with each individual. See also supplemental tables, Table S1

- Read_Counts_Table.csv; contains read counts for each gene (rows) and individual (column). See also NCBI SRA database under accession number PRJNA1168051

- Visual_Genes.csv; contains the normalized TMMS counts for visual opsin genes and cyp17c1. It also includes the proportional expression of each gene and the predicted sensitivity index (PSI)

The "Script.Rmd" contains the code to replicate the analysis in R Software.

The analysis was performed running R version 4.4.1 (2024-06-14) on macOS aarch64-apple-darwin20. The following packages were used:

  BiocManager       gplots        edgeR       Glimma        limma        vegan
   "1.30.25'    '3.1.3.1'      '4.2.1'     '2.14.0'     '3.60.4'      '2.6-8' 
  lattice      permute       partR2    ggfortify    agricolae       pander 
  '0.22-6'      '0.9-7'      '0.9.2'     '0.4.17'      '1.3-7'      '0.6.5' 
  lme4           Matrix          rsq       pracma         gridExtra    ggplot2 
  '1.1-35.5'      '1.7-0'        '2.6'      '2.4.4'        '2.3'      '3.5.1' 
   car        carData         zoo         MESS    RColorBrewer    plotrix 
 '3.1-3'      '3.0-5'     '1.8-12'     '0.5.12'      '1.1-3'      '3.8-4' 
  tidyr        dplyr     matrixStats      stringr        readr 
  '1.3.1'      '1.1.4'      '1.4.1'      '1.5.1'      '2.1.5'



The "Script.html" file provides a more reader-friendly version of the code which allows to preview of the output of single steps. This is also available at https://cesarbertinetti.weebly.com/sharing.html.


