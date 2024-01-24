<div align="center">
  <img height="100" src="https://upload.wikimedia.org/wikipedia/commons/9/95/Twitter_new_X_logo.png"  />
</div>

###

<h1 align="center">SENTIMENT ANALYSIS PEMINDAHAN IBU KOTA NEGARA INDONESIA MENGGUNAKAN METODE RANDOM FOREST</h1>

###

<h3 align="right">hi everyone<br>👋🏼😁</h3>

###

<p align="left">I'm Prastio Rifki Wijaya, from Central Java - Indonesia<br><br>I am a student in the Informatics Engineering study program and the branch of science I study is information processing through computer systems.</p>

###

<br clear="both">

<h1 align="center"></h1>

###

<h3 align="right">🎯about this project :</h3>

###

<p align="left">The random forest method was chosen because the training process with this method is much faster than with decision trees. Apart from that, the Random Forest method has a high level of accuracy compared to the Logistic Regression model in the same case. Apart from knowing the responses to citizens' tweets about moving to the Indonesian capital, sentiment analysis can also find out the comparison of the number of positive, negative and neutral tweets about moving to the Indonesian capital after the enactment of the IKN Law. You can also find out the level of performance produced by the Random Forest method with various scenarios tested in the opinion analysis of moving to the Indonesian capital.</p>

###

<br clear="both">

<h1 align="center"></h1>

###

<h3 align="right">🧭Flow of work on this project :</h3>

###

<p align="left">1) Dataset Collection<br>Dataset collection was carried out using a crawling technique using a program in Python with the help of the Twitter API to obtain keys and tokens used in the process of extracting tweet data. Tweet data is taken using crawling techniques and stored in JSON form, then converted to CSV format.<br><br>2) Dataset Preparation<br>Dataset preparation is carried out after data collection. In this research, it was found that the data that had been withdrawn and collected amounted to 817 tweet data, with the data withdrawal period starting from April 19 2019 to November 23 2023. After that, a cleaning process was carried out, namely cleaning the data from the characters, tweet names, numbers, hashtags, retweets. , link and delete empty data and data that is detected to be the same or duplicate. The result of this stage was that 774 tweet data were obtained which could be used for the next research stage.<br><br>3) Labeling<br>Once the dataset is prepared, the next step involves annotating the dataset. The Google Colab application is used for labeling datasets. A careful filtering process was then applied to the dataset, which contains a total of 814 entries, with the specific aim of reducing the number of entries to only 774. There will be 4 types of labels, namely pro, con, neutral and other. The purpose of other labels is data that cannot be read or defined as pro, con, or neutral.<br><br>4) Data Preprocessing<br>Data preprocessing is carried out by changing random or unstructured text data into structured data, with the aim of making processing easier by the system. There are several stages of data preprocessing carried out in this research, including the following.<br>a. Case Folding and Tokenize<br>b. Stopwords<br>c. Stemming<br><br>5) Feature Extraction<br>The Feature Extraction used by researchers in this research is the TF-IDF method to determine the frequency value of a word in the dataset and the frequency in the dataset. This calculation from TF-IDF is used to determine how relevant a word is in the dataset used. In using the TF-IDF method, researchers used the library provided by Scikit Learn, namely using TfidfVectorizer. In the process, TfidfVectorizer converts a collection of raw documents into a TF-IDF feature matrix.<br><br>6) Dataset Division<br>The dataset will then be divided into two, namely training data and test data. The dataset was divided using a comparison of 90% training data, namely 733 data and 10% test data, namely 82 data.<br><br>7) Creation of Classification Models<br>At this stage the data that has been shared will carry out its respective duties. Training data is used to provide training to the model used, after that the model will be tested using test data. In this study, researchers used the random forest method to create a classification model. In this study, researchers used a library from Scikit Learn, namely RandomForestClassifier. The Random Forest method is used to find the best feature classification among a random subset of features, thereby producing a better model.<br><br>8) Evaluation of Classification Models<br>The final stage of this research is evaluating the classification model. In evaluating the classification model, we will analyze and evaluate the performance of the random forest classification model. At this stage, a confusion matrix is used, the contents of which describe the performance of the classification model that has been used based on the prediction results compared with the correct data presented in the form of a confusion matrix. Evaluation of model performance, namely in terms of accuracy, recall, precision, f1-score and macro avg.</p>

###

<h3 align="right">🛠 Language and tools :</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="40" alt="pandas logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="40" alt="numpy logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=matlab" height="40" alt="matlab logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="github logo"  />
</div>

###

<br clear="both">

<div align="center">
  <a href="https://www.linkedin.com/in/prastio-rifki-wijaya-046166243/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  </a>
  <a href="https://www.youtube.com/@prastiorifkiwijaya23" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="youtube logo"  />
  </a>
  <a href="https://twitter.com/rifki_prastio" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Twitter&logo=twitter&label=&color=1DA1F2&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="twitter logo"  />
  </a>
  <a href="wijayaprastio23@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=102C57&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="gmail logo"  />
  </a>
</div>

###

<h1 align="left"></h1>

###
