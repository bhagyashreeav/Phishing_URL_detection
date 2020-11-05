# Phishing_URL_detection

The demonstration of phishing is turning into an advanced danger to this quickly developing universe of innovation. Today, every nation is focusing on cashless exchanges, business online, tickets that are paperless and so on to update with the growing world. Yet phishing is turning into an impediment to this advancement. The project means to investigate this region by indicating an utilization instance of recognizing phishing sites using ML. The project was carried out in Anaconda IDE and was written in Python. The proposed method used four machine learning classifiers to achieve this and a comparative study of the four algorithms was made. The four algorithms used are K-Nearest neighbor, Kernel Support Vector Machine, Decision Tree and Random Forest Classifier.

The dataset consists of 30 URL features that will be considered for the final classification of the URL as phishing or not. It is a supervised classification problem and has been implemented using four algorithms.

Performance evaluation.
----------------------

Accuracy score cannot always be considered as a good perrformance evaluation metrics. One good reason could be accuracy paradox. 
Recall score is a metric that we can use to select the best model when there is a high cost associated with False Negative. And precision is a that we can use to select the best model when there is a high cost associated with False Positive. F1 Score might be a better measure to use if we need to seek a balance between Precision and Recall. 
And hence the evaluation metric used in here is F1 score and was found to be highest in RFC with a score of 97.129%
