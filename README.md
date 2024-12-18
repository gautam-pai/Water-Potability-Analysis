# Water Potability Analysis
 The dataset includes several key attributes that are important for assessing water quality and safety. These attributes are pH, hardness, total dissolved solids (TDS), chlorine, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity. The most critical attribute featured in the dataset is potability, which is essential for determining whether the water is safe for consumption.bidity and finally the data to classify is portability



Hyper Tuning Parameter-
DecisionTreeClassifier
Best Parameters =  {'splitter': 'best', 'max_depth': 15, 'criterion': 'entropy'}
Best Estimator =  DecisionTreeClassifier(criterion='entropy', max_depth=15)
Best Score =  0.9975571428571429

---------------------------
RandomForestClassifier
Best Parameters =  {'max_features': 'sqrt', 'max_depth': 15, 'criterion': 'log_loss'}
Best Estimator =  RandomForestClassifier(criterion='log_loss', max_depth=15)
Best Score =  0.9975428571428571

---------------------------
GradientBoostingClassifier
Best Parameters =  {'n_estimators': 50, 'loss': 'exponential', 'learning_rate': 0.5, 'criterion': 'friedman_mse'}
Best Estimator =  GradientBoostingClassifier(learning_rate=0.5, loss='exponential',
                           n_estimators=50)
Best Score =  0.997457142857143

---------------------------
AdaBoostClassifier
Best Parameters =  {'n_estimators': 50, 'learning_rate': 0.5}
Best Estimator =  AdaBoostClassifier(learning_rate=0.5)
Best Score =  0.9975571428571428
