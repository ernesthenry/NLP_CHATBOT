# Sentiment Analysis ChatBot

This project is a simple Python-based chatbot that uses sentiment analysis to respond to user inputs. The chatbot analyzes the sentiment of the user's message and provides feedback based on whether the sentiment is positive, negative, or neutral.
## Features

- **Sentiment Analysis**: Uses the `TextBlob` library to analyze the sentiment of the user's message.
- **Interactive Chat**: The bot interacts with the user in a simple command-line interface.
- **Dynamic Responses**: The bot's response changes based on the sentiment score of the user's message.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ernesthenry/NLP_CHATBOT.git
    cd NLP_CHATBOT
    ```

2. **Create a virtual environment (optional but recommended)**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

    If `requirements.txt` doesn't exist, you can install `TextBlob` manually:
    ```bash
    pip install textblob
    ```

4. **Download necessary NLTK data** (if required):
    ```python
    python -m textblob.download_corpora
    ```

## Usage

1. **Run the chatbot**:
    ```bash
    python chatbot.py
    ```

2. **Interact with the chatbot**:
   - The bot will prompt you to enter a message.
   - Based on your message, the bot will analyze its sentiment and respond accordingly.
   - The chat continues until you manually stop it.

## Example Interaction

ChatBot: Hi, how can I help you?

You: I'm feeling great today!

ChatBot: That's great to hear! Sentiment score: 0.8

You: I'm not very happy with this service.

ChatBot: I'm sorry to hear that. Sentiment score: -0.5

You: It's just an okay experience.

ChatBot: Hmm, I see. Sentiment score: 0.0



## Dependencies

- `Python 3.x`
- `TextBlob`
- `NLTK`



## Contributing

Contributions are welcome! Please open an issue or submit a pull request with any improvements or suggestions.

## Contact

For any questions or suggestions, feel free to contact me at [henry38ernest.com].
