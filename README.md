# Conversational Computational Empathy

An intelligent customer support system that understands user intent and sentiment from call conversations, and responds in an empathetic and human like manner.

---

## Project Report

A detailed 109 page report covering methodology, architecture, and results.

Read the full report here:  
https://docs.google.com/document/d/13bG4pFFYTncHvJjQSCx1ZjSco9synpm0/edit?usp=sharing&ouid=105605514906295320178&rtpof=true&sd=true

---

## Overview

This project focuses on building an intelligent customer support system that understands user intent and sentiment from call conversations, then responds in an empathetic and context aware manner.

We leverage Transformer-based models to capture contextual relationships in transcribed call data. The system performs:

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

1. Speech-to-Text Conversion  
   Customer call audio is transcribed into text.

2. Text Processing  
   The text is cleaned and prepared for model input.

3. Transformer-based Analysis  
   - Intent detection  
   - Sentiment analysis  

4. Response Generation  
   Generates empathetic and context-aware replies.

5. Text-to-Speech Output  
   Converts the response back to audio with a natural delay (approximately 2 seconds pause threshold).

---

## Architecture

- Transformer-based Neural Networks  
- NLP pipeline for intent and sentiment analysis  
- Integrated speech processing (Speech-to-Text and Text-to-Speech)

---

## Key Features

- Context-aware understanding of conversations  
- Emotionally aware response generation  
- End-to-end conversational pipeline (STT → NLP → TTS)  
- Simulated natural conversational flow  

---

## Applications

- Customer Support Automation  
- Call Center Assistance  
- AI-based Conversational Agents  

---

## Tech Stack

- Python  
- Transformer-based NLP models  
- Speech-to-Text (STT)  
- Text-to-Speech (TTS)  

---

## Future Work

- Integration of fraud detection from conversational patterns  
- Real-time deployment with streaming audio  
- Multilingual support  
- Improved response generation using advanced language models  

---

## Authors

- Saurav Bhandari  
- Sijan Bhattarai  
- Satyam Ghimire  
- Birat Paudel  
