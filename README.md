## Code base for multivariate analysis (ordination) of INCLINE community data from control plots

This repository is the code base for a manuscript in preparation. It will contain R scripts for data cleaning, analysis, and visualisation. This reposirory is linked to the development of the [HMSC_INCLINE](https://github.com/evalieungh/hmsc_incline) repository in that both HMSC and ordination was used in the same manuscript but the multivariate analyses have been split out and will be moved here.

## NB! this is a work in progress. The scripts are not 100% clean and finished, and results may not be reproducible. 

This readme file was generated on 2024-10-01 by Eva Lieungh

Contact:
Eva Lieungh,
https://orcid.org/0000-0003-4009-944X,
Natural History Museum, University of Oslo,
eva.lieungh[at]nhm.uio.no /
evaleriksen[at]gmail.com

## Related resources:

- Eva Lieungh, & Rune Halvorsen. (2023). DCA and GNMDS output for 4640 subplots and 95 vascular plant species in four alpine grasslands (1.0) [Data set]. Zenodo. <https://doi.org/10.5281/zenodo.8064319>
- INCLINE data repository will be published on OSF along with a data paper by Gya et al. (in prep): https://osf.io/zhk3m/ 

### Contents

This is the folder structure in my local copy of the directory. Most of these folders are listed in `.gitignore` and will not be uploaded to GitHub. See Related resources list above for the necessary data.

| Folder or file name | Description |
| ------------------- | ----------- |
| archive/ | files made redundant, old versions | 
| data/ | raw and input data |
| data_processed/ | modified data, intermediate files |
| writing | manuscript drafts and backups, other texts |
| results | output files, models, figures etc. |
| resources | external resources not to be uploaded (add to .gitignore) |
| src   | scripts/code/notebooks  |
| .gitignore | file specifying folders and files Git should not track or upload |
| README.md | this file, read as the front page of GitHub repository |

### Funding sources that supported this project

PhD project funded by the Norwegian Ministry of Education and Research, through the Natural History Museum, University of Oslo. Vascular plant community data were collected for the INCLINE project, Research Council of Norway FRIMEDBIO project 274712. PI: Vandvik, Töpper. 2018–2021. 

### Sharing and access

See license. Copy snippets freely, but please refer to this repository if you use large parts of several scripts (that is, if you are doing most of the same analyses and your starting point is a copy of these scripts). See for instance the [ICMJE authorship guidelines (Vancouver convention)](https://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html) to help you decide which kind of acknowledgement is appropriate. 

### Help and useful tricks

Questions? Contact me, or post an issue in this repository. 

A neat trick to find the answer to questions like "what script creates and saves the important_data.Rds file?" is to open a terminal in the ´/src´ folder and enter this command to search (grep) inside all files (-e) inside that folder and subfolders (-r): ´grep -r -e "important_data.Rds"´
