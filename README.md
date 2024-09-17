# Alfred - Your Personal Assistant for Mac

Alfred is a voice-activated assistant built on Python, designed for macOS, specifically tested on a MacBook M1 using PyCharm as the development environment. It listens for voice commands and performs tasks like opening applications, playing music, searching the web, checking the weather, scheduling events, and much more.

## Features

- Open Applications: You can open apps like Mail, Calendar, Excel, Word, etc.
- Web Search: Perform Google searches using voice commands.
- Weather Updates: Get weather updates directly.
- Spotify Integration: Control Spotify to play music.
- Calendar Integration: Schedule and fetch events from your calendar.
- Get Directions & Transit: Get directions and transit details using Apple Maps.

## Setup Instructions

1. Clone the Repository:
   ```bash
   git clone https://github.com/yourusername/alfred-mac-assistant.git
   cd alfred-mac-assistant
   ```

2. Install Dependencies:
   The project uses the `speech_recognition` Python package. Install it along with other dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Once running, Alfred listens for commands. Some key voice commands include:

- "Hey Alfred"
- "Open [application/website]"
- "Play music"
- "Look up [query]"
- "How's the weather?"
- "What's the date and time?"
- "Get directions to [destination]"
- "Schedule event [title] at [YYYY-MM-DD HH:MM]"

## Compatibility

- macOS (Tested on MacBook M1)
- Python 3.7+
- PyCharm (Recommended IDE)

## Built With

- Python - Main programming language.
- speech_recognition - For capturing and interpreting voice commands.
- osascript - For controlling macOS applications via AppleScript.

## Notes

This project uses the built-in Mac `say` command for text-to-speech functionality. It is specifically designed and tested on a MacBook M1. Results may vary on different macOS versions or hardware.

Feel free to fork and modify it to fit your needs!
