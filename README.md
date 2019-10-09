# Lung-Cancer-Trial-Survival-Analysis
This project is about the survival analysis of the lung cancer trial. 

Reliability analyses can be applied to medical clinical trials to determine the effectiveness of a novel treatment. The Veteran’s Administration Lung Cancer Trial dataset was reviewed to 1)
determine variable relationships; 2) compare the reliability of the standard and test chemotherapy treatment; 3) predict survivability of the patients with lifetime distributions, the Cox proportional
hazards model, random survival forest, and Cox multilayer perceptron; and 4) determine individualized treatment recommendations for patients. Weibull distribution was found to best
explain the lifetime distribution the best using goodness of fit measures like AIC, -2Loglikelihood, BIC and Anderson Darling. The novel treatment showed to have higher
reliability than the standardized treatment but was not always recommended due to a patient’s characteristics. It was found that the Karnofsky score and histological cell type were significant
predictive drivers throughout all models. The Cox proportional hazards model had the highest concordance index value (0.763); however, this model is likely invalid for the dataset. The Cox
multilayer perceptron resulted in a c-index of 0.73, while random survival forest had the lowest c-index value.
