![image](https://github.com/user-attachments/assets/30f0f9f1-75d8-4fcd-bec6-5768c3867a1b)Supplementary Information

The manuscript submitted to Scientific Reports Journal, which is entitled "Exploring community-based reporting of livestock abortions for Rift Valley Fever disease surveillance in Uganda: A pilot study"

The authors are:  Abel Wilson Wilson Walekhwa; Andrew JK Conlan; Stella Acaye Atim; Anna Rose Ademun; Emmanuel Hasahya; James L.N. Wood; Lawrence Mugisha
The corresponding author for the submission process is: Mr Abel Wilson Walekhwa, wabelwilson@gmail.com

This study was conducted in Isingiro District, Uganda.  This study involved the set up of a call centre for reporting and follow-up of livestock abortions in bid to detect Rift Valley fever disease.
This code was prepared by Abel Wilson Walekhwa and Andrew JK Conlan and it is aimed at helping you follow the paper methodology and results.

The Objective: To design and pilot a community-based early warning surveillance system for potential RVF outbreaks in Isingiro district, Uganda based on self-reported cases of livestock abortions from farmers.
Key message: 
•	The feasibility of implementing a community-based livestock abortions surveillance programme from farms to the centralized district call centre in Isingiro district, Uganda.
•	Mixed infection of animals having livestock abortions (RVF and brucellosis)

Dataset I: Abortions_all_03102023.xlsx

Description

This is the main dataset which we used for analysis in RStudio using Markdown. This dataset had the following variables; 

Unique ID (This was assigned in transporting the samples from the field). 

rvfelisa_IgM (This is the results for serological analysis for IgM for RVF). 

Meanod_IgM (this means the average output of laboratory OD after running IgM twice). We ran twice as part of quality control and quality assurance in the laboratory. 

rvfelisa_IgG (This is the results for serological analysis for IgG for RVF). 

Meanod_IgG (this means the average output of laboratory OD after running IgG twice). 

Host_rvf (This means the different animal species where samples were picked). 

Brucelliosis (This is the IgG serological results for brucellosis from different hosts). 

Host_brucellosis (this means the animals where the samples were picked from to analyse for brucellosis). 

The parameters of gender, age, education, household_size, subcounty, parish, village were all from the person who was reporting the abortion alerts. Village is the smallest administrative unit followed by parish and subcounty. So, you are tracing the actual location of the animal/farms where abortions were occurring, you could use village. 

Date_alert (This means the actual date when a phone call was made to the call centre). 

Date_investigation (This means the date when the investigation team left the call centre to the farm to follow-up on the reported abortions cases). 

Date_samplecollection (This means the date when sera was picked from the animals from different farms). 

Animalclinical_presentation (This means clinical presentation at farm level as observed by the investigation team). The details of W,X,Y,Z has been detailed under data curation. Stage_pregnancy (This means the gestation period for the animal before the abortion occurred). 

Herd_size (This means the number of animals found at the farm at the time of investigation). Rvf_vaccination_status (This means the status of vaccination for different animals as reported by the farmer/animal owner). 

Environmental_features (This means the environmental conditions that were identified by investigation team at farm level). The details of A, B,C,D has been described under data curation. 

History_animal_movement (This means the possibility of a new animal introduced in the farm or local setting as reported by the farmer). 

Dataset II: uga_admbnda_adm2_ubos_20200824.shp	

Description

This is a shapefile for Uganda. This was obtained from data.world(https://data.world/ocha-rosea/6d6d1495-196b-49d0-86b9-dc9022cde8e7)

Data Curation

1.	Environmental conditions

A	Bushes, Recent rainfall (less than 14 days), Heavy forests, Stagnant water

B	Only 03 present; Bushes, Stagnant water, Heavy forests

C	Only two present; Bushes, Recent rainfall (less than 14 days)

D	Only one present

2.	Clinical presentations

W: Up to 4 and above presentations: Sudden onset of abortion among pregnant animals Weakness /Unsteady gait   Mucopurulent nasal discharge  Profuse fetid diarrhoea   High fever  


X: Up to 3 presentations

Y: Up to 2 presentations

Z: Up to 1 presentation



