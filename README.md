# Alpha - Voice Assistant

Alpha is a Python-based voice assistant that can perform various tasks and provide information based on voice commands. It utilizes several libraries and APIs to enable voice recognition, speech synthesis, web browsing, Wikipedia search, music playback, calendar operations, joke generation, and more. Let's explore its features and functionalities.

## Features:

1. **Voice Recognition**: Alpha uses the SpeechRecognition library to recognize voice commands spoken by the user.

2. **Speech Synthesis**: The pyttsx3 library is employed to convert text into speech, allowing Alpha to respond to the user's queries and commands.

3. **Wikipedia Search**: Alpha can search for information on Wikipedia using the Wikipedia API. It can provide summaries of articles and open the full articles in a web browser.

4. **Web Browsing**: The webbrowser module enables Alpha to open web links in a web browser. It supports popular platforms like Google Chrome.

5. **Music Playback**: Alpha can play music on different platforms, including YouTube, Spotify, Apple Music, and Amazon Music. It utilizes the pywhatkit library to search for and play songs.

6. **Calendar Operations**: Alpha can display calendars using the calendar module. It can show the calendar for a specific year and month.

7. **Joke Generation**: Alpha can generate random jokes using the pyjokes library. It adds a touch of humor to its responses.

8. **WhatsApp Messaging**: Alpha can send instant or scheduled WhatsApp messages. It utilizes the pywhatkit library to send messages to specific phone numbers.

9. **Personalization**: Alpha can remember and change the user's name. It can also provide the user's birthday upon request.

10. **Random Number Generation**: Alpha can generate random numbers within a specified range.

11. **Contact Management**: Alpha supports basic contact management functionalities. It can create and view contacts stored in a text file.

12. **System Operations**: Alpha can provide the current time and date and initiate a system shutdown.

## How to Use:

1. Install the required libraries:
   - random
   - webbrowser
   - speech_recognition
   - wikipedia
   - pyttsx3
   - time
   - pywhatkit
   - calendar
   - pyjokes
   - pyautogui
   - os

2. Instantiate the `Alpha` class with the user's name and birthday (optional).

3. Interact with Alpha using voice commands. Some example commands include:
   - "How are you?"
   - "Hello"
   - "What can you do?"
   - "Who made you?"
   - "What's your name?"
   - "Tell me a joke"
   - "Play a song on YouTube"
   - "What's the time?"
   - "Send a WhatsApp message"
   - "Search on Google"
   - "Search on Wikipedia"
   - "Change my name"
   - "Thank you"
   - "Goodbye"

Note: Make sure to have a microphone connected to your system for voice input.

## Limitations:

1. The code relies on external libraries and APIs, so an internet connection is required for certain features like Wikipedia search and music playback.

2. The speech recognition accuracy may vary depending on the user's pronunciation and background noise.

3. Some functionalities may be limited or unavailable based on the current implementation.

4. The code may need modifications or updates to work with newer versions of the libraries or APIs used.

Feel free to customize and enhance Alpha according to your specific needs and preferences. Enjoy interacting with your own voice assistant!
