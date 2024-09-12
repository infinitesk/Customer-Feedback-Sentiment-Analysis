# Sentiment Analysis of Customer Feedback

## Project Overview

This project aims to analyze customer feedback using advanced Natural Language Processing (NLP) techniques to derive actionable insights. The feedback data is processed to determine sentiment categories such as positive, neutral, or negative, providing valuable information on customer satisfaction and areas for improvement.

## Key Features

- **Data Extraction and Preparation**: Extracted relevant columns (`Customer ID`, `Category`, and `Customer Feedback`) from a customer feedback dataset to perform sentiment analysis.

- **Sentiment Analysis using Transformers**: Leveraged the `twitter-roberta-base-sentiment-latest` model from the Hugging Face Transformers library to classify feedback into sentiments. Each feedback entry is analyzed to determine the sentiment label (e.g., positive, negative, neutral) and its associated confidence score.

- **Data Visualization**:
  - Created pivot tables and heatmaps to visualize the distribution of sentiments across different customer feedback categories.
  - Developed bar plots to showcase the overall sentiment distribution in the feedback data, providing an overview of customer sentiments.

- **Word Cloud for Negative Sentiments**: Generated a word cloud from negative feedback to highlight frequently mentioned words, helping identify key issues and areas that need attention.

## Technologies Used

- **Python**: Data manipulation and analysis (Pandas, NumPy)
- **Transformers Library**: Sentiment analysis using pre-trained models from Hugging Face
- **Data Visualization**: Seaborn and Matplotlib for plotting heatmaps, bar plots, and other visualizations
- **WordCloud Library**: To generate word clouds of negative feedback text

## Results and Insights

- The project provides a comprehensive view of customer sentiments, categorized by different aspects of service.
- The sentiment distribution visualizations help stakeholders understand customer satisfaction and prioritize improvements.
- Word cloud analysis of negative feedback assists in identifying specific issues that customers frequently mention, guiding targeted improvements.

---

