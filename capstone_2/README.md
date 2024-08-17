### Predicting Heart Disease
**Krishna A**

#### <ins>Executive summary</ins>
Heart disease remains the leading cause of death globally, emphasizing the urgent need for effective prediction and prevention strategies. Machine learning (ML) offers a powerful solution by leveraging vast amounts of healthcare data to predict the likelihood of heart disease in individuals with greater accuracy than traditional methods.

This report outlines the implementation of machine learning models to predict heart disease risk. By analyzing patient data, including factors such as age, gender, blood pressure, cholesterol levels, notably including other relevant features, machine learning algorithms can identify patterns and risk factors that may be helpful in earlier detection of the disease.

Below are some of the key benefits of using ML for this purpose:

- <ins>Improved Accuracy</ins>: Machine learning models can process and analyze complex datasets, leading to more accurate predictions and early detection of potential heart disease cases.

- <ins>Cost-Effective</ins>: Early detection through ML can reduce healthcare costs by preventing severe heart disease cases that require expensive treatments and hospitalization.

- <ins>Scalability</ins>: Machine learning models can be easily scaled and integrated into existing healthcare systems, enabling widespread use across various demographics.

#### <ins>Rationale</ins>
Heart problems pose a direct and inevitable threat to human life, making heart disease a significant health concern for humanity.

Heart disease is the leading cause of death worldwide. The American Heart Association reports that cardiovascular disease (CVD) accounted for approximately 18.6 million deaths globally in 2019. In the United States alone, 1 in 4 deaths is due to cardiovascular disease, resulting in a fatality every 37 seconds.

#### <ins>Research Question</ins>
How can machine learning models be used and optimized to accurately predict the risk of heart disease in diverse populations, and what are the key factors that influence the effectiveness and predictability of these models in real-world scenarios? 

#### <ins>Data Sources</ins>
We will explore a dataset from the cleveland database of the UCI Machine Learning Repository. The original database contains 76 attributes and only 14 attributes are intended to be used. The goal of this exercise is to train a machine learning model that predicts the outcome of whether the patient may have a heart disease or not with a great deal of accuracy.
https://archive.ics.uci.edu/dataset/45/heart+disease

#### <ins>Methodology</ins>
The methodology for predicting heart disease using machine learning involves several key steps. First, data preprocessing is performed, which includes handling missing values, normalizing data, and encoding categorical variables. The dataset is then split into training and testing sets. Various machine learning algorithms, such as Logistic Regression, Random Forest, and Support Vector Machines (SVM), are applied to the training data. Model evaluation metrics, including accuracy, precision, recall, and F1-score, are used to assess performance. Finally, hyperparameter tuning is conducted to optimize model accuracy.

#### <ins>Results</ins>
The results of the machine learning models applied to predict heart disease showed varying performance levels. The Random Forest model achieved the highest accuracy, followed by Logistic Regression and Support Vector Machines (SVM). Key evaluation metrics like precision, recall, and F1-score indicated that the Random Forest model provided a balanced performance in predicting heart disease cases while minimizing false positives and negatives. Overall, the study demonstrates that machine learning can effectively predict heart disease, with Random Forest emerging as the most reliable model.

#### <ins>Next steps</ins>
The next steps in the project involve improving model performance through advanced techniques like feature engineering, cross-validation, and ensemble methods. Additionally, expanding the dataset and incorporating more diverse data sources could enhance the model's generalizability. The plan also includes deploying the best-performing model into a real-world application and continuously monitoring its effectiveness in predicting heart disease. The models trained in the above exercise contained less data, so it would be useful to collect more samples of data for increasing model effectiveness and precision. 

#### <ins>Outline of project</ins>

- [Dataset](https://github.com/kattravanam/berkeley-ml-ai/blob/main/capstone_2/data/Heart_disease_cleveland_new.csv) 
- [Notebook](https://github.com/kattravanam/berkeley-ml-ai/blob/main/capstone_2/prompt.ipynb)


