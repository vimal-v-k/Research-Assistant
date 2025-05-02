# Research-Assistant-Using-DeepSeek-Whisper

A comprehensive speech-to-text research assistant that records audio, separates vocals, transcribes content, formats text professionally, and provides document/general knowledge-based question answering.

## Features

- **Audio Processing**  
  🎤 Real-time microphone recording  
  🔊 Vocal separation using Demucs  

- **Speech-to-Text**  
  ✍️ OpenAI Whisper transcription  
  🧹 Automatic grammar correction using Deepseek-R1  
  📝 Structured content formatting using Deepseek-R1  

- **Document Generation**  
  📄 Automatic PDF creation  
  🏷️ Smart filename generation  
  ⏱️ Timestamped logs

- **Knowledge Retrieval Using Deepseek-R1**  
  📚 PDF document processing  
  🔍 Vector similarity search  
  ❓ Document-based Q&A

## Quick Start

1. Install requirements:
pip install -U git+https://github.com/facebookresearch/demucs
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
pip install -r requirements.txt

## Run the notebook:
jupyter notebook Researcher_Assistant.ipynb

