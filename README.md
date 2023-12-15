# Python Quiz Game v2.0

[![License: MIT](https://img.shields.io/badge/License-MIT-magenta.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.9-gray.svg)](https://www.python.org/downloads/release/python-390/)
![Version](https://img.shields.io/badge/version-v2.0-brightgreen)

## Python Quiz Game v2.0

The Python Quiz Game v2.0 is an interactive quiz game built with Python 3.9 and Tkinter GUI. It uses The Open Trivia Database API to fetch questions and provides a fun way to test your knowledge on various topics.

## Files

- `main.py`: The main script that runs the quiz game.
- `quiz_brain.py`: The brain of the quiz game, handling quiz logic.
- `data.py`: Handles fetching questions from The Open Trivia Database API.
- `question_model.py`: Defines the data model for quiz questions.
- `ui.py`: Manages the user interface using Tkinter.
- `images/`: Folder containing `false.png` and `true.png` images used in the Tkinter GUI.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/akumarm23/Day34-QuizGameV2.git
   cd Day34-QuizGameV2
   ```

2. Install required dependencies:

   ```bash
   pip install requests
   pip install tkinter
   ```

3. Run the script:

   ```bash
   python main.py
   ```

## Features

- Fetches quiz questions from The Open Trivia Database API.
- Randomly shuffles questions for each quiz session.
- Tracks and displays the score.
- Provides a user-friendly Tkinter GUI with true/false buttons.
- Displays correct/incorrect feedback using images (`true.png` and `false.png`).

## How to Play

1. Answer each question by clicking the true/false buttons.
2. Get immediate feedback on your answer with visual cues.
3. Track your score throughout the quiz.
4. Enjoy a fun and educational quiz experience!

## Acknowledgments

Feel free to contribute and enhance the functionality of this Python Quiz Game v2.0! Happy quizzing!
