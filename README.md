# MentalHealthAnalysis

# Introduction

Mental health is very critical to the well being of a person, but is not given enough importance in today’s day and age. Mental health disorders remain widely underreported. According to the statistics, 1 in 10 people suffer from Mental Health disorders globally. People usually do not talk about their mental health with their peers. Social media is one platform where people express their views freely. We used Natural language processing (NLP) techniques to infer people's mental states from what they write on social media sites like Reddit. These conclusions can then be utilized to establish online pathways that link users to health information and help, as well as individualized actions. However, there's been relatively little work done in distinguishing different mental health diseases and assessing severity.
In this project, We will use textual data from Reddit to categorize posts not just as a binary classification problem (Casual Conversations vs conversations relating to mental health), but also to understand the type of ailment and its severity, leading to the creation of a distinct label for the risk of suicide.

Dataset:

We have created a dataset using Reddit's PRAW API.The dataset contains different posts from specific subreddits:
depression
Anxiety
BPD (Bi-Polar Disorder)
MentalHealth
SuicideWatch
CasualConversation.
We have used the subreddits as labels for the posts. Each subreddit is designed to represent a specific ailment, except r/mentalhealth which contains general discussions concerning mental health. The other exception is r/CasualConversation, which we have included to provide a variety of data to the models. This is crucial for generalizing data that hasn't been seen before.
Some of the columns of interest are:
Title: Title of the post
Body: The content of the Reddit post
Score: It is the number of upvotes minus the number of downvotes
Upvote Ratio: It is the number of upvotes divided by total number of votes
Subreddit: Contains labels depicting which subreddit the corresponding post belongs to.

We have around 6000 posts from the above-mentioned subreddits.



