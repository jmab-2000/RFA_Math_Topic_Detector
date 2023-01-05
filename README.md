# RFA_Math_Topic_Detector
A Random Forest Algorithm that utilizes bag-of-words that can Identify First Quarter Grade 10 Math topics. The classification are series_and_sequences, polynomials, and polynomial_equation

File Descriptions

│   algebra__polynomial_roots.txt (FILE RETRIEVED FROM MATHEMATICS DATASET)

│   BOW_dataset_v1.csv (BAG-OF-WORDS GENERATED FROM FIRST MODEL)

│   BOW_dataset_v2.csv (BAG-OF-WORDS GENERATED AFTER REMOVING HIGHLY CORRELATED PAIRS)

│   BOW_dataset_v2.xlsx (EXCEL FILE VERSION OF 'BOW_dataset_v2.csv')

│   check_corr.xlsx (CHECKING IF AFTER REMOVING ONE VALUE OF HIGH CORRELATED PAIR IF IT GENERATED NEW CORRELATION TO OTHER COLUMNS)

│   correlation.xlsx (CORRELATION TABLE OF BAG-OF-WORDS V1)

│   dataset-december.csv (encoded dataset from physical books and DepEd Modules)

│   dataset_after_transformation.csv (dataset after processing all math expressions)

│   dataset_html.html (html table of dataset)

│   EDA V2.ipynb (includes top words and high correlated value pair question instances)

│   EDA_v1.ipynb (describing the dataset and creating the correlation table)

│   high_corr_pair.csv (generated high correlation pairs in csv)

│   initial_dataset.csv (combined math dataset and dataset-december.csv)

│   remove_words_v1.csv (compilation of words to remove [the first value of the high correlation pair])

│   RFA_Model v2.ipynb (the final model after removing some columns/words)

│   rfa_model.sav (serialized model of RFA_MODEL v2)

│   rfa_model_v1.sav (serialized model of RFA_MODEL v1)

│   RF_MODEL v1.ipynb (The First generated model)

│   text_processor.ipynb (processor of questions to be classified)

│   vectorizer.sav (serialized CountVectorizer for vectorizing instances of RFA_MODEL v2)

│   vectorizer_v1.sav (serialized CountVectorizer for vectorizing instances of RFA_MODEL v1)

│   word_cloud.ipynb (word cloud generated from the dataset_after_transformation.csv from all instances and by class)
