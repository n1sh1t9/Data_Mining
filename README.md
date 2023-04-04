# Data_Mining
- The primary aim of the project is to accurately classify and identify the different types of clothes.
- The different types of clothes in our dataset are T-shirts, Trousers, pullovers, Dress, Coat, Sandal, shirts, sneakers, bags, and Ankle Boot.
- The dataset consists of pixel values that range from 0 to 255 with 0 being white and 255 being black.
- We have scaled these pixel values to get them in the range of 0 to 1 for computational efficiency.
- Logistic Regression, Support Vector Machine, and Neural Networks are the three models that we have implemented in order to make accurate predictions of the different types of clothes.

| Model | Regularization | Accuracy |
|-------|----------------|----------|
| LR    | Ridge          | 84.18%   |
| LR    | LASSO          | 84.22%   |
| SVM   | Linear         | 85%      |
| SVM   | Gaussian Radial| 86.86%   |
| SVM   | Polynomial     | 84.62%   |
| NN    | 3 layers       | 85.88%   |
| NN    | 4 layers       | 85.54%   |

- The Support Vector Machine(SVM) with Gaussian Radial function has the best accuracy score of 86.86%.

- Neural Networks show the highest probability functions for each of the predictions as compared to the other models.
