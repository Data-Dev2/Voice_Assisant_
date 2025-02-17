# Voice Assistant Web App (Flask)

This project is a simple voice assistant web application built with Flask. It allows users to provide voice input, processes their requests, and responds using text-to-speech or web search results.

## Features
- **Speech Recognition**: Utilizes the Google Speech API to convert voice input into text.
- **Text-to-Speech**: Implements Google Text-to-Speech (gTTS) to generate audio responses.
- **Web Search**: Opens Google or YouTube based on user commands.
- **Calculations**: Integrates the WolframAlpha API to perform basic computations.
- **Microphone Input**: Accepts and processes audio directly from the web interface.

## Prerequisites
Ensure you have the following installed before running the application:
- Python 3.x
- Flask
- gTTS
- SpeechRecognition
- WolframAlpha
- Selenium
- WebDriver (e.g., for Chrome or Firefox)

## Installation
Clone the repository and navigate to the project directory:
```sh
git clone https://github.com/Data-Dev2/voice-assistant-flask.git
cd voice-assistant-flask
```
Install the required dependencies:
```sh
pip install -r requirements.txt
```

## Running the Application
Start the Flask server with:
```sh
python app.py
```
Then, open your browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/).

## Frontend
The project includes a simple HTML/JavaScript interface for interacting with the assistant.
- **HTML**:
  - Provides an input form for users to speak or type commands.
  - Communicates with the Flask backend using JavaScript and AJAX.
- **JavaScript**:
  - Sends audio input to the backend.
  - Handles responses and plays back the generated speech.

