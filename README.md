Gen-Ai-powered-2D-Game
This project is a game generator that creates playable 2D browser-based games from text prompts. It uses Python (Flask/Streamlit) on the backend and HTML, CSS, JavaScript on the frontend to dynamically generate game logic and serve it to users.

📂 Project Structure

app.py → Backend logic to handle user prompts and generate game code.
requirements.txt → Python dependencies.
static/game.js → Core JavaScript for running the generated games.
static/index.html → Frontend UI for interacting with the generator.
🚀 Features

Accepts user text prompts to define game ideas.
Generates interactive 2D games dynamically.
Browser-based execution with simple controls.
Easy to extend for more game types or AI-based improvements.
🔧 Tech Stack

Backend: Python (Flask/Streamlit)
Frontend: HTML, CSS, JavaScript
Game Engine: Custom JavaScript logic
▶️ Usage

Clone the repo.
Install dependencies: pip install -r requirements.txt
Run the backend: python app.py
Open the browser at http://localhost:5000 to start generating games.
