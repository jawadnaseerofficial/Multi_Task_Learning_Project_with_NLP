Multi-task learning (MTL) is a machine learning approach where a model is trained simultaneously on multiple related tasks!
Libraries used:

Pandas, Numpy, Scikit-learn, nltk, tensorflow, seaborn, matplotlib
Following is the architecture of the project:

Architecture
Datasets:

(i) Emotion Data: https://www.kaggle.com/datasets/nelgiriyewithana/emotions
(ii) Violence Data: https://www.kaggle.com/datasets/gauravduttakiit/gender-based-violence-tweet-classification?select=Train.csv
(iii) Hate Speech Data: https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset

Compontents:

(i) Individual Inputs:

Multi-Task model accepts input for each task individually.
(ii) Individual Outputs:

Multi-Task model generates output for each task individually
(iii) Shared Core Layers:

Multi-Task models functionality is that a sinlge model can do multiple related tasks. To exhibit this functionality the core layers of the model like (Embedding, LSTM, pooling, dropout etc) are shared among all the tasks and are not seperately available for them
