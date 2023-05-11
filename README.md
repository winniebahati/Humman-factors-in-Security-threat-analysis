## Effects of Human Factors in Security Threat Analysis
This repository contains necessary materials used to conduct an experiement on the effect of human factors in security threat analysis.

## General overview
For the execution of this experiment, sevral steps were followed. First, we adopted the case scenario from the ACM ethics Malware Disruption case. This case can be found here https://ethics.acm.org/code-of-ethics/using-the-code/case-malware-disruption/ . The scenario presented to the participants was inspired by the ACM ethics Malware Disruption case. 
Second, we defined the number of dimensions to be considered in the vignette persona. Each fictitious persona or vignette has 2 dimensions: 𝑁ame and 𝑆𝑒𝑛𝑖𝑜𝑟𝑖𝑡𝑦 (i.e., position at a large security consulting firm). The vignette were used to offer possible security mitigation to the threat presented in the case scenario.
Third, all participants reviewed the same security threat scenario, however, the analyst persona assigned to them were randomized.

Please note- the survey questionnaire provided for the purpose of replication contains all vignette personas considered in this study. However, we configured Qualtrics to randomly assign one vignette to each participant joining the survey. That is, each participant received one possible security mitigation/analyst persona.


## The Task
Participants joining the survey were required to read the case scenario and answer a series of questions. First, perception questions of security outcomes and the analyst persona randomly asigned to them. Second, provide demographic information about themselves. Third, control questions used to account for their understandability of the task and materials provided. 

## Available material for replication
To aide in the replication, we have made available the following materials;

A copy of the survey containing all the question and the different vignette personas used. For each vignette we have also provided their proposed security outcomes and additional information such as the justifiation of the security outcome, and an appendix.
Sample participants response file
python notebook


## How to cite us
 To be updated.


## Getting started

To execute the python file:

1. First dowload the "sample participants responses" file. The format of the csv file is the same as the one used during this data analysis.
2. Add the csv file to your Google drive
3. Open the .ipynb file and follow the specified steps.
4. Change the drive directory and the file name of the downloaded csv sheet
5. All relevant python packages have already been pre-defined where necessary



## Repository Structure
This is the root directory of the repository. The directory is structured as follows:

    template-replication-package
     .
     |
     |--- src/                             Source code used in the analysis of data
     |
     |--- data/                            Survey questionnaire and sample participants responses
                  
  

