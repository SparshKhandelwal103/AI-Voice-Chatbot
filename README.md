# AI Voice Chatbot

## Overview
This project is an AI-powered voice chatbot that allows users to interact with it through voice commands. It is designed to provide a seamless conversational experience by leveraging natural language processing and machine learning algorithms.

## Key Features
- Voice recognition and response
- Multi-turn conversation handling
- Integration with various APIs for enhanced functionalities
- Support for multiple languages

## Tech Stack
- **Programming Language:** Python
- **Frameworks:** Flask, TensorFlow
- **Libraries:** SpeechRecognition, gTTS (Google Text-to-Speech), NLTK
- **Database:** SQLite
- **Deployment:** Docker, Heroku

## Architecture
The AI Voice Chatbot follows a microservices architecture where the voice recognition, natural language processing, and response generation components are decoupled for scalability and maintainability.

## Setup & Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/SparshKhandelwal103/AI-Voice-Chatbot.git
   cd AI-Voice-Chatbot
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up the database:
   ```bash
   python setup_database.py
   ```
4. Run the application:
   ```bash
   python app.py
   ```

## Usage Examples
To interact with the AI Voice Chatbot, you can use the following commands:
- "Hey Chatbot, tell me a joke."
- "What’s the weather like today?"

## Future Improvements
- Enhance the natural language understanding capabilities
- Add support for more APIs
- Implement user authentication for personalized experiences
- Improve response time and accuracy
