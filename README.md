# project-sentimental-analysis-of-iphone7-
The objective of the analysis is to predict – what is the probability that customer would file fraudulent  / Genuine warranty to understand important factors associated with them.

Project Architecture / Project Flow

                 DATA ACQUISITIO-->EDA AND FEATURE EXTRACTION-->SENTIMENTAL ANALYSIS-->PREPARE AND TRAIN MODEL-->EVALUATE MODEL-->DEPLOYEMENT
                
Perform an Exploratory Data Analysis (EDA) on a dataset;
Build a quick and dirty model, or a baseline model, which can serve as a comparison against later models that we will build;
Iterate this process. We will do more EDA and build another model;
Engineer features: take the features that we already have and combine them or extract more information from them to eventually come to the last point, which is
Get a model that performs better.

Web scraping
Web Scripting is an automatic method to obtain large amounts of data from websites. Most of this data is unstructured data in an HTML format which is then converted into structured data in a spreadsheet or a database so that it can be used in various applications. There are many different ways to perform web scraping to obtain data from websites. these include using online services, particular API’s or even creating your code for web scraping from scratch. Many large websites like Google, Twitter, Facebook, StackOverflow, etc. have API’s that allow you to access their data in a structured format. This is the best option but there are other sites that don’t allow users to access large amounts of data in a structured form or they are simply not that technologically advanced. In that situation, it’s best to use Web Scraping to scrape the website for data.

Web scraping requires two parts namely the crawler and the scraper. The crawler is an artificial intelligence algorithm that browses the web to search the particular data required by following the links across the internet. The scraper, on the other hand, is a specific tool created to extract the data from the website. The design of the scraper can vary greatly according to the complexity and scope of the project so that it can quickly and accurately extract the data.

SENTIMENTAL ANALYSIS
Sentiment analysis is the process of using natural language processing, text analysis, and statistics to analyze customer sentiment. The best businesses understand the sentiment of their customers—what people are saying, how they’re saying it, and what they mean. Customer sentiment can be found in tweets, comments, reviews, or other places where people mention your brand. Sentiment Analysis is the domain of understanding these emotions with software, and it’s a must-understand for developers and business leaders in a modern workplace.

As with many other fields, advances in deep learning have brought sentiment analysis into the foreground of cutting-edge algorithms. Today we use natural language processing, statistics, and text analysis to extract, and identify the sentiment of words into positive, negative, or neutral categories.

PREPARE AND TRAIN MODEL
For now, let us tell you that in order to build and train a model we do the following five steps:

Prepare data.
Split data into train and test.
Build a model.
Fit the model to train data.
Evaluate model on test data.
But before we get there we will first:

take a closer look at our data,
we explain how to train linear regression,
we define metrics that are used to evaluate the model,
then discuss why we need split data.

EVALUATE MODEL
Overfitting and underfitting are the two biggest causes for poor performance of machine learning algorithms.
Overfitting: Occurs when the Model performs well for a particular set of data(Known Data), and may therefore fail to fit additional data(Unknown Data) or predict future observations reliably.
Underfitting: Occurs when the model cannot adequately capture the underlying structure of the data.
Generalization: refers to how well the concepts learned by a machine learning model apply to specific examples not seen by the model when it was learning.

DEPLOYMENT
In a typical machine learning and deep learning project, we usually start by defining the problem statement followed by data collection and preparation, understanding of the data, and model building, right?

But, in the end, we want our model to be available for the end-users so that they can make use of it. Model Deployment is one of the last stages of any machine learning project and can be a little tricky. How do you get your machine learning model to your client/stakeholder? What are the different things you need to take care of when putting your model into production? And how can you even begin to deploy a model?

Flask is a web application framework written in Python. It has multiple modules that make it easier for a web developer to write applications without having to worry about the details like protocol management, thread management, etc.

Flask gives is a variety of choices for developing web applications and it gives us the necessary tools and libraries that allow us to build a web application.
                 
  
