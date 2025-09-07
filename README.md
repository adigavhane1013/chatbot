AI Chatbot Development
An intelligent AI-powered chatbot developed using Python and Hugging Face Transformers. The chatbot is capable of understanding and responding to natural language queries across various domains including general knowledge, mathematics, weather updates, and news.

Features
Natural language understanding and response generation using Hugging Face Transformer models (e.g., dialoGPT).

Integration with multiple external APIs for enriched responses:

Wikipedia API for factual knowledge answers

WolframAlpha API for solving complex mathematical and logical queries

OpenWeatherMap API for real-time weather information

News API for the latest news updates

Interactive GUI built with Tkinter for easy and responsive user interaction.

Modular API-driven architecture allowing easy addition/removal of knowledge domains.

Technologies Used
Python

Hugging Face Transformers

Tkinter

Wikipedia API

WolframAlpha API

OpenWeatherMap API

News API

Setup Instructions
Clone or download this repository.

Install the required Python packages:

bash
pip install transformers torch wikipedia wolframalpha requests tk  
Obtain API keys for WolframAlpha, OpenWeatherMap, and News APIs, and configure them in the project’s configuration file or environment variables.

Run the chatbot application script:

bash
python chatbot.py  
Use the GUI to interact with the chatbot in real-time.

Usage
Type questions or commands in the chat input box.

The chatbot will process the input and respond with appropriate answers using integrated APIs and AI models.

Examples of supported queries: general knowledge, math problems, weather updates, news headlines.

Project Structure
chatbot.py — Main application script containing chatbot logic and GUI code.

api_keys.py — Configuration file to store API keys securely (not to be shared publicly).

requirements.txt — List of all Python dependencies.

Notes
Requires internet connection to access APIs for dynamic responses.

API keys are necessary for WolframAlpha, OpenWeatherMap, and News services.

The chatbot model can be further fine-tuned or replaced with other Hugging Face models as needed.
