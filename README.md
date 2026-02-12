# Bangla TTS Dataset

> **Note:** The full version of this dataset will be uploaded to [Hugging Face](https://huggingface.co) soon.

This repository contains a Bangla Text-to-Speech (TTS) dataset created for developing high-quality speech synthesis models. The dataset includes clean, well-aligned audio and text pairs from a single professional voice actor.

## Overview

- **Language:** Bangla (Standard Bangladeshi Bengali)
- **Total Duration:** ~18.24 hours of processed audio
- **Number of Clips:** ~16,000
- **Audio Format:** WAV, 16-bit, 22,050 Hz
- **Sentence Types:** Simple, compound, complex
- **Genre Coverage:** Literature, diaries, news, autobiographies, science, economics, religious content, music, and more
- **Speaker:** Single professional female voice actor
- **Phoneme Coverage:** 230 unique compound letters used in modern Bangla

## Dataset Features

- Cleaned and denoised audio
- Clipped into short sentences (~0–12 seconds)
- Text aligned to audio clips
- Covers diverse sentence structures, tenses, and perspectives (first, second, third person)
- UTF-8 encoded text files

## File Structure

Each audio clip (`.wav`) has a corresponding text file (`.txt`) with the same name.


The text files contain the exact transcript for the associated audio clip.

## Purpose

This dataset was created to:

- Address the limitations of existing Bangla datasets
- Provide a single-speaker, error-free, high-quality audio dataset
- Support research and development of TTS systems for Bangla

## Notes

- Collected in a controlled environment (Audio Synthesis Lab)
- Professional recording equipment used
- Extensive preprocessing to remove noise, normalize pitch, and ensure clarity
- Ideal for TTS training and evaluation tasks

## License

[Specify your license here]

---

**References:**  
Dataset created for the paper:  
**STFT-GradTTS: A Robust, Diffusion-Based Speech Synthesis System with iSTFT Decoder for Bangla**  
[Paper Link](https://link.springer.com/article/10.1007/s10772-025-10241-w)
