# College Inquiry Chatbot

A simple chatbot that answers questions about a college, built using Python, TensorFlow, and NLTK.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The College Inquiry Chatbot is a conversational AI system designed to provide information about a college to prospective students, current students, and other interested parties. It uses natural language processing techniques and a pre-trained neural network model to understand user queries and generate relevant responses.

## Features
- Answers questions about the college's programs, facilities, and campus life
- Provides information about admission requirements and deadlines
- Responds to general inquiries and directs users to appropriate resources
- Continuously learns and improves its responses based on user feedback

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/college-inquiry-chatbot.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the necessary NLTK data:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   ```

## Usage
1. Run the chatbot script:
   ```bash
   python chatbot.py
   ```
2. The chatbot will start running and prompt you for input.
3. Type your questions or statements, and the chatbot will respond accordingly.
4. To exit the chatbot, type "bye" or "Goodbye".

## Training
The chatbot is pre-trained on a dataset of college-related questions and answers. To retrain the model with new data:
1. Prepare your training data in a JSON format similar to `intents.json`.
2. Update the `train_chatbot.py` script with the new data file path and model parameters.
3. Run the training script:
   ```bash
   python train_chatbot.py
   ```
4. The trained model will be saved as `chatbotmodel.h5`.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
