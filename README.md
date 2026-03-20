# QuizGamePython


AI-Powered Yes/No Quiz App
A sleek, desktop quiz application built with Python, Tkinter, and OpenAI. The app generates dynamic general knowledge questions using the GPT-3.5 model, providing a fresh experience every time you play.

🚀 Features
Dynamic Question Generation: Uses OpenAI's API to create unique "Yes/No" questions on the fly.

Modern UI: Styled with the ttkthemes "Yaru" theme for a clean, professional look.

Real-time Scoring: Instant feedback on whether your answer was correct or incorrect.

Progress Tracking: Visual progress bar to show how far you are in the 5-question circuit.

Restart Functionality: Seamlessly reset the quiz and start a new round without restarting the app.

🛠️ Prerequisites
Before running this application, ensure you have the following installed:

Python 3.x

An OpenAI API Key


🧠 How it Works
The application follows a simple but effective logic flow:

Request: The app sends a prompt to gpt-3.5-turbo requesting a Yes/No question and its answer in a specific string format.

Parsing: The script splits the API response to separate the question text from the correct answer.

UI Update: The UI updates the label with the new question.

Validation: When a user clicks "YES" or "NO", the check() function compares the input to the API's answer and updates the score and progress bar.
