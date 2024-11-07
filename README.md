# NVIDIA NIM Testing RAG

This project is a Streamlit application that uses NVIDIA's AI endpoints for document retrieval and question answering. It leverages various libraries from the LangChain ecosystem to load, split, and embed documents, and then uses these embeddings to answer user questions.


## Setup

1. **Clone the repository:**

    ```sh
    git clone https://github.com/OnurAsimIlhan/nvidia-nim-rag.git
    cd nvidia-nim-rag
    ```

2. **Create and activate a virtual environment:**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Set up the environment variables:**

    Create a `.env` file in the root directory and add your NVIDIA API key:

    ```env
    NVIDIA_API_KEY=your_nvidia_api_key
    ```

## Usage

1. **Run the Streamlit application:**

    ```sh
    streamlit run finalapp.py
    ```

2. **Interact with the application:**

    - Enter your question in the text input field.
    - Click on "Documents Embedding" to prepare the vector store.
    - The application will display the response and relevant document chunks.

