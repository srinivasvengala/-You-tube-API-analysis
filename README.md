## YouTube Channel Analysis using API
## 1. Introduction
The project aims to analyze the statistics and performance of various YouTube channels. The key metrics evaluated include subscriber count, total views, total videos, and view-to-subscriber ratio. The analysis also delves into video-specific metrics such as views, likes, comments, and word frequency in video titles.

## 2. Data Collection
The data was collected using the YouTube Data API. The following channels were analyzed:

Marques Brownlee (MKBHD)
Mrwhosetheboss
Trakin Tech
Prasad Tech Telugu
Tech Burner

## 3. Data Preparation
The data was collected and converted into a pandas DataFrame for analysis. The key steps included:

- Fetching channel statistics (subscribers, views, total videos).
- Converting data types for analysis.
- Handling missing values.

## 4. Channel Statistics
The initial data collection provided the following statistics for each channel:

Channel Name	Subscribers	Views	Total Videos	Playlist ID
Mrwhosetheboss	19,200,000	5,736,954,503	1,715	UUMiJRAwDNSNzuYeN2uWa0pA
Prasadtechintelugu	4,580,000	1,682,728,105	4,423	UUb-xXZ7ltTvrh9C6DgB9H-Q
Marques Brownlee	19,300,000	4,397,019,728	1,674	UUBJycsmduvYEL83R_U4JriQ
Tech Burner	11,900,000	2,146,555,105	1,337	UUXUJJNoP1QupwsYIWFXmsZg
Trakin Tech	14,500,000	2,708,297,180	3,996	UUEPL07qzVsOcHd3sMUws65g

## 5. Visualizations
Several visualizations were created to understand the distribution and relationships between different metrics.

### 5.1 Subscribers, Views, and Total Videos
Bar charts were generated for subscribers, views, and total videos for each channel.
The view-to-subscriber ratio was calculated and visualized.
### 5.2 Top 10 Videos
Top 10 videos by views and likes were identified and plotted using bar charts.
### 5.3 Scatter Plot
A scatter plot of views vs likes for the top 100 videos was created to visualize the relationship between these two metrics.
### 5.4 Word Frequency Analysis
Titles of all videos were analyzed to count the frequency of words.
Words were also analyzed based on the average number of views they generated.
## 6. Detailed Analysis
### 6.1 Channel-wise Analysis
For each channel, detailed statistics were collected, including the number of subscribers, total views, and total videos. This helped in understanding the overall reach and engagement of each channel.

### 6.2 Video-wise Analysis
A detailed breakdown of each video's statistics was performed, which included:

Title, published date, description, tags.
Views, likes, comments, duration, definition, and caption status.
## 7. Key Findings

-Subscriber and View Metrics: Marques Brownlee and Mrwhosetheboss had the highest subscriber counts and views.
Engagement Metrics: High engagement was observed in terms of likes and comments on videos with unique and catchy titles.

-Title Analysis: Words like "most", "best", and "top" appeared frequently in high-view videos, suggesting these words attract more viewers.

## 8. Conclusion
1. MrWhosetheBoss is having the heighest subsribers and view count among the selected youtubers so further analys is made on MrWhosetheBoss

2. Average views is 3.3M and average likes for all 1712 videos is 1.5M 

3. "The BRIGHTEST TORCH in the World!" video is highest viewed and highest liked video so far for MrWhosetheBoss.

4. MrWhosetheBoss used 'best'(10.5%), 'vs'(9.2%), 'smartphone/s'(7.5%) most frequently in his titles indicating he is focused more on ranking the best thing out of many, smartphone reviews and impressions and  comparision videos.

5. 16% of the view share for a selected word list is smartphone followed by iphone (13%), vs (11%) and phone (9.7%) explaining that the subscribers are interested in iphone videos and comparision videos and overall subscribers are interested in smartphone videos.

## 9. Future Work
1. Youtube comments for each playlist is scraped and sentiment analysis can be done to study the type of audience for a perticular youtuber in a perticular genre and expect the controversial comments related to the video title or the video content

2. Models can be deployed to predict the view count and like count for a specific title words used.

9. Future Work
Future analysis can include sentiment analysis of comments, a deeper dive into video metadata, and trends over time to predict future performance and engagement.
