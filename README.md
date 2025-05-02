# News-Al-Chatbot

An AI-driven news chatbot created with Python, Tkinter, and NewsAPI. This chatbot fetches the latest headlines and summaries on user-defined topics like technology, sports, health, and more. It uses NLTK to summarize the articles and presents them in a friendly, interactive interface.

## 🔍 Features

- 🧠 Handles topic-based user queries (e.g., "What’s new in technology?")
- 🌐 Fetches current news articles from [NewsAPI](https://newsapi.org/)
- ✂️ Summarizes news articles using NLTK’s sentence tokenization
- 🖥️ User-friendly GUI powered by Tkinter
- 📌 Easily extendable to support additional topics or improved summarization logic

## 💡 How It Works

1. The user enters a query about a specific topic (e.g., "Give me the latest in sports").
2. The chatbot identifies the topic from the user input using keyword matching.
3. It fetches the latest news articles on the topic from the NewsAPI.
4. The chatbot summarizes the articles using NLTK’s sentence tokenization feature.
5. Summarized articles are displayed in the GUI for the user to read.

## 🛠️ Tech Stack

- **Python 3** - Programming language
- **Tkinter** - GUI toolkit for building the chat interface
- **NLTK** - Natural language processing library for summarizing text
- **NewsAPI** - API to fetch the latest news data
- **Requests** - Library for making HTTP requests to the NewsAPI

## 🚀 Getting Started

### Prerequisites

To run this project, you’ll need Python and some dependencies. To install them, use the following commands:

1. Install Python dependencies:

    ```bash
    pip install requests nltk
    ```

2. Download the required NLTK data:

    ```python
    import nltk
    nltk.download('punkt')
    ```

3. Replace the `NEWS_API_KEY` variable in the code with your own API key from [NewsAPI](https://newsapi.org/).

### Running the Application

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/ai-news-chatbot.git
    ```

2. Navigate to the project folder:

    ```bash
    cd ai-news-chatbot
    ```

3. Run the chatbot script:

    ```bash
    python ai_news_chatbot.py
    ```

4. The chatbot interface will open, and you can start interacting with it.

## 📝 Example Use

1. User enters: `Tell me the latest in technology`
2. The bot responds with:
    ```
    📰 1. [Article Title 1]
    📝 Summary: [Brief summary of the article]

    📰 2. [Article Title 2]
    📝 Summary: [Brief summary of the article]
    ```

## Supported Topics

- Technology
- Sports
- Business
- Entertainment
- Science
- Health

If the chatbot doesn't recognize the topic, it will ask the user to choose one of the supported topics.

## 🧑‍🤝‍🧑 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue to improve the project. If you'd like to suggest a new feature or fix a bug, let me know!

## 🙏 Acknowledgements

- **NewsAPI** for providing access to a vast database of real-time news articles.
- **NLTK** for simplifying text processing and summarization.
- **Tkinter** for making it easy to build the GUI in Python.
