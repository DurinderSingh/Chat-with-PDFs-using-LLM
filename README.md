
# **Chat with PDFs: AI-Powered Insights**

## Introduction
Chat with PDFs uses the Google Gemini large language model to facilitate interactive conversations with PDF documents. Users can upload PDFs and ask questions about the content, receiving precise and insightful responses powered by advanced AI. The app features a user-friendly web interface built with Streamlit, allowing for seamless and intuitive document interaction. Whether for research, business, or personal use, "Chat with PDFs" makes extracting and understanding information from PDFs easier than ever.
## Key Features

1. **Upload Multiple PDFs**:
    Easy upload of multiple PDF files directly from the user’s device.

2. **Interactive Q&A**:
    Ask questions about the content of the uploaded PDFs and receive accurate, AI-powered responses.

3. **Contextual Understanding**:
    Utilize the Google Gemini large language model to comprehend and interpret the context of questions related to the PDF content.

4. **User-Friendly Interface**:
    Intuitive web interface built with Streamlit for seamless interaction and navigation.

5. **Instant Response**:
    Get immediate answers to queries about the PDF content, enhancing efficiency and productivity.

6. **Document Analysis**:
    Analyze and extract key information from PDFs to answer specific questions.

## Tools and Libraries Used

- Google Gemini
- Streamlit
- Python
- Langchain
- google-generativeai
- python-dotenv
- PyPDF2
- chromadb
- faiss-cpu
- langchain_google_genai
## Installation
To provide clear and effective installation instructions in your README, you should include the following details:

### Installation
1. **Prerequisites**:
- Python version 3.10 or above
- Git (for cloning repository)
- Visual Studio Code

2. **Clone the Repository**:
   - Instructions to clone the project repository from version control (e.g., GitHub).

   ```bash
   git clone https://github.com/DurinderSingh/Chat-with-PDFs-using-LLM.git
   ```

3. **Create a Virtual Environment** (Optional but recommended):
   - Set up a virtual environment to manage dependencies.

   ```bash
   conda create -p venv python==3.10
   ```

4. **Activate the Virtual Environment**:
   - Activation command varies depending on your operating system.

   **Windows**:
   ```bash
   conda activate "your environment path or name"
   ```

5. **Install Dependencies**:
   - Install the required Python libraries and tools listed in `requirements.txt` or similar.

   ```bash
   pip install -r requirements.txt
   ```

6. **Configuration**:
 Get your google api key from https://makersuite.google.com/app/apikey

   ```plaintext
   Create a `.env` file in the root directory and add the following:
   GOOGLE_API_KEY=your_api_key
   ```

7. **Run the Application**:
   - Instructions for starting the application.

   ```bash
   streamlit run app.py
   ```

8. **Access the Application**:
   - Provide details on how to access the running application (e.g., localhost URL).

   ```plaintext
   Open your web browser and go to http://localhost:8501
   ```
## Author - Durinder Singh
This project is part of my portfolio, showcasing the LLM and Generative AI skills essential for AI Engineer roles. If you have any questions, feedback, or would like to collaborate, feel free to get in touch!