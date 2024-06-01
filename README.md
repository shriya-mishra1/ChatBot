# ChatBot

This repository contains the source code for a simple chatbot implemented in Python. The chatbot utilizes natural language processing techniques to understand and respond to user queries. It is trained on a dataset containing intents and responses, allowing it to engage in meaningful conversations with users on various topics.

## Contents

- `chatbot_model.h5`: This file contains the trained model used by the chatbot for understanding and generating responses.
- `classes.pkl`: This pickle file stores the classes used for classification in the chatbot model.
- `gui_chatbot.py`: This script provides a graphical user interface (GUI) for users to interact with the chatbot.
- `intents.json`: This JSON file contains the intents and corresponding patterns/responses used for training the chatbot.
- `train_chatbot.py`: This Python script is used to train the chatbot model using the intents and responses provided in `intents.json`.
- `words.pkl`: This pickle file stores the words used for tokenization in the chatbot model.

## Usage

1. Clone the repository to your local machine.
2. Ensure you have Python installed.
3. Run `train_chatbot.py` to train the chatbot model.
4. Once the model is trained, you can interact with the chatbot using `gui_chatbot.py` or integrate it into your own applications.

Feel free to contribute to this project by creating pull requests or reporting any issues you encounter.

## About the Author

This project is maintained by [shriya-mishra1](https://github.com/shriya-mishra1). 

## License

This project is licensed under the [MIT License](LICENSE). 

```
