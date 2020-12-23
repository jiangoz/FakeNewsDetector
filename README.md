# FakeNewsDetector

### A collaborative project by 3 members: Yi Jiang, Kincent Lan, Richard Li

#### We aim to help address the problem of misinformation by attempting to classify and distinguish fake news from real news, using supervised learning.

We obtained our dataset, which came from a CSV file, from the online website Kaggle. The data came in the form of title, text, date, and subject and contained no other information. As such, we data-wrangled statistics from the qualitative data to be able to detect and generalize characteristics of fake and real news. We also used the TfidVectorizer to obtain further additional information that may aid our classification problem. To visualize the dataset, we used the statistics we pulled out from the articles and made a scatterplot, heatmap, and a histogram. To analyze this dataset, we used the , k-Nearest Neighbor classifier, Multinomial NB: Naive Bayes, and Decision Tree classifier. When it came to hypertuning our algorithms, we used Gridsearch for cross-validation and testing.
