# Multilingual Chatbot Project

Welcome to the Multilingual Chatbot Project! This project features a simple rule-based chatbot that can interact with users in multiple languages including English, German, Japanese, and Chinese. 

## Features

- **Multilingual Support**: The chatbot can converse in English, German, Japanese, and Chinese.
- **Predefined Responses**: The chatbot provides responses based on predefined rules and patterns.
- **Extended Conversations**: The chatbot can handle greetings, farewells, inquiries about time and date, and more.
- **Dynamic Language Switching**: Users can switch between languages during the chat session.
- **Exit Option**: Users can exit the chatbot at any time by typing 'exit'.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/multilingual-chatbot.git
   cd multilingual-chatbot
   ```

2. **Install Required Libraries**

   The only library required for this project is `datetime`. If you need to install any other libraries, you can do so using pip:

   ```bash
   pip install re datetime
   ```

### Running the Chatbot

To start the chatbot, simply run the `main.py` script:

```bash
python main.py
```

## Usage

1. **Select a Language**

   When you start the chatbot, you will be prompted to select a language by entering a number:
   
   ```
   Welcome to chatbot! with many languages!
   1. English
   2. German
   3. Japanese
   4. Chinese
   5. Exit
   Write the number of the language you want: 
   ```

2. **Interact with the Chatbot**

   After selecting a language, you can start typing your messages. The chatbot will respond based on the predefined rules.

3. **Exit the Chatbot**

   You can exit the chatbot at any time by typing 'exit'.

## Examples

Here are a few example interactions:

### English

```
You: Hi
Bot: Hello! How can I assist you?

You: What is your name?
Bot: I'm just a chatbot.

You: What is the capital of Japan?
Bot: The capital of Japan is Tokyo.

You: exit
Goodbye!
```

### German

```
You: Hallo
Bot: Hallo! Wie kann ich Ihnen helfen?

You: Wie heißt du?
Bot: Ich bin nur ein Chatbot.

You: Was ist die Hauptstadt von Japan?
Bot: Die Hauptstadt von Japan ist Tokio.

You: exit
Goodbye!
```

## Extending the Chatbot

### Adding New Languages

To add a new language, create a new class similar to `ChatbotEnglish` and `ChatbotGerman`. Define the `welcome_message` and `conversation` methods along with any additional methods needed for specific responses.

### Adding More Responses

To add more responses, update the `predefined_rules` dictionary in each chatbot class. You can add new patterns and responses to handle more types of interactions.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.
