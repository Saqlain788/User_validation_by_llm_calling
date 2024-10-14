# Project Title: Google Colab LLM Tool Calling Example

## Overview
This project demonstrates how to utilize a Large Language Model (LLM) from Google Gemini, using the `langchain` library, to build a tool-calling system that interacts with typed user data and performs automated actions. The workflow is implemented in Google Colab, using various techniques to install dependencies, interact with APIs, validate data, and visualize a graph of the LLM's state transitions.

## Features
- **Install and Use Required Libraries**: The project begins by installing the required Python packages, including `langchain`, `langchain-google-genai`, and `langgraph`.
- **Integration with Google Gemini API**: Retrieves the API key for Google Gemini and initializes the ChatGoogleGenerativeAI model for use.
- **TypedDict Validation Tools**: Defines classes for user and address validation and integrates a custom validation function with the LLM.
- **LLM Tool-Binding**: Binds the validation function to the LLM, enabling the model to use external functions during a conversation.
- **State Graph and Visualization**: Builds a state graph using the `StateGraph` class and visualizes the flow using Mermaid.
- **User Interaction**: Invokes the LLM and state graph to interact with example user data, performing tasks such as validation and user information addition.
