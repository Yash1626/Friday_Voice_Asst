
# Friday_Voice_Assistant

# Friday Voice Assistant

## Overview

Friday is a simple voice assistant implemented in Python using various libraries to perform tasks like searching Wikipedia, accessing websites, providing the current time, and more. The code utilizes the `pyttsx3` library for text-to-speech conversion, `speech_recognition` for recognizing voice commands, `wikipedia` for searching Wikipedia, `webbrowser` for opening websites, `os` for file handling, and `datetime` for getting the current time.

## Installation

1. Install required libraries:

```bash
pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia-api
pip install wolframalpha
```

2. Make sure you have a working microphone for voice input.

3. Run the code in a Python environment.

## Features

1. **Voice Greetings:** Friday greets the user based on the time of day (morning, afternoon, or evening).

2. **Voice Commands:** Users can interact with Friday using voice commands.

3. **Wikipedia Search:** Users can ask Friday to search Wikipedia, and it will provide a summary of the requested topic.

4. **Open Websites:** Friday can open popular websites such as YouTube, Google, Amazon, WhatsApp, Facebook, Spotify, Netflix, Visual Studio Code, Moodle, and Student Portal.

5. **Current Time:** Friday can tell the user the current time.

6. **Goodbye:** Users can say goodbye to Friday, and it will bid farewell.

## How to Use

1. Run the script.
2. Listen for the greeting from Friday.
3. Speak a command or question when prompted.
4. Friday will respond verbally or perform the requested action.

## Voice and Text Output

Friday uses the 'sapi5' API for inbuilt voices in Windows. The voice is set to a male voice for better clarity. The `pyttsx3` library is responsible for converting text to speech.

## Voice Recognition

Voice commands are recognized using the `speech_recognition` library. The `takecommand` function captures user input from the microphone, converts it to text, and processes the command.

## Task List

- [x] Greet users based on the time of day.
- [x] Provide a manual describing available commands.
- [x] Implement voice commands for Wikipedia search.
- [x] Open popular websites.
- [x] Tell the current time.
- [x] Provide a farewell message when the user says goodbye.

## Important Notes

- The code assumes a working internet connection for Wikipedia searches and website access.
- Ensure that the required websites are accessible from the user's location.

Feel free to modify and extend the code based on your preferences and requirements. Enjoy using Friday!

