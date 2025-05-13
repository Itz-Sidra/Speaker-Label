# Speaker Separation & Transcription Web App

This is a Streamlit-based web application for performing speaker separation and transcription on audio files using AssemblyAI's API. The app processes audio files, identifies multiple speakers, and transcribes the content with timestamps and speaker labels.

## Features

- **Speaker Separation**: Diarizes audio to identify individual speakers.
- **Transcription**: Provides a text transcription of the audio with timestamps.
- **Audio Segment Extraction**: Allows playback of specific audio segments for individual speakers.
- **Speaker Statistics**: Displays word count and speaking duration for each speaker.

## Requirements

- Python 3.10
- AssemblyAI API Key

## File Structure

- app.py: Main application script.
- requirements.txt: Python dependencies.
- .streamlit/secrets.toml: Configuration file for secrets (e.g., API keys).

## Key Libraries Used

- Streamlit: For building the interactive UI.
- Pydub: For audio processing and segment extraction.
- Requests: For API communication with AssemblyAI.

## API Integration

The app integrates with the AssemblyAI API, leveraging the following endpoints:
- Upload: Uploads audio files for processing.
- Transcript: Requests transcription with speaker labels.

## Deployment:

<a href="https://speaker-audio-separation.streamlit.app/"> Demo </a>

