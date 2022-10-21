# Fake-job-prediction / Text Analysis / Natural language toolkit(NLTK) Python

**Intrioduction**

Fake jobs defined as employment scam which attempt to defraud people who are seeking vacancies by tricking victim’s good employment with unrealistic hope but the vacancy is none-exist. Previously, jobs advertised was via newspapers, TV or Radio, but in the era of technology more jobs are posted online. 

Due to the rise of job scams, machine learning on prediction of employment scam started getting popular to be studies these days where many people are unemployed or work at home during COVID-19 pandemic. Better features of machine learning of classification algorithms will be study to predict if a job posted is fraudulent or genuine. To further research on the important features of fake jobs such as company profile, description, requirements and other details based on the texts. 

NLTK is one of the Python packages that is powerful to provides natural language algorithms that assist the machine to understand, analysis, pre-process the text data. In addition, it is free and open source and well documented. NLTK comprises of the popular algorithms such as stemming, topic segmentation, part of speech tagging, tokenizing and more. Tokenization is the initial stage of text analytics which will break down a sentence into smaller chunks of words or sentence name token. 

Text analysis of this project was analysed by created wordcloud upon pre-processing of data where later followed by tokenisation with the help of stopwords to remove punctuation and signs. Charts and histograms are later to visualise the analysis and comparison. 

![image](https://user-images.githubusercontent.com/58686831/197243175-5f6f9e54-2f3a-485a-9ece-e7b42dd57f93.png)

![image](https://user-images.githubusercontent.com/58686831/197243046-3835d82c-002e-477d-9112-2ef1051b03d1.png)


**Result**

Table below is the experimental results of this project and it does not shown much difference in the measurement metric of Accuracy and F1-score (F-Measure) among all the classifiers. Most of the models showing similar measurement and it is hard to decide which is the promising machine learning algorithms to predict fake jobs posting. 
![image](https://user-images.githubusercontent.com/58686831/197242842-14745542-d442-40b0-8ee9-d2e712ddaf08.png)

ROC_AUC results of all the classifiers tested for genuine and fake jobs predictions. Random Forest scored highest with performance of 78%. Specialy to highlight that, Random Forest classifiers with n_estimator of 200 also scored the highest for both the measurement metrics in term of Accuracy and F-measurement among all other classifiers. Random Forest classifier shown an excellent and significant performance models. The second highest performed classifier model multi-level perceptron with 73% of ROC_AUC score and 95% of accuracy and F1-score of 97% which is competence to random forest classifier.

![image](https://user-images.githubusercontent.com/58686831/197242747-529125e4-e417-457f-9735-6b6a2936c1a4.png)


**Conclusion**

Genuine and fake jobs posting detection will reduce job scam and bring losses to victims. Job seekers will only lead to the genuine jobs posting and legitimate employer. This project had selected the relevant and best features of text to predict the fake jobs. The features selected are the company profile, descriptions and requirements text column to undergone text analysis and fitted into 5  classifiers models  which is adjusted with appropriate parameters except Gaussian Naïve Bayes with default parameter which is baseline techniques for models performance comparison. Final outcome of this experiment shown that Random Forest classifier furnish the most promising performance in all the 3 measurement metrics applied. Random Forest classifiers with n_estimator of 200 achieved 98% in predicting fake jobs posting.
