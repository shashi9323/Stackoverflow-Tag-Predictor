# Stackoverflow-Tag-Predictor
This competition tests your text skills on a large dataset from the Stack Exchange sites.  The task is to predict the tags (a.k.a. keywords, topics, summaries), given only the question text and its title. The dataset contains content from disparate stack exchange sites, containing a mix of both technical and non-technical questions.
All of the data is in 2 files: Train and Test.

Train.csv contains 4 columns: Id,Title,Body,Tags

Id - Unique identifier for each question
Title - The question's title
Body - The body of the question
Tags - The tags associated with the question (all lowercase, should not contain tabs '\t' or ampersands '&')
Test.csv contains the same columns but without the Tags, which you are to predict.

The questions are randomized and contains a mix of verbose text sites as well as sites related to math and programming. The number of questions from each site may vary, and no filtering has been performed on the questions (such as closed questions).

Acknowledgements
We thank Stack Exchange (and its users) for generously releasing the source dataset through its Creative Commons Data Dumps. All data is licensed under the cc-by-sa license.
