# WhatsApp Chat Analytics

---

## Overview

This project provides a comprehensive analysis of WhatsApp chat data, utilizing various techniques such as data parsing, exploratory data analysis (EDA), sentiment analysis, emoji sentiment analysis, and advanced natural language processing with BERT. The goal is to extract meaningful insights from chat interactions and understand user engagement patterns.

---

## Dataset

- **Source:** Whatsapp Chat export  files (in `.txt` format).
- **Features:** Timestamp, Sender, Message
- **Note:** This repository has no dataset for privacy purposes.

---

## Features

- **Chat Data Parsing:** Efficiently parse WhatsApp chat files to extract timestamps, senders, messages, and message length.
- **Data Cleaning:** Remove irrelevant entries to enhance data quality for analysis.
- **Exploratory Data Analysis (EDA):** Visualize messaging patterns, including daily message volume and sender statistics.
- **Sentiment Analysis:** Classify messages into positive, negative, and neutral sentiments, providing insights into user emotions.
- **Emoji Sentiment Analysis:** Analyze emoji usage and their sentiment impact on conversations.
- **BERT-based Semantic Analysis:** Utilize BERT embeddings for clustering conversations and uncovering key interaction themes.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Emoji
- NLTK
- Scikit-learn
- Gensim
- Transformers (BERT)
- NetworkX
- WordCloud
- TextBlob
- Torch

---

## Setup

1. Clone this repository:
```bash
git clone https://github.com/aravindnathan02/whatsapp-chat-analytics.git
```

2. Navigate to the repository:
```bash
cd whatsapp-chat-analytics
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

4. Export your desired Whatsapp Chat for Analysis:
```bash
Whatsapp Chat --> Options --> More --> Export Chat (without media)
```

---

## Usage

1. Place your WhatsApp chat text file (e.g., `WhatsApp_Chat.txt`) in the project directory.
2. Run the Jupyter notebooks in the following order:
    - 1_data_preprocessing.ipynb: Parse and clean the chat data.
    - 2_exploratory_data_analysis.ipynb: Perform EDA and visualize results.
    - 3_communication_network_analysis.ipynb: Visualize the communication network.
    - 4_sentiment_analysis.ipynb: Analyze message sentiment and its distribution.
    - 5_emoji_sentiment_analysis.ipynb: Analyze emoji usage and its sentiment.
    - 6_bert_analysis.ipynb: Conduct semantic analysis using BERT.

