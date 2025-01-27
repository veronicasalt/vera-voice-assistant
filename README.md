# Vera Voice Assistant
Vera is a simple voice assistant built in Python that leverages speech recognition and text-to-speech capabilities to provide helpful responses and perform basic tasks. With Vera, users can search the web, find locations, check the time, and interact using natural voice commands.

## Features
- **Voice Interaction**: Communicates via natural language and responds to user input.
- **Search the Web**: Prompts the user for a query and opens the results in a browser.
- **Find Locations**: Retrieves location information using Google Maps.
- **Check the Time**: Provides the current time when asked.
- **Custom Greetings**: Responds to basic greetings and personal questions.

## Usage
Vera can handle the following commands:

- **Greetings**: Say "hello," "hi," or "hey" to start an interaction.
- **Ask Vera's Name**: Say "What is your name?"
- **Time Inquiry**: Say "What time is it?"
- **Web Search**: Say "Search" and provide a search query when prompted.
- **Find a Location**: Say "Find location" and provide a place when prompted.
- **Exit**: Say "Exit" to terminate the program.

## Limitations
Speech Recognition: Accuracy depends on the clarity of the user's speech and the quality of the microphone.
Internet Dependency: Requires an active internet connection for both speech recognition and text-to-speech features.
Location Search Bug: The variable location in the "find location" feature is undefined. Replace location with search in the URL generation.

## Future Improvements
- Add more robust error handling and fallback mechanisms.
- Expand Vera's functionality with additional commands and integrations.
- Enhance location search functionality by fixing the bug in the location feature.
- Implement a GUI for a better user experience.

## Acknowledgments
This project uses the following libraries:

SpeechRecognition for voice input.
gTTS for text-to-speech conversion.
playsound for playing audio files.
