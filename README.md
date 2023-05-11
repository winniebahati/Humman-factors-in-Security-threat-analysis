Effects of Human Factors in Security Threat Analysis
This repository contains necessary materials used to conduct an experiement on the effect of human factors in security threat analysis.

General overview
For the execution of this experiment, sevral steps were followed. First, we prepared a questionnaire all textual materials. This included choosing relevant but comparable scenarios. To this end, we presented a kubernetes and a GitHub scenario for the first and confirming experiments. To further make the student's background knowledge comparable , for the subjects relevant to this study (security and the domains of the selected scenarios), we developed training videos. From the scenarios, we compiled 10 threats, each containing a unique thretad ID, threat description, assumption, affected components, and an associated STRIDE threat type. 5 of the threats were real and 5 were fabricated. Additional reading materials, selcted book chapters on STRIDE were also made availabe.

To measure the role of the data flow diagram in validating threats, we proposed comparing it to a process diagram, a sequence diagram. To this end, we defined two treatment group. Intervention received both the DFD and sequence diagram while control group received only a sequence diagram.

## The Task
Participants joining the survey were required to read the ase secnario and answer a series of questions. First, perception questions of security outcomes and the analyst persona randomly asigned to them. Second, provide demographic information about themselves. Third, control questions used to account for their understandability of the task and materials provided. 

## Available material for replication
To aide in the replication, we have made available the following materials;

A copy of the survey containing all the question and the different vignette personas used. For each vignette we have also provided their proposed security outcomes and additional information such as the justifiation of the security outcome, and an appendix.
Sample participants report and exit questionnaire
python notebook


## How to cite us
 To be updated.



## Quick start
Here a documentation on how to use the replication material should be provided.

### Getting started

To execute the python file:

First dowload the "sample participants responses" file. The format of the csv file is the same as the one used during this data analysis.
Add the csv file to your Google drive
Open the .ipynb file and follow the specified steps.
Change the drive directory and the file name of the downloaded csv sheet
All relevant python packages have already been pre-defined where necessary



## Repository Structure
This is the root directory of the repository. The directory is structured as follows:

    template-replication-package
     .
     |
     |--- src/                             Source code used in the analysis of data
     |
     |--- data/                            Survey questionnaire and sample participants responses
                  
  

