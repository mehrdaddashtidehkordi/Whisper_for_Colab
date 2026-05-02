Audio Transcription with Whisper (Colab + GPU Support)

This project provides a simple yet powerful pipeline for transcribing audio files into text using OpenAI’s Whisper model. It is optimized for Google Colab and supports GPU acceleration for faster and more accurate results.

 ***Features
Automatic speech-to-text transcription
GPU acceleration (if available)
High-accuracy transcription using the large Whisper model
Export transcription as a .docx (Word) file
Easy file upload & download in Google Colab

*** Requirements
Google Colab environment (https://colab.research.google.com)
Python 3.x
GPU (optional but recommended)

 ***Installation

Run the following commands:

pip install git+https://github.com/openai/whisper.git
pip install python-docx
sudo apt update && sudo apt install ffmpeg
*** Usage
Run the notebook in Google Colab
Upload your audio file when prompted
The model will transcribe the audio
A .docx file will be generated and downloaded automatically
*** Notes
The large model provides higher accuracy but requires more resources.
You can specify the language manually for better results:

language='en'
GPU significantly speeds up processing.
*** Output
transcription_output.pdf → Contains the transcribed text
*** Example Workflow

Upload → Transcribe → Generate Word File → Download
