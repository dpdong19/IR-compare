[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dpdong19/IR-compare/HEAD)

# Data and code to compare the discoverability of Digital Commons and Figshare

## GENERAL INFORMATION
This readme file was generated on 2022-07-04 by Dong Danping

#### Author Contact 
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

Licenses/restrictions placed on the data: CC-BY-4.0 License<br />
Links to publications that cite or use the data: [to be updated]<br />
Links to other publicly accessible locations of the data: <br />
https://github.com/dpdong19/IR-compare
https://doi.org/10.25440/smu.19121768

**Recommended citation for this dataset:** 
Dong, D., & Tay, A. (2022). Data and code to compare the discoverability of Digital Commons and Figshare. https://doi.org/10.25440/smu.19121768


## DATA & FILE OVERVIEW

### File List

**_/analysis/2021-11_DataAnalysis_DCvsFig.ipynb_**<br />
This is the Jupyter Notebook containing notes and scripts of statistical analysis for the case study. 

**_/analysis/DCvsFigshare-downloads-combined-v1.csv_**<br />
This file contains clean data for analysis containing download stats from Apr to Oct 2021 for both InK(Digital Commons) and RDR(Figshare). <br />

**Relationship between files**: The Jupyter Notebook and data file should be placed in the same folder for the code to run. 


### Data Dictionary

**_DCvsFigshare-downloads-combined-v1.csv_**

Number of variables: 15<br />
Number of cases/rows: 92

**Variable List**<br />
**Identifier**: unique ID for each record. Also the URL to access the record. (Note: Figshare records have been unpublished after the study thus no longer accessible)<br />
**IR**: Name of the IR. InK is on Digital Commons and RDR is on Figshare. <br />
**Title**: title of the deposited journal article<br />
**Column D-J**: monthly download count excluding bots downloads from April to October 2021. <br />
**Total**: sum of column D-J, total download count during the study period<br />
**AugToOct**: sum of column H-J from Aug to Oct 2021<br />
**GS_avail**: whether the record can be found in Google Scholar. <br />
**uniq_PDF**: whether the record provides the only PDF in Google Scholar<br />
**primary**: whether the record is displayed as the primary record in Google Scholar. <br />

**Missing data codes**: blank

## METHODOLOGICAL INFORMATION

Methods are described in **_2021-11_DataAnalysis_DCvsFig.ipynb_** and published book chapter [link to be added]

