## PHP2550: Practical Data Analysis -Project2
###  Predictive model for Tracheostomy Placement in Neonates with severe bronchopulmonary dysplasia
The repository presents a detailed exploration of regression model developed for predicting tracheostomy placement among neonates with severe bronchopulmonary dysplasia (sBPD). The primary aim is to guide the indication criteria and timing of tracheostomy placement based on a national dataset that includes demographic, diagnostic, and respiratory parameters of infants admitted to collaborative Neonatal Intensive Care Units (NICUs)

###  Background
In recent years, the increased survival of infants with severe bronchopulmonary dysplasia (BPD) has led to extended ventilation, making tracheostomy the primary intervention in infants under one year (Akangire & Manimtim, 2023). The timing of tracheostomy placement in neonates with severe BPD remains unclear, with ongoing debates about the criteria for indication and optimal timing, especially considering its impact on growth (Akangire & Manimtim, 2023). Current prediction methods lack detailed respiratory parameters and fail to provide predictions at different postmenstrual ages (PMA). This project aims to develop a predictive regression model to guide indication criteria and timing for  tracheostomy placement among neonates with severe bronchopulmonary dsyphlasia.

###  Method
The project utilizes data from the BPD Collaborative Registry, a collaboration between interdisciplinary BPD programs in the United States and Sweden. Collected data include respiratory parameters and demographics at 36 and 44 weeks. A generalized linear mixed-effects regression approach, incorporating Lasso and Ridge regression for variable selection, is employed. Lasso-selected variables form the basis of the predictive model, which is trained and evaluated using the same dataset. Model performance is assessed using sensitivity, specificity, and the area under the receiver operating characteristic curve (AUC).

### Results
The predictive model is developed using 995 observations. The model is developed on train set and evaluated on the test set. On the test data, the model achieves an AUC of 0.9437, demonstrating a sensitivity of 0.54 and specificity of 0.9795. The overall accuracy on the test set is 0.9162. Both predictive models developed at 36 weeks and 44 weeks did not show any much differences in their performance. However each model was fitted with different set of predictors, with very minimal overlap. 

###  Conclusion
This predictive model for tracheostomy timing in infants with severe BPD showcases its capacity to distinguish cases and accurately identify infants in need of tracheostomy. The overall accuracy underscores the model's reliability for informing clinical decisions although there is room for further improving the model.


.
