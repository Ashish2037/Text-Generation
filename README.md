
# Introduction
This repository contains code for a simple system that transcribes user input from recorded audio and compares it with pre-generated data science interview questions. The goal is to assess the similarity between the user's response and the expected answers to the questions.


# Record and Transcribe:

The record_and_transcribe function uses the Whisper Automatic Speech Recognition (ASR) model to transcribe audio. Adjust the recording parameters (e.g., duration) as needed.

# Check Similarity:

The check_similarity function generates data science interview questions using the Hugging Face Hub language model (LLM) and compares the user's transcribed response with the expected answers.

You may need to set up a Hugging Face Hub API token by setting the HUGGINGFACEHUB_API_TOKEN environment variable.


# Hugging Face Hub API Token:
Set the HUGGINGFACEHUB_API_TOKEN environment variable with your Hugging Face Hub API token.






