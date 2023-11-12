## PHP2550: Practical Data Analysis - Project2

##  Model to Predict Tracheostomy Placement in Neonates

###  Background

In recent years, the increased survival of infants with severe bronchopulmonary dysplasia (BPD) has led to extended ventilation, making tracheostomy the primary intervention in infants under one year (Akangire & Manimtim, 2023). The timing of tracheostomy placement in neonates with severe BPD remains unclear, with ongoing debates about the criteria for indication and optimal timing, especially considering its impact on growth (Akangire & Manimtim, 2023). Current prediction methods lack detailed respiratory parameters and fail to provide predictions at different postmenstrual ages (PMA). The primary aim of this project is to develop a predictive regression model to guide the indication criteria and timing for its tracheostomy placement among neonates with severe bronchopulmonary dysplasia (sBPD).

## Method

The project utilizes data from the BPD collaborative Registry, a collaboration between interdisciplinary BPD programs in the United States and Sweden. Collected data include respiratory parameters and demographics at 36 and 44 weeks. A generalized linear mixed-effects regression approach, incorporating Lasso and Ridge regression for variable selection, is employed. Lasso-selected variables form the basis of the predictive model, which is trained and evaluated using the same dataset. Model performance is assessed using sensitivity, specificity, and the area under the receiver operating characteristic curve (AUC).

#  

The repository presents a detailed exploration and interpretation of regression models developed for predicting tracheostomy placement among neonates with severe bronchopulmonary dysplasia (sBPD). The primary aim is to guide the indication criteria and timing of tracheostomy placement based on a national dataset that includes demographic, diagnostic, and respiratory parameters of infants admitted to collaborative Neonatal Intensive Care Units (NICUs)
.
