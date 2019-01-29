# Sarcasm-Detection-using-ML
The goal of this project is to try detecting sarcasm in social media posts. The data used for training and testing is obtained from Kaggle and contains Reddit comments with its parent comments as well as labels.
The label ‘0’ represents non-sarcastic comment and ‘1’ indicates that comment is sarcastic. 
Kaggle link: https://www.kaggle.com/danofer/sarcasm
This project includes the comparative study of detecting sarcasm in text using supervised learning with handcrafted features and using neural networks.
For hand crafted features models, distinctive features are designed and extracted from comments for training. The extracted set of features of comments and along with its labels are fed to classifiers as input to classify the comment as sarcastic or non-sarcastic. 3 different classifiers are tried, Random Forest, Gradient Boost and SVM. For the second approach of developing neural network models, useful features are extracted by the model through its learning process. The tuned and trained model is further used to evaluate the balanced test data
