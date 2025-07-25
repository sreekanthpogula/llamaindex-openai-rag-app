# llamaindex-openai-rag-app
This repository contains a simple RAG (Retrieval-Augmented Generation) application built using LlamaIndex and OpenAI's GPT-3.5 Turbo model. The application allows users to query a set of documents and receive contextually relevant answers.

## Features
- Query a set of documents using natural language.
- Retrieve relevant context from the documents.
- Generate answers using OpenAI's GPT-3.5 Turbo model.
- Easy to set up and run locally.

## Requirements
- Python 3.8 or higher
- `llama-index` library
- `openai` library
- Access to OpenAI's API

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/llamaindex-openai-rag-app.git
    ```
2. Navigate to the project directory:
    ```bash
    cd llamaindex-openai-rag-app
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set up your OpenAI API key:
    ```bash
    export OPENAI_API_KEY='your_openai_api_key'
    ```
5. Prepare your documents in the `documents/` directory.
6. Run the application:
    ```bash
    streamlit run app.py
    ```

## Usage
Once the application is running, you can interact with it via the command line. Simply type your query, and the application will return an answer based on the relevant documents.

## Example
```bash
$ python app.py
Welcome to the RAG Application!
Type your query below:
What is the capital of France?
Retrieving relevant documents...
Answer: The capital of France is Paris.
```

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details