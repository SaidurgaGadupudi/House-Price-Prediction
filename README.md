# House-Price-Prediction
# This project is about HOUSE PRICE PREDICTION .Dataset is downloaded from the link :
https://www.kaggle.com/datasets/heptapod/uci-ml-datasets.
The dataset is preprocessed with following :
1)Importing libraries
2)Filling in the missing values
3)Correlation
4)Scaling (Standardization)
After this the model is trained with following regression methods :
1)Linear Regression
2)Decision Tree
3)Random Forest
4)KNN
5)Lasso & Ridge
6)Polynomial Regression
7)SVM
R2_SCORE VALUES AND RMSE VALUES FROM EACH REGRESSION METHOD :
METHOD                                        RMSE                                         R2_SCORE
LINEAR                                        4.47673949                                 0.64957618
LASSO                                          5.31495278                                 0.61479250
RIDGE                                          5.06946267                                 0.64955507
DECISION TREE                          5.01481139                                 0.65707028
RANDOM FOREST                     2.82769032                                  0.89104369
SVM                                            7.26976684                                  0.27932928
KNN                                             6.36840947                                 0.44695831
POLYNOMIAL                             4.47673949                                 0.72671263
CONCLUSION :
On the basis of the r2_score and rmse values of all the regression method , model will get trained perfectly with best method having high r2_score and least error which is Random Forest in this case , so that the model will predict the outputs more accurate.
