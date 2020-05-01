Our topic is about 'Predicting Artists by the Lyrics'. Authorship detection is an essential part of the Natural Language Process, it helps us to identify the authors of texts. In this project, authorship detection was applied to predict the artists of lyrics. We dealt with this problem by implementing different classification machine learning algorithms to different features that were vectorized by TF-IDF and Bag of words.  Among all these models we utilized, the Support Vector Machine (SVM) classifier on TF-IDF gained the best accuracy of 79%, and Naive Bayes achieved the highest accuracy of 61.4% on bag of words.


Description of documents in this repository:
songdata.csv is the data we applied in this project;

util.py contains functions of tokenization and evaluations;

final_project.py includes vecorization and model function, it also call functions from util.py;

ewl_function_words.txt is the output of function words;

To run the code and get the the result, please use 
'python final_project.py --function_words_path ewl_function_words.txt --path songdata.csv'
