# Chat with PDF using Gemini
This project sets up a Streamlit app that allows users to upload PDF files, process their content, and ask questions based on the extracted text. The app uses Google Generative AI embeddings and FAISS for vector storage and similarity search.

# Features
Upload PDF files.
Extract text from the uploaded files.
Split the text into manageable chunks.
Create a vector store for the text chunks.
Ask questions related to the uploaded files and get responses.

# Requirements
```
Python 3.7 or higher
Streamlit
PyPDF2
langchain
langchain-google-genai
google-generativeai
FAISS
python-dotenv
```

# Installation
Clone the repository:

``` git clone https://github.com/yourusername/chat-with-pdf-gemini.git ```
``` cd chat-with-pdf-gemini ```

# Create and activate a virtual environment:

``` conda create -p venvs python==3.10 -y ```
``` conda activate venvs/ ```

# Install the required packages:

``` pip install -r requirements.txt ```

# Set up environment variables:

Create a .env file in the root directory of your project.
Add your Google Generative AI API key to the .env file:

``` GOOGLE_API_KEY=your_api_key_here ```
# Usage
Run the Streamlit app:

``` streamlit run app.py ```

# Interact with the app:

1. ** Open your browser and go to http://localhost:8501.
2. **Upload your PDF files using the file uploader in the sidebar.
3. **Enter a question related to the content of the uploaded files.
4. **Click on the "Submit & Process" button to process the files.
5. **View the answer to your question displayed on the main page.

# File Structure

1. **requirements.txt: Contains all the dependencies to be downloaded.
2. **app.py: Main script to run the Streamlit app.
3. **.env: File to store environment variables (not included in the repository, needs to be created).
4. **README.md: This file.
