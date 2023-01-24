# LibriVox-Audiobook-NER-Views-Prediction
The objectives of this project are:

-To mine data related to top audiobooks from LibriVox released between 2018-2022, with the help of Beautiful Soup and Whisper speech recognition model.
-To perform Named Entity Recognition (NER) on the text extracted using Spacy.
-To train a model for predicting views on English Language audiobooks.
This Project is divided into three parts:

1.Data Mining (ipynb file: 1.Mining) Input - Librivox archive URL Output - librivox_df (csv file attached)

2.Named Entity Recognition (ipynb file: 2.NER) Input - librivox_df (csv file attached) from Part 1. Output - en_books_df (csv file attached)

Other attached:

Excel file of names sorted based on gender - 'Sorted_names.xlsx'

3.Data Preprocessing and Predictive Analysis (ipynb file: 3.Pred) Input - en_books_df (csv file attached) from Part 2. 
Final result - Trained Linear Regression Prediction Model
