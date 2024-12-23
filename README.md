Alexa-Like Application

An Alexa-like voice assistant built in Python that performs various tasks such as answering questions, playing YouTube videos, telling jokes, and more. This project demonstrates basic AI functionalities like speech recognition, text-to-speech, and web integration.

Features

Voice Commands: Recognizes and processes voice input.

YouTube Integration: Plays requested videos on YouTube.

Wikipedia Search: Fetches summaries from Wikipedia for a topic.

Tells Jokes: Brightens your day with a random joke.

Time Query: Provides the current time.

Fun Responses: Includes playful conversational replies.

Tech Stack

Programming Language: Python

Libraries:

speech_recognition for voice input.

pyttsx3 for text-to-speech conversion.

pywhatkit for YouTube video playback.

datetime for fetching the current time.

wikipedia for retrieving information from Wikipedia.

pyjokes for generating jokes.

Setup Instructions

Clone the repository:

git clone https://github.com/yourusername/alexa-like-assistant.git
cd alexa-like-assistant

Install dependencies:

pip install -r requirements.txt

Run the application:

python assistant.py

Usage

Run the script using Python.

Speak your command when prompted (e.g., "Alexa, play Shape of You" or "Alexa, tell me a joke").

The assistant will respond with appropriate actions or outputs.

Sample Commands

"Alexa, play Despacito."

"Alexa, tell me the time."

"Alexa, tell me about Python programming."

"Alexa, tell me a joke."

Code Overview

assistant.py

The main script contains:

talk(text): Converts text to speech and speaks it out.

take_command(): Listens to the user's voice and processes the command.

run_alexa(): Executes the appropriate action based on the command.

Features Implemented

YouTube Playback: Uses pywhatkit to search and play songs/videos on YouTube.

Wikipedia Integration: Fetches and speaks a brief summary of the requested topic.

Time Query: Retrieves the current time using the datetime module.

Jokes: Uses pyjokes to tell random jokes.

Fun Responses: Replies playfully to certain questions.

Future Enhancements

Add weather updates using an API like OpenWeatherMap.

Implement NLP for more natural and flexible interactions.

Add a GUI for improved user experience.

Enable smart home integration for IoT devices.

Contribution

Contributions are welcome! Feel free to fork the repository, submit pull requests, or raise issues for any bugs or feature requests.


Author

Shristi
