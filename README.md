# rcsfa-RC3-BSLE_P

Guide for generating stats and figures associated with the data package Barnes M E ; Aronstein P J ; Bailey J D ; Bladon K D ; Forbes B ; Garayburu-Caruso V A ; Grieger S ; Graham E B ; McKever S A ; Myers C R ; Munson K M ; O'Day P A ; Powers-McCormack B ; Renteria L ; Roebuck A ; Scheibe T D ; Young R P ; Myers-Pigg A N (2024): Data and scripts associated with: “Burn severity and vegetation type control phosphorus concentration, molecular composition, and mobilization”. River Corridor and Watershed Biogeochemistry SFA, ESS-DIVE repository. Dataset. <doi:10.15485/2547035> accessed via <https://data.ess-dive.lbl.gov/datasets/doi:10.15485/2547035>

### This guide provides step-by-step instructions to reproduce figures and stats for the manuscript associated with this data package.

*Before getting started, one must download files from an associated data package (Grieger et al., 2022; doi: 10.15485/1894135:*

-   v1_BSLE_Metadata_and_Protocols.zip

-   v3_BSLE_Data.zip (Version number may change with subsequent releases)

Steps:

1.  The manuscript data package data folder will contain the following folders:

-   P-NMR

-   P-XANES

2.  Locate the folder from the data package called "data" in your working directory.

3.  Within the ‘data’ folder, create a new folder called "BSLE_Data_Package_v3". Insert unzipped versions of the two folders downloaded above. Maintain the original folders and folder names.

4.  Run processing code from the data package. *Note that all instances of saving the data frame and figures have been commented out.* If you would like to save these, please remove the #s from those lines of code.

-   For file paths, note the need to use ‘/’ for Windows or ‘’ for Mac users
