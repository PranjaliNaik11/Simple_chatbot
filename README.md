# Simple Chatbot

## Introduction
This is a simple Python chatbot created to interact with users in various ways: introducing itself, guessing the user's age, counting numbers up to a specified limit, and playing a quiz game.

## Functionality

### 1. Introduction
Upon starting, the chatbot will introduce itself and provide the year it was created.

### 2. Greeting
After introduction, the chatbot asks the user for their name and greets them personally.

### 3. Guessing Age
Next, the chatbot attempts to guess the user's age by asking for remainders when the age is divided by 3, 5, and 7.

### 4. Counting Numbers
Following age guessing, the chatbot demonstrates its ability to count numbers from 0 up to a positive integer entered by the user.

### 5. Quiz Game
Finally, the chatbot engages the user in a quiz game. It asks a question with four options and continues asking for an answer until the correct option is chosen. Upon correct answer, the chatbot congratulates the user and exits gracefully.

## Usage:
1. **Starting the Chatbot**: Run the Python script `chatbot.py`.
2. **Interaction**: Follow the prompts provided by the chatbot.
3. **Exiting**: The chatbot will exit after the quiz question is answered correctly.

## Requirements
- Python 3.x

## Files Included
- `simple_chatbot.py`: The main Python script containing the chatbot logic.

## How to Run
To run the chatbot:
```bash
python simple_chatbot.py
```

## Development Notes
- The chatbot is designed to be simple and educational, demonstrating basic interaction and logic flow in Python.
- It handles input validation for numeric entries to ensure smooth operation during counting and quiz sections.

## Future Improvements
- Enhance the quiz section with a broader range of questions and topics.
- Implement natural language processing to handle more complex conversations.
- Introduce additional interactive features to make the chatbot more engaging.
