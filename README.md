# ML-Course-TweetSentiment

This respository presents Machine Learning (COMP9417) Group Project, created by Jack Duan and Gary Lu, in attempting a Kaggle Competition - Tweet Sentiment Extraction. Review report pdf for detailed analysis. 

Overview is presented as following do points:
- Attempts in trying traditional methods in tacklying NLP.
- Attempts in understanding existing pre-trained models in tacklying NLP.
- Presents the best outcome method (Roberta) observed over 4 weeks of research. 


About this project:
https://www.kaggle.com/c/tweet-sentiment-extraction
We are required to train a model that can extract sentiment component from a tweet.

To Run this project:
ENV:
Before running our code you should know that we train our modle in google colab to make it faster.You might need to install some mouldes,all the moudle we imported are show above,if you run our code in google colab environment, the only moudle you need to install is ¡°transformers¡±,what you need to do is firstly do "pip install transformers"in colab before run the whole code.The version of our tensorfolow is ¡°2.3.0¡± and the version of python is "3.6.9".

If the working environment has only python built-in modules,the following step is what you need to do.
"pip install tokenizers"
"pip install tensorflow==2.3.0"
"pip install transformers"
"pip install  scikit-learn"
PATH:
When you run our code ,you should put all 4 RoBerta moudle files as well as " test.csv " , " train.csv " , " sample_submission.csv " into one folder,and change the parameter of path to that folder.

result:
In the console you should get the k(default is 2) jaccard score ,and the mean of all the jaccard score.As for working folder you will get a file called "submission.csv",which is the final output of the project.

We saved final result and experiment result in google drive
https://drive.google.com/drive/folders/1m7XYQRiXwMQjrT9Vx4tRBi8Q9w-jks9E?usp=sharing



You Should Know:
Even though we use a pre-trained Roberta moudle,it will still take around 1 hour on colab GPU acc,and if you use CPU to run that code ,the time will be much  longer.

