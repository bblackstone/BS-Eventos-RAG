# BS-Enventos Reservation Chatbot

This project implements a Retrieval-Augmented Generation (RAG) chatbot for answering questions about BS-Enventos reservations. It utilizes the FLAN-T5 language model and a vector database to retrieve relevant information and generate informative responses. 

## Features

* **RAG-based Approach:** Employs a combination of retrieval and generation techniques for accurate and context-aware responses.
* **FLAN-T5 Model:** Utilizes the powerful FLAN-T5 language model for natural language understanding and generation.
* **Vector Database:** Stores reservation data in a vector format for efficient similarity search.
* **Chat Interface:** Provides a user-friendly chat interface built with Streamlit for interacting with the chatbot.
* **Flask API:** Exposes the chatbot functionality through a Flask API for integration with other applications.
* **Ngrok Integration:** Enables public access to the chatbot and API using ngrok tunnels.

## Requirements

* Python 3.7 or higher
* Required libraries: `transformers`, `torch`, `mysql-connector-python`, `streamlit`, `flask`, `pyngrok`, `sklearn`
* Ngrok account (for public access)
* Hugging Face token (for accessing FLAN-T5 model)
* MySQL database with reservation data (or use the sample data provided)

## Installation

1. Install the necessary libraries:
2. Set your Hugging Face token and Ngrok authtoken in the notebook.
3. Configure the MySQL database connection details if using a custom database.

## Usage

1. Run the notebook cells to initialize the chatbot, API, and chat interface.
2. Access the chat interface through the provided ngrok URL.
3. Interact with the chatbot by typing your questions.

