# Alexa Clone with Python

This project is a **simple voice assistant** built using Python that can perform various tasks like checking the time, weather, telling jokes, sending emails, and more. The assistant uses speech recognition and text-to-speech synthesis to interact with the user.

## Features

- **Speech Recognition**: Converts spoken words into text using the `SpeechRecognition` library.
- **Text-to-Speech**: Converts text responses into speech using the `pyttsx3` library.
- **Weather Updates**: Get real-time weather updates for any city.
- **Jokes**: Tell jokes using the `pyjokes` library.
- **Web Search**: Performs a web search using Google Search API.
- **Send Emails**: Sends emails through SMTP.
- **Open Applications**: Open applications like PowerPoint or Google Chrome on your computer.
- **Time and Date**: Get the current time and date.

## Requirements

- Python 3.x
- Libraries:
  - `SpeechRecognition`
  - `pyttsx3`
  - `requests`
  - `pyjokes`
  - `pocketsphinx`
  - `google-api-python-client`
  - `smtplib` (comes with Python)
  - `pyaudio` (for microphone input)

You can install the necessary libraries using `pip`:

```bash
!pip install pyttsx3
!pip install SpeechRecognition
!pip install requests
!pip install pyjokes
!pip install pocketsphinx
!pip install google-api-python-client
```

For **Windows users**, you may also need to install `pyaudio` manually if it isn't working with `pip`:

```bash
!pip install pyaudio
```

## Setup

1. **Install Dependencies**: First, install the required dependencies as mentioned above.
2. **Voice Recognition**: The voice assistant uses your system's microphone. Ensure that your microphone is connected and configured properly.
3. **API Keys**: For some features (like Google Search), you'll need an API key. Please refer to the relevant API documentation to set it up.

## How to Use

1. Run the Python script.
2. The assistant will start listening for your commands.
3. Say a command like:
   - "What time is it?"
   - "Tell me a joke."
   - "What's the weather in New York?"
   - "Open PowerPoint."
   - "Search Python tutorials."
4. The assistant will respond with a voice output and take action based on your command.

### Example Commands:
- **"What time is it?"** — The assistant will tell you the current time.
- **"Tell me a joke"** — The assistant will tell a random joke.
- **"Search Python tutorials"** — The assistant will search the web for Python tutorials.
- **"Weather in London"** — The assistant will fetch the weather for London.
- **"Open PowerPoint"** — The assistant will open PowerPoint on your computer.

## Code Structure

- **main.py**: Contains the main logic of the voice assistant, including speech recognition, text-to-speech, and command handling.
- **weather.py**: Handles weather-related functionality using an external weather API.
- **email.py**: Contains logic for sending emails.
- **jokes.py**: Provides a random joke using the `pyjokes` library.
- **search.py**: Handles web search functionality.

## Improvements & Future Work

- **Advanced NLP**: Integrate Natural Language Processing (NLP) to understand more complex commands.
- **Multi-tasking**: Handle multiple tasks simultaneously.
- **Add More Features**: Integrate with more APIs to perform tasks like setting reminders, controlling IoT devices, etc.
- **Voice Feedback**: Improve speech output quality and add more responses for various queries.

## Contributing

Feel free to fork the repository, create a pull request, and contribute to the project. If you find any bugs or have suggestions for improvements, please open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/JenifaMehjabin/Alexa-Clone/blob/master/LICENSE) file for details.

---

This README gives users a clear understanding of the project, how to set it up, and what functionalities the assistant provides. You can adjust or expand the sections based on your project needs.
