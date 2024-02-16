# FerriMetric---an-AI-Nutrition-Deficiencies-PredictionApplication
Designed with team in Boston University , Sep 2023-Dec2023
1.Co-designed and implemented an AI-based nutritional deficiencies detection tool FerriMetric in order to identify patients’ potential health risks due to unbalanced daily nutrition intake .
2.Integrated with API to crawl and extract the nutritional information of top 5 popular meals from 10 countries using English. Cleaned and prepared data into json format. Applied random forest algorithm on the data to predict patient’s iron bioavailability of iron and blood transferrin saturation. 
3.Presented research to company staff and professors at the Boston University Research Fair.

This is a corporated project and I only post final summary code here, more details here:https://github.com/avantika747/EC601---FerriMetric/tree/main

FerriMetric is a tool at the intersection of Nutrition Science and Artificial Intelligence that provides numeric metrics for the assessment of iron levels in humans.

Keywords: Nutrition Science, Artificial Intelligence, Machine Learning, Random Forest Regression, Bioavailability of Iron, Transferrin Saturation, K-means Clustering, Temporal Dietary Patterns, Feature Engineering

1. Calculating the amount of iron (when ingested through daily diet) that was actually available for absorption by the body.
2. Model-1: Engineering a new feature for the above estimation that takes into consideration the effect of iron absorption enhancers, inhibitors and the type of meal consumed.
3. Model-2: Taking laboratory values such as Iron Serum and UIBC (Unsaturated Iron Binding Capacity) to calculate TIBC (Total Iron Binding Capacity) and eventually Transferrin Saturation, which is the percentage of iron bound to the iron-binding sites of the blood protein, Transferrin.
4. Making use of USDA's Nutritional Information API to extract the nutritional information of various popular meals (in standard units) from different countries: https://api.nal.usda.gov/fdc/v1/foods/search
