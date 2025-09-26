# Lund _et al,_ 2025
This is a repository for the publication "Functional assays for cancer relevance of variants and modifier interactions from patient genomic background using CRISPR-LOH and CRISPR-Select". The scripts used for SCCG variant calling and quantification in Lund _et al.,_ 2025 are freely available and customisable for alternative experimental designs. For technical support contact either jbc53@cam.ac.uk or casper.lund@bric.ku.dk.

# System requirements
The system requirements including required packages and their versions are outlined `sessionInfo_SCCG_quantification.txt` and `sessionInfo_SCCG_variant_calling.txt`. No non-standard herdware is required to run the analyses. The analyses were conducted on a MacBook Air 2022, M2 with 16 GB memory on macOS Ventura 13.0.1.

# Installation guide
For package installation guide please refer to https://cran.r-project.org/ for R packages and https://pypi.org/ and https://github.com/MissionBio/ for Python packages. Installation vary depending on connection specification, but should complete in minutes.

# Instructions
The data to reproduce and demo the analysis pipeline are avaiable in this GitHub. The initial variant calling has been performed using MissionBio's GUI, and the .5 outputs are available in `./data`. To reproduce and demo the analysis, download all the files from this GitHub, keeping the folder architecture. Ensuring all required directories are avialable, run the Python scripts to call the variants at a single cell resolutions, followed by running the R scripts to perform the variant quantification. The computational runtime on the specified setup is to be expected at a few minutes. 

The pipeline is ready out of the box to reproduce the data from Lund _et al.,_ 2025, and can easily be modified to your experimental design by editing the amplicons and variants of interest. Using the Python and R scripts as templates, this is achievable for anyone with moderate coding experience in Python and R. 
