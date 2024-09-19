# SUPERVISED & UNSUPERVISED LEARNING
## About Books Dataset
![alt text](<Ekran görüntüsü 2024-09-19 212109.png>)

- Let's see null values and fill them
![alt text](<Ekran görüntüsü 2024-09-19 221522.png>)

- Then convert categorical data into numerical form for learning a model
- Price format must be changed also
![alt text](<Ekran görüntüsü 2024-09-19 221559.png>)

- Data Visualization
![alt text](distributionsofbooksbyyear-1.png)
The most number of books is in 2010 and it is decreasing

## SUPERVISED LEARNING ALGORITHMS
### LINEAR REGRESSION
![alt text](<Ekran görüntüsü 2024-09-19 222155.png>)

### LOGISTIC REGRESSION
- Because of Price is a continuous variable, it couldn't used on logistic regression model

### KNN(k-Nearest Neighbors)
![alt text](<Ekran görüntüsü 2024-09-19 222405.png>)

### Decision Trees
![alt text](<Ekran görüntüsü 2024-09-19 222456.png>)

### Random Forest Regressor
![alt text](<Ekran görüntüsü 2024-09-19 222543.png>)

- Linear regression has a lower MSE value and a lower R² Score compared to the other models, so I choose linear regression model to move on.

## Improvement
- I added more features to improve the model
![alt text](<Ekran görüntüsü 2024-09-19 222730.png>)

- In conclusion, the best model is linear regression and I improved it by adding more features. Last MSE is 68.32 and R² Score is 0.04


## UNSUPERVISED LEARNING ALGORITHM
## K-means Clustering
![alt text](<Ekran görüntüsü 2024-09-19 223049.png>)
- This is very complicated

## Improvement
- I used log transformation of price and raised number of clusters
![alt text](<Ekran görüntüsü 2024-09-19 223211.png>)

## Model Evaluation
- To use unsupervised learning model, silhouette score is the best
- Silhouette Scores for each fold: [0.5164488719469142, 0.5404159662452475, 0.5422671970951595, 0.5373777055169642, 0.545220299684004]
Average Silhouette Score: 0.5363460080976579
- The clusters are well separated