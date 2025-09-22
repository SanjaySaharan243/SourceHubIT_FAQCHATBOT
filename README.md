### FAQ Chatbot

A simple FAQ chatbot built with Flask (Python) and Google’s Gemini API.
The chatbot takes user questions from a web interface, sends them to Gemini, and displays formatted answers (Markdown → HTML).

## Features

## Flask backend with REST endpoint (/ask)

## Google Gemini integration (gemini-2.5-pro model)

## Markdown → HTML rendering (supports code blocks, lists, etc.)

## Bootstrap-based frontend with chat-style UI

## Easy setup using .env for API keys

## Project Structure
project/
├── app.py                # Flask application
├── requirements.txt      # Python dependencies
├── .env                  # Environment variables (API key)
├── templates/
│   └── index.html        # Frontend page
└── static/
    └── style.css         # Custom CSS (optional)

## Requirements

Python 3.8+

A Google Gemini API key
