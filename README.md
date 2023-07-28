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
  <img width="890" alt="Screenshot 2023-07-27 at 8 07 48 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/f00b4f4a-0ea8-4a20-bdcf-e2a04226b510">
  
- The sentiment analysis revealed that 64% of the data science topics discussed in these videos garnered positive feedback from the audiences, with only 6% of the comments being neutral. Only a third of the comments expressed negativity.

  <img width="468" alt="Screenshot 2023-07-27 at 8 08 18 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/5e954d6b-6a8b-411d-a326-0048e6284714">

- The more likes and comments a video has, the more views the video gets. Likes seem to be a better indicator for interaction than comments and the number of likes seems to follow the "social proof", which means the more views the video has, the more people will like it.

  <img width="934" alt="Screenshot 2023-07-27 at 8 08 46 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/ff76982b-cb07-4c8e-aab9-bc7841b12db3">


- Most-viewed videos tend to have an average title length of 30-70 characters. Too short or too long titles harm viewership.

   <img width="914" alt="Screenshot 2023-07-27 at 8 09 11 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/12a6402f-8e85-4f71-87d8-711e9b9b3dae">


- Videos are usually uploaded on Tuesdays, Fridays, and Saturdays. Thursdays and Sundays, in particular, í not a popular time for posting new videos.

  <img width="907" alt="Screenshot 2023-07-27 at 8 09 39 PM" src="https://github.com/ChloeHo12/Analysis-of-Top-10-Data-Science-Channels-using-Youtube-API/assets/98048503/41d0098d-02b9-4c70-b42c-9423a92008e0">



