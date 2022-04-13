# Practical epigenomics

This repository contains the solutions of the Epigenomics practical. 

Specifically, there are the following folders:

- **peaks_promoter_regions**: it contains bed files with the ATAC-seq peaks overlapping promoter regions for each tissue.
- **peaks_outside_coordinates**: it contains bed files with the ATAC-seq peaks outside gene coordinates for each tissue.
- **distal_regulatory_elements**: it contains bed files with the ATAC-seq peaks overlapping peaks of H3K27ac AND H3K4me1 for each tissue (considered as regulatory elements).
- **regulatory_elements_distance**: it contains tsv files with the closest gene and the distance to the closest gene for each regulatory element and tissue.

It also contains this file: **code_epigenetics_practical.txt** with all the code used to perform all these analyses.

Finally, this python script: **get.distance.py** was used to obtain the closest gene and the distance to the closest gene for each regulatory element.
