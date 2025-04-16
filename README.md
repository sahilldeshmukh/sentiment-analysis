# Sentiment Analysis GUI Application

This project is a simple **Sentiment Analysis** tool built using **Python**, the **VADER SentimentIntensityAnalyzer** from the `vaderSentiment` library, and a GUI created with **Tkinter**. It allows users to input a sentence and receive sentiment scores for positive, neutral, and negative categories, as well as an overall sentiment classification.

## 📌 Objective

The aim of this project is to analyze a given sentence and determine the sentiment it expresses—whether **Positive**, **Negative**, or **Neutral**. It helps in understanding public opinion or feedback, which is valuable in domains like marketing, customer service, and political analysis.

## 💡 Features

- Input any sentence via a user-friendly graphical interface
- Detects and displays:
  - Positive sentiment score
  - Neutral sentiment score
  - Negative sentiment score
  - Overall sentiment category
- Options to clear input/output and exit the application

## 🛠️ Technologies Used

- Python 3.x
- `vaderSentiment` library
- `Tkinter` for GUI

## 🧪 How it Works

- The sentence entered by the user is analyzed using `SentimentIntensityAnalyzer`.
- The tool calculates the sentiment polarity scores:
  - `pos`: Probability of positive sentiment
  - `neu`: Probability of neutral sentiment
  - `neg`: Probability of negative sentiment
  - `compound`: Overall polarity score
- Based on the compound score:
  - ≥ 0.05: Positive
  - ≤ -0.05: Negative
  - Else: Neutral

## 🚀 Getting Started

### Prerequisites

Install required library:

```bash
pip install vaderSentiment
