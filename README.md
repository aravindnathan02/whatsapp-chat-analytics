# WhatsApp Chat Analytics

---

## Overview

This project provides an in-depth analysis of WhatsApp chat data, offering insights into message trends, most active users, word frequency, sentiment analysis, and more. It allows users to visualize and interpret chat histories, helping uncover valuable conversation patterns.

---

## Dataset

- **Source:** Whatsapp Chat data
- **Features:** Timestamp, Sender, Message
- **Note:** This repository has no dataset for privacy purposes.

---

## Features

- **Message Parsing:** Parses the data from raw text data in an ordered manner using regex.
- **Message Frequency Analysis:** Visualizes the distribution of messages over time (hourly, daily, monthly).
- **User Activity Analysis:** Identifies the most active users based on the number of messages sent.
- **Word Cloud Generation:** Displays the most frequently used words in the chat.
- **Sentiment Analysis:** Classifies messages and emojis based on sentiment (positive, negative, neutral).
- **Message Length Distribution:** Analyzes the length of messages across different users.
- **Time-based Insights:** Investigate chat patterns during specific times of the day, month, and year.
- **Topic modeling:** Performs topic modeling using Latent Dirichlet Allocation (LDA) and calculates coherence scores.
- **Conversation clustering:** Creates clusters of chat messages to indicate various conversation topics using pre-trained BERT model and K-means clustering.

---

## Setup

1. Clone this repository:
```
git clone https://github.com/aravindnathan02/whatsapp-chat-analytics.git
```

2. Navigate to the repository:
```
cd whatsapp-chat-analytics
```

3. Install the required dependencies:
```
pip install -r requirements.txt
```

4. Export your desired Whatsapp Chat for Analysis:
```
Whatsapp Chat --> Options --> More --> Export Chat (without media)
```

---

## Project Workflow

1. **Data Preprocessing:** Convert the raw data into organized data.
2. **Exploratory Data Analysis (EDA):** Understand the dataset to uncover patterns and generate a word cloud.
3. **Communication Network Analysis:** Build a conversation network graph based on message sequences (useful while analyzing group chats).
4. **Sentiment Analysis:** Extensive topic modeling using LDA and sentiment analysis on the messages.
5. **Emoji Sentiment Analysis:** Perform sentiment analysis on emojis on each sender and calculate overall emoji sentiment.
6. **BERT Analysis:** Generate embeddings through a pre-trained BERT model and visualize conversation clusters using K-means and t-SNE.
