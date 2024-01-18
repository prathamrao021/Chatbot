# Chatbot using PyTorch

This Python script, `chat.py`, is a chatbot implementation using a neural network for natural language processing. It can engage in text-based conversations with users.

## Usage
1. Make sure you have the necessary libraries installed, including PyTorch and NLTK.
2. Create or download an `intents.json` file that contains conversation intents and patterns.
3. Run the script using a Python interpreter.
4. Start chatting with the bot by typing your messages.

## Dependencies
- Python
- PyTorch
- NLTK

## Customization
You can customize the chatbot's behavior by modifying the `intents.json` file to define conversation intents and responses. Feel free to adapt the code to your specific use case.

## License
This project is open-source under the [MIT License](LICENSE).

## Author
Pratham Rao


# Neural Network Model for Chatbot

The `model.py` file defines the neural network model used in the chatbot for natural language processing.

## Model Architecture
- The model consists of a feedforward neural network with two hidden layers.
- It uses the ReLU activation function for non-linearity.

## Usage
You can use this model as part of your chatbot project by importing it as needed. It's designed to work with the `chat.py` script.

## Dependencies
- Python
- PyTorch

## License
This code is open-source under the [MIT License](LICENSE).

## Author
Pratham Rao


# NLTK Utility Functions

The `nltk_utils.py` file contains utility functions for text processing using the NLTK library.

## Functions
- `tokensize`: Tokenizes a sentence into words.
- `stem`: Stems a word to its base form.
- `bag_of_words`: Creates a bag-of-words representation of a tokenized sentence.

## Usage
These utility functions are used by the chatbot (`chat.py`) for text preprocessing tasks. You can adapt them for other NLP projects as needed.

## Dependencies
- Python
- NLTK
- numpy

## License
This code is open-source under the [MIT License](LICENSE).

## Author
Pratham Rao


# Chatbot Training Script

The `train.py` script trains a neural network model for a chatbot using PyTorch.

## Usage
1. Prepare an `intents.json` file with conversation intents and patterns.
2. Ensure you have the required libraries installed, including PyTorch, NLTK, and numpy.
3. Run the script to train the chatbot model.
4. The trained model and related data will be saved in a file named "data.pth."

## Dependencies
- Python
- PyTorch
- NLTK
- numpy

## Customization
You can customize the chatbot's training data and hyperparameters in this script to adapt it to your specific chatbot project.

## License
This code is open-source under the [MIT License](LICENSE).

## Author
Pratham Rao


