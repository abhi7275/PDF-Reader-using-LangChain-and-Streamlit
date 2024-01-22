# PDF-Reader-using-LangChain-and-Streamlit

## Overview
This Streamlit application, powered by LangChain, serves as an interactive reader for PDF documents. It employs natural language processing (NLP) and chat models to enable users to ask questions about the contents of uploaded PDFs and receive informative responses.

## Installation
Ensure you have Python installed on your system. Use the following commands to set up and run the application:

```bash
pip install -r requirements.txt
streamlit run app.py

How to Use

    Access the application through the provided Streamlit URL.
    Upload a PDF document.
    Click the "Process" button to analyze the document.
    Ask questions related to the document's content.
    The application provides interactive chat responses and displays relevant pages of the document.

Dependencies

    Streamlit
    LangChain
    PyPDF2
    Tempfile
    Base64

File Descriptions

    app.py: The main application script.
    htmlTemplates.py: Contains HTML templates used for rendering chat messages.

Tasks
Task 1: Import the Libraries

The necessary libraries are imported, including Streamlit, LangChain, and other dependencies.
Task 4: Process the Input PDF

Defines a function process_file to process the uploaded PDF using LangChain embeddings and retrieval models.
Task 6: Method for Handling User Input

The handle_userinput function manages user queries, updates the chat history, and displays messages in an interactive chat format.
Main Function

The main function sets up the Streamlit layout, processes user input, and displays the results interactively.