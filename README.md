###### House Price Prediction

Following are steps followed:
1. Data Reading
2. Data Preprocessing
3. Data Visualization
4. Training Model

####### Observations
1. Correlation matrix shows us only few features determinantly influence the final price
2. The given data was standardised using standard scaler

###### Models
Grid search CV is implemented for selecting best model and hyperparameter tuning
Following models have been implemneted
1.Linear Regression
2.Lasso
3. Ridge
4. Decision Tree Regressor
5. Random Forest Regressor
6. Gradientboosing Regressor
Out of all above six, RandomForets Regressor gave us the good results with score equals to 77.5%

##### product Matching
1. Sentence Transformers are used to get text embeddings 
2. SentenceTransformers is a Python framework for state-of-the-art sentence, text and image embeddings. 
3. Using cosine formula  similarity is calculated. Other similarity measures include dot product, Euclidean distance
4. similar embeddings are finally placed in a table format.
 ##### MOdel
 1.all-MiniLM-L6-v2
