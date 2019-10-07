# Stack_Overflow_tag_Prediction


### DESCRIPTION:

Stack Overflow is the largest, most trusted online community for developers to learn, share their programming knowledge, and build their careers.

Stack Overflow is something which every programmer use one way or another. Each month, over 50 million developers come to Stack Overflow to learn, share their knowledge, and build their careers. It features questions and answers on a wide range of topics in computer programming. The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers in a fashion similar to a wiki or Digg. As of April 2014 Stack Overflow has over 4,000,000 registered users, and it exceeded 10,000,000 questions in late August 2015. Based on the type of tags assigned to questions, the top eight most discussed topics on the site are: Java, JavaScript, C#, PHP, Android, jQuery, Python and HTML.

### PROBLEM STATEMENT:

Suggest the tags based on the content that was there in the question posted on Stackoverflow.


### SOURCE/USEFUL LINKS:
Data Source : https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data

Youtube : https://youtu.be/nNDqbUhtIRg

Research paper : https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tagging-1.pdf

Research paper : https://dl.acm.org/citation.cfm?id=2660970&dl=ACM&coll=DL

### REAL WORLD OBJECTIVE:
Predict as many tags as possible with high precision and recall.
Incorrect tags could impact customer experience on StackOverflow.
No strict latency constraints.

### DATA OVERVIEW
Refer: https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/data

All of the data is in 2 files: Train and Test.

Train.csv contains 4 columns: Id,Title,Body,Tags.

Test.csv contains the same columns but without the Tags, which you are to predict.

Size of Train.csv - 6.75GB

Size of Test.csv - 2GB

Number of rows in Train.csv = 6034195

The questions are randomized and contains a mix of verbose text sites as well as sites related to math and programming. The number of questions from each site may vary, and no filtering has been performed on the questions (such as closed questions).


### DATA FEILD EXPLANATION

Dataset contains 6,034,195 rows. The columns in the table are:

Id - Unique identifier for each question

Title - The question's title

Body - The body of the question

Tags - The tags associated with the question in a space-seperated format (all lowercase, should not contain tabs '\t' or ampersands '&')
