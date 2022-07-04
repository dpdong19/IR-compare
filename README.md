This readme file was generated on 2022-07-04 by Dong Danping


## GENERAL INFORMATION
Title of Dataset: Data and code for a case study comparing the discoverability of Digital Commons and Figshare


### Author Contact Information
Name: Dong Danping
ORCID: 0000-0002-2229-6709
Institution: Singapore Management University
Email: danpingzzz@gmail.com

Name: Aaron Tay
ORCID: 0000-0003-0159-013X
Institution: Singapore Management University
Email: aarontay@smu.edu.sg


Date of data collection: 2021-04-01 to 2021-10-01


## SHARING/ACCESS INFORMATION

Licenses/restrictions placed on the data: CC-BY-4.0 License
Links to publications that cite or use the data: [to be updated]

Links to other publicly accessible locations of the data: 
https://github.com/dpdong19/IR-compare
https://doi.org/10.25440/smu.19121768

**Recommended citation for this dataset:** 
Dong, D., & Tay, A. (2022). Data and code for a case study comparing the discoverability of Digital Commons and Figshare. https://doi.org/10.25440/smu.19121768


## DATA & FILE OVERVIEW

**File List**

_/analysis/2021-11_DataAnalysis_DCvsFig.ipynb_
This is the Jupyter Notebook containing notes and scripts of statistical analysis for the case study. 

_/analysis/DCvsFigshare-downloads-combined-v1.csv_

This file contains clean data for analysis containing download stats from Apr to Oct 2021 for both InK(Digital Commons) and RDR(Figshare). 

Relationship between files: The Jupyter Notebook and data file should be placed in the same folder for the code to run. 


**Data Dictionary**

_DCvsFigshare-downloads-combined-v1.csv
_

Number of variables: 15
Number of cases/rows: 92

Variable List: 
Identifier: unique ID for each record. Also the URL to access the record. (Note: Figshare records have been unpublished after the study thus no longer accessible)
IR: Name of the IR. InK is on Digital Commons and RDR is on Figshare. 
Title: title of the deposited journal article
Column D-J: monthly download count excluding bots downloads from April to October 2021. 
Total: sum of column D-J, total download count during the study period
AugToOct: sum of column H-J from Aug to Oct 2021
GS_avail: whether the record can be found in Google Scholar. 
uniq_PDF: whether the record provides the only PDF in Google Scholar
primary: whether the record is displayed as the primary record in Google Scholar. 

Missing data codes: blank

## METHODOLOGICAL INFORMATION

Methods are described in 2021-11_DataAnalysis_DCvsFig.ipynb and published book chapter [link to be added]

