# English to Hindi Speech Translation System

A deep learning-based speech-to-speech translation system that converts English speech into Hindi speech using Whisper for speech recognition, a fine-tuned MarianMT model for English-to-Hindi translation, and gTTS for Hindi speech generation.

## Overview

The project combines three major deep learning/NLP components:

- **Whisper** for English speech recognition
- **MarianMT** for English-to-Hindi neural machine translation
- **gTTS** for Hindi speech synthesis

The complete pipeline is:

```text
English Speech
      ↓
Whisper
      ↓
English Text
      ↓
Fine-Tuned MarianMT
      ↓
Hindi Text
      ↓
gTTS
      ↓
Hindi Speech
