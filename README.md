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
  
  <img width="1428" alt="Screenshot 2023-07-25 at 10 17 09 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/ca363708-2071-4955-bd3d-3e03595351cb">

- The sentiment analysis revealed that 64% of the data science topics discussed in these videos garnered positive feedback from the audiences, with only 6% of the comments being neutral. Only a third of the comments expressed negativity.

  <img width="775" alt="Screenshot 2023-07-25 at 10 48 15 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/58648392-0446-4cc7-b2a5-1cfbc718d78c">
 
- The more likes and comments a video has, the more views the video gets. Likes seem to be a better indicator for interaction than comments and the number of likes seem to follow the "social proof", which means the more views the video has, the more people will like it.

  <img width="1049" alt="Screenshot 2023-07-25 at 10 49 08 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/c3c43f40-c262-4668-baca-fa620a4eaaf3">
  
- Most-viewed videos tend to have average title length of 30-70 characters. Too short or too long titles seem to harm viewership.
  <img width="1062" alt="Screenshot 2023-07-25 at 10 49 47 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/a1c6728a-bb69-4b90-b0fc-6e103d5187b3">

- Videos are usually uploaded on Tuesdays, Fridays, and Saturdays. Thursdays and Sundays in particular is not a popular time for posting new videos.
  <img width="1044" alt="Screenshot 2023-07-25 at 10 50 13 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/98abb613-2ec2-493f-80c9-8d8ece2732c4">


