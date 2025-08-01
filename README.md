In the pursuit of the Google Advanced Data Analytics certification, I have chosen to work on the TikTok project. The synthetic TikTok data can be accessed [here](https://docs.google.com/spreadsheets/d/1BTVomLOrzNRGtF4QGTwf86eVm5gOpwpE4Ai_F1NAHbo/template/preview?resourcekey=0-OGt7Jh_Vj5AcZaxwYvegpA)<br><br>
Background:<br> 
TikTok users have the ability to submit reports that identify videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. The process generates a large number of user reports that are challenging to consider timely. As such, TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful predictive model, TikTok can reduce the backlog of user reports and prioritize them more efficiently. <br>With this final product of building a predictive model in mind, the guided projects are completed in the following order:
1) [Course 2 lab, data analysis with Pandas](https://github.com/ZhengLonggg/Google-Advanced-Data-Analytics-Projects/blob/main/Course%202%20lab%2C%20Data%20Analysis%20with%20Pandas.ipynb) <br>
This is the first project that I completed for my Google Advanced Data Analytics course.  In this fictional case study, I analyzed a synthetic TikTok dataset. Each TikTok video, represented as a row in the dataset, is mainly classified as either a 'claim' or an 'opinion'. TikTok videos are classified as 'claim' when the TikTok content creator asserts a statements as fact or presents information that can be objectively verified. On the other hand, TikTok videos that are classified as 'opinion' are those where TikTok content creators express their feelings or views.  
The objectives of this lab include: <br>
• Building a dataframe for the TikTok dataset.<br>
• Gathering descriptive statistics.<br>
• Visualizing the TikTok data in Python.<br>
• Using pandas to manipulate the data for analysis and visualisation.<br><br>
2) [Course 3 lab, EDA with Python](https://github.com/ZhengLonggg/Google-Advanced-Data-Analytics-Projects/blob/main/Course%203%20lab%2C%20EDA.ipynb) <br>
In the second guided project, I focused on exploratory data analysis (EDA) with the TikTok dataset. I practised uncovering patterns by presenting findings through boxplots, histograms, barplots, pie charts, and scatterplots. These visualisations have helped me to explore and compare the relationships between different variables, such as the viewing proportion of TikTok videos classified as 'claim' versus those classified as 'opinion'. <br>
The objectives of this lab include: <br>
• Exploring and cleaning the TikTok dataset.<br>
• Performing EDA. <br>
• Visualisating with various charts. <br>
• Determine outliers. <br><br>
3) [Course 4 lab, hypothesis testing with Python](https://github.com/ZhengLonggg/Google-Advanced-Data-Analytics-Projects/blob/main/Course%204%20lab%2C%20Hypothesis%20Testing.ipynb)  <br>
Next, we investigate the relationship between TikTok authors' verification status and their average video view counts. Specifically, do verified authors command higher average view counts, or are the view counts similar between verified and unverified authors? To answer this, we use hypothesis testing. <br>
The objectives of this lab include: <br>
• Dropping rows with null values. <br>
• Using hypothesis testing to determine if there's a significant difference in the view count for verified vs unverified authors. <br>
• Posing potential follow-up questions based on the findings. <br><br>
4) [Course 5 lab, Regression Modeling](https://github.com/ZhengLonggg/Google-Advanced-Data-Analytics-Projects/blob/main/Course%205%20lab%2C%20Regression%20Modeling.ipynb)  <br>
In this project, I built a regression model in Python to predict whether a TikTok account is verified based on certain video characteristics, such as the duration of the TikTok video and its view count. <br>
The objectives of this lab include: <br>
• Encoding categorical variables for regression compatibility. <br>
• Building a logistic regression model to predict account verification status. <br>
• Visualising the model performance using a confusion matrix. <br>
• Interpreting model coefficients to identify key predictors. <br>
• Evaluating model performance using a classification report and metrics such as accuracy, precision, and recall. <br><br>
5) [Course 6 lab, Classifying videos using machine learning](https://github.com/ZhengLonggg/Google-Advanced-Data-Analytics-Projects/blob/main/Course%206%20lab%2C%20Classifying%20videos%20using%20machine%20learning.ipynb)  <br>
Finally, we utilise two machine learning models, random forest and XGBoost, to find the most influential features in determining whether a TikTok video is classified as a 'claim' or an 'opinion'. <br>
The objectives of this lab include: <br>
• Cleaning the data before fitting it into the machine learning models <br>
• Using GridSearch to find the best hyperparameters <br>
• Evaluating each machine learning model's performance using average recall and precision scores <br>
• Selecting the better machine learning model after analysing its confusion matrix and classification report <br>
• Utilising feature importance to find the most predictive features <br>
