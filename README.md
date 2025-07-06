AIM

The aim of this project is to develop a reliable machine learning system that can automatically predict whether a given water sample is suitable for use in concrete construction. By analyzing key chemical properties of water, the goal is to help engineers and construction teams make quick and accurate decisions on water quality, ensuring strong and durable concrete structures without the need for time-consuming manual testing.

RESULT
After training and testing four different classification models — Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine — the results showed that the Support Vector Machine performed the best overall. It gave the highest balance of accuracy, precision, recall, and F1 score on the test data. This means the final model can reliably distinguish between good and bad water samples, making it a helpful tool for real-time water quality monitoring in concrete construction projects.

Model	                      Accuracy     Precision    Recall (Sensitivity)    Specificity	    F1 Score

Logistic Regression	          0.86	        0.76	            0.86	              0.85	        0.81

Decision Tree                 0.74	        0.63	            0.62	              0.81	        0.63

Random Forest	                0.77	        0.69	            0.63	              0.85	        0.66

Support Vector Machine (SVM)	0.86	        0.76	            0.87	              0.85	        0.81

