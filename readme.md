--Project Tasks--

1. Imported:-
            NUMPY for numeric computations,
            Pandas for creating and managing dataframes, 
            NLTK (Natural Language Toolkit) for implementing NLP concepts, and 
            SEABORN for visualization


2. Created dataframe from CSV file with over 500k records of Amazon reviews.

3. Data cleaning:-
            Removed unnecessary columns:
                      Time, 
                      HelpfulnessNumerator, and 
                      HelpfulnessDenominator

4. Data preprocessing:-
            Grouped and ordered both old and newly created columns  
            Made inferences from data using Pivot table and Heatmap

5. Data Modelling:-
            Vectorized review text using Count Vectorizer,
            Fit the data in Logistic Regression model, and
            Displayed the most common positive and negative words

6. Created functions to compute and display results:-
            Vectorized and fit data with Logistic Regression model, then displayed model accuracy and top words from reviews, 
            Vectorized and fit data with Logistic Regression model, predicted values on test data and displayed model accuracy and confusion matrix for the predictions

7. Imbalanced data:-
            Checked for imbalaned data from the count of resultant values
            Confirmed presence of imbalanced data using Dummy Classifier
            Balanced the data by oversampling with RandomOverSampler

8. Data Modelling II
            Removed the reviews with score 3 (neither positive nor negative)
            Vectorized data using TF-IDF Vectorizer and balanced the data using RandomOverSampler
            Modelled the data using Logisctic Regression and displayed the performance with Accuracy and Confusion Matrix


<details>
  <summary></summary>
  
  ## --To do last--
  1. Create Wordclouds for top positive and negative words in reviews
  2. Add stemming and lemmatization along with stop words
  3. Change color scheme of Confusion Matrix Plot
  4. Add filter to remove numeric values from data
  5. Improve on calculation of accuracy from Confusion matrix (Average the normalized values of accurate responses maybe??)
</details>



   