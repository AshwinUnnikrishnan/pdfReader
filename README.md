
---

# PDF Chatbot

This is a Python-based chatbot that extracts text from PDF files, allows users to ask questions based on the content, and retrieves relevant answers from the extracted text. It utilizes various libraries and tools for natural language processing, text extraction, and conversational retrieval.

## Installation

To install the dependencies, run:

```bash

pip install -r requirements.txt

```

## Usage

1\. **Run the Chatbot**: Execute the main script `main.py`.

2\. **Upload PDF File**: The bot prompts the user to upload a PDF file. Once the file is uploaded, it processes the text content.

3\. **Ask Questions**: After processing, users can ask questions related to the PDF content.

4\. **Get Answers**: The chatbot retrieves relevant answers from the processed text and provides them to the user.

## Libraries Used

- **PyPDF2**: For reading PDF files and extracting text content.

- **Langchain**: A library for natural language processing tasks, including text splitting, embeddings, and conversational retrieval.

- **Chainlit**: A library for building asynchronous chatbot systems.

## Functionalities

- **Text Extraction**: Extracts text content from uploaded PDF files.

- **Conversational Retrieval**: Utilizes conversational retrieval chains to answer user questions based on the extracted text.

- **Asynchronous Processing**: Handles user interactions asynchronously for a seamless chat experience.

## Contributing

Contributions are welcome! Feel free to submit issues, feature requests, or pull requests.



---
