
# Big Data Analysis for Biomedical Research - Final Project
Final Project for Big Data Analysis 2022  
*Research Project by Sebastian Warma and Arastu Sharma*
## Modelling Dementia & Alzheimer's Inidence based on Age-Related Correlates in the  Blood and CSF
Through the attached datasets we hope to evaluate the following research question: 
**Can we develop a model to predict the incidence of dementia or Alzheimers given a panel of neuroinflammatory biomarkers and Alzheimer’s related protein pathology measurement?**

### Background
Neuroinflammation and related protein aggregation pathways have been implicated in the development of neurodegenerative disorders, namely Alzheimer’s disease and dementia. Increased amyloid beta activity results in compounding plaque aggregation leading to widespread neuronal decay (Leng and Edison, 2020). Along with the process of aging, heightened M1 related inflammatory sensitivity occurs, resulting in higher pro-inflammatory marker expression, ultimately contributing to disease severity and further degradation (Heneka et al, 2015). High levels of pro-inflammatory cytokines may precede the initiation of neurodegeneration for multiple disease states, such as Huntington’s disease and Parkinson’s disease (Morales et al., 2014). Previous prediction models exist for analyzing the severity of an individual’s Alzheimer’s disease state based on EEG and MRI data (Jesus Jr. et al., 2021). Hall et al., 2019 developed a prediction model for dementia and neuropathology based on several biomarkers, however did not specify the correlations and criteria for being in an Alzheimer’s disease state based on neuroinflammation and a more comprehensive protein aggregation panel. Due to the compounding nature of these neurodegenerative and neuroinflammatory pathways, we suspect that analyzing datasets of neuroinflammation and protein aggregation, an assessment of the disease state and correlation of such compounding biomarkers is possible.


### Datasets
| Dataset | Available | Size | Format | Participants | Description |
| - | -- | ------------ | ----- | ------ | -------------- |
| Aging Dementia & TBI Study | Y | 150kB | csv | 108 | 29 blood and CSF markers plus demographic and clinical diagnosis data |
| Harvard Aging Brain Study | N | NA | csv | 290 | A combination of imaging and subjective questionnaire data which complements the objective biomarkers in the above dataset.|


*Currently we have access to clinical data from the Aging Dementia and TBI Study. However, we have requested access from the Harvard Aging Brain Study, and we hope to combine these two data sets.*


#### Files
[ADTstudy_DonorInformation.csv](https://github.com/Sebastian-Warma/Big-Data-Analysis-Final-Project/files/8481882/DonorInformation.csv)  
[ADTstudy_ProteinAndPathologyQuantifications.csv](https://github.com/Sebastian-Warma/Big-Data-Analysis-Final-Project/files/8481884/ProteinAndPathologyQuantifications.csv)

#### References
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5909703/  
https://www.nature.com/articles/s41582-020-00435-y  
https://www.frontiersin.org/articles/10.3389/fncel.2014.00112/full  
https://www.frontiersin.org/articles/10.3389/fnhum.2021.700627/full  
https://alzres.biomedcentral.com/articles/10.1186/s13195-018-0450-3   
