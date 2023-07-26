# Project Name: Analysis of Top 10 Data Science Channels using Youtube API

## 1. Overview
**Analysis of Top 10 Data Science Channels using Youtube API** is a data-driven project aimed at exploring key factors that influence the success of YouTube videos in the data science niche. The project involves leveraging the YouTube API to obtain video data, conducting in-depth analyses, and dispelling common myths surrounding video performance. By utilizing various data analysis techniques and Transformer models for sentiment analysis, I aim to provide valuable insights to content creators, data science students, and enthusiasts.

## 2. Project Objectives
- **Validating Common "Myths" About Video Success**: Investigate the impact of likes, comments, video duration, and title length on video views to validate or debunk common beliefs surrounding YouTube video performance.
- **Unveil trending topics**: Stay up-to-date with frequently discussed topics in Data Science.
- **Understanding Creator Upload Patterns**: Analyze the upload frequency of data science creators, examining the best days for publishing new videos to maximize audience engagement.
- **Sentiment analysis**: Use the Transformer model for a sentiment classifier to analyze audiences' comments to get audiences' reactions out of the topics. eg: Are viewers reacting positively/negatively to the development of AI?

## 3. Workflow and Methodology
- **Obtaining Video Metadata via YouTube API**: The first step involves utilizing the YouTube API to gather video metadata from the top 10-15 data science channels. To achieve this, I will create a developer key, request data from the API, and transform the responses into a usable data format. 
- **Data Preprocessing**: Once the video metadata is collected, the next step is to preprocess the data to ensure consistency and handle any missing or erroneous information. 
- **Exploratory Data Analysis (EDA)**: Through EDA, I aim to gain initial insights into factors that contribute to video success and identify potential relationships between variables.
- **Key takeaways**: The final step of the project entails drawing important takeaways based on the findings from the exploratory data analysis. 

## 4. Key takeaways
In this project, I have delved into the video data of the top 10 Data Science/Data Analytics channels on YouTube, unearthing several fascinating insights that would benefit anyone starting a YouTube channel, be it in data science or any other field:
- The most popular topics these channels discuss include project tutorials, Data Science, Machine Learning, Learning Python, and Interview Prep.
  <img width="966" alt="Screenshot 2023-07-25 at 10 13 53 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/a898cb1a-c239-4853-84e5-c4d94e8ae938">
- The sentiment analysis revealed that 50% of the data science topics discussed in these videos garnered positive feedback from the audiences, with only 8% of the comments being neutral. Interestingly, 41% of the reactions expressed negativity.
- Videos that receive higher numbers of likes and comments tend to garner more views. Likes, in particular, appear to be a stronger indicator of viewer engagement compared to comments. Moreover, the number of likes seems to follow the concept of "social proof," where increased views result in more likes from viewers.
- Most-viewed videos typically have titles with an average length of 30-70 characters. Titles that are either too short or excessively long impact viewership.
- In terms of uploading schedules, the most common days for video releases are Tuesdays, Fridays, and Saturdays. Conversely, Thursdays and Sundays are not popular choices for posting new videos.

