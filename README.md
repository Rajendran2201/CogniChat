# CogniChat
## Streamlit PDF Chatbot
A Langchain app developed to chat with Multiple PDFs

This is a Streamlit application that allows users to upload multiple PDF documents and interactively chat about the content of those documents using a conversational AI model. The chatbot is designed to process PDF files, extract text from them, and generate embeddings for the text chunks using Hugging Face models. Users can ask questions about the uploaded documents, and the chatbot will provide responses based on the document content.

## Installation

1. Clone the repository:

   ```bash
   git clone  https://github.com/Rajendran2201/CogniChat
   ```

2. Navigate to the project directory:

   ```bash
   cd streamlit-pdf-chatbot
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the Streamlit application, execute the following command:

```bash
streamlit run app.py
```

This will start the Streamlit server locally, and you can access the application in your web browser by navigating to the provided URL.

## Features

- Upload multiple PDF documents.
- Process the uploaded documents to extract text.
- Generate embeddings for the text chunks using Hugging Face models.
- Interact with a conversational AI model to ask questions about the document content.
- View chat history and responses in real-time.

## Dependencies

- Streamlit: For building interactive web applications.
- PyPDF2: For reading PDF files and extracting text.
- langchain: For text processing and embedding generation.
- Hugging Face Transformers: For accessing pre-trained language models.
- dotenv: For loading environment variables from a .env file.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them to your branch.
4. Push your changes to your fork.
5. Submit a pull request with a description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Rajendran2201/CogniChat/blob/main/License.md) file for details.

## Authors

- [Rajendran S](https://github.com/Rajendran2201)

## Acknowledgments

- Inspiration: [Alejandro AO](https://github.com/alejandro-ao)

## Screenshots 

<img width="1440" alt="Screenshot 2024-03-23 at 21 09 53" src="https://github.com/Rajendran2201/CogniChat/assets/137254223/38156858-db38-4974-926b-666812e64e5d">
<img width="1440" alt="Screenshot 2024-03-23 at 21 10 36" src="https://github.com/Rajendran2201/CogniChat/assets/137254223/1a7b04fb-4264-4329-be21-1e94cbc1901b">

