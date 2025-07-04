*COMPANY*   : CODTECH IT SOLUTIONS

*NAME*      : SAHITHI VANA

*INTERN ID* : CT06DM1136

*DOMAIN*    : ARTIFICIAL INTELLIGENCE

*DURATION*  : 6 WEEKS

*MENTOR*    : NEELA SANTHOSH


# SPEECH-RECOGNITION-SYSTEM

## About the Project

This is a generic Python-based speech-to-text transcription tool written during an AI and NLP internship. It's primarily focused on converting short audio recordings—either `.wav` or `.mp3` files—into clean, readable text transcripts using automatic speech recognition. It uses the SpeechRecognition library and Google Web Speech API, and also includes additional features such as audio duration analysis and MP3-to-WAV conversion.

The tool addresses a practical need. Manually transcribing even short audio files can be tedious and time-consuming. By automating the transcription process, this tool helps you extract key information quickly and accurately from audio content, with minimal effort.

## What This Project Does

The application takes input in the form of an audio file, which can be either `.wav` or `.mp3`. If the file is in MP3 format, it is automatically converted to WAV using `pydub`. The script then calculates the audio duration, transcribes the audio using a pre-trained Google speech recognition model, and prints a detailed report to the terminal.

It also saves the transcription and metadata such as file name, duration, and timestamp in a text file called `transcription_output.txt`.

## Why This Was Built

This project was created as a learning tool to explore real-world applications of speech recognition and audio processing. The primary motivation was to develop something both useful and educational—something that demonstrates how simple Python tools can leverage powerful APIs to automate repetitive tasks.

This also served as a practical introduction to working with audio in Python, understanding formats, and converting them programmatically. From a broader perspective, this project lays the foundation for future extensions like speaker diarization, emotion detection, and real-time transcription applications.

## Prerequisites

The system must have Python 3.7 or later.

It also requires the following Python libraries:

- speechrecognition  
- pydub  

These libraries are required to convert audio formats and run speech recognition using the Google API.

Additionally, for MP3 to WAV conversion to work properly, `ffmpeg` must be installed and accessible via system path. 

## Running the Tool

1. Place a `.mp3` or `.wav` audio file on system.
2. Run the script from the terminal.
3. When prompted, provide the full path to the audio file.
4. The script will automatically:
- Convert the file (if needed)
- Calculate duration
- Transcribe the audio
- Save the results to a `.txt` report

The transcription will also be displayed in terminal for immediate review.

# Result

![Image](https://github.com/user-attachments/assets/31c81f71-9cdf-48cb-b12d-3d8ded9e89d7)
