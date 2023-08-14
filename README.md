# Reddit_AI_Topic_Analysis
Unveiling Trends in AI Ethics: Exploring the Ethical Dimensions of AI, Prepared for SICSS 2023 - Tor Vergata

Co-contributors to this project are **Yawri Carr** and **Genevieve Smith**.

It was prepared as final project for the Summer Institute in Computational Social Sciences at Tor Vergata, Rome.
The project covers how to retrieve relevant topics in Reddit's [AI & Ethics](https://www.reddit.com/r/AIethics/) subreddit.

## Main Research Questions
- What topics in AI ethics are most prevalent?
- How do these topics change over time?

## Main Findings
- Seems to be a possible relationship between current events in AI and the sentiment of posts in the thread;
- Good opportunity to use transformers to unbias the topic modeling, however, too many topics were chosen.
  
## Limitations
- Limited amount of data;
- Outdated chats;
- Difficult to map events to the posts in the subreddit.

## Overview of the repo's organisation
The R script covers scrapping the posts from the subreddit, preprocessing them and performing a sentiment analysis and topic modeling.
The python script looks into using a Hugging Face transformer ([bart-large-mnli](https://huggingface.co/facebook/bart-large-mnli)) and how this could improve our findings from the topic modeling.

