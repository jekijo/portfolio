<br />

<h1 style="text-align: center;">Data Science and Machine Learning</h1>

### About Me
I am a Data Scientist graduate with an educational background in psychology and neuroscience. In addition to my two degrees I have 
multiple projects showcasing the skills I've acquired, as well as new projects that I continue to work on. You can read more about
my projects and experiences here! Along with descriptions, I've also included any report papers that were written proceeding 
the completion of team based projects.
<br />
---
<br />
## Experience 
### Hack for LA 
After graduating from undergrad, I spent a year gaining additional software engineering skills to build on a few classes I had taken. I then joined a group of volunteer engineers and data scientists to help on the 311 Data project, where I
contributed as a full stack engineer to help implement new features to the 311 Data website for roughly 6 months. More information about this org can be found [here](https://www.hackforla.org/projects/311-data).<br />
<br />
---
<br />
## Projects
### Neural Decoding of Movement (Ongoing)
Using an open source neurophysiology dataset that contains spike activity from neural population recordings, I trained a vanilla pytorch neural network to predict movements from the neural data. The original neural network expressed
unsatisfactory performance, running into the vanishing gradient problem. The next step for this project will be to implement an LSTM to attempt to boost performance. There is currently no Github link for this project, but I will be updating the
progress on this project frequently! Here is a [link](https://elifesciences.org/articles/73155#s4) to the paper that this project’s data was collected from. 
<br />
### Steam Review Sentiment Analysis
##### [Full Report](assets/Steam_Final_Report.pdf)
Worked as part of a team that pulled data from the Steam API to train supervised models for sentiment classification tasks, and unsupervised models for sentiment analysis tasks. For our supervised model tasks, we trained multiple different types of classification models, including logistic regression, random forest, SVM, and multinomial Naive Bayes, to read in video game review comments and evaluate if they were positive or negative. Once our data was cleaned and properly combined, it was vectorized using both TF-IDF, as well as CountVectorization and passed through each model for training. We were then able to distinguish the best model to then perform feature importance analysis, and hyperparameter sensitivity analysis to validate the robustness of our classification model. Below are some visualizations regarding this section of the project.

![](/assets/steam_performance.png)<br />
| *This table shows the key metrics for model performance across the trained models.* |<br />
![](/assets/feature_importance.png)<br />
| *Here we can see the feature importance of key data features.* |<br />
![](/assets/sens_analysis.png)<br />
| *This chart shows the results of sensitivity analysis done on the random forest classifier.* |<br />


For the unsupervised model task, we dropped unnecessary data features, and utilized Word2Vec, Latent Semantic Analysis (LSA), and Latent Dirichlet Allocation (LDA) to focus on the word content within each review. We used these methods to better understand the relationship particular words or topics had with the positivity or negativity of a given game review. Below are some example visualizations from our project that highlight some of our findings.<br />

![](/assets/chi_squared.png)<br />
| *Here we can see the most influential words of all review genres ordered by Chi-Squared score value. The terms "best" or some form of "10/10" seem to be amongst the strongest influencers for review sentiment, most likely in the positive direction.* |<br />

![](/assets/intertopic.png)<br />
| *We were also able to use LDA to section reviewers into three different groups. Group one were mainly positive reviwers, group two had mixed feelings, and group three were mainly negative. In this chart you can see the term frequency for certain words based on the chosen group (group three), compared to the overall term frequency of all reviews.* |<br />

You can read a more detailed report in the link above, where we go in depth on our feature engineering, modeling methods, and results of the project.
<br />
### College Football Player Transfer Predictions
##### [Full Report](assets/CFB_Report.pdf) 
Using all open source data found from multiple sources, our team of three created a website that utilized supervised learning models to predict the probability that any given college football player would enter the transfer portal. We combined various player statistics, team statistics, coaching, and recruiting information into one large dataset. Due to class imbalances, we used SMOTE to oversample the minority class to improve model performance.<br />
From here, multiple different models were trained on various iterations of the data to cover offensive positions as well as defense. Below you can see the tables detailing evaluation results for each model compared to a dummy classifier, as well as the average probability returned for the positive and negative class for each model.
##### Position Group Model Performance
![](/assets/CFB_model_performance.png)
##### Average Model Probability
![](/assets/CFB_probability.png)<br /> 
You can read a more detailed report in the link above, where we go in depth to our methods, evaluations, impacts, and architecture of creating this project.<br /> 
You can also view a quick video demo [here](https://www.youtube.com/watch?v=MR8CaqypfQc).<br /> 
Github [link](https://github.com/raulmartinez1855/wolverines-capstone)
<br />
### NBA Draft Pick Success Analysis
##### [Full Report](assets/NBA_Report.pdf)
Worked with two other students to analyze how the draft ranking of an NBA player relates to both individual and team success. We cleaned and combined multiple data sources ranging over the past few decades covering player statistics, player accolades, team statistics and accolades, and player draft data. From here, we created multiple visualizations to showcase different relationships between draft position and different metrics of success.<br />
You can find a more detailed slide deck of our findings, as well as all of our visualizations in the full report link. We also go over additional background information, motivations, and how we defined success within our project. 
<br />
---
<br />
## Education
University of Michigan | Ann Arbor, MI<br />
Master’s of Science in Applied Data Science<br />
Jan 2023- May 2024<br />
GPA: 3.961<br />

University of Houston | Houston, TX<br />
Bachelor’s of Science Psychology<br />
Aug 2017- May 2021<br />
GPA: 3.9<br />
