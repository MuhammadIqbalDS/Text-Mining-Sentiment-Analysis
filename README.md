# CORETAX Sentiment Analysis

## Background
CORETAX, introduced by Indonesia’s Directorate General of Taxes (DGT) in January, is designed to modernize tax administration processes. However, since its implementation, users have reported various challenges, including system errors, slow processing times, and accessibility issues. Public sentiment shared on X (formerly Twitter) provides valuable insights into user experiences and system reception.

## Problem Statement
What is the overall public sentiment towards CORETAX? Is the response predominantly positive or negative?

## Stakeholders
This analysis is particularly relevant to the Directorate of Taxation Information and Technology (TIP) and the Indonesian Tax Ministry (DJP), both of which are responsible for CORETAX implementation and public engagement.

## Approach
A sentiment analysis was conducted on tweets mentioning CORETAX, classifying them as either positive or negative. Natural Language Processing (NLP) techniques, such as tokenization and sentiment classification, were employed to categorize the sentiment accurately.

## Dataset
The dataset consists of tweets containing mentions of CORETAX and includes the following attributes:

| Column         | Description                                  |
|---------------|----------------------------------------------|
| id_str        | Unique identifier for each tweet            |
| username      | Twitter handle of the user                  |
| created_at    | Timestamp of the tweet                      |
| full_text     | Content of the tweet                        |
| retweet_count | Number of times the tweet was shared       |
| favorite_count| Number of likes received                   |

## Findings
The sentiment analysis revealed that public perception is predominantly negative, mainly due to technical issues. Common negative keywords include “error,” “gagal” (fail), and “tidak bisa” (cannot). Positive sentiment is significantly lower, primarily consisting of tweets praising instances where the system functioned smoothly. The IndoBERT model achieved 86% accuracy, though the recall score for positive sentiment was relatively low (0.50), indicating a tendency to classify tweets as negative.

## Conclusion
This analysis highlights key user concerns and provides insights for improving CORETAX. Addressing technical issues and enhancing user experience are critical steps toward increasing adoption and public satisfaction with the system.

