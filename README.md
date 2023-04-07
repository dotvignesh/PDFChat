# PDFChat

The PDFChat app allows you to chat with your PDF files using the power of langchain, OpenAI Embeddings, and GPT3.5 in the backend. 
It uses Streamlit for the user interface.

## Installation

To install and run the application, follow the instructions below:

1. Clone the repository using Git:

   ```bash
   git clone https://github.com/dotvignesh/PDFChat.git
   ```

2. Change into the repository directory:

   ```bash
   cd PDFChat
   ```

3. Create a conda environment based on the requirements.txt file:

   ```bash
   conda create --name pdfchat --file requirements.txt
   ```
   
4. Activate the new conda environment

   ```bash
   conda activate pdfchat
   ```

5. Get your OpenAI API Key by following these steps:
   - Go to [OpenAI Website](https://platform.openai.com/account/api-keys)
   - Create an account or log in
   - Navigate to the "API Keys" section
   - Click on the "Create new secret key" button (or use an existing one)
   - Copy the API key

6. Create a `.env` file in the root of the repository directory, and add the following line, replacing `<your-api-key>` with your actual API key:

   ```bash
   OPENAI_API_KEY=<your-api-key>
   ```

7. Run the application using streamlit:

   ```bash
   streamlit run app.py
   ```

The application should now be running at http://localhost:8501.


## Usage

Once the app is running, you can upload your PDF files and start chatting with them using the built-in chat interface.

Enjoy chatting with your PDF files!

