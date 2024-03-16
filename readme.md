

## Introduction

The PDF-Asker Chat App is a Python application that allows you to chat with multiple PDF documents. You can ask questions about the PDFs using natural language, and the application will provide relevant responses based on the content of the documents. This app utilizes a language model to generate accurate answers to your queries. Please note that the app will only respond to questions related to the loaded PDFs.

## How It Works

The application follows these steps to provide responses to your questions:

1. PDF Loading
2. Text Chunking
3. Language Model
4. Similarity Matching
5. Response Generation.

## Dependencies 
1. Install the required dependencies by running the following command:
   
   pip install -r requirements.txt
   
2. Obtain an API key from OpenAI and add it to the `.env` file in the project directory.
3. Obtain an API key from Hugging Face and add it to the `.env` file in the project directory.


## Usage
-----
To use the PDF-Asker Chat App, follow these steps:

1. Ensure that you have installed the required dependencies using this command
   
  pip install -r requirements.txt
  
3.  Add the OpenAI API key and Hugging Face API Key to the `.env` file.

4. Run the `main.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ```

5. The application will launch in your default web browser, displaying the user interface.
6. Load multiple PDF documents into the app by following the provided instructions.
7. Ask questions in natural language about the loaded PDFs using the chat interface.

## License

[MIT License](LICENSE)
