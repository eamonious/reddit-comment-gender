## Predicting Gender in Reddit Comments

In this project, I focused on working with classifier models, including Logistic Regression, Naive Bayes, Random Forest, etc, and natural language processing techniques such as pulling text off the web with APIs, parsing text with tokenizers and regex expressions, vectorizing text into features that can be trained on with classifiers to draw conclusions.  

For the purposes of this project, I used comments pulled from the subreddits r/AskMen and r/AskWomen.  These are moderately large volume subreddits, the purpose of which is to allow redditors to post a question to be answered exclusively by male or female redditors, respectively.  What I realized is that the direct comment replies to the parent thread should be overwhelmingly gender specific, men answering in AskMen and women answering in AskWomen, essentially offering a decent proxy for gender labeling.  Using natural language processing and classification models to classify such comments as belonging to one sub or the other, can we isolate the linguistic factors that discriminate between men answering questions aimed at men, and women answering questions aimed at women?


