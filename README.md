# Voice/Text/Morse Code Converter

This is a Python-based console application that allows users to convert between **voice, text, and Morse code**. It supports:
- Voice to Text
- Text to Morse Code
- Morse Code to Text
- Text to Speech
- Morse Code Playback (Beeping)
- File Save/Load
- Voice to Morse Code (with audio beeps)

---

## Features

| Feature                  | Description                                                   |
|--------------------------|---------------------------------------------------------------|
| Voice to Text         | Converts spoken input into text using Google Speech API       |
| Text to Morse         | Converts text into Morse code                                 |
| Morse to Text         | Converts Morse code into readable text                        |
| Text to Speech       | Reads text aloud using the pyttsx3 text-to-speech engine      |
| Play Morse Code       | Beeps Morse code via your system speaker (Windows only)       |
| Save/Load to File     | Save any text or Morse to a file and reload it later          |
| Voice to Morse Code | Combines voice recognition and Morse conversion + audio beeps |

---

## Requirements

Make sure you have Python 3 installed. Then install the required Python libraries:

```bash
pip install speechrecognition pyttsx3 pyaudio
```

Note: On Windows, winsound is built-in.

## How It Works
1. Voice Recognition
Uses speech_recognition and the Google API to transcribe spoken words into text.

2. Morse Code Mapping
Uses a dictionary to map letters and numbers to Morse code and vice versa.

3. Text to Speech
Uses pyttsx3 to convert text into spoken output.

4. Morse Code Beeps
Uses winsound.Beep to emit high-pitched short and long beeps for dots (.) and dashes (-).

---

## Future Enhancements

Add support for multiple languages
Create a GUI with Tkinter or PyQt
Add Morse code decoding from audio input
Export Morse to audio files (WAV/MP3)

---

### Author    
Created with 💗 by Sathvik Reddy
