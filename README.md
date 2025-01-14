# Voice Assistant Using Python

This is a basic voice assistant built using Python. The assistant can perform tasks such as:
- Play music via YouTube.
- Tell the current time.
- Provide information about a person or topic using Wikipedia.
- Tell a random joke.

### Requirements
- `speech_recognition`: For recognizing voice commands.
- `pyttsx3`: For converting text to speech.
- `pywhatkit`: For controlling YouTube and performing other tasks.
- `wikipedia`: For fetching information about a person or topic.
- `pyjokes`: For telling jokes.

### Setup
1. Install the required libraries:
    ```bash
    pip install speechrecognition pyttsx3 pywhatkit wikipedia pyjokes
    ```
2. Ensure you have a microphone connected to your system.
3. Run the script and speak to your assistant, starting your command with the word "Alexa".

### Features
- **Music**: "Alexa, play music" will play a song from YouTube.
- **Time**: "Alexa, what time is it?" will tell the current time.
- **Wikipedia**: "Alexa, who is [name]?" will give a summary from Wikipedia.
- **Jokes**: "Alexa, tell me a joke" will tell a random joke.

### Usage
Run the script, and the assistant will continuously listen for commands. Speak clearly into your microphone, and the assistant will respond.

### Notes
- You can customize the assistant’s responses and add more features as needed.
