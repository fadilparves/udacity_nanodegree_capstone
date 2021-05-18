# udacity_nanodegree_capstone

# Problem Statement
The excessive changes in the lifestyles of inhabitants across the world through the last decades has moved the human societies from farming foods and active lives into fast foods and inactive lifestyles. The grouping of such lifestyle with growing cigarette consuming has improved the risk factors of cardiovascular diseases (CVDs). Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide.

Heart failure is a common event caused by CVDs. Most cardiovascular diseases can be prevented by addressing behavioral risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity and harmful use of alcohol using population-wide strategies.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

# Evaluation 

For this project, I used recall and precision for evaluation metric as the target output is imbalanced, using accuracy alone will not give us good idea on how well the model performed.
Precision is attempts to find what proportion of positive identifications was actually correct.

𝑃𝑟𝑒𝑐𝑖𝑠𝑖𝑜𝑛 = 𝑇𝑃 ÷ 𝑇𝑃 + 𝐹𝑃

Recall is the attempt to find what proportion of actual positives was identified correctly 

𝑅𝑒𝑐𝑎𝑙𝑙=𝑇𝑃 ÷𝑇𝑃+𝐹𝑁

By using both of this metrics, I manage to choose the best algorithm for this problem and also manage to evaluate the effectiveness of the machine learning model in predicting the classes.

# Result
|Model|Precision|Recall|
|-----|--------|-------|
|Logistic Regression|0.82|0.77|
|KNN|0.43|0.47|
|Decision Tree Classifier|0.66|0.63|
|Random Forest Classifier|0.79|0.71|
|SVC|0.29|0.50|

Hence the final chosen model is Logistic Regression.

# Future Improvement

* More data points for better generelization
* Utilize ANNs for improving the performance provided more data is recorded
