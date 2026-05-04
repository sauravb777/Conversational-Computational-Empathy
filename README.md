# Conversational Computational Empathy

An intelligent customer support system that understands user intent and sentiment from transcribed call conversations, and responds in an empathetic and human like manner.

---

## Project Report

A detailed 60+ page report covering the methodology, architecture, and results.

[Read the full project report](https://docs.google.com/document/d/13bG4pFFYTncHvJjQSCx1ZjSco9synpm0/edit?usp=sharing&ouid=105605514906295320178&rtpof=true&sd=true)

---

## Overview

This project focuses on building an intelligent customer support system that understands user intent and sentiment from call conversations, then responds in an empathetic and context aware manner.

For the current implementation, we directly use the transcribed text of customer calls as input. The system does not yet convert live audio calls into text in real time. That part is kept as a future improvement.

We leverage Transformer-based models to capture contextual relationships in the transcribed text. The system performs:

- Intent Classification
- Sentiment Analysis

Based on this understanding, it generates appropriate and empathetic responses to improve customer interaction quality.

---

## Objective

The main objective of this project is:

- To understand and interpret the intentions and emotions expressed by customers during a call
- To use this understanding to generate empathetic and appropriate responses

---

## System Pipeline

1. Speech transcription input  
   The already transcribed call text is used as input.

2. Text processing  
   The text is cleaned and prepared for model input.

3. Transformer-based analysis  
   - Intent detection
   - Sentiment analysis

4. Response generation  
   The system generates empathetic and context-aware replies.

5. Text-to-speech output  
   The response is converted back to audio with a natural pause threshold of approximately 2 seconds.

---

## Architecture

- Transformer-based neural networks
- NLP pipeline for intent and sentiment analysis
- Integrated speech processing using text-to-speech

---

## Key Features

- Context-aware understanding of conversations
- Emotionally aware response generation
- End-to-end conversational pipeline
- Natural conversational flow simulation

---

## Applications

- Customer support automation
- Call center assistance
- AI-based conversational agents

---

## Tech Stack

- Python
- Transformer-based NLP models
- Speech-to-Text input handling
- Text-to-Speech output generation

---

## Future Work

- Real-time conversion of live calls to text
- Integration of fraud detection from conversational patterns
- Multilingual support
- Improved response generation using advanced language models

---

## Authors

- Saurav Bhandari
- Birat Paudel
- Sijan Bhattarai
- Satyam Ghimire
