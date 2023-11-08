# EX-9-Simulating-Classification-using-WEKA-Tool
DATE : 28/09/23
# AIM :
To perform a classification technique using WEKA tool.

# WEKA :
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements. WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram −

![image](https://github.com/Kamali22004796/EX-9-Simulating-Classification-using-WEKA-Tool/assets/120567837/0e1ddd65-8928-4a68-8592-03db8cc75af7)


# CLASSIFICATION :
Classification in data mining is a common technique that separates data points into different classes. It allows you to organize data sets of all sorts, including complex and large datasets as well as small and simple ones. It primarily involves using algorithms that you can easily modify to improve the data quality. This is a big reason why supervised learning is particularly common with classification in techniques in data mining. The Classification algorithm is a Supervised Learning technique that is used to identify the category of new observations on the basis of training data. In Classification, a program learns from the given dataset or observations and then classifies new observation into a number of classes or groups. Such as, Yes or No, 0 or 1, Spam or Not Spam, cat or dog, etc. Classes can be called as targets/labels or categories.
# PROCEDURE :
1.Load the data file into the WEKA explorer. The data can be loaded from the following sources − Local file system Web Database

2.Click on the "Open file" button. A directory navigator window opens as shown in the following screen −

![image](https://github.com/Kamali22004796/EX-9-Simulating-Classification-using-WEKA-Tool/assets/120567837/27c5f20c-97a1-40b4-91cf-9690b24eef93)


3.Click on the Classify tab, and you would see the following screen

![image](https://github.com/Kamali22004796/EX-9-Simulating-Classification-using-WEKA-Tool/assets/120567837/bc80d78a-25f3-468d-92bd-d3ad3a43d557)


4.Now, keep the default play option for the output class −

![image](https://github.com/Kamali22004796/EX-9-Simulating-Classification-using-WEKA-Tool/assets/120567837/0aaaf228-c8a3-4b28-ab2c-c01ec1e73f05)


5.Click on the Choose button and select the following classifier − weka→classifiers>trees>J48.

![image](https://github.com/Kamali22004796/EX-9-Simulating-Classification-using-WEKA-Tool/assets/120567837/e551748c-b1fb-4e5c-a2ff-af3257e9a4bb)


6.Click on the Start button to start the classification process. After a while, the classification results would be presented on your screen as shown here −

![image](https://github.com/Kamali22004796/EX-9-Simulating-Classification-using-WEKA-Tool/assets/120567837/5fc67070-df5d-4e64-b61c-20184410b39f)


7.To see the visual representation of the results, right click on the result in the Result list box. Several options would pop up on the screen as shown here −

![image](https://github.com/Kamali22004796/EX-9-Simulating-Classification-using-WEKA-Tool/assets/120567837/0c85b92f-c528-4533-bd19-1028c238635f)


8.Select Visualize tree to get a visual representation of the traversal tree as seen in the screenshot below −

![image](https://github.com/Kamali22004796/EX-9-Simulating-Classification-using-WEKA-Tool/assets/120567837/429bca60-9ede-417e-b62c-99b256907db0)


9.Selecting Visualize classifier errors would plot the results of classification as shown here −

![image](https://github.com/Kamali22004796/EX-9-Simulating-Classification-using-WEKA-Tool/assets/120567837/1e5e58cb-b8d1-4d49-8cc7-d9f3a3a1d6f8)


10.A cross represents a correctly classified instance while squares represents incorrectly classified instances. At the lower left corner of the plot you see a cross that indicates if outlook is sunny then play the game. So this is a correctly classified instance.

# RESULT :
Thus the simulation of classification technique has been executed using WEKA tool successfully.
